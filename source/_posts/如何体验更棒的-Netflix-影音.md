---
title: 如何体验更棒的 Netflix 影音
date: 2019-03-28 01:46:00
tags: 流媒体
---

Netflix 同时支持 Dolby Vision、Dolby Atmos、Ultra HD 4K。每一样都是业界顶级，都能带来非常震撼的效果，也是绝大部分平台和流媒体无法提供的。Netflix 绝对能给你提供最棒的影音效果。这篇就由浅入深讲讲 Netflix的音质和画质，以及如何避免踩坑享受到更好的。

![banner](<https://sebs.club/hexoBlog/5b513d75180e0.image_.jpg>)

## 手机移动端

先说结论：如果你是除华为（Mate 10、Mate 20、P20、Nova3 ）以及荣耀10以外绝大部分国产手机你看 Netflix 就限制在了 SD 540p 的画质，比如小米 9。与此同时苹果、华为、三星、SONY、LG、以及 Google 等近两年的旗舰都是支持 1080p 高清以及 HDR 甚至 Dolby Vision 的（后面会单独讲）。参考：Netflix [官方支持设备列表链接](https://help.netflix.com/en/node/23939)

#### 如何知道自己手机是否支持看高清版权内容

如果你是官方列表支持的手机，并且你没有解锁BL，那么肯定是支持的。如果你用的是 iPhone， iPhone 6 Plus 以后的所有 iPhone Plus 以及 iPhone X、XS 和 XS Max 都支持1080p，而 iPhone XR 则是720p。iPhone 8 及以后的所有 iPhone（包括 iPhone XR 这个我验证过了） 都支持 Dolby Vison。参考Netflix [官方帮助文档](https://help.netflix.com/zh-tw/node/23927) 。

可以特别注意看下不同手机截图的 Love Death&Robots 后面的 Tag 标志，和 DRM Info 的 Widevine Security Level 的等级。L1 为最高等级， L3 最低。如果你感兴趣帮忙统计，可以下载 DRM Info 软件，然后将你的两张截图注明机型发给我 pengchujin@hotmail.com 十分感谢。

- 小米 9（Widevine L3 不支持 HD高清 最高是 540p SD 画质），希望小米能赶快解决吧。

  ![](<https://sebs.club/hexoBlog/mi_9_netflix.jpg>)

- 坚果 R1 和 小米9 一样 Widevine L3 不支持 HD高清 最高是 540p SD 画质。

  ![](<https://sebs.club/hexoBlog/1850660664_meitu_1.jpg>)

- 三星 S8（和 Netflix 列表说的一致支持 HD 1080p 高清不支持 HDR 三星从 S9开始支持 HDR ）

  看到 Widevine L1 和预期一致， 支持 HDCP 2.2 所以理论可以串流高清乃至HDR。

  ![s8](<https://sebs.club/hexoBlog/s8.jpg>)

- 三星 S10 支持 HD 高清和 HDR 是肯定的，不过 S10 硬件是支持 Dolby Atmos 的这里没有 Tag。当然目前 Netflix 也没有说移动设备支持 Dolby Atmos 的事。但用 S10 的朋友却听出了 Netflix 的声音要更立体很多，因该是因为手机手机打开了Dolby音效，而不是 Netflix 在手机上支持 Dolby Atmos。

  ![S10](<https://sebs.club/hexoBlog/s10.jpg>)

  - 这是 iPhone X 的截图，支持 HD 和 Dolby Vison 的。

    ![](<https://sebs.club/hexoBlog/webwxgetmsgimg.jpeg>)

这里的内容就比较炸裂有趣的，我买的国产旗舰居然连高清视频都看不了，更别提 HDR 了。

最主要的原因就出在很多国产手机厂商根本不重视版权这方面，没有做 Widevine DRM L1的支持。DRM 是 Digital Rights Management 即数字版权管理的简称。Widevine 则是 Google 2010年末重金收购的一家数字版权管理软件公司。 理论是这个需要硬件、软件、以及授权（Google 官方说不收费）来实现加密保护版权。Netfilx Hulu等服务商也会在打开内容前先检查设备的 Widevine DRM Level 等级，依据级别来决定客户端所能提供的清晰度。比较惨的是绝大部分国产手机的级别都是 Widevine DRM L3，也就是最低的级别。这个先决条件这就让这些国产手机的画质停留在了 SD 540p。感兴趣 android DRM 可以看看 [DRM in Android](https://blog.csdn.net/Innost/article/details/9732847)、[Android 官网 DRM](https://source.android.com/devices/drm#build)   。

一加国际化做的很好、但也是在一加6和6T才加入了 Widevine DRM L1的支持（解锁后会掉到 L3）。之前的5和5T因为不支持被骂的不行也才推出了邮寄回售后给补上的方案。解锁一定会掉吗？不是。我的Pixel 解锁了依然是L1。参考 [XDA](https://www.xda-developers.com/oneplus-5t-netflix-amazon-prime-video-hd/)

这样的例子同样也发生在了小米的身上，国际化的产物 PocoPhone F1 同样也是不支持 Widevine DRM L1 被消费者指责，但就在上个月 MIUI 推出的更新解决了这个问题，你只用更新下系统就能补上 L1 的支持来享受高清的流媒体。但直接更新系统就能补上 DRM 这也让人好奇是怎么实现做到的。那么小米9或者其他国产手机是不是也能用过我们指责和要求来推动他们 DRM 的支持？我觉得很有必要，希望国内厂家重视下吧。参考 [XDA](https://www.xda-developers.com/xiaomi-poco-f1-widevine-l1-netflix-hd/)

###### Tips

使用手机并且是流量数据的情况下，在 App 设定-行动数据流量 设置为最大流量 才能加载最高清的画质。

如果你是 iPad 或者其他平板可以直接参看上面 Netflix 的帮助，较新的 iPad 都是支持 HD 高清的（可能没有 Tag）。然后最新的 iPad Pro 是支持 Dolby Vision 的。

## 电脑端

仍然先说结论：Mac 以及 Linux 等除了 Win10 以外的所有的系统最高都是 1080p， 只有在 Win 10 系统并且硬件支持的情况下能看Ultra HD 4K 并且可以支持 HDR 以及 Dolby Atmos。

如果你是使用 Mac 或者 Linux 你在使用 Chrome 或者 Firefox 浏览器可以观看网页版 Netflix，通过安装浏览器插件可以观看 1080p 高清内容，Dolby 5.1 的声道支持。如果不装插件最高是 720p，你可以通过 安装 Chrome  [Super Netflix](https://chrome.google.com/webstore/detail/super-netflix/iakpdiefpdniabbekcbofaanjcpjkloe) 来查看当前观看内容的清晰度。

- [Chrome 1080P 插件](https://chrome.google.com/webstore/detail/netflix-1080p/cankofcoohmbhfpcemhmaaeennfbnmgp)
- [Firefox 1080P 插件](https://addons.mozilla.org/en-US/firefox/addon/force-1080p-netflix/)

#### Windows 10 上 Netflix 画质与音质详解

Windows 10 设备应该是看 Netflix 性价比最高的设备了，默认就支持高清了。在 Netflix UWP 或者 Edge 浏览器中就能观看。看到这肯定会好奇为啥就 Edge 支持高清和4K？因为 Edge 支持微软的 PlayReady DRM ，PlayReady DRM 是收费的，其他桌面的浏览器都只支持 Widevine Security Level3 这也是连高清都不支持的原因了。更详细的可以看 [Quora](https://www.quora.com/When-does-Netflix-use-WideVine-DRM-instead-of-Microsoft-PlayReady-DRM) 上的回答，非常详细具体。

![4k win](<https://sebs.club/hexoBlog/myce-netflix-ultra-hd.png>)

如果你想在 Win 10 上看到 Netfix 4K 的内容你需要满足下面这些条件。

-  较新的 Win 10 系统和驱动，然后通过 App 或者 Edge 打开。
- 4K 60HZ 的显示器并且显示器接口得支持 HDCP 2.2。HDCP 即 High -bandwidth Digital Content Protection 高带宽数字内容保护技术的简称，通过 HDMI 等接口传输的时候内容必须加密。当然 HDCP 是收费的，显示器的硬件厂商得交钱买。买 4K 显示器的时候一定得注意要支持 HDCP 2.2 。
- 显卡得是 7代以后的 Intel Cpu（因为7代以后的才支持这种加密格式哦），N 卡是 GTX 1050 以及更新的然后是最新的驱动，A 卡 RX 400 以及以后的系列。理论上支持 Play Ready 3.0 就 OK。可以看看 [Youtube](https://www.youtube.com/watch?v=E9bsC6-EL4E) 这个视频讲解的比较详细。
- 然后就是 你 Netflix 是最高级的套餐，网络速度大于 25Mbps ，App 里清晰度设置为了高。

###### Tips 按 Ctrl+Shift+Alt+D 可以在 Netflix App 和 Edge 里查看播放详情。

Win App 的 Netflix 是支持 Dolby Atmos 全景音效的，当然如果影片源只有 Dolby 7.1 和 Dolby 5.1 都会 Tag 给你标出。如果你有支持 Dolby Atmos 的耳机或者音箱你应该会得到更震撼的声音。

![Atmos](<https://sebs.club/hexoBlog/win_atmos.jpeg>)

Win 10 上 Netflix HDR 目前只支持10系和更高的N卡，或者 Intel 7代及以后的 集成显卡，A 卡不支持。你可以在系统显示设置里打开 HDR，然后 Netfix 的 Tag 也就有了。可以参看 [Youtube](https://www.youtube.com/watch?v=Jo1nqQ_f3ME) 以及 AMD [社区的回答](https://community.amd.com/thread/236257)

![HDR](<https://sebs.club/hexoBlog/maxresdefault.jpg>)

## 盒子和电视

这里因为设备选择的比较少并且都基本限制死了，只有认证的盒子才能看 Netflix 盒子版本。这里推荐几款自己觉得比较有性价比的。

- Apple TV 4K 全支持！
- mi box s 国际版 能看 4k 不支持 HDR/Dolby Vision 和 Dolby Atmos。
- Nvidia Shield 和 Nvidia Shield Pro 支持 4K 和 HDR
- Xbox One S和 Xbox One X 也全支持（HDR 非 Dolby Vision）。
- Chromecast Ultra 支持 4K 和 Dolby Vision
- Amazon Fire TV 4K Stick 支持 4k 以及 Dolby Vision

电视当然也得 4K 的才支持 4K，有真的 HDR 才支持 HDR 或者 Dolby Atmos， 及得 HDMI2 和 HDCP 2.2 也是必要条件。音箱也这样。

参考 Netflix [4K支持列表](https://help.netflix.com/en/node/13444)  [HDR10/Doly Vision支持列表](https://help.netflix.com/en/node/42384)  [Dolby Atmos支持列表](https://help.netflix.com/en/node/64066)

## 总结

#### Dolby Atmos

Dolby Atmos >  Dolby 7.1 > Dolby 5.1

Atmos 能给人带来的声音是彻底立体的，而不是 7.1 那种一个圈然后7个平面方位，和一个重低音。Atmos 将声音变为了对象，立体化了。将 7.1 的那个圈平面提升到了立体对象, 将平面的声音感受带到了 3D 立体的声音。这个在声音格式也不一样，如果设备不支持则会自动降级到 7.1/5.1 来播放。可以参看 [Quora的回答](https://www.quora.com/What-is-the-difference-between-Dolby-Atmos-and-Dolby-7-1) 以及  [Dolby Atmos 官方介绍](https://www.dolby.com/us/en/brands/dolby-atmos.html)

- Dolby Atmos

![](<https://sebs.club/hexoBlog/4137.jpg>)

- Dolby 7.1

  ![](<https://sebs.club/hexoBlog/image.jpeg>)

#### Dolby Vision 和 HDR 10

Dolby Vision > HDR 10

Dolby Vision 属于 HDR，HDR 10 是开源免费的。Dolby Vision 收费，当然付费了 Dolby 肯定会给你指导，而 HDR 10 肯定就自己来。HDR 10 和 Dolby Vision 最大的区别是 HDR 10 是静态的，Dolby Vision 是动态的 HDR，即随着画面变化会有不同的 HDR 配置有不同的效果。这个在 HDR10+ 上是有的。另外一点  Dolby Vision 支持 12bit 的颜色而 HDR 10 的10就是 10 bit，也就最高支持10bit的了。

- HDR10+ 和 Dolby Vision 理念几乎一样

![](<https://sebs.club/hexoBlog/hdr-02.jpeg>)

其实可以看出 Netflix 限制画质的唯一目的就是保护自己的版权，当然盗版猖獗，对如XX影视等等还是来说无用工。

这篇文章肯定有很多说的不够详细和正确，但还是希望对你看 Netlflix 有所帮助。以后也会不停修正，也欢迎给出建议和指出错误等。最后希望国产手机重视下 DRM，别让我们连高清视频都看不了。 