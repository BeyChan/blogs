# OS学习栈

## 序言

**最近正在重新系统的学习iOS，收集了一些自己认为不错的博客和资料和大家分享。**

## 底层

[iOS底层原理总结 - 探寻OC对象的本质](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Faa7ccadeca88)
[iOS底层原理总结 - 探寻Class的本质](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F74db5638f34f)
[iOS底层原理总结 - 探寻KVO本质](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F5477cf91bb32)
[isa和Class](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fhalfrost.com%2Fobjc_runtime_isa_class%2F)--参考：(

[What is a meta-class in Objective-C?](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttp%3A%2F%2Fwww.cocoawithlove.com%2F2010%2F01%2Fwhat-is-meta-class-in-objective-c.html)、[iOS 程序 main 函数之前发生了什么](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttp%3A%2F%2Fblog.sunnyxx.com%2F2014%2F08%2F30%2Fobjc-pre-main%2F)、[从 NSObject 的初始化了解 isa](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fgithub.com%2FDraveness%2FiOS-Source-Code-Analyze%2Fblob%2Fmaster%2Fcontents%2Fobjc%2F%25E4%25BB%258E%2520NSObject%2520%25E7%259A%2584%25E5%2588%259D%25E5%25A7%258B%25E5%258C%2596%25E4%25BA%2586%25E8%25A7%25A3%2520isa.md%23shiftcls)、[深入解析 ObjC 中方法的结构](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fgithub.com%2FDraveness%2FiOS-Source-Code-Analyze%2Fblob%2Fmaster%2Fcontents%2Fobjc%2F%25E6%25B7%25B1%25E5%2585%25A5%25E8%25A7%25A3%25E6%259E%2590%2520ObjC%2520%25E4%25B8%25AD%25E6%2596%25B9%25E6%25B3%2595%25E7%259A%2584%25E7%25BB%2593%25E6%259E%2584.md%23%25E6%25B7%25B1%25E5%2585%25A5%25E8%25A7%25A3%25E6%259E%2590-objc-%25E4%25B8%25AD%25E6%2596%25B9%25E6%25B3%2595%25E7%259A%2584%25E7%25BB%2593%25E6%259E%2584)、[刨根问底 Objective－C Runtime（1）－ Self & Super](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttp%3A%2F%2Fchun.tips%2F2014%2F11%2F05%2Fobjc-runtime-1%2F)

)
--参考:(、、*)[如何正确使用runtime](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fhalfrost.com%2Fhow_to_use_runtime%2F)[深入理解Objective-C：Category](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Ftech.meituan.com%2F2015%2F03%2F03%2Fdiveintocategory.html)[《Objective-C +load vs +initialize》](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttp%3A%2F%2Fblog.leichunfeng.com%2Fblog%2F2015%2F05%2F02%2Fobjective-c-plus-load-vs-plus-initialize%2F)[iOS动态性(二)可复用而且高度解耦的用户统计埋点实现](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F0497afdad36d)[KVO中的缺陷](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttp%3A%2F%2Fwww.mikeash.com%2Fpyblog%2Fkey-value-observing-done-right.html)
--参考：（）[深入研究 Block 用 weakSelf、strongSelf、@weakify、@strongify 解决循环引用](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fhalfrost.com%2Fios_block_retain_circle%2F)[iOS 如何实现 Aspect Oriented Programming](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fhalfrost.com%2Fios_aspect%2F)[KVC原理剖析](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F1d39bc610a5b)[KVC解析（一） —— 基本了解](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F910ef801f4f9)[KVC解析（二） —— 不可不知的赋值深层次原理](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F1b8f9d11c8c4)[KVC解析（三） —— 不可不知的取值深层次原理](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F1a44bc7c0f6f)[KVC解析（四） —— keyPath的深度解析](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F42d488071d48)[KVC解析（五） —— KVC几种典型的异常处理](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fbd5dada8cc6a)[KVC解析（六） —— KVC容器类及深层次原理](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F034822741acd)[KVC解析（七） —— KVC正确性的验证](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F2402ceb7dc98)[AutoreleasePool底层实现原理 - 简书](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3D_Aq1v-VaHJvRstPvaGOgjEOwEMD45xh8JkgOZjTP9AbHI2TBdNxml6EUpTgT0VTS%26wd%3D%26eqid%3Dd1de880500004b83000000025c91c816)[OS底层原理总结 - RunLoop](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fde752066d0ad)[RunLoop入门 看我就够了](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F2d3c8e084205)[RunLoop已入门？不来应用一下？](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fc0a550d2ac97)[深入理解RunLoop - 简书](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3DXL5QmV7MUDVcjn_xSIULwCsqVVa0bcm658FDOcLV2701Q8IVV-Gn1bj4mq0IFPL6%26wd%3D%26eqid%3Ddf19aacd00007acf000000035c6ab681)[深入理解RunLoop](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fblog.ibireme.com%2F2015%2F05%2F18%2Frunloop%2F)









