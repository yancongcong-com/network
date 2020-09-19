# CAPWAP概述

## CAPWAP术语

- 控制隧道
  - AP:UDP 10000端口   AP版本配置下发    AC:UDP 5246端口
- 数据隧道
  - AP:UDP 10001端口    无线用户数据        AC:UDP 5247端口

## CAPWAP隧道建立

1. AP获取ip地址
   - dhcp (option 138)
   - 静态
2. AP发现AC  Discovery
   - AP发送Discovery  Request广播，组播(224.0.1.140)，单播
   - 状态从idle(空闲)到Discovery(发现)
   - AC利用隧道IP(为lo0)发送 Discovery Respose
   - 状态从idle到 DTLS Setup
     - TLS协议------>安全网络传输协议
       - 危险
         1. 窃听
         2. 篡改
         3. 伪装
     - SSL(Secure Socket Layer安全套接字层)协议发展为TLS(Transport  Layer  Security传输层安全)
     - DTLS数据包传输层安全性协议
3. AP请求加入AC  Join
   - AP与AC建立DTLS链接
   - AP发送单播Join Request
   - AC回复单播Join Response(检查版本)
   - AP/AC状态从Discovery到Join
4. AP自动升级  Image data
   - AP发送单播Image  Data Request
   - AC发送单播Image Data Response(AP版本升级重启重新)
   - AP/AC状态从Join到Image Data
5. AP配置下发   Configuration
   - AP发送单播Config Status  Request
   - AP/AC状态从Image Data到Config
   - AC回复单播Config Status  Response
   - AP状态从Config到Data  Check
6. AP确认 Data  check
   - AP发送Change State Event Request
   - AC状态从Config到Data  Check
   - AC回复Change  State Event Response
   - AP状态到Run
7. 通过capwap隧道转发数据Run
   - 30秒后
   - AP向AC发送Keep-Alive(数据隧道)
   - AC状态进入Run 
   - AP/AC发送Echo (控制隧道)
   - 每30秒发送报文维护隧道

## CAPWAP数据转发

| 性能比较         | 本地转发                                           | 集中转发                                  |
| ---------------- | :------------------------------------------------- | ----------------------------------------- |
| 数据延迟         | 数据到ISP的跳数更少，延时更小                      | 数据到达ISP要先到达AC,在由AC上行延时更大  |
| 转发性能         | 转发性能取决于用户网络，不易形成瓶颈，转发性能更高 | 转发性能取决与AC,易形成瓶颈，转发性能偏低 |
| 设备处理         | 大多数情况下AC不做数据转发，减少转发压力和瓶颈     | 对AC数据转发能力是挑战                    |
| 设备要求         | 对AC/AP的性能要求较低                              | 对AC/AP的性能要求较高                     |
| 转发性能综合对比 | 相对较高                                           | 相对较低                                  |

































































