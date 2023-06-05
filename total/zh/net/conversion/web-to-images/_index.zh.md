---
title: 使用 C# 将网页 HTML 转换为图像
description: 抓取网站网页并将 HTML 导出到图像。开发 .NET 应用程序以将网站数据抓取为 JPEG、PNG、GIF、BMP 等格式。 
family: total
platformtag: net
feature: conversion
informat: WEB
outformat: IMAGE
otherformats: WORD EXCEL POWERPOINT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 C# 将网页转换为图像" h2="从 HTML 网页中提取网站数据。在 .NET 应用程序中将 HTML 转换为 JPG、GIF、PNG、BMP 图像。" >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">为什么要将网页转换为图像？</h2>
<p>将网页转换为图像在多种情况下都很有用。这是许多应用程序的共同要求。 在某些情况下，需要将整个网页捕获为图像，包括屏幕上不可见的部分。 这对于生成网站预览、捕获收据和发票或出于法律目的存档网页很有用。它可用于创建用于文档或测试目的的网页屏幕截图。 它还可用于创建网页的缩略图或预览，以用于搜索结果或图像库。 无论您是构建桌面应用程序还是 Web 应用程序，都有许多选项可用于使用 C# 将网页转换为图像。</p><br />

<p>使用 C# 将网页转换为图像可以提供多种好处，包括：</p><br />
<ul>
<li>改进的可访问性： 对于有视觉障碍或其他残疾的人来说，图像可以更容易阅读和理解。</li>
<li>增加便携性： 图像可以轻松共享或嵌入到其他文档或应用程序中。</li>
</ul>
<p>使用 C# 将网页转换为图像也会带来一些挑战，包括：</p><br />
<ul>
<li>有限的格式支持： 某些 API 或工具可能不支持所有图像格式，或者可能对输出图像的大小或分辨率有限制。</li>
<li>兼容性问题： 某些网页可能无法在所有浏览器中正确呈现，或者可能需要特定设置或插件才能正确显示。</li>
</ul>
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何使用 C# 将网页转换为图像？" %}}
要使用 C# 将网页转换为图像，您可以使用 Aspose.HTML for .NET API，它提供将 HTML 页面转换为图像格式（包括 JPEG、PNG 和 TIFF）的功能。</p>

1. 使用其中可用的构造函数之一加载 HTML 文档 [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/). 您可以从文件、HTML 代码、流或 URL 加载 HTML。
2. 创建一个新的实例 [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) 并将 ImageFormat 属性设置为 JPEG。默认情况下，格式属性设置为 PNG。
3. 利用 [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) Converter 类中的方法将 HTML 文档保存为 JPEG 文件。 您需要将 HTMLDocument、ImageSaveOptions 和输出文件路径作为参数提供给 ConvertHTML() 方法。
4. 生成的 JPEG 文件将保存到指定的文件路径。
 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Web 抓取和图像转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或直接从 Visual Studio 的包管理器控制台安装。

二 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 子API， [Aspose.HTML for .NET](https://products.aspose.com/html/net/) 将被整合。

或者，从 ZIP 文件中获取脱机 MSI 安装程序或 DLL [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "convert-web-pages-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}