## CALayer

[CALayer图层简介](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fe5e3a950cbc5)

## CoreGraphics

[Quartz 2D编程指南(一)—— 简介](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fdb39e1f5a5de)
[Quartz 2D编程指南(二)—— Quartz 2D概览](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F2d7ea3e1481e)
[Quartz 2D编程指南(三)—— 图形上下文](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F9961bfbb07e3)
[Quartz 2D编程指南(四)—— Paths路径(一)](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F25f31a35c0b0)
[Quartz 2D编程指南(五)—— Paths路径(二)](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fd50aa8f0529a)
[Quartz 2D编程指南(六)—— 颜色和颜色空间](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fad476ac4a342)
[Quartz 2D编程指南(七)—— 变换](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F6f2322ea78f5)
[Quartz 2D编程指南(八)—— Patterns图案样式](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fb300ecd98531)
[Quartz 2D编程指南(九)—— 阴影](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F9b9cdce415b1)
[Quartz 2D编程指南(十)—— 渐变](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fe4fc20e7c785)
[Quartz 2D编程指南(十一)—— 透明](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fcae95f5d2d33)
[Quartz 2D编程指南(十二)—— Quartz 2D中的数据管理](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fe00c5ea34c5c)
[Quartz 2D编程指南(十三)—— 位图图像和图像蒙版(一)](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fa2d359416240)
[Quartz 2D编程指南(十四)—— 位图图像和图像蒙版(二)](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F3e44d805a495)
[Quartz 2D编程指南(十五)——Core Graphics图层绘制](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F5a8237bafc95)
[Quartz 2D编程指南(十六)——PDF文档创建，查看和转换](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F478c52aa4e28)
[Quartz 2D编程指南(十七)—— PDF文件解析](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F4ccd16550089)
[Quartz 2D编程指南(十八)——PostScript转换](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F39372dc412c1)

以上文章全部读完对Quartz 2D会有一个全面的了解

## ImageI/O

[iOS中ImageIO框架详解与应用分析](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fmy.oschina.net%2Fu%2F2340880%2Fblog%2F838680)

[iOS](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3DyO23WI_YOdy6e1TUgCgOZLJiuHdjy5BgfDzSFeuth2g1S-2ItXsld9Q1_2L0bYsh%26wd%3D%26eqid%3Dd3b821100011c42c000000035ceca03f)

[图片压缩限制大小最优解](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3DyO23WI_YOdy6e1TUgCgOZLJiuHdjy5BgfDzSFeuth2g1S-2ItXsld9Q1_2L0bYsh%26wd%3D%26eqid%3Dd3b821100011c42c000000035ceca03f)



## 多线程

[深入浅出GCD](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttp%3A%2F%2Fcocoa-chen.github.io%2F2018%2F03%2F01%2F%25E6%25B7%25B1%25E5%2585%25A5%25E6%25B5%2585%25E5%2587%25BAGCD%25E4%25B9%258B%25E5%259F%25BA%25E7%25A1%2580%25E7%25AF%2587%2F)(滴滴工程师博客)
[iOS 多线程：『GCD』详尽总结](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F2d57c72016c6)
[iOS多线程-各种线程锁的简单介绍 - 简书](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3Dxestk1fwy_0SLFbTBG6JIyiUksZ9mliTo92eznTtzMQ1EM7qeR4K5_jk3M7CQJVZ%26wd%3D%26eqid%3Df27eda7500001f9b000000035c447820)
[线程死锁](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttp%3A%2F%2Fios.jobbole.com%2F82622%2F)
[NSOperation的进阶使用和简单探讨](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.cnblogs.com%2Fblogwithstudyofwyn%2Fp%2F10011029.html)

## 网络

##### 原理

[一篇文章带你详解 HTTP 协议（网络协议篇一）](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F6e9e4156ece3)
[一篇文章带你熟悉 TCP/IP 协议（网络协议篇二）](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F9f3e879a4c9c)
[iOS安全系列之一：HTTPS](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttp%3A%2F%2Foncenote.com%2F2014%2F10%2F21%2FSecurity-1-HTTPS%2F)
[浅析HTTPS中间人攻击与证书校验](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fd4822bc289cf%3Futm_campaign%3Dharuki%26utm_content%3Dnote%26utm_medium%3Dreader_share%26utm_source%3Dweixin%26from%3Dgroupmessage%26isappinstalled%3D0)
[SSL三种类型证书有什么区别](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Ffreessl.wosign.com%2F2018110901.html)
[为什么Tcp连接的创立需要三次握手 ,而断开需要四次挥手_CSDN博客](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3Dqu9avSNQ89BSGQ-IK2nCwCaFqWWqclJ9u_lEnlrk9sTYxKzQhuT1rpw6fkRqmBS9MZcDT7oc7yF2qRlNr_xNIAvnbaJGZaOIL61lG8o0Rt_%26wd%3D%26eqid%3Da793cca20005739f000000035c6e7b73)
[iOS中长连接的那些事](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F85535a17372b)

