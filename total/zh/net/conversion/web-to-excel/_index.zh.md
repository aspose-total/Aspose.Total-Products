---
title: 使用 C# 提取网站数据并将网页 HTML 转换为 Excel 文件
description: 抓取网站网页以及将 HTML 导出到 Microsoft Excel 文档。开发 .NET 应用程序以将网站数据抓取为 XLS、XLSX 格式。
family: total
platformtag: net
feature: conversion
informat: WEB
outformat: EXCEL
otherformats: WORD POWERPOINT PDF IMAGES
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 C# 将网页转换为 Excel" h2="从 HTML 中提取网页数据。在 .NET 应用程序中将 HTML 导入 Microsoft Excel XLS、XLSX 格式。" >}}

{{% blocks/products/pf/feature-page-summary %}}

<p>网页是互联网的重要组成部分，它们包含对个人和组织有用的大量信息。 然而，一些用户可能会发现从网页中提取数据具有挑战性，尤其是当信息分布在多个页面时。在这种情况下，将网页转换为 Excel 格式可能是一个有用的解决方案。</p><br />
<p>将网页转换为 Excel 格式涉及将网页上的数据转换为可以轻松导入 Excel 的结构化格式。 可以使用专门为此目的设计的软件工具自动执行此过程。 这些工具可以从多个网页中提取数据并将它们转换成单个 Excel 文件，可以根据需要进行分析和操作。</p><br />

<p>但是，重要的是要强调在网络抓取方面负责任和道德实践的重要性。 尊重网站的服务条款，遵守法律规定，避免从事可能侵犯隐私或知识产权的活动，都是需要考虑的重要方面。</p>

<h2 class="heading-border">使用 Aspose.HTML 作为 Scraper API</h2>

<p>通过利用 Aspose.HTML for .NET API（它是 Aspose.Total for .NET 的一个组件），您可以无缝地创建自己的应用程序，用于分析 HTML 文档并从中提取数据。 这个 API 提供了一套全面的工具，大大简化了这项工作，使您能够有效地处理 HTML 内容。</p><br />

<p>在开发爬虫的过程中，数据选择器对于从 HTML 文件中识别和提取所需信息具有重要意义。 这些选择器通常使用 XPath、CSS 选择器或两者的结合，作为在 HTML 结构中定位特定数据元素的有价值的工具。 作为一种导航机制，这些选择器有助于精确定位和提取您要检索的数据。</p>

<h2 class="heading-border">Web Scrapping 可以执行的任务</h2>

<p>通过使用 Aspose.HTML for .NET，开发人员可以毫不费力地自动化从网页中提取数据的过程，使他们能够有效地完成以下网页抓取任务。</p><br />

1. [HTML Navigation](https://docs.aspose.com/html/net/html-navigation/) - 彻底分析 HTML 文档及其元素。受益于详细分析、元素迭代的自定义过滤以及使用 CSS 选择器或 XPath 的无缝导航等功能。
2. [下载网站](https://docs.aspose.com/html/net/download-website/) - 从 URL 高效地下载网站并自定义下载过程。 根据您的具体要求选择下载整个网站或特定网页。
3. [从 URL 下载文件](https://docs.aspose.com/html/net/download-file-from-url/) - 从 URL 轻松下载文件。
4. [从网站下载图像](https://docs.aspose.com/html/net/download-images-from-website/) - 从网站下载各种类型的图像。
5. [从网站下载 SVG](https://docs.aspose.com/html/net/download-svg-from-website/) - 使用 C# 从网站检索可缩放矢量图形 (SVG) 文件。

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何使用 C# 提取 Web 数据？" %}}

1. 使用 URL 从 URL 初始化 HTML 文档 [HTMLDocument](https://reference.aspose.com/html/net/aspose.html/htmldocument/htmldocument/) 构造函数。
2. 使用指定选择器 [QuerySelectorAll(selector)](https://reference.aspose.com/html/net/aspose.html.dom/document/queryselectorall/) 方法检索与选择器匹配的所有元素。
3. 遍历元素列表并根据您的特定要求格式化输出。
 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="网页抓取和转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或直接从 Visual Studio 的包管理器控制台安装。

二 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 子 API， [Aspose.HTML for .NET](https://products.aspose.com/html/net/) 和 [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) 将被整合。

或者，从 ZIP 文件中获取脱机 MSI 安装程序或 DLL [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "extract-data-using-csharp.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="使用 Aspose.Cells 将 HTML 转换为 Excel" %}}
<p>要将 HTML 转换为 XLS，您可以使用 Aspose.Cells for .NET API，它允许您仅用几行代码以编程方式执行此任务。 使用 API，您可以开发跨平台的应用程序，这些应用程序能够生成、修改、转换、呈现和打印各种 Excel 文件。 .NET Excel API 超越了简单的格式转换，因为它还可以将 Excel 文件呈现为图像、PDF、HTML、ODS、CSV、SVG、JSON、WORD、PPT 等。 这种全面的功能使其成为以行业标准格式交换文档的绝佳选择。</p><br />

<p>将 HTML 转换为 Microsoft Excel XLS，C# 中的 XLSX 对于 .NET 开发人员来说是一个简单的过程。 您只需几行代码即可实现此目的：</p><br />

1. 通过创建 Workbook 类的实例来加载 HTML 文件。
1. 通过调用 Workbook 实例上的 Save 方法，将加载的 HTML 转换为 Excel。

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "convert-html-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}