---
title: Clash Win 和 Mac 使用教程
date: 2019-02-18 00:50:50
tags:
---

#### Win 和 Mac 上最好用的 SS & V2ray 免费客户端

选择 Clash 作为客户端主要是因为：

1. 界面UI比较简洁漂亮，Mac 和 Win 基本还能统一。
2. 支持 ss 和 v2ray
3. 可以自定义 rule 规则，这点也是最大的优势。能让访问不同的内容走不同的节点，这个对于有 Netflix 或者相关需求的人来说实在太棒了！同时 Captures  也能看到自己访问的路由规则信息。
4. 配置规则可以从远程获取，虽然略麻烦但写好的规则用起来就更方便。
5. Win 版本自带 EnableLoopback 方便让 uwp 应用走代理，这也是 Netflix 用户福音。

#### 下载&安装

- Win 版本 [Github](https://github.com/Fndroid/clash_for_windows_pkg)
- Mac 版本  [Gihub](https://github.com/yichengchen/clashX)

![Win Clash](https://sebs.club/hexoBlog/835c9d2cd88c6d6a3226da1f555fa81.png)

下载安装好了推荐打开 System Proxy 和 Auto Launch 系统代理和开机启动。 

#### 添加配置文件

Clash 的配置文件和 Surge 类似， 不会配置的可以参考这里  [Clash Rule 规则](https://github.com/Hackl0us/SS-Rule-Snippet/wiki/clash(X\)) 和 [Yml 文件](https://raw.githubusercontent.com/Hackl0us/SS-Rule-Snippet/master/LAZY_RULES/clash.yml)，推荐将配置的文件放在私有的服务器或者 阿里云的 OSS 等。当然你也可以直接修改本地的 Config.yml 直接使用。

如果你是从远程获取，选择 Profiles 粘贴上远程 yml 文件地址（记得浏览器打开检查下文件）

![Clash add Profiles](https://sebs.club/hexoBlog/93ac6e73fa504dfccdd96833642dce4.png)

然后点击 Download 如果获取到了 会提示 Success  这个时候其实就已经应用了。开心的上网吧。

![Clash success](https://sebs.club/hexoBlog/925a84fba932328e1bb8fbf6b80c659.png)

Mac 这里基本类似，在右上角点击小猫。将 Set as system proxy 勾上，然后在 config - remote Config - set url 填上远程地址。这样 Mac 也可以开心的使用啦。(感谢 Mon$wag 提供的 Mac 截图)

![Mac Clash](https://sebs.club/hexoBlog/photo_2019-02-18_05-48-01.jpg)

#### 规则的选择

- Rule 规则代理模式（推荐日常使用）

  ![clash rule](https://sebs.club/hexoBlog/794675b8c35321819b0dbd42704a62e.png)

  Rule 在配置文件里写好了的，我这里 配置文件分成了 Proxy普通代理 和  Netlfix 代理的选择。访问 Netflix 可以方便切换线路也节约流量。

- Globa 全局代理模式

  ![clash global](https://sebs.club/hexoBlog/aad8531d433417c751e8a44b337334e.png)

  Global 会直接代理所有流量走服务器或者直连，选择 REJECT 会拒绝所有连接也就是不能上网了。

  DIRECT 是所有流量都不走代理直连。

  下面的都是选择不同节点啦，内容都是来自你配置文件的服务器。

- DIRECT 直连

  和 Global 里一样直连模式，不走代理。

#### UWP 应用走代理

目前的版本已经自带 EnableLoopback ，能很简单的 让 win UWP 的应用走代理，对于 Netflix 这样 UWP 能看更高清画质的应用还是有意义的。

![Loopback](https://sebs.club/hexoBlog/7bf2068dd4d1f3d8a2c6e841301d10e.png)

勾选上你需要走代理的 UWP 应用 Save Changes 保存即可

![uwp](https://sebs.club/hexoBlog/11a8d2c9901e57dba42bf98ad575827.png)



Clash 除了配置文件需要一定的学习成本外，还是非常非常好用的。特别是对于 Windows 用户来说。不过配置文件也能更好的方便自己，看看自己写写还是值得的。