##### 基础

[NSURLSession系列（一） - NSURLConfiguration](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fbbba5fa0a24e)
[NSURLSession系列（二）- 创建Session对象](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F561a74378aa9)
[NSURLSession系列（三）-请求过程](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fc122d251ce21)
[NSURLSession系列（四）- 设置缓存](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fb51ce49be183)
[NSURLSession系列（五）- cookie](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F39d46fb5f3d5)
[NSURLSession系列（六）-内存管理](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fed7c07774e86)
[CFNetwork框架详细解析 —— CFNetwork编程指导之简介（一）](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fe57bd4fb786e)
[CFNetwork框架详细解析—— CFNetwork编程指导之CFNetwork概念（二）](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F32e616ab6c0d)
[CFNetwork框架详细解析 —— CFNetwork编程指导之流的处理（三）](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F2a1a0b24b0b9)
[CFNetwork框架详细解析—— CFNetwork编程指导之与HTTP服务器通信（四）](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F5eddae3863ca)
[CFNetwork框架详细解析 —— CFNetwork编程指导之与验证HTTP服务器通信（五）](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fd665d4c834a7)
[CFNetwork框架详细解析—— CFNetwork编程指导之使用FTP服务器（六）](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F175a94fb49e8)
[CFNetwork框架详细解析 —— CFNetwork编程指导之使用网络诊断（七）](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Faf46ff445370)
[NSURLRequestCachePolicy 缓存策略讲解](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3DAPYO1kjFbeWObbaT1Sv2DQRx_4xo-H5htmj-i3o_MliCOtA_fZhw-Jrv3-RxZpYJ%26wd%3D%26eqid%3Da570f72100079d1c000000035ca0b681)
[利用CocoaHttpServer搭建手机本地服务器](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F2cd0333bfa31)
[CocoaHTTPServer 和 视频边下边播](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F962c65c7fc5a)

##### 即时通讯

[iOS即时通讯，从入门到“放弃”？](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F2dbb360886a8)
[iOS:protocolBuffer + ysocket 实现即时通讯](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F30386c192e09)
[NSUrlSession](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.cnblogs.com%2Fzanglitao%2Fp%2F4082334.html)
[WebSocket介绍和Socket的区别](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3D9HSF1BdgLXzzxu_0RPxow6vrv1tIMIcmbwH4HcynO0OjLCnerKCS29tqaacm8qRHvEbwj3Tq8KBvGJ3_kuwO3q%26wd%3D%26eqid%3Db7fe65590003b180000000035c70c644)
[WebSocket协议：5分钟从入门到精通](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.cnblogs.com%2Fchyingp%2Fp%2Fwebsocket-deep-in.html)
[MQTT 协议基本介绍](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fecde412d2eeb)
[BSDSocket搭建服务器](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fctinusdev.github.io%2F2017%2F08%2F13%2FBSDSocketServer%2F)
[MQTT-Client-Framework](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fgithub.com%2Fckrey%2FMQTT-Client-Framework)

##### 服务器

[NodJs搭建Web服务器](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fd76ecf5ed690)

## WebKit

[WKWebView详解](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fcloud.tencent.com%2Fdeveloper%2Farticle%2F1033743)(非常详细)
[深入剖析 WebKit](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fming1016.github.io%2F2017%2F10%2F11%2Fdeeply-analyse-webkit%2F)(滴滴技术专家戴铭博客)
[JavaScriptCore全面解析 （上篇）](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fcloud.tencent.com%2Fdeveloper%2Farticle%2F1004875)(详细易懂的文章)
[JavaScriptCore全面解析 （下篇）](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fcloud.tencent.com%2Fdeveloper%2Farticle%2F1004876)(详细易懂的文章)
[深入浅出 JavaScriptCore](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F3f5dc8042dfc)
[深入理解JavaScriptCore](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fmp.weixin.qq.com%2Fs%2FH5wBNAm93uPJDvCQCg0_cg%3Futm_medium%3Dhao.caibaojian.com%26utm_source%3Dhao.caibaojian.com)
[深入剖析 JavaScriptCore](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fming1016.github.io%2F2018%2F04%2F21%2Fdeeply-analyse-javascriptcore%2F)(滴滴技术专家戴铭博客)

## 存储

[iOS - keychain 详解及变化](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.cnblogs.com%2Fjunhuawang%2Fp%2F8194484.html)
[iOS Keychain使用说明](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fa432b32276a9)
[Swift保存RSA密钥到Keychain](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fc1e9bffc76f4)

## 音视频

