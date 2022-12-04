##  NOFK加密代理程序

## NOKF加密代理程序-完全自定义端口转发，分为自由版、民主版二个版本。以下有二个版本的详细介绍。
###### 免责：本程序为免费程序，所支付费用为代购服务器及服务器维护费用。中国境内用户请在法律法规允许范围内使用。
## 目录
### [NOFK加密代理客户端-自由版介绍](#nofk加密代理客户端-自由版介绍-1)
### [NOFK加密代理客户端-民主版介绍](#nofk加密代理客户端-民主版介绍-1)
### [试用与付费](#试用与付费-1)
### [使用说明V1.0](#使用说明v10-1)
#### [---NOFK加密代理客户端-自由版使用说明](#nofk加密代理客户端-自由版使用说明)
#### [---NOFK加密代理客户端-民主版使用说明](#nofk加密代理客户端-民主版使用说明)
### [相关问题解答](#相关问题解答-1)
### [加入群组](#加入群组-1)
#

## [NOFK加密代理客户端-自由版介绍](#nofk加密代理客户端-自由版介绍-1)
#### NOFK加密代理客户端-自由版只支持windows系统，其工作流程为，我们代购一台云服务器（这台云服务器仅为单人使用，不共用）并安装服务端程序，然后提供服务器接口密钥，使用者只需把密钥输入客户端程序，即建立了代理客户端与服务器的通讯 ，在客户端上，使用者可以指定服务器端口、本地端口、转发目标地址等参数，在终端设备上输入对应的本地ip:端口，从而实现了将本地数据加密转发到目标地址的功能。
#### 自由版适合显卡机、芯片机，特别适合打新一些小矿池上的新币种。
### NOFK加密代理客户端-自由版特点
#### 1、完全开放式定制转发端口，可加密转发任意矿池、任意币种。
#### 2、每个客户端采用独立服务器进行转发，转发服务器不混用，完全保证线路稳定及安全，不易被攻击。
#### 3、服务端无任何抽水软件，直接转发到目标矿池，低延时，低拒绝率。
#### 4、自带矿机监测功能，实时监测矿机运行状态。
客户端运行界面演示：
###### ![image](https://github.com/NOFKPROXY/NOFKPROXY/blob/main/img/1.JPG)
###### ![image](https://github.com/NOFKPROXY/NOFKPROXY/blob/main/img/2.JPG)
实测图：矿机连的是鱼池-ETC 本地算力144M  本地网络：湖南联通  中转服务器：香港VPS云服务器
###### ![image](https://github.com/NOFKPROXY/NOFKPROXY/blob/main/img/3.png)
鱼池24小时算力：137M 损失率在5%以内。
###### ![image](https://github.com/NOFKPROXY/NOFKPROXY/blob/main/img/4.png)
#### 关于算力损失率可以查看这篇文章：https://minersns.com/7226-1-1.html
#### 在5%左右算力损失率是正常的，如果超过太多，排除本地矿机和网络问题外，那可能就是被抽水了。
#
#
## [NOFK加密代理客户端-民主版介绍](#nofk加密代理客户端-民主版介绍-1)
#### NOFK加密代理客户端-民主版是跨平台应用，支持X86 ,ARM架构的linux和windows，具有更好的设备兼容性，部署更简单、方便。其工作流程，在服务器部署方面与自由版是一样的，只是客户端无需进行任何设置，直接获取服务端上的配置文件，一步到位，简单快捷。
###### 开发中，预计12月10日上线......
#
#
## [试用与付费](#试用与付费-1)
#### 我们代购这家云服务器提供商算是一家老牌主机商，合作也有5年之久，在带宽及稳定性方面都还可以，目前提供二个配置，具体配置及价格如下：
![image](https://github.com/NOFKPROXY/NOFKPROXY/blob/main/img/%E4%BB%B7%E6%A0%BC.jpg)
测试ip:156.240.107.254 (购买前ping测试一下延迟)
###### ![image](https://github.com/NOFKPROXY/NOFKPROXY/blob/main/img/ping.png)
本地网络：湖南联通   [此延迟时间只是本地到云服务器的时间，但本地到目标矿池的延迟时间肯定会比这个长，具体取决于云服务器到目标矿池的延迟时间。](#试用与付费-1)
#### [试用及订购云服务器，<a href="https://www.nofkcloud.com" target="_blank">点这里</a> (需要注册登陆)](#试用与付费-1)
#### 登陆后左侧栏 产品与服务 - 订购产品  
#### 注意：本网站只是方便大家订购云服务器，其它功能不可用。
#
#
## [使用说明V1.0](#使用说明v10-1)
## [NOFK加密代理客户端-自由版使用说明](#nofk加密代理客户端-自由版使用说明)
#### 运行客户端条件：
#### 1.推荐安装win10精简版系统（系统资源占用少，关闭了自动更新等不必要的功能），硬件配置方面没有太高要求，如果带机量不多，可以使用低功耗的迷你主机。
#### [2.关闭系统防火墙和杀毒软件，如不关闭的话，放行自定义添加的端口，并将客户端程序添加到杀毒软件的白名单。](##nofk加密代理客户端-自由版使用说明)
#### 客户端操作说明：
#### ![image](https://github.com/NOFKPROXY/NOFKPROXY/blob/main/img/%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E.jpg)
#### ![image](https://github.com/NOFKPROXY/NOFKPROXY/blob/main/img/2.JPG)
#### 1.为服务器到期时间，到期后，数据会保留三天，请及时续费。
#### 2.订购服务器后，客服会给到这个接口密钥，填入其中，后面状态灯为绿，表示与服务器通讯正常；为红时，表示通讯中断，此时首先检查本地网络状况是否正常，如正常，再联系客服检查服务器端是否正常。[注意：服务器接口密钥是唯一的，如果透露给陌生人，则其他人也可以共享你的服务器。请勿外泄给陌生人。](##nofk加密代理客户端-自由版使用说明)
#### 3.此客户端最大允许连接的设备数量，超过这个数量的矿机肯定是连接不上的。[注意，实际数量最好是比允许连接数少个几台。以这个套餐为例，实际数量应在47-48台以内，这样保证连接稳定性。](##nofk加密代理客户端-自由版使用说明)
#### 4.服务编码为客服处理故障、续费时使用，只需要提供你的编码即可。
#### 5 6.指定服务器端口和本地端口，注意填入高位端口号，如1000以上的端口都可，不要填入二、三位数的端口号。
#### 7.[注意填入格式为：矿池-币种，一定要按此格式填写。](##nofk加密代理客户端-自由版使用说明)
#### 8.[填入目标矿池TCP协议的地址加端口，不要填入SSL协议地址，另外，stratum+tcp:// 这个部分不需要填入。](##nofk加密代理客户端-自由版使用说明)
#### 9.点击添加矿池后，所填入的信息会在下表中显示出来。
#### 10.在完成上传配置并重启客户端后，将此地址填入挖矿软件中，[注意使用的是TCP协议，不能使用：stratum+ssl 。](##nofk加密代理客户端-自由版使用说明)如果需要配置多个矿池和币种，继续前面的步骤，注意端口不能重复使用。
#### 11.[完成添加后，点击上传配置，即可将本地的配置信息上传到服务器，一定要执行此步骤，](##nofk加密代理客户端-自由版使用说明)至此整个配置过程完成。矿机即可正常连接到矿池。注意，不要频繁点击上传配置，因为每点击一次，服务端程序就会重启一下。
#### 12 13.可以对配置进行修改及删除，[完成后必须点击上传配置，](##nofk加密代理客户端-自由版使用说明)服务器端才能进行更新，完成后需要重启客户端。
#### 14.如果需要在其它设备使用原有的配置文件，只需要点击这个按钮，即可将配置文件下载到本地直接使用，不需要重新配置。
#### 15.设置开机自启动客户端。
#### 16.版本提示，如有新版本，请及时更新。
#### 17.矿机状态，这里只会显示在线矿机，离线矿机不会显示，可以根据矿工名排查。另，芯片矿机名显示可能会不准确。
#
#
## [NOFK加密代理客户端-民主版使用说明](#nofk加密代理客户端-民主版使用说明)
###### 正在赶来的路上......
#
#
## [相关问题解答](#相关问题解答-1)
#### [1.是不是每个客户端都有对应一台服务器？](#相关问题解答-1)
#### 是的，主要是保障线路的稳定性与安全性，现在市面上有很多诸如中转线路、中转代理软件之类的，但大多数都是共用一条线路，一旦线路出现了被攻击或服务器故障，所有机器就都停摆了。采用这种方式就是分散服务器，只要用户自己不泄露服务器ip，是无法被攻击的。
#### [2.目前有很多可用的其它代理软件，为什么还要用NOFK？](#相关问题解答-1)
#### 确实，目前可用的代理软件很多，像gost、nginx、VPN等等，但都存在一个配置相对较麻烦的问题，对linux不熟悉的，不是很好操作。NOFK全图形界面操作，简单，即学即用。即使有些用户懂得用这些程序配置，也是需要海外服务器进行中转的，而我们就是提供服务器，客户端程序免费使用。
#### [3.可以提供全套程序，用自己的服务器搭建吗？](#相关问题解答-1)
#### 目前不可以，后续有计划会做成通用版程序。
#### [4.服务端存在被抽水的情况吗?](#相关问题解答-1)
#### 不存在，对这个问题，有没有被抽水可以从这几方面判断：
######    a.如果被抽水的话，拒绝率相对会比较高。
######    b.更直观的就是收益了，如果收益明显少于平均收益，那就被抽水了。
######    c.本地算力比矿池24小时平均算力相差太多，正常差异在5%以内或左右。
#### 所以用NOFK连续测试24小时后，就可以看得出有没有被抽水。
#### [5.用户可以登陆自己的服务器吗？](#相关问题解答-1)
#### 目前不可以，如果用户登陆服务器后，下载了服务端程序，那他就可以自用了。
#### [6.如果服务器还未到期，但设备卖了，怎么处理服务器？](#相关问题解答-1)
#### 可以提供服务器的登陆账号和密码，由用户自己继续使用（在订购系统里完成实名认证），因为服务器是代购的，所以没有单独的操作后台。
#
#
## [加入群组](#)
####  小飞机群：https://t.me/NOFKPROXYGROUP （唯一TG群组，谨防假冒群组，防止诈骗）
