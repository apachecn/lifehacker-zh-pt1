# 如何开启 Zoom 新的端到端加密

> 原文：<https://lifehacker.com/how-to-turn-on-zooms-new-end-to-end-encryption-1845499757>

Zoom 端到端加密(E2EE)的技术预览版将在下一次 Windows、Mac 和 Android 应用更新中向免费和高级用户推出，iOS 和 iPad 也将很快推出。启用 Zoom 的 E2EE 使视频通话更加安全，但有一个问题:Zoom 的 E2EE 禁用了其他几个功能，包括私人聊天、临时会议室等。



我们将讨论使用 Zoom 的 E2EE 设置需要做出的所有妥协，但首先让我们谈谈 Zoom 如何加密您的视频会话，以及为什么您应该考虑不惜代价打开它。

根据 Zoom 的博客文章 宣布新的加密选项，Zoom E2EE 使用相同的“默认情况下保护 Zoom 会议安全的 256 位 AES-GCM 加密”，但 Zoom 管理加密和与参与者共享密钥。启用了 E2EE 的用户在本地生成自己的加密密钥，然后在通话中与其他用户共享。Zoom 永远不知道密钥，无法解密会议数据。

如果这令人困惑，底线是 E2EE 使呼叫之外的任何人都无法访问会议或查看其数据，包括 Zoom 本身。隐私保护的提升是一个受欢迎的变化，尤其是在新冠肺炎提高了这款应用的受欢迎程度，导致 Zoom 的隐私政策受到审查之后。

如上所述，打开变焦的 E2EE 会禁用几个关键的变焦功能:

*   临时会议室
*   群组投票
*   在主持人之前加入
*   云记录
*   流动
*   现场转录
*   一对一私人聊天
*   满足表情符号反应

好消息是，每次会议都可以启用和禁用 E2EE，因此您不会永久失去对这些功能的访问。这使您可以自由地为您主持的每个呼叫设置所需的隐私和功能级别。

此外，请记住，该功能正处于“第一阶段”的技术测试中，因此，到 2021 年“第二阶段”推出时，其中一些限制可能会被取消。但是，为了在第 1 阶段使用 E2EE，所有参与者必须在加入加密会议之前打开该设置。

### 如何在缩放中打开端到端加密

您需要在用户设置中打开 Zoom 的 E2EE，然后才能在会议中使用它:

1.  [登录 Zoom 的门户网站。](https://zoom.us/signin)T3】
2.  进入**设置>会议>安保。**
3.  Enable **“允许使用端到端加密已启用。”**
4.  出现确认更改的提示时，点击**“打开”**。
5.  接下来，选择您的默认安全级别。**“增强加密”**如果你想继续使用 Zoom 的所有功能(你仍然可以使用 E2EE 进行单独通话)，这是最好的选择。选择**“端到端加密”**将对所有会议使用 E2EE，但对于您主持的呼叫，受限功能将始终被禁用。
6.  点击**“保存”**