[AVFoundation编程指南文档-思维导图总览](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fa79aa9895c7a)
[AVFoundation开发秘籍笔记-01AVFoundation入门](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F0cb70e6fc357)
[AVFoundation开发秘籍笔记-02播放和录制音频](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fbd333acf62e2)
[AVFoundation开发秘籍笔记-03资源和元数据](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F77ee886584cd)
[AVFoundation开发秘籍笔记-04视频播放](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fdae440ae2030)
[AVFoundation开发秘籍笔记-05AVKit用法-AVPlayerViewController](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F6707dbe9bcca)
[AVFoundation开发秘籍笔记-06捕捉媒体](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F73dcf80b30d9)
[AVFoundation开发秘籍笔记-07高级捕捉功能之录制视频缩放](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F74b6a30f418f)
[AVFoundation开发秘籍笔记-07高级捕捉功能之人脸识别](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F0a9dfd0cb30c)
[AVFoundation开发秘籍笔记-07高级捕捉功能之机器码识别(条码扫描)](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F9440f8010bcd)
[AVFoundation开发秘籍笔记-08读取与写入媒体](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F9da06111fe5a)
[AVFoundation开发秘籍笔记-09媒体的组合和编辑](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Ff0d294395d6a)
[AVFoundation开发秘籍笔记-010混合音频初接触](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fd8a13c2e8426)
[AVFoundation开发秘籍笔记-11创建视频过渡效果](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F180bbd05006e)
[AVFoundation开发秘籍笔记-12动画图层内容CoreAnimation](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F82dc76230562)
[AVFoundation视频处理的时间CMTime](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F417618d25524)
[基于AVPlayer实现的视频播放器](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.cnblogs.com%2Fziyi--caolu%2Fp%2F5673160.html)
[一步一步教你实现iOS音频频谱动画（一）](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fjuejin.im%2Fpost%2F5c1bbec66fb9a049cb18b64c)
[一步一步教你实现iOS音频频谱动画（二）](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fjuejin.im%2Fpost%2F5c26d44ae51d45619a4b8b1e)

## 直播

[菜鸟也能懂的 - 音视频基础知识。](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F614b3e6e641a)
[【如何快速的开发一个完整的iOS直播app】(原理篇)](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fbd42bacbe4cc)
[【如何快速的开发一个完整的iOS直播app】(播放篇)](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F7b2f1df74420)
[【如何快速的开发一个完整的iOS直播app】(采集篇)](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fc71bfda055fa)
[【如何快速的开发一个完整的iOS直播app】(美颜篇)](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F4646894245ba)
[1小时学会：最简单的iOS直播推流（一）项目介绍](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F30b82f1e61a9)
[1小时学会：最简单的iOS直播推流（二）代码架构概述](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F77fea6e0eccb)
[1小时学会：最简单的iOS直播推流（三）使用系统接口捕获音视频](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F19d07d5dd788)
[1小时学会：最简单的iOS直播推流（四）如何使用GPUImage，如何美颜](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F7b484ee0fb15)
[1小时学会：最简单的iOS直播推流（五）yuv、pcm数据的介绍和获取](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fd5489a8fe2a9)
[1小时学会：最简单的iOS直播推流（六）h264、aac、flv介绍](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F92122e0dfdba)
[1小时学会：最简单的iOS直播推流（七）h264/aac 硬编码](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F0f0fc1ec311a)
[1小时学会：最简单的iOS直播推流（八）h264/aac 软编码](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fe8f56af4895d)
[1小时学会：最简单的iOS直播推流（九）flv 编码与音视频时间戳同步](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F24410b604ea9)
[1小时学会：最简单的iOS直播推流（十）librtmp使用介绍](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F5c79b3b00d68)
[1小时学会：最简单的iOS直播推流（十一）sps&pps和AudioSpecificConfig介绍（完结）](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F4297342231ee)
[开发视频直播APP需要了解的技术原理和技术细节](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3D9UsmGOSA6PBg0LAetygZwpT41CXZoGLDzkdkrqmSVsc1f2TKdxu_UgUERoVzyCGqiNpubF--Qu8YZZMkE-rtxuiBvfoS2hxDPF7d5qohETO%26wd%3D%26eqid%3D96bc485c0003372a000000035c3e835a)(只是讲了使用哪些技术和SDK)
[GPUImage详细解析](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F7a58a7a61f4c)
[GPUImage详细解析（二）](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F1eea8bf8451e)
[GPUImage详细解析（三）- 实时美颜滤镜](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F2ce9b63ecfef)
[GPUImage详细解析（四）模糊图片处理](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F5e6563d37921)
[GPUImage详细解析（五）滤镜视频录制](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F4701d006b514)
[GPUImage详细解析（六）-用视频做视频水印](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F722d65bac58d)
[GPUImage详细解析（七）文字水印和动态图像水印](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F965df0f28014)
[GPUImage详细解析（八）视频合并混音](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fc2b9af191c7d)
[GPUImage详细解析（十）用GPUImage和指令配合合并视频](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Ffe7f06d26b4f)
[GPUImage详细解析（十一）美颜+人脸识别](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F095107abc7ba)
[GPUImage详细解析（十二）Sobel边界检测](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F6d2cdb446ec3)

