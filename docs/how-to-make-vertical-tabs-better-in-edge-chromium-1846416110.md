# 如何在边缘铬中更好的制作垂直标签

> 原文：<https://lifehacker.com/how-to-make-vertical-tabs-better-in-edge-chromium-1846416110>

今天更新你的 Edge Chromium 浏览器，你会得到一个有趣的小提示，询问你是否要启用浏览器新的垂直标签功能。作为一个总是喜欢尝试新事物的人，我决定采纳浏览器的建议。

Watch

当然，这在浏览器的左侧给了我一个非常可怕的标签列表。(是的，我 [真的需要清除](https://lifehacker.com/how-to-konmari-your-browser-tabs-1832760171)——这只是填充我的 1440p 显示器的整个垂直空间的列表的一小部分。)

你会注意到我在 Reddit 上的所有链接都混在了一起。这是有意的:我一直在寻找让垂直标签栏更易于管理的方法——因为它现在看起来更像一个轮廓，而不是位于我浏览器顶部的大量标签——我偶然发现了一些技巧，以考虑你是否正在试驾新界面 。

在我开始之前，要知道你的侧边栏的默认外观并不一定是永久的。点击标签栏右上角的小**<**箭头将整个折叠成一系列图标。将鼠标放在它们上面，你的标签就会展开。我承认，我不认为这是最有用的设置，但它至少让我的浏览器看起来超级干净。

至于组织黑客，我建议在浏览器的地址栏中输入 **edge://flags** 并启用三种不同的标志:

*   **#edge-tab-groups:** *允许用户将选项卡组织成视觉上不同的组，例如，将与不同任务相关联的选项卡分开。*
*   **# edge-tab-groups-auto-create:***如果启用了选项卡组，会自动为用户创建组。*
*   **# edge-tab-groups-collapse:***如果启用了选项卡组，则允许选项卡组可折叠和可展开。*

这些不会对你已经打开的标签做任何事情，但是它会把你从同一个域创建的新标签放到一个方便的标签组中，你可以随意折叠和展开。虽然你仍然可以把你的标签栏弄得乱七八糟，但是至少把你的标签分组在一起会帮助你更好地管理它。

你可以采取的另一种方法——替代或补充“分组”功能——是使用一个扩展来组织你的打开标签列表。我喜欢 [**标签管理器**](https://chrome.google.com/webstore/detail/tab-organizer/kkcbifggchajpkagcpagenpfghbplghc?hl=en) ，它自动将你所有的标签按网址排序。当你点击键盘热键时，这个扩展会自动排序你的标签，但是我发现把它设置成按时间间隔自动排序标签更有用。眼不见心不烦。

最后，你还可以启用另外两个浏览器标志来获得乐趣，而不是因为它们会帮助你保持标签有序。再次拉起 **edge://flags/** 打开:

*   **#tab-hover-cards:** *使包含选项卡信息的弹出窗口在悬停在选项卡上时可见。这将替换选项卡的工具提示。*
*   **# tab-hover-card-images:***如果启用了选项卡悬停卡，则在选项卡悬停卡中显示预览图像。*

现在，当你将你的鼠标悬停在你的垂直栏中的任何标签上时，你会得到一个可爱的弹出窗口，给你网站的完整标题和图片预览:

尽管如此，我仍然在等待最大的调整——调整垂直标签栏的大小，这样我就可以在默认情况下看到更多一点的网站名称。当微软在 Edge Chromium 的测试版中测试该功能时，这个是可能的，所以希望它在某个时候返回。