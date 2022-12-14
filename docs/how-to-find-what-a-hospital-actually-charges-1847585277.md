# 如何找到医院的实际收费

> 原文：<https://lifehacker.com/how-to-find-what-a-hospital-actually-charges-1847585277>

众所周知，在手术或程序发生之前，很难弄清楚你会为它支付多少钱。首先，医院不会对每个人收取相同的费用；他们与保险公司协商价格，并经常试图对确切数字保密。不过，也有好消息:一项联邦法律现在要求医院公布它们的价格清单。还有一个坏消息:列表通常很难找到，甚至更难阅读。



最近，当我们与调查记者丹·魏斯曼就升级 进行交谈时，这个话题出现了，他告诉我们，法律并没有使货比三家变得更容易——尽管这可能取决于你所在的医院和你居住的州。

现在，纽约时报已经 [发布了他们自己的指南](https://www.nytimes.com/2021/08/22/upshot/health-care-prices-lookup.html) 来查找你当地医院的价目表。这是一个多步骤的过程，你可能不会成功，因为许多医院没有遵守法律，或者选择了一种难以操作的方式。但还是有希望的。以下是他们的建议:

1.  **了解您确切的医疗保健计划**。举个例子，仅仅知道你已经团结起来是不够的。具体点。你有健康维护组织或 PPO 吗？你是通过雇主买的还是从 ACA 市场买的？

2.  **谷歌“价格透明”和医院的名字**。从那里，在医院的网站上找一些写着“收费清单”、“标准收费清单”、“全面的机器可读文件”或“协商价目表”的东西
3.  **寻找 CPT 代码**，代表特定程序或服务的 5 位数字。您可能需要打电话给医院，询问哪些 CPT 代码将为您的手术付费。
4.  **寻找价格**。如果您支付现金，可能会有基本费率、不同的保险公司以及他们收取的价格等栏目。

不幸的是，没有医院必须使用的标准文件格式，所以你能找到的可能会有所不同。还有一些根本没贴他们的。

## 这在实践中行得通吗？

尽管有各种警告，我并没有抱很高的希望，但我还是试运行了这个程序。

我试着对我附近的一家医院(在 UPMC 网络中)使用上面的步骤，最初的谷歌结果把我带到了一个价格评估者那里。我不得不点击屏幕，承认给出的价格只是一个估计，并不保证，即使这样，我也找不到一些常见的程序，如膝关节置换手术。这不是我要找的网页。

所以我回去在谷歌搜索中输入“标准费用”,这一次，我进入了一个不同的有价格的页面。我甚至在上面找到了售价 5109 美元的“全膝初级”。但是没有 CPT 代码，也没有按保险计划区分。医院的网页上说这是“基本费用”，保险后你最终支付的费用可能会有所不同。他们也把 [说成](https://www.upmc.com/locations/hospitals/passavant/patients-visitors/passavant-patient-info/cdm) :

> 因为您的保险计划福利决定了您的自付费用，并且您的服务付款是基于合同费率，所以医院 CDM 标准收费文件不是确定您将为医疗保健支付的自付费用的有用工具。

相反，他们建议你使用评估工具或打电话获得一个估计。顺便说一句，这个估计可能比你实际得到的费用高或低。

如果你的医院似乎没有遵守法律，纽约时报推荐 [在这里](https://www.cms.gov/hospital-price-transparency/contact-us) 提出投诉，但很难确定事实是否如此。如果我是一名病人或护理人员，试图为护理定价，我是不是也应该是一名律师*和*一名医疗结算专家？

或者，就此而言，我应该是一个字面上的机器吗？在所有的企业都说它的 chargemaster“不是一个有用的工具”之后，UPMC 的页面提供了一个机器可读的文件，他们说这个文件确实包括协商的价格，以及每个程序花费的现金。使用一个 [JSON 阅读器工具](http://jsonviewer.stack.hu) ，我可以很好地查看它，可以 Ctrl-F 并四处查看，但不能完全理解其中的所有内容。我*认为*我看到一个全膝关节置换的现金支付率为 3856 美元，谈判价格低至 395.24 美元，但我真的不确定我是否读对了。

未来还是有一点希望的:有了那些高深莫测但机器可读的价目表，第三方公司很可能会跳出来为你阅读。NYT 指出，绿松石有益健康。在我所在的地区，当地报纸为地区医院 提供了一种工具 [，这种工具使用起来有点笨拙，只显示了 70 种常见的程序，但结果很有启发性:在一家医院，保险公司为标价为 713 美元的乳房 x 光检查支付 99 美元到 362 美元不等的费用。医疗保险为同样的程序支付 66 美元；付现金的人要付 570 美元。](https://newsinteractive.post-gazette.com/hospital-price-transparency/)

这种价格差异是价格透明度如此重要的原因，但当你只是试图对自己的金钱和健康负责时，试图操纵数据是令人愤怒的。我希望，如果你去寻找当地医院的价目表，你会发现一些比我更有用的信息。