以上文章全部读完对直播开发将有全面的了解

## 内购

1. iOS内购IAP（一） —— 基础配置篇(一)
2. iOS内购IAP（二） —— 工程实践（一）
3. iOS内购IAP（三） —— 编程指南之关于内购（一）
4. iOS内购IAP（四） —— 编程指南之设计您的应用程序的产品（一）
5. iOS内购IAP（五） —— 编程指南之检索产品信息（一）
6. iOS内购IAP（六） —— 编程指南之请求支付（一）
7. iOS内购IAP（七） —— 编程指南之促进应用内购买（一）
8. iOS内购IAP（八） —— 编程指南之提供产品（一）
9. iOS内购IAP（九） —— 编程指南之处理订阅（一）
10. iOS内购IAP（十） —— 编程指南之恢复购买的产品（一）
11. iOS内购IAP（十一） —— 编程指南之准备App审核（一）
12. iOS内购IAP（十二） —— 一个详细的内购流程（一）
13. iOS内购IAP（十三） —— 一个详细的内购流程（二）
14. iOS内购IAP（十四） —— IAP的收据验证（一）
15. iOS内购IAP（十五） —— IAP的收据验证（二）

## 推送通知

[iOS开发 iOS10推送必看(基础篇)](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Ff5337e8f336d)
[iOS开发 iOS10推送必看(高阶1)](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F3d602a60ca4f)
[iOS10推送必看UNNotificationServiceExtension - 简书](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3DmQzLfmjc0tihAuIIeYAn-x825Z16pefCnYrPqQBL9jZ7F9XpRwm8NWL6yG5SEzgW%26wd%3D%26eqid%3D9d6ee35e003391bf000000035cadafda)
[iOS10推送必看UNNotificationContentExtension](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F45933f5450a4)

## 架构

[iOS应用架构谈 开篇](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fcasatwy.com%2Fiosying-yong-jia-gou-tan-kai-pian.html)（规范）
[iOS应用架构谈 view层的组织和调用方案](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fcasatwy.com%2Fiosying-yong-jia-gou-tan-viewceng-de-zu-zhi-he-diao-yong-fang-an.html)
[iOS应用架构谈 网络层设计方案](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fcasatwy.com%2Fiosying-yong-jia-gou-tan-wang-luo-ceng-she-ji-fang-an.html)
[iOS应用架构谈 本地持久化方案及动态部署](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fcasatwy.com%2Fiosying-yong-jia-gou-tan-ben-di-chi-jiu-hua-fang-an-ji-dong-tai-bu-shu.html)
[iOS应用架构谈 组件化方案](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fcasatwy.com%2FiOS-Modulization.html) (重要)
[私有库管理和模块化管理](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttp%3A%2F%2Fwww.pluto-y.com%2Fcocoapod-private-pods-and-module-manager%2F)
[iOS组件化 - 简书](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3DRLIaytUKkbH6LLDH9qDatMbK5MtaRT7JmfxQFyg6awjPORwxeMu8ZVFdGQRsl3Tm%26wd%3D%26eqid%3D8fa16ad60002e2bc000000035c812ecd)
[快速理解 设计模式六大原则](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3DWBtkhIlxzmSTL_2CGai-keTRD-4e0F9uzJvON2l3iOeklOVIdgcX_Ocovn7uisViVak_hJ9hjI09ONHBldkTbOhVS0ajPTzDPR8ykmK9Po7%26wd%3D%26eqid%3Df5c2df480000fb70000000035c9c86f6)（我面58的时候被问过）
[iOS设计模式的六大设计原则 - 简书](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3DhNuRS4PdZ3kbFyzKC72ubvbonWdoczfsSTTX-TrAEGOb7LuJHgnqf6QX1-sFsqrH%26wd%3D%26eqid%3Df5c2df480000fb70000000035c9c86f6)

## 调试

[xcode中debug的一些用法(lldb)](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F7f9a274c798f)
[深入iOS系统底层之crash解决方法介绍](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fcf0945f9c1f8)
[xcode8 instruments测试工具使用一](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F921e90c510f9)
[Xcode8 Instruments 测试工具使用二](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F57a079bc8a61)
[Xcode8 Instruments 测试工具使用三](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Ffc517cfdd25e)
[Xcode8 Instruments 测试工具使用四](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F65930b5364a9)
[Xcode8 Instruments 测试工具使用五](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fa871f5a784aa)
[ios 单元测试【单元测试编码规范】](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F70d5c6eaecbc)
[iOS Crash处理方法（一）：利用MethodSwizzle避免Crash](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F3ae2f9589fae)
[iOS Crash处理方法（二）：自己编写代码定位Crash](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F035d9e86334a)

