# 尽快更新 Google Chrome 来修补这个安全漏洞

> 原文：<https://lifehacker.com/update-google-chrome-asap-to-patch-this-security-flaw-1849499843>

如果看起来你刚刚更新了 Chrome，那是因为你确实更新了。谷歌 [周三将其网络浏览器更新至版本 105](https://lifehacker.com/everything-new-in-chrome-105-1849478347) ，引入了新功能和安全补丁。然而，仅仅几天后，谷歌又提供了另一个更新。该公司通常不会在没有充分理由的情况下发布惊喜更新，他们有一个理由:Chrome 105 包括一个零日安全漏洞。



谷歌在周五发布的博客文章 中宣布了这一更新。新版本 105.0.5195.102 现在可用于 Windows、Mac 和 Linux，并且只引入了一个补丁:

> *   [$ TBD] [ [1358134](https://crbug.com/1358134) ] **High** CVE-2022-3075: Insufficient data verification in Mojo. *was reported anonymously on August 30th, 2022*

只有一个更改的更新可能看起来不太重要，但在这种情况下，它很重要——尽快更新很重要。该漏洞被识别为 CVE-2022-3075，是一个数据验证不充分的问题。这不是很好，但通常不会非常紧迫；在大多数情况下，我认为谷歌会等到下一次更新时才会向用户推出这样的补丁。但谷歌已经证实，该漏洞的利用存在于野外，使该漏洞成为零日安全问题。

零日是一个安全漏洞，开发者以前不知道这个漏洞。相比之下，大多数安全缺陷都是由开发人员或向开发人员披露这些缺陷的第三方发现的，从而允许所述开发人员为该漏洞创建补丁并在任何人发现如何利用该漏洞来攻击用户以获取个人利益之前修复该漏洞。

不幸的是，显然有人已经知道如何利用 CVE-2022-3075，这就是为什么谷歌在周三的大 105 更新后这么快就推出了一个令人惊讶的漏洞补丁。

## 如何更新谷歌 Chrome 来修补这个零日安全漏洞

谷歌希望所有的 Chrome 应用都能免受这种零日威胁。因此，该公司可能会在发布时自动将您的浏览器更新到最新版本。虽然你的 Chrome 实例可能已经更新了，但自动更新过程可能需要几周时间，这让你在此期间很容易受到攻击。

为了确保你现在的安全，最好手动触发更新。点击浏览器窗口右上角的三个点，然后选择**帮助>关于谷歌浏览器**。允许 Chrome 搜索新的更新。如果有，点击**重启**安装。