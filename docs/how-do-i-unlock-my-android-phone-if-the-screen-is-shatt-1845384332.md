# 我的安卓手机屏幕碎了怎么解锁？

> 原文：<https://lifehacker.com/how-do-i-unlock-my-android-phone-if-the-screen-is-shatt-1845384332>

这是一个突击测验。你放下手机。当你拿起它时，你注意到你打碎了屏幕。你是否:

***(a)** 用刻薄的话表达对自己笨拙的失望*

***(b)** 哀叹从未为你的设备设置指纹或人脸认证*

***(c)** 考虑一下，既然不能使用屏幕，你将如何访问手机内容*

Watch

***(d)** 想想你这个月还剩多少零花钱可以买一部新手机*

***(e)** 以上所有*

我不想把话放在生活黑客读者 **Dominique 的**嘴里，但我*怀疑*她在从 **(a)** 开始，转移到 **(c)** ，很可能向 **(e)** 投降。我们都经历过。

打碎手机屏幕一点都不好玩。虽然如果你擅长备份你的设备，你可能不会有太多的数据丢失要处理，但我怀疑许多人不会备份像他们的短信这样的内容，除非他们的手机为他们备份(即使这样，你是不是只备份短信，还是也包括多媒体？)

如果你在备份照片方面不够严谨，或者如果你的 Android 上有文件——而且只有你的 Android——当你的设备亲吻路面时，我可以从这里感觉到你的焦虑在增加。事实上，这可能就是多米尼克现在所经历的。她写道:

> “我有一台 lg stylo 4，屏幕已经坏了。我打不到解锁加载所需的号码。请帮帮忙！我需要我的消息！”

### 透过破碎的屏幕使用你的 Android:简单的方法

无论你对屏幕做了什么，有两种明显的方法可以访问你的 Android。我刚刚测试了第一个(也是最简单的)，它像一个*魔咒*一样工作，尽管你可能需要跑到你最喜欢的当地零售商(或亚马逊)去拿一件小设备。

你要做的是:看看你手机的接口。你需要一个适配器来插入这个连接器——如果你用的是安卓系统，可以是某种 USB，如果你用的是 iPhone，可以是 USB-C 或 Lightening。在您的情况下，您需要一个 USB-C(公)转 USB-A(母)适配器，看起来有点像这样:

你可以把它插到你的手机上，然后把一个普通的电脑鼠标直接插到开口端。(是的，使用“男性”和“女性”命名约定感觉非常过时。)

一旦你做到这一点，你的手机应该立即识别你的鼠标作为输入设备。然后，你就可以像使用手指一样使用它了——调出你的 PIN 输入，点击数字，以及做你通常在 Android 上做的一切事情。我的建议？用它给自己发电子邮件，无论你想在手机上获取什么。或者，在你考虑如何处理破碎的设备时，为你的设备做一个可靠的备份(记得单独保存任何发短信的照片或视频，或者使用 [一款可以备份文本和媒体的应用](https://play.google.com/store/apps/details?id=com.riteshsahu.SMSBackupRestore&hl=en_US&gl=US) )。

如果你碰巧有一个带有多个 USB-A 端口的 USB-C 集线器，你可以插入鼠标和键盘，使这个过程更加容易。

### **透过破碎的屏幕使用你的安卓系统:艰难的道路**

如果你想玩得更开心，你可以用电脑“侵入”你的手机，假设你之前已经启用了一个叫做 USB 调试的有趣的小设置。要在我的 Pixel 上这样做，你需要调出关于手机的**设置>，然后向下滚动并多次点击**版本号**来解锁**开发者选项**。然后回到主**设置**屏幕，点击系统，点击**高级**，点击**开发者选项**，向下滚动一点直到你可以启用 **USB 调试**。具体步骤可能因您的 Android 而异。**

从那里，从制造商的网站上为你的设备找到合适的 [ADB 驱动程序](https://developer.android.com/studio/run/oem-usb)——你可能想直接去谷歌一下。(为了节省你的时间，这里有 [LG 的驱动](https://www.mylgphones.com/lg-android-usb-device-drivers) 。我有一个 Pixel，所以我需要 [SDK 平台工具](https://developer.android.com/studio/releases/platform-tools.html) ，可能还有 [谷歌 USB 驱动](https://developer.android.com/studio/run/win-usb) 。)

将它们安装在您的系统上。打开命令提示符或终端，导航到存放*adb.exe 的文件夹。(*我没有 LG 手机，所以不能给你测试这个。值得一提的是，解压 SDK 平台工具后可以很容易地找到 adb.exe 的*文件。)*

从那里，尝试输入`adb reboot`并按回车键。除非您已经授权 ADB 访问您的手机，否则不会发生任何情况。这是你需要在解锁的手机上做的事情，这意味着你需要*已经*做了这件事，解锁技巧才能工作。

假设您之前已经跳过了所有这些关卡——我确实说过这是一条艰难的道路——那么您将能够使用这些命令来解锁您的设备:

*亚行外壳输入按键事件 26*
*亚行外壳输入触摸屏刷卡 930 880 930 000*
*亚行外壳输入文本 XXXX*
*亚行外壳输入按键事件 66*

显然，把“XXXX”换成你的密码。如果您想要更简单的方法，只需复制并粘贴这一整行:

*T2`adb shell input keyevent 26 && adb shell input touchscreen swipe 930 880 930 000 && adb shell input text XXXX && adb shell input keyevent 66`*

我刚刚在我的 Pixel 上测试了这个，它工作得非常好。也就是说，在使用这个方法之前，你有太多的工作要做，所以我认为键盘/鼠标技术——“简单的方法”可能是最好的。但是，您可能希望先发制人地完成这些步骤，以便从您的计算机上为您的新手机启用 ADB 访问。这样，万一灾难再次来袭，你可以*也可以*使用亚行的 [为你的设备做一个备份](https://9to5google.com/2017/11/04/how-to-backup-restore-android-device-data-android-basics) 。

如何访问该备份的内容是一个额外的过程，但至少您可以...什么事？老实说，确保你的手机总是通过谷歌的工具/服务备份可能是你最好的选择。当然，要确保你在 Android 上存储的任何东西都有备份。你永远不知道你的手机下一次会在什么时候来一次信心的飞跃。

* * *

*<small>你是否有一个让你夜不能寐的技术问题？厌倦了对您的 Windows 或 Mac 进行故障诊断？寻找关于应用程序、浏览器扩展或实用程序的建议来完成特定任务？让我们知道！在下面的评论或者邮件中告诉我们</small>*[*<small></small>*](mailto:david.murphy@lifehacker.com?subject=Tech%20911)<small>*<small>。</small>T15】*</small>

<small></small>