## 性能优化

[iOS 保持界面流畅的技巧](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fblog.ibireme.com%2F2015%2F11%2F12%2Fsmooth_user_interfaces_for_ios%2F)
[iOS启动时间优化](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttp%3A%2F%2Fwww.zoomfeng.com%2Fblog%2Flaunch-time.html)
[RunLoop应用之性能优化 - 恋~时光 - 博客园](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3DFsid8y4rZqxcqw-1sBV95yRKo7t8IB8jD7uekjwnB53W2ZJZfMCC0xlUznnd-T6GFK-puh91TMSJTmhlCozyCa%26wd%3D%26eqid%3Ddf19aacd00007acf000000035c6ab681)
[UITableView优化--使用runloop,优化耗时较多的事件 - i..._CSDN博客](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3DbUPBKwRiutMtsXBO2K4NWVNexCl-0VoD2nJlafYuetu8uVkIX9jhFQvMT_VfQC7bbqL10Wtbiyvh3izM_mFGkXSnuDUAJNLDYGL4Ow0y1TW%26wd%3D%26eqid%3Ddf19aacd00007acf000000035c6ab681)
[iOS视图渲染以及性能优化总结 - 简书](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3DRnXH41WbwSU3Q8GOYa2CVrOf0LfWSEe8HqIXxZjkuvgAqbzUH3vvELZxkRspGqPQ%26wd%3D%26eqid%3Ddad9992b00028321000000035c6c0706)
[NSCache和NSURLCache、网络缓存优化 - Mike_zh - 博客园](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3D81V7s5eF6tL_eQG1BVhF-W3Q-DAHig48sk5Lov7UfX5I-_y_6UnfjBkz0OQr5KGAq_CvpeSLbd-awQucnNO7La%26wd%3D%26eqid%3Dc29a16180001785d000000035c7799b1)
[深度优化iOS网络模块](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttp%3A%2F%2Fwww.cocoachina.com%2Fios%2F20161115%2F18085.html)
[对界面流畅性方面的见解](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttp%3A%2F%2Fblog.ibireme.com%2F2015%2F11%2F12%2Fsmooth_user_interfaces_for_ios%2F)（大神）
[IM UI性能优化之异步绘制 - 简书](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3DU6nLZvDMXqKv4D8cKQrBGyOV8gDjgqm__EMPITqDu4ADG_a-Kl6-mehORcQe-DUD%26wd%3D%26eqid%3Dd50586db00023bf7000000035c8325fc)
[FPSLabel](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fgithub.com%2Fibireme%2FYYText%2Fblob%2Fmaster%2FDemo%2FYYTextDemo%2FYYFPSLabel.m)
[skyming/iOS-Performance-Optimization](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fgithub.com%2Fskyming%2FiOS-Performance-Optimization) (一篇对优化文章的全面收集)
[如何精确度量 iOS App 的启动时间 - 简书](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3DCZLpShYB9zvThQ84mWab_i3NfmC-RDOD2igcX96x5DICbsk3YnhNNXZGmWxE4PfM%26wd%3D%26eqid%3De2f13b030014f2db000000035cac313a)
[深入剖析 iOS 性能优化](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fming1016.github.io%2F2017%2F06%2F20%2Fdeeply-ios-performance-optimization%2F%23more)(滴滴技术专家戴铭博客)

## 安全

iOS - 使用FMDB进行数据库加密 - 简书
Xcode动态调试原理 - 简书
iOS-对App进行砸壳 - 简书
1. APP安全机制（一）—— 几种和安全性有关的情况
2. APP安全机制（二）—— 使用Reveal查看任意APP的UI
3. APP安全机制（三）—— Base64加密
4. APP安全机制（四）—— MD5加密
5. APP安全机制（五）—— 对称加密
6. APP安全机制（六）—— 非对称加密
7. APP安全机制（七）—— SHA加密
8. APP安全机制（八）—— 偏好设置的加密存储
9. APP安全机制（九）—— 基本iOS安全之钥匙链和哈希（一）
10. APP安全机制（十）—— 基本iOS安全之钥匙链和哈希（二）

## 第三方框架源码解析

