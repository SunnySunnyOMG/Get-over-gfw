# 回国的同学们，还在为找不到好的科学上网VPN而烦恼吗？ 现在推出私人订制科学上网服务，安全、稳定~~~

众所周知的原因，天朝的GFW（长城防火墙）会使得在国内无法正常访问境外的某些网站，如 Google全线产品:)、Facebook等

现在市面上的各种翻墙工具，多人使用、树大招风，很容易被有关部门突然封禁，不稳定也不安全

在下渥太华程序狗一名:rolleyes:，最近为回国的朋友配置了一套国内电脑翻墙上网的solution，觉得体验不错，所以现在尝试发个帖子看是否有人也对私人配置的翻墙工具感兴趣， 如果你：

*  希望稳定、安全的科学上网体验
*  有在线看墙外视频、下载墙外文件的需求
*  没事干想查一下学校邮箱，gmail等等
*  疲于寻找网上众多复杂的VPN

那么你可以尝试一下我的翻墙solution~

******************************************************************************************
***技术说明预警！！！ 不感兴趣的同学可以直接跳过***
******************************************************************************************
我是用的技术栈是 虚拟专用服务器（VPS） + shadowsocks，通过远程服务器对网络传输加密的方式来KO掉GFW的审核，

简单来说就是加密传输信息，让GFW无法解密识别你的网络通讯，因此也不能屏蔽（通俗解释，专业人士轻喷）

这种方法比起传统的VPN翻墙，有以下优势：
* 所有的流量都经过算法加密，因此更安全
* 因为协议的原因，在网络速度上也更快
* 通过异步I/O和事件驱动程序运行，响应速度快

有能力的同学，完全可以自己配置，需要一些linux，服务器部署相关的知识，当然github也得玩得转~
具体的教程可以上网搜啦~

******************************************************************************************
***预警结束！！！***
******************************************************************************************

好啦~ 说了这么多，不知道还有没有人感兴趣，那么现在要说说资费问题啦~
目前大概有几档配置，目前我打算主要靠每月可用的流量来区分：

### 1. 一档配置 =。= （应该是最普遍的需求了吧）

网络服务器配置（服务器配置关系到网络请求的处理速度，但是要我说对个人用户影响不大）：

* 单核 CPU处理
* 1GB 内存
* 25GB SSD 缓存

每月可用翻墙流量（这个比较重要）：

* 1000GB （对你没看错）

### 2. 二挡配置

网络服务器配置：

* 单核 CPU处理
* 2GB 内存
* 40GB SSD 缓存

每月可用翻墙流量：

* 2000GB

### 3.三档配置（话说真的会有人用到吗……害怕ing）

网络服务器配置：

* 四核 CPU处理
* 8GB 内存
* 100GB SSD 缓存

每月可用翻墙流量：
4000GB
```
其实一般人用到一档的配置就可以了吧，
当然你有特殊需要，给你整个16核CPU， 100000GB的翻墙服务器也是可以的（要上天吗? 微笑）
```
之前给朋友配置的就是一档配置，下图是服务器的管理界面（用的是洛杉矶机房，速度还行）：
![image](https://raw.githubusercontent.com/SunnySunnyOMG/Get-over-gfw/master/upload_2017-12-31_20-12-13.png)
### 那么需要再次声明的是
#### 1.目前所有的配置都将会有一个专属于你的翻墙服务器，不与任何人公用~
这样做是为了安全和稳定考虑（我知道很浪费，毕竟不是人人都能用到1000GB不是），所以
#### 2. 如果你不介意与朋友分享某个服务器和流量，那么也可以告知我，这样的话每多一个人，则在原价的基础上加5刀，为保证质量，每个服务器最多20人共享
#### 3. 所有的网络连接均不限速！

### 思考了一下，暂行资费如下：

#### 1. 所有配置（无论一档、二挡、三挡、自动挡还是手动档）
初次配置费用是 <strong>30 刀</strong>，之所以有这个费用，是因为我要为你单独购买一个后端服务器，并进行初次配置，让其成为合你格的私人翻墙服务器，这个是一劳永逸的事情，是一次性收费

#### 2. 每月收费（用于服务器维护）
* 一档：10刀/月
* 二挡：20刀/月
* 三挡：50刀/月

对于绝绝绝绝大部分人（看个网页、查个邮件），一档已经绰绰绰绰有余， 如有其他需求可另行联系
至于价格，相信曾经用过收费VPN的筒子们都明白，我这个不限速+私人服务器的上网服务，每月仅10刀（一档）已经是价格低到爆炸…… 之所以这么低也是因为目前还是重在推广=。=，以后会看情况涨价:oops::oops::oops:（嘘~~）

### 那么，需要科学上网服务的筒子们可以通过下列方式联系我：
#### 1. 邮件（推荐）： zxu024@uottawa.ca
#### 2. 微信联系



