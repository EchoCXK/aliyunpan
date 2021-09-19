# 阿里云盘小白羊版

#### 项目说明

这是我个人基于阿里云盘网页版开发的PC客户端，支持win7-11 32位/64位，macOS，linux

> **9.19：[v2.9.19预览版已发布](https://github.com/liupan1890/aliyunpan/issues/251)，可以尝鲜了**

  <br />
  
v1.6.29：[https://wwe.lanzoui.com/b01npsg8h](https://wwe.lanzoui.com/b01npsg8h)

v2.9.19：[https://wwe.lanzoui.com/b01nqc4gd](https://wwe.lanzoui.com/b01nqc4gd)

MacOS：[https://www.macwk.com/soft/aliyun-drive-xiaobaiyang](https://www.macwk.com/soft/aliyun-drive-xiaobaiyang)

Mac版由macwk.com使用自有签名打包dmg，可以简单点击安装了(不需要输入终端命令)，推荐下载此版本，已测MacOS10.12-11.4,兼容M1
<br />

已经发布在小众软件发现频道，大爱小众[meta.appinn.net](https://meta.appinn.net)

<br />

``````
2021年9月19日 已完成功能：
多账号登录、常用文件操作（新建文件夹、收藏、重命名、复制、移动、删除、详情、视频雪碧图）、
MPV 播放视频、在线预览图片、在线预览文本、上传文件、上传文件夹、批量改名、在线解压、
回收站、收藏夹、连接到远程 Aria2 下载、导入阿里云分享链接、

等待完成的功能：
相册功能、网盘和相册间文件互相复制、分享文件、聚合搜索、网盘内文件搜索、打包下载、
在线预览 Office、缩略图列表、瀑布流列表、文件同步盘、重复文件扫描、帐号间文件复制
``````

<br />

#

#### 为什么要用小白羊？

##### 更快
小白羊针对上传 大量小文件 做了优化：可以一次性快速地上传10万+个文件，比官方客户端上传快几倍！（12分钟 减少到 6分钟）<br />

小白羊针对上传 大文件 做了优化：采用更快的sha1计算方式，减少20%的CPU使用率，减少电脑卡顿并能节省十几分钟的上传前的计算时间！使用更合理的计算逻辑，对机械硬盘更友好<br />

小白羊针对下载 大量小文件 做了优化：可以一次性快速地下载数万个文件/文件夹，最多30文件同时下载，比官方客户端下载更快！（半小时 减少到 五分钟）<br />

小白羊对下载 大文件 做了优化：使用aria2下载，16 线程并发，单个文件就可以跑满你的宽带！（从平均2MB/s 提速到 40MB/s）<br />
详情参阅上面的对比录像和性能测试文档

##### 更好
小白羊可以显示文件夹体积，可以文件夹和文件混合排序(文件名/体积/时间)，并且文件名排序时更准确！

小白羊可以通过远程Aria2功能把文件直接下载到远程的VPS/NAS上

小白羊可以批量的对 大量文件/多层嵌套的文件夹 一键重命名

小白羊可以快速复制文件，可以直接预览视频的雪碧图，可以直接删除文件

小白羊仍在努力开发新功能，让大家使用起来更方便！


#

#### 常见问题
**1.Mac系统下载后提示：已损坏，您应该将它移到废纸篓？**

答：这是因为苹果系统要求程序被证书签名，一年688元，我没有买。请参照此链接方式二操作即可
https://blog.csdn.net/H_Zaiii/article/details/105730557

**2.怎样版本更新？怎样彻底卸载？**

答：版本更新：删除旧文件，下载新版解压即可。彻底卸载：删除小白羊的文件夹，删除C:\Users\用户名\AppData\Roaming\alipay这个文件夹即可

**3.可以选择多个文件后批量操作吗？**

答：当然可以，<br />
1.支持点击文件名前面的勾选按钮多选<br />
2.支持点击区间选择后，批量拖选<br />
3.支持配合Ctrl键、Shift键，实现自由选中多个文件，跟win10文件管理器多选操作是一样的<br />

**4.可以指定把文件下载到哪里吗？**

答：可以，<br />
在设置里勾选　[　每次下载都让我选择下载位置　]　后，就可以选择把文件下载到哪里了，<br />
默认的是按照阿里云盘的完整路径保存的，<br />
勾选后 就会去掉阿里云盘的完整路径，直接保存到你选择的文件夹里


**5.可以一次下载整个文件夹吗？可以一次上传整个文件夹吗？支持断点续传吗？**

下载：可以批量下载多个文件夹，没有文件数量的限制！下载文件时也支持断点续传，可以随时暂停恢复继续下载

上传：直接拖动要上传的文件夹扔到小白羊窗口上就可以了！也可以点击上传按钮选择文件夹！没有上传数量的限制！支持单个体积几百GB的大文件，上传文件时支持秒传，支持断点续传，可以随时暂停恢复继续上传！

**6.支持在线预览哪些文件？**

1.支持预览所有的音视频格式（支持音轨、字幕、倍速快放、倍速慢放、音量/对比度/亮度调整等等，具体操作请百度 “ mpv播放器 ” ）<br />
2.支持在线预览图片和txt<br />