一行行看SDWebImage源码(一)
一行行看SDWebImage源码(二)
SDWebImage4.0源码探究(一)面试题 - 简书
SDWebImage源码阅读系列(5)
SDWebImage源码解析（一）——WebCache+Manager模块
SDWebImage源码解析（二）——SDImageCache缓存模块
SDWebImage源码解析(三)——SDWebImage图片解码/压缩模块 - 简书
SDWebImage源码解析（四）——SDWebImage图片下载模块
AFNetworking到底做了什么？
AFNetworking到底做了什么？(二)
AFNetworking到底做了什么？(终)
AFNetworking之于https认证
AFNetworking源码阅读系列(6)
FMDB 使用进阶 - 简书
FMDB源码阅读系列(3)
fmdb中databasequeue的使用,避免死锁 - codeTao - 博客园
[iOS 开发] WebViewJavascriptBridge 从原理到实战 - 简书
[iOS]JPVideoPlayer 3.0 使用介绍
[iOS]JPVideoPlayer 3.0 源码解析
[iOS]仿微博视频边下边播之封装播放器
[iOS]仿微博视频边下边播之滑动TableView自动播放
[iOS]从使用 KVO 监听 readonly 属性说起
[iOS]如何重新架构 JPVideoPlayer ?
MJExtension框架源码分析 - 飞鱼湾 - 博客园
优雅的PromiseKit
AsyncDisplayKit的使用
Texture
Alamofire框架的使用一 —— 基本用法

## 零散知识点

[iOS开发 简化view controller](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fmp.weixin.qq.com%2Fs%2FKa_a3eAkTqSNJRJrtHZX0g)
[iOS 实现自动登录（从低级做法到高级做法）](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fmp.weixin.qq.com%2Fs%2FG1PLOhRF6j8J30dgQVOraA)
[深入iOS系统底层之程序映像](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fmp.weixin.qq.com%2Fs%2FyG0WIX4EC6XSf_WJDiXbgQ)
[面试驱动技术 - Block看我就够了【干货】](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fmp.weixin.qq.com%2Fs%2FNuF4qAoN6ZRDK2v2i1rmfA)
[iOS组件化方案对比](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fmp.weixin.qq.com%2Fs%2FN0DPrkX1uW_4pwRFb9L1-w)
[深入iOS系统底层之crash解决方法介绍](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fmp.weixin.qq.com%2Fs%2FpeNU5WMXYDi9AaTrSt_Pag)
[iOS开发之Notification与多线程](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fblog.csdn.net%2Fhmh007%2Farticle%2Fdetails%2F61920956)
[iOS开发 之 不要告诉我你真的懂isEqual与hash!](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F915356e280fc)
[使用LLDB调试程序](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fcasatwy.com%2Fshi-yong-lldbdiao-shi-cheng-xu.html)
[获取UUID和keychain存储代码](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F17fd9d10c281)
[Block里面的weak-strong理解 - 简书](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3DHptrbi7V8vFNVCTOwY8lvS1yGOBwfyNzxfVlolc-pUfS9OPjDNa0OE7NHiKbIEcP%26wd%3D%26eqid%3Dd48df02e0004a615000000035c6d8967)
[iOS 开发者必会的几项技能，不知不用你就OUT了](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F970559cfdb6f)
[Xcode 10.1新功能及解决的问题](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fmp.weixin.qq.com%2Fs%2FNN5mjvYOo3eayTBDG60Eow)
[关于iOS学习进阶的必读一些博客总结](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fc47c24ab1e76)
[UIViewController中各方法调用顺序及功能详解 - 简书](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3DDpcmdEM7tmXNGL9NQCo_W0Hepgg0woteGTOgmXoZX2j6MW-P52_atFcpMK2aqYXk%26wd%3D%26eqid%3Df7cc398000037b5e000000035c42a4d0)
[iOS中的SEl和IMP到底是什么](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F4a09d5ebdc2c)
[iOS 程序启动过程](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fa0b9ce0497f9)
[为什么Swift比OC快? - 简书](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3D3PzPiHIfmeU7jzuh4odi7TKPTnhKTFJWRH9cL09aB_H3T2L-FODQul1pSIVtQbQB%26wd%3D%26eqid%3D9b6db215000f240d000000035c711d80)
[深入理解@autoreleasepool - 简书](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3D0YxdrYRYX5eofLo_HBSVtMUBSfhvzZxgnMlWpRlt8pqYkwG91Mi4hyPuh81LP9D5%26wd%3D%26eqid%3D802ec4c80002fe41000000035c7167b5)
[YYKit @autoreleasepool 使用，优化内存](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.cnblogs.com%2FXXxiaotaiyang%2Fp%2F5118737.html)
[iOS加密方式（RSA签名、加密、AES）](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F49a17e4a1ec4)
[公钥与私钥,HTTPS详解 - 迪米特 - 博客园](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3DyUMJTVWzU8S8tMkVvCUWem2QceZjM85HVVnBXdQrb41p-G_lcMIieQU284A6ibK44PEe9CKxMtb0wxgjUYL49q%26wd%3D%26eqid%3D88a90fac00890530000000035c77c63e)
[自动埋点](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fmp.weixin.qq.com%2Fs%2Fu-HmmrSAgtER1N2pKxCm0A)
[网易HubbleData无埋点SDK在iOS端的设计与实现](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fneyoufan.github.io%2F2017%2F04%2F19%2Fios%2F%25E7%25BD%2591%25E6%2598%2593HubbleData%25E6%2597%25A0%25E5%259F%258B%25E7%2582%25B9SDK%25E5%259C%25A8iOS%25E7%25AB%25AF%25E7%259A%2584%25E8%25AE%25BE%25E8%25AE%25A1%25E4%25B8%258E%25E5%25AE%259E%25E7%258E%25B0%2F)
[iOS类方法load和initialize详解 - 简书](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3DAGeXtFysaBNjLNvjjYCG_JsN46bdNVN5_LyjR-eJNy9LK-4hRBesztwspRtsbhaO%26wd%3D%26eqid%3Db1dd29af000336e5000000035ca220c9)
[NSTimer循环引用解决方案 - 简书](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.baidu.com%2Flink%3Furl%3DZXT018rDLs3GxFi-92eJivnGG9Wq2nephnpzt5JuOxsSYQlsg04_SGhhlH6eZo9e%26wd%3D%26eqid%3Db7220f5a00027311000000035ca22a99)（补充：造成循环引用的原因是runloop持有timer,timer持有target，用timer的block方法也可以防止泄露）
[iOS PassKit Wallet 开发](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F9adfccdb661b)
[iOS 初中级工程师简历指北](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fmp.weixin.qq.com%2Fs%2FIs3mgjm2QwhlTHmN3ynR1A)
[非越狱下 iOS代码注入&HOOK微信登录](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fmp.weixin.qq.com%2Fs%2FcdzF6uQR7G1dJj1F2ogpQg)
[iOS里的动态库和静态库](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fmp.weixin.qq.com%2Fs%2FKvdv-dpz1JQoXhtYjZ1hkg)

