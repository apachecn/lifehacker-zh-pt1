# 如何保护自己免受新的 Windows 10 和 11 安全漏洞的影响

> 原文：<https://lifehacker.com/how-to-protect-yourself-from-the-new-windows-10-and-11-1847338342>

在最新版本的 Windows 中发现了一个新的安全漏洞，黑客可以利用该漏洞远程安装程序，窃取数据和密码，甚至将用户锁定在他们的电脑之外。微软表示，所有比 Windows 10 版本 1809 更新的 Windows 版本都会受到影响——包括 Windows 11 测试版。



根据 [微软的漏洞报告](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2021-36934) ，该漏洞源于“多个系统文件上过度许可的访问控制列表(ACL)，包括安全账户管理器(SAM)数据库。”该漏洞尚未被成功利用，但微软的报告警告说，鉴于该漏洞的严重性，这种攻击是“可能的”。为了执行攻击，攻击者需要直接访问一个人的计算机——无论是物理上，还是通过诱骗他们下载恶意软件加载的文件。一旦黑客获得了访问权，他们就可以给自己完全的管理员控制权并“安装程序”;查看、更改或删除数据。或者创建具有完全用户权限的新帐户。

 [https://lifehacker.com/embed/inset/iframe?id=twitter-1417467063883476992&autosize=1](https://lifehacker.com/embed/inset/iframe?id=twitter-1417467063883476992&autosize=1) 

微软表面上会在 Windows 10 和 11 的未来安全更新中修补这个问题，但在此之前用户应该小心。实践常识性的数据安全，如不点击未知的电子邮件链接或从粗略的网站下载文件，以及使用可靠的反恶意软件程序。

还有一个临时的解决方法，可以限制对 PC 上易受攻击的系统文件的访问。这将把黑客拒之门外，但会使使用系统还原功能恢复文件变得更加困难，因此它不是一个长期的解决方案。尽管如此，如果您想完全保护自己免受可能的安全漏洞，这是值得考虑的。

首先，您需要限制对“**% windir % \ system32 \ config**”*系统文件夹的访问。*

1.  *使用任务栏搜索**“PowerShell”**(注意:您也可以在命令提示符下执行这些步骤。)*
2.  *在结果中右键点击**“Windows PowerShell”**，点击**“以管理员身份运行”***
3.  *在 PowerShell 中，键入以下命令: `icacls %windir%\system32\config\*.* /inheritance:e`*
4.  *按下**“回车”***

*接下来，您需要删除系统还原点。确保在您限制对 **%windir%\system32\config** 的访问后*执行此操作。**

1.  *在 Windows 文件资源管理器中右键单击**“我的电脑”**，选择**“属性”***
2.  *点击左侧菜单中的**“系统保护”**。*
3.  *在**“可用驱动器”**列表中，单击选中您的本地硬盘，然后单击**“配置”***
4.  *点击**“删除”，**然后**“继续”**确认。*

*一旦旧的备份被删除，你可以创建一个新的系统还原点，如果你想:回到系统保护标签，突出你的驱动器，然后点击**“创建”**添加还原点的描述(如日期和时间)，然后点击**“好的”***

*【】SlashGear*