---
title: 通过 C# .NET 将 DOCM 转换为 ODP 
url_ignore: /zh/net/conversion/docm-to-odp/ 
description: 使用 C# 将 Word docm 文档转换为 PowerPoint odp 文件。在 ASP.NET 或其他 .NET 应用程序中转换多个文件。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="使用 C# 将 DOCM 转换为 ODP" h2="在 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台上构建 Microsoft Word DOCM 到 PowerPoint ODP 转换应用程序。" logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="如何使用 C# 将 DOCM 转换为 ODP" %}}

 为了使任何 Word 文档文件到 PowerPoint odp 演示文稿批量转换的过程自动化，我们将使用 [Aspose.Words for .NET](https://products.aspose.com/words/net) 和 [Aspose.Slides对于 .NET](https://products.aspose.com/slides/net) API。前者是用于处理或操作 Microsoft Word 文档的文字处理 API。而后者是一个演示文稿操作 API，可让您创建或修改 Microsoft PowerPoint 幻灯片。这两个 API 都是 [Aspose.Total for .NET](https://products.aspose.com/total/net) 包的一部分。您可以从 Nuget 直接 [下载](https://releases.aspose.com/)，也可以使用包管理器控制台中的以下命令。

{{% blocks/products/pf/agp/code-block title="包管理器控制台命令" offSpacer="true" %}}

```cs
PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通过 C# 将 DOCM 转换为 ODP 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Total 使开发人员只需几行代码即可轻松加载 DOCM 文件并将其转换为 ODP。

{{% /blocks/products/pf/agp/text %}}

1. 为 .NET 添加 Aspose.Total 的引用
1. 使用 [Aspose.Words.Document](https://reference.aspose.com/words/net/aspose.words/document) 类加载 DOCM 文件
1. 将 DOCM 文档保存为 HTML
1. 创建 [Aspose.Slides.Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) 对象
1. 在演示文稿内任何幻灯片形状的文本框架中导入 HTML 内容
1. 使用 [Aspose.Slides.Presentation.Save("output.odp", SaveFormat.Odp)](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) 保存文档)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

{{% blocks/products/pf/agp/text %}}

 所有主要操作系统都支持 Aspose.Total for .NET。只需确保您具有以下先决条件。 

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows 或与 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台兼容的操作系统。
-  Microsoft Visual Studio 等开发环境。
-  Aspose.Words for .NET &amp;用于 .NET DLL 的 Aspose.Slides 或用于项目中引用的 .NET DLL 的 Aspose.Total。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="此代码示例展示了如何使用 C# 将 DOCM 转换为 ODP" offSpacer="" %}}

```cs// 加载单页 Microsoft Word DOCM 文件
Aspose.Words.Document docm = new Aspose.Words.Document("sourceWordFile.docm");

// 将 DOCM 文件保存为 HTML 
docm.Save("filepath\\test.html", SaveFormat.Html);

// 要转换多页 DOCM 文档，请使用 Aspose.Words 分别将每个页面导出为 HTML，然后使用以下代码转换为 ODP。

using (Presentation odp = new Presentation()){

	// 访问演示文稿的默认第一张幻灯片
	ISlide slide = pres.Slides[0];

	// 添加自选图形以适应 HTML 内容 
	// 根据需要调整
	IAutoShape ashape = slide.Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, pres.SlideSize.Size.Width - 20, pres.SlideSize.Size.Height - 10);

	ashape.FillFormat.FillType = FillType.NoFill;

	// 将文本框添加到形状
	ashape.AddTextFrame("");

	// 清除添加的文本框中的所有段落
	ashape.TextFrame.Paragraphs.Clear();

	// 使用流阅读器加载 HTML 文件
	TextReader tr = new StreamReader("filepath\\test.html");

	// 在文本框中添加来自 HTML 流阅读器的文本
	ashape.TextFrame.Paragraphs.AddFromHtml(tr.ReadToEnd());

	// 保存 ODP 演示文稿
	odp.Save("filepath\\pres.odp", Aspose.Slides.Export.SaveFormat.Odp);
}

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="将 DOCM 转换为 ODP 的免费应用程序" sectionDescription="查看我们的 [DOCM 到 ODP 转换](https://products.aspose.app/words/conversion/word-to-odp) 的现场演示，具有以下优势。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 无需下载或设置任何东西。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 无需编写任何代码。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上传您的 DOCM 文件并点击“转换”按钮。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 您将立即获得生成的 ODP 文件的下载链接。" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

Aspose.Total for .NET 是完整的文档操作 API 包。 API 可轻松集成到任何基于 .NET 的应用程序中，以操作 Microsoft Word、Excel、PowerPoint、Outlook、PDF、图像、条形码和 100 多种其他格式。程序员可以轻松地使用它们在任何 .NET、C#、ASP.NET 和 VB.NET 应用程序中创建、修改、渲染、打印和转换最流行的文件格式，而无需任何其他软件。

    {{% /blocks/products/pf/agp/content %}}
{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="您还可以将 DOCM 转换为许多其他文件格式，包括下面列出的几种文件格式。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/docm-to-ppt/" name="DOCM 到 PPT" description="Microsoft PowerPoint 97-2003" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/docm-to-pptx/" name="DOCM 到 PPTX" description="打开 XML 表示格式" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/docm-to-pps/" name="DOCM 到 PPS" description="幻灯片放映" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/docm-to-pot/" name="DOCM 到 POT" description="Microsoft PowerPoint 模板文件" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/docm-to-ppsx/" name="DOCM 到 PPSX" description="幻灯片放映" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/docm-to-pptm/" name="DOCM 到 PPTM" description="启用宏的演示文件" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/docm-to-ppsm/" name="DOCM 到 PPSM" description="启用宏的幻灯片放映" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/docm-to-potx/" name="DOCM 到 POTX" description="Microsoft PowerPoint 模板演示文稿" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/docm-to-potm/" name="DOCM 到 POTM" description="微软 PowerPoint 模板文件" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/docm-to-odp/" name="DOCM 到 ODP" description="OpenDocument 演示格式" >}} 



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}