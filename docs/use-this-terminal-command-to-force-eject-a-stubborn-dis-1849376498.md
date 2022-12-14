# 使用此终端命令来强制从 Mac 中推出硬盘

> 原文：<https://lifehacker.com/use-this-terminal-command-to-force-eject-a-stubborn-dis-1849376498>

我们都经历过这种情况:你有一个外部硬盘或 USB 拇指棒插入你的 Mac，你准备分道扬镳。你把它拖到垃圾桶里，或者右击弹出它，只会得到一个臭名昭著的问候，“磁盘没有弹出，因为一个或多个程序可能正在使用它。”你环顾你的 Mac:没有应用程序打开，没有程序运行。不管是什么导致了弹射延迟，都不是你的错。彼得·帕克 睿智地说，“我错过了我的问题所在。”



不幸的是，macOS 把它变成了你的问题。你的电脑不释放你的磁盘可能有多种原因( [)我们在](https://lifehacker.com/why-finder-wont-let-you-eject-disk-images-and-how-to-f-1848320523) 之前已经讨论过了，但通常，主要问题是这样的:macOS 正在运行一个进程，访问你看不到的磁盘上的文件。这就是为什么，即使*所有的东西*都关闭了，你也能看到，你的 Mac *坚持*磁盘在使用中。我们有时都难以释怀。

也就是说，你的 Mac 并不总是让你晾在一边:偶尔，你会看到强制推出磁盘的选项，但即使是这种解决方案也有一个警告:你如何真正知道你的 Mac 目前没有向磁盘写入任何东西？如果您使用软件或从 Mac 上拔下磁盘来强制推出它，您可能会损坏它的数据。

幸运的是，有一个简单的解决方案，只要你使用终端没问题。在一个关于这个主题的 [Reddit 帖子](https://www.reddit.com/r/mac/comments/wfwxux/comment/iiwbpr5/?utm_source=share&utm_medium=web2x&context=3) 中，一个用户建议使用以下命令来快速结束 macOS 和你的硬盘之间运行的任何未知进程:

**sudo lsof/Volumes/{磁盘名称}**

“lsof”命令代表“列出打开的文件”，它的作用就是列出系统中所有打开的文件，并首先列出打开这些文件的进程。正因为如此，当用户不能卸载(或弹出)磁盘时，它经常被使用——t 这个命令告诉你哪个进程正在使用哪个文件，这是你仅仅通过使用表面级 macOS 看不到的。只要你自己停止使用硬盘，你就应该只看到 macOS 端的任何进程。

一旦您知道了有问题的进程，您就可以终止它，并安全地弹出磁盘而不用担心。为此，你需要打开活动监视器(按下 **Command + Space** 然后搜索“活动监视器”)。切换到**磁盘**标签，然后滚动“进程名称”列表，直到您看到终端中显示的那个。单击它，然后单击菜单栏顶部的(X)。最后，在弹出窗口中选择“退出”以结束该过程。现在，试着弹出你的磁盘:它应该马上离开你的电脑。

正如另一位用户在 Reddit 帖子中指出的，在许多情况下——至少在 macOS 上——罪魁祸首是 Quick Look。“快速浏览”功能允许您浏览文档、图像和其他文件，而无需先打开这些文件。如果运行此终端命令后弹出快速查看，此用户建议您尝试对外部磁盘上的另一个文件*而不是*使用快速查看。例如，打开 Mac 的主盘，快速浏览其中的一个文件:这个过程可以把东西抖松，让你可以毫无问题地弹出你的磁盘。