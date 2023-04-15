# 苹果/安卓翻墙教程    

​       这篇文章将帮助没有经验的同学绕开国防网，自由浏览全世界的互联网信息。本文践行实用主义，只介绍最常规的工具和方法，帮助新同学立即上手，不对XRAY/SSR/V2Ray/Trojan等技术做详细分析。提醒：本文仅作为学习交流所用，严禁用于商业及违法犯罪。

![img](https://telegra.ph/file/7a46b0c57c11ad789c00f.png)

## 苹果iPhone、ios翻墙方法：

#### 方法1.shadowrocket（小火箭）+订阅链接

①**注册美区apple ID**，有两种方法：

​    1.可以按常规方法注册，免费，略费时，参考： https://zhuanlan.zhihu.com/p/367821925

​    2.直接买一个已经购买了shadowrocket的美区apple ID，一劳永逸。除了小火箭，也可以用[surge](https://github.com/bannedbook/fanqiang/blob/master/ios/Surge.md)、[Potatso Lite ](https://github.com/bannedbook/fanqiang/blob/master/ios/PotatsoLite.md)、[Quantumult X](https://github.com/bannedbook/fanqiang/blob/master/ios/QuantumultX.md)等app。如果你有朋友购买了小火箭的apple ID，可以借用，在你app store登录后下载（不要在设置里登录），然后再退出即可；如果你买了，同样也可以分享给别人使用。（购买地址参考：[https://store.kxsw.org](https://store.kxsw.org/) 或 [https://manateestores.us](https://manateestores.us/)）

![img](https://telegra.ph/file/890eb8e2195a8b6f77bed.png)

认准正版小火箭名字和图标

②**在app store登录美区id**（`不是在设置里登录`），**搜索shadowrocket**，下载，安装好之后打开，

软件支持直接使用机场订阅链接来添加节点信息，如下图所示点击软件主界面左上角 ➕ 按钮，在弹出窗口进入添加节点界面，类型选择 `Subscribe` 后，出现节点订阅配置界面，在 `URL` 处输入订阅地址【https://fast.lycorisrecoil.org/link/GmDQOZevDi4xh4r5?sub=1】(不含中括号)，其余选项什么都不用改，点完成。这时‘首页’会看到该订阅地址对应的节点列表，点‘连通性测试’，可以看到延迟（单位毫秒ms,数字越小速度越快），‘首页‘最上面的按钮，点击显示蓝色后，它的左侧会显示‘已连接’，如果按钮是蓝色，说明已经**成功**绕开GFW，可以访问谷歌、推特、油管等海外站点；如果按钮是红色，说明连接不成功，可能是因为网络问题、节点失效、或订阅链接失效，可以尝试在节点列表里测试联通性，更换节点。我们也会不定期在电报频道免费更新订阅链接。

建议再点击软件主界面右下角设置 -> 订阅设置，可以开启’打开时更新‘按钮，或设置你想更新的频率。



③苹果版shadowrocket扩展：[点击此处详细了解shadowrocket配置](https://maddodo.github.io/2023/04/15/shadowrocket/)因为各种原因，翻墙后的网络可能不稳定，或者订阅链接完全失效，这就需要你掌握更多的技能，**授人以鱼不如授人以渔**，我们尽量提供方法和免费订阅资源，你也需要掌握必要的技能。关注我们的电报频道[Telegram@WMZB2023](https://t.me/wmzb2023) ，可以获得最新的免费资源。你也可以自己找服务商购买自用，跟朋友分享，一般一个月十几块。([点击此处](https://xn--gmq396grzd.com/)参考可用机场，注册-登录-套餐购买)



#### 方法2. VPN

​       VPN傻瓜式操作，即开即用。考虑到隐私保护，不推荐中国区apple ID购买国产VPN，还是建议使用美区或其他地区apple ID购买诸如**ExpressVPN、hotspot shield、protonVPN、NordVPN、SurfShark等主流品牌VPN**。有些VPN有免费流量体验，懒人可以尝试。



​       苹果翻墙扩展：强烈建议你拥有一个独自使用的美区或其他海外地区apple ID，除了可以下载小火箭，还可以下载电报、脸书、推特、油管、WhatsApp、ins等所有国内被封锁的应用。关注电报频道[Telegram@WMZB2023](https://t.me/wmzb2023)获取免费订阅链接。使用[surge](https://github.com/bannedbook/fanqiang/blob/master/ios/Surge.md)、[Potatso Lite ](https://github.com/bannedbook/fanqiang/blob/master/ios/PotatsoLite.md)、[Quantumult X](https://github.com/bannedbook/fanqiang/blob/master/ios/QuantumultX.md)等app翻墙，原理差不多，不赘述。苹果首推小火箭shadowrocket+付费机场订阅。



## 安卓Android翻墙方法：

安卓更简单，跟苹果一样，可以直接使用VPN，或使用安卓版小火箭使用机场订阅链接翻墙。这里主要介绍Clash工具，其他工具大同小异。



#### 方法1.国外付费VPN,参考前文推荐的品牌，注意避开山寨VPN。

![img](https://telegra.ph/file/57e94b2fee4747abff190.png)

#### 方法2.Clash for Android（小猫咪）

​       如果有谷歌账号可以直接在[谷歌商店](https://play.google.com/store/apps/details?id=com.github.kr328.clash)下载，如果没有，就在GitHub下载：https://github.com/Kr328/ClashForAndroid/releases （根据你的手机处理器系列，建议选择premium版本，例如你手机是第8代64位arm处理器，就选择 cfa-2.5.12-premium-arm64-v8a-release.apk 下载安装，一般都选第一个）

​       安装好之后同样使用这个订阅地址：【https://fast.lycorisrecoil.org/link/GmDQOZevDi4xh4r5?sub=1】

​       [**点击了解Clash详细教程**](https://maddodo.github.io/2023/04/15/clash/)


### 总结：

###        **以上只是部分方法，电脑翻墙方法也差不多，你必须掌握至少一种，才能确保网络自由。有些人千方百计阻止我们翻墙，阻止我们获得更多的信息，但是我们不得不翻，也不能不翻，因为我们不是羊圈里的羔羊。**



​       最后，有些资源可能会有变动，我们会在电报频道[**Telegram@wmzb2023**](https://t.me/wmzb2023) 持续分享。国产智能终端（华为/小米等）、软件（反诈APP/拼多多/360/抖音等）通常都会恶意采集用户信息，建议尽量避免使用。

​       Telegram下载地址：[https://telegram.org](https://telegram.org/)

​       也可以在网页注册和登录 [https://web.telegram.org](https://web.telegram.org/)



​       以上VPN品牌、网络服务商和appleID销售商与我们没有任何联系和经济关系，仅作参考，以协助新同学上手。如果购买以上服务，建议尝试小金额和短期订阅，避免资金风险，今后我们会筛选更靠谱的商家。请务必关注我们的电报频道，未来会发布更多有价值的资讯，我们也可在电报交流。



​       Everyone is free .
