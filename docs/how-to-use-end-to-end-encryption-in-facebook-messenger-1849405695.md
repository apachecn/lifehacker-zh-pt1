# 如何立即在 Facebook Messenger 中使用端到端加密

> 原文：<https://lifehacker.com/how-to-use-end-to-end-encryption-in-facebook-messenger-1849405695>

Meta 可能不是数字隐私的堡垒(很可能是它的敌人)，但时代可能正在改变。8 月 11 日星期四，该公司宣布了 ，他们正在测试 Facebook Messenger 的端到端加密(E2EE)作为*的默认设置*，这意味着所有 Messenger 用户的聊天都会受到保护，除非他们选择不被监视。虽然这些变化预计不会在一段时间内对所有用户生效，但现在有一些方法可以在 Messenger 中启用 E2EE。



## 端到端加密的工作原理

在典型的消息传递中，文本被公开地存储在你的设备、你发送它们的设备以及消息传递平台的服务器上 ( 即 Facebook Messenger 本身 ) 。任何有权访问存储这些信息的设备的人都可以阅读这些信息，包括信息平台的主机。这使得像 Meta 这样的公司很容易将你的信息交给当局，如果这样的请求通过的话。

然而，使用端到端加密，信息不是以纯文本形式发送和存储，而是被“打乱”。“如果你试图阅读一条加密的信息，它会显示为一堆无法辨认的字符，使得拦截变得毫无用处。

要解读这条信息，你需要一把“钥匙”。“为了发送消息，该密钥可以是您的设备，也可以是接收者的设备。这两个设备是唯一能够解读你的特定对话的设备——e 尽管 Meta 正在促进这些信息的传递，但它没有办法为自己或任何来询问它们的人解读这些信息。

Meta 正在测试将 E2EE 作为 Messenger 中所有对话的默认消息协议，这将为所有用户提供开箱即用的好处。然而，目前测试还处于初始阶段，据报道 Meta 最初只有几百个用户。从统计上来说，你不属于那个测试组，所以你需要使用 Messenger 的隐藏 E2EE 功能来利用安全优势。

## 如何在 Facebook Messenger 中启用端到端加密

这个隐藏的功能被称为“秘密对话”，使用起来相当简单(尽管有点隐蔽)。首先，打开您希望 E2EE 加入的聊天，然后轻按显示屏顶部的联系人姓名。在“更多操作”下，点击“转到秘密对话”，Messenger 将立即打开一个新的 E2EE 聊天，并以独特的黑白主题完成，以表明它不是一个普通的 Messenger 聊天。

问题是另一个用户需要使用兼容秘密对话和 E2EE 的设备和 Messenger 应用程序。如果不是，当您试图在秘密对话中发送任何内容时，会收到一条错误消息。您也不能与群组进行秘密对话——在您开始在多方聊天中分享任何敏感信息之前，请记住这一点。你将不能发送 gif，进行音频或视频通话，或者在秘密对话中付款，这在某种程度上限制了该功能。

尽管如此，出于 E2EE 的目的，秘密对话可以完成工作:请记住，对于您开始秘密对话的每个联系人，您将在您的应用程序中看到两次聊天。如果你想保护你的信息，确保你点击的是带锁图标的线程，而不是普通的对话。也就是说，Messenger 在启用秘密对话时会说得很清楚，所以如果您在聊天中没有看到任何关于它的内容，请假设 E2EE 没有激活。

## 在脸书上使用 E2EE 的其他方式

秘密对话也不是 Messenger 的唯一 E2EE 选项:还有一种叫做消失模式的东西。Meta，然后是脸书， [在 2020 年 11 月](https://messengernews.fb.com/2020/11/12/swipe-up-discover-vanish-mode-for-messenger-and-instagram/) 推出了它，宣传它是一种类似 Snapchat 的消息体验:退出聊天后，文本会消失，应用程序会对任何拍摄线程截图的人说闲话。然而，该公司*没有*强调的是，消失模式的聊天是完全端到端加密的。

要使用消失模式，您只需从某个 Messenger 聊天窗口的底部向上滑动。当你这样做时，你会看到“向上滑动以打开消失模式”，以及一个进度环，显示你还需要拉起多少才能启用该功能。一旦戒指被填满，放开:聊天将切换到消失模式，加密所有消息并在你退出时删除它们。您也可以在聊天设置中启用或禁用消失模式:滚动到页面底部，轻按“消失模式”，然后切换滑块。

一旦 Meta 默认推出 E2EE，它实际上是从 Messenger 中移除了消失模式，但你仍然可以为消失的消息启用类似的功能。该公司保留了 Instagram 版本的消失模式，但它不是 E2EE，所以它远没有那么安全。