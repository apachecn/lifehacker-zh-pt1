# 如何用定时器关闭 Windows 10

> 原文：<https://lifehacker.com/how-to-shut-down-windows-10-with-a-timer-1846664830>

在 Windows 10 中，你不需要一个花哨的应用程序来在特定时间关闭电脑，但手头有一个也无妨。在你的命令提示符下放一行快速的通常是你需要的，让你的系统在设定的时间过后自动关闭，但是你也可以抓取一个应用程序来为你做所有的“硬”工作。

Watch

无论你选择哪种解决方案——我将在本文中介绍这两种——按时间关闭你的电脑是一个有用的技巧，放在你的后口袋里。例如，假设你正在复制一堆文件或下载一些大型游戏。如果你离开你的办公桌或者上床睡觉让这个过程继续，你可能不想让你的系统在这个过程结束后不必要地运行几个小时。当然，你可以设置它在一段时间后睡眠或关闭显示器，但这并不完全一样，这是假设睡眠你的系统不会导致更多的问题，正如我有时注意到的那样。

要开始使用这个基本方法，请弹出一个常规的**命令提示符**并键入以下内容:

`shutdown -s -t [seconds]`

显然，您希望将[秒]位替换为您希望系统在关闭前等待的秒数。这意味着你必须做一些数学计算。例如:

*   **5 分钟:** 300 秒
*   30 分钟:1800 秒
*   **1 小时:**3600 秒
*   6 小时:21600 秒

如果您算错了，或者发现您不再需要关机定时器，您随时可以通过键入以下内容来取消它:

`shutdown -a`

用一个 **"-r"** 标志替换 **"-s"** 标志将会重启你的电脑而不是关闭它，以防你因为任何原因而选择这条路。您还可以将您的命令转储到 Windows 快捷方式中，以防您不想再为命令提示符而烦恼。如果你需要额外的选项，你甚至可以创建多个不同时间的快捷方式。

否则，如果你宁愿有一个简单的应用程序可以为你做所有这些事情，我建议看看开源的**关机定时器经典**，在 [GitHub](https://github.com/lukaslangrock/ShutdownTimerClassic/releases) 和 [Windows 商店](https://www.microsoft.com/store/apps/9NTDG6C9BTTW) 上都有。把它放在你的系统上，你会得到一个方便的小界面来设置倒计时(也可以是小时/分钟/秒，而不仅仅是秒):

你甚至可以用密码锁定关机定时器，如果你想用这种荒谬有效的方法让你的孩子在该睡觉的时候离开*《我的世界》*:

不过，我最喜欢的是这款应用的不可错过的倒计时器。当你的系统重新启动的时候，你一点也不会感到惊讶，不像命令提示方法，它只会轻而易举地关闭你的系统。

如果你选择 GitHub 的关机定时器经典版，你可以选择一个独立的或者基于安装程序的版本。实际上我会推荐前者，因为这更像是一个“当我需要它的时候”的应用程序，你可能不需要在你的系统上实际安装而不是在你需要的时候启动它并设置一个关机定时器。也就是说，Windows Store 版本的应用程序将确保它始终保持最新和有效——这是两个版本都令人信服的理由。