##### 自动化打包

[iOS持续集成—Jenkins(最新最全)](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F9cb3d8c8c78d)
[详解Shell脚本实现iOS自动化编译打包提交](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fzackzheng.info%2F2015%2F12%2F27%2Fan-automated-script-for-building-archiving-submission-sending-emails%2F)(运行脚本上传到Fir&AppStore,内容较详细)
[iOS 命令行打包(新手)](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F8db4192228fe)(打包的命令，内容简洁)
[企业级APP通过网页实现下载安装](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2F1d5514b4e06a)

## Swift

[SwiftUI](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fdeveloper.apple.com%2Ftutorials%2Fswiftui%2Fcreating-and-combining-views)
[SwiftUI 的 DSL 语法分析](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fzhuanlan.zhihu.com%2Fp%2F68294674%3Futm_source%3Dwechat_session%26utm_medium%3Dsocial%26s_s_i%3DL9nC%252FV%252Bwk%252FHripk8OHmbSPnX5FFjgBjFbDbTW%252BdARiI%253D%26s_r%3D1)

## 编译原理

[iOS编译过程的原理和应用](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fgithub.com%2FLeoMobileDeveloper%2FBlogs%2Fblob%2Fmaster%2FiOS%2FiOS%25E7%25BC%2596%25E8%25AF%2591%25E8%25BF%2587%25E7%25A8%258B%25E7%259A%2584%25E5%258E%259F%25E7%2590%2586%25E5%2592%258C%25E5%25BA%2594%25E7%2594%25A8.md)
[iOS汇编入门](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fgithub.com%2FLeoMobileDeveloper%2FBlogs%2Fblob%2Fmaster%2FBasic%2FiOS%2520assembly%2520toturial%2520part%25201.md)
[深入iOS系统底层之程序中的汇编代码](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fmp.weixin.qq.com%2Fs%2F1pHDP8LyRiDtT5SqVymLfw)

## 知名学习网站与博客

[iOS Example](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fiosexample.com%2F)[Cocoa Controls](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fwww.cocoacontrols.com%2F)(这两个网站收集了大量的开源组件和库，并且进行了非常详细的分类。)
[Open-Source iOS Apps](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fgithub.com%2Fdkhamsing%2Fopen-source-ios-apps)(收录了很多优秀的，完整的开源iOS App，并做了详细分类，专门标出了上架了App Store的开源iOS APP)
[Awesome iOS](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fgithub.com%2Fvsouza%2Fawesome-ios)(一个值得推荐的网站，里面包含了 iOS 开发的方方面面，而且内容都是经过人工筛选、分类的。)
[NSHipster](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fnshipster.com%2F)(AFNetworking 和 Alamofire 的作者 Mattt维护的网站,主要关注一些不常用的iOS知识点)
[知名开发者](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fgithub.com%2Fipader%2FSwiftGuide%2Fblob%2Fmaster%2F2019%2FSwiftDevelopers.md)
[开源项目团队](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fgithub.com%2Fipader%2FSwiftGuide%2Fblob%2Fmaster%2F2019%2FSwiftDevelopmentTeam.md)
[iOS 开发舆图](https://link.juejin.im/?target=https%3A%2F%2Flinks.jianshu.com%2Fgo%3Fto%3Dhttps%3A%2F%2Fming1016.github.io%2F2019%2F07%2F29%2Fios-map%2F)