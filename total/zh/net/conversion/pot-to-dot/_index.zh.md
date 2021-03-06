---
title: 通过 C# .NET 将 POT 转换为 DOT 
url_ignore: /zh/net/conversion/pot-to-dot/ 
description: 使用 C# 将 PowerPoint pot 文档转换为 Word dot 文件。在 ASP.NET 或其他 .NET 应用程序中转换多个文件。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="使用 C# 将 POT 转换为 DOT" h2="在 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台上构建 Microsoft PowerPoint POT 演示文稿到 Word DOT 文档转换应用程序。" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOT" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="POT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" apiHomeLink="https://products.aspose.com/total/family/" codeSamplesLink="https://github.com/aspose-total" liveDemosLink="" docsLink="https://docs.aspose.com/total/net" installationsDocsLink="https://docs.aspose.com/total/net" nugetLink="https://www.nuget.org/packages/aspose.total" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/total/net" learnAsLink="https://docs.aspose.com/total/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C# 将 POT 转换为 DOT" %}}

 为了使任何 PowerPoint pot 演示文稿到 Word dot 文件批量转换的过程自动化，我们将使用 [Aspose.Slides for .NET](https://products.aspose.com/slides/net) 和 [Aspose.Words对于 .NET](https://products.aspose.com/words/net) API。前者是一个 PowerPoint 演示文稿操作 API，可让您创建或修改 Microsoft PowerPoint 幻灯片。而后者是用于处理或操作 Microsoft Word 文档的文字处理 API。这两个 API 都是 [Aspose.Total for .NET](https://products.aspose.com/total/net) 包的一部分。您可以直接从 Nuget [下载](https://downloads.aspose.com/) 或使用包管理器控制台中的以下命令。

{{% blocks/products/pf/agp/code-block title="包管理器控制台命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通过 C# 将 POT 转换为 DOT 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Total 使开发人员只需几行代码即可轻松加载 POT 文件并将其转换为 DOT。

{{% /blocks/products/pf/agp/text %}}

1. 添加 Aspose.Slides for .NET 和 Aspose.Words for .NET 的引用
1. 使用 [Aspose.Slides.Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) 类加载 PowerPoint POT 演示文稿
1. 将文档保存到 [MemoryStream](https://docs.microsoft.com/en-us/dotnet/api/system.io.memorystream?view=net-5.0) 对象中
1. 创建 [Aspose.Words.Document](https://reference.aspose.com/words/net/aspose.words/document) 并使用 MemoryStream 对象对其进行初始化
1. 使用 [Aspose.Words.Document.Save("output.dot", SaveFormat.Dot)](https://reference.aspose.com/words/net/aspose.words.document/save/methods/3) 保存文档)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

{{% blocks/products/pf/agp/text %}}

 所有主要操作系统都支持 Aspose.Total for .NET。只需确保您具有以下先决条件。 

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows 或与 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台兼容的操作系统。
-  Microsoft Visual Studio 等开发环境。
-  Aspose.Slides for .NET 和 Aspose.Words for .NET DLL 在您的项目中引用。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="此代码示例展示了如何使用 C# 将 POT 转换为 DOT" offSpacer="" %}}

```cs
// 加载 Microsoft PowerPoint POT 文件
Aspose.Slides.Presentation pot = new Aspose.Slides.Presentation("source.pot");

var stream = new MemoryStream();

pot.Save(stream, Aspose.Slides.Export.SaveFormat.Html);
stream.Flush();
stream.Seek(0, SeekOrigin.Begin);
// stream.Position = 0;

// 将演示文稿的内容加载到 Word 文档中
var dot = new Aspose.Words.Document(stream);
      
// 保存 Word DOT 文档
dot.Save("output.dot", Aspose.Words.SaveFormat.Dot);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="将 POT 转换为 DOT 的免费应用程序" sectionDescription="查看我们的 [POT 到 DOT 转换](https://products.aspose.app/slides/conversion/) 的现场演示，具有以下优势。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 无需下载或设置任何东西。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 无需编写任何代码。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上传您的 POT 文件并点击“转换”按钮。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 您将立即获得生成的 DOT 文件的下载链接。" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

Aspose.Total for .NET 是完整的文档操作 API 包。 API 可轻松集成到任何基于 .NET 的应用程序中，以操作 Microsoft Word、Excel、PowerPoint、Outlook、PDF、图像、条形码和 100 多种其他格式。程序员可以轻松地使用它们在任何 .NET、C#、ASP.NET 和 VB.NET 应用程序中创建、修改、渲染、打印和转换最流行的文件格式，而无需任何其他软件。

    {{% /blocks/products/pf/agp/content %}} 

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="您还可以将 POT 转换为许多其他文件格式，包括下面列出的一些文件格式。" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/pot-to-doc" name="POT 转 DOC" description="Microsoft Word 二进制格式" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/pot-to-docx" name="POT 转 DOCX" description="Office 2007+ 文字文档" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/pot-to-rtf" name="POT 转 RTF" description="富文本格式" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/pot-to-dot" name="POT 转 DOT" description="Microsoft Word 模板文件" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/pot-to-dotx" name="POT 转 DOTX" description="微软 Word 模板文件" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/pot-to-dotm" name="POT 转 DOTM" description="Microsoft Word 2007+ 模板文件" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/pot-to-docm" name="POT 转 DOCM" description="Microsoft Word 2007 马可文件" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/pot-to-flatopc" name="POT 转 FLATOPC" description="Microsoft Word 2003 WordprocessingML 格式" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/pot-to-odt" name="POT 转 ODT" description="OpenDocument 文本文件格式" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/pot-to-ott" name="POT 转 OTT" description="OpenDocument 标准格式" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/pot-to-wordml" name="POT 转 WORDML" description="Microsoft Word 2003 WordprocessingML 格式" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/pot-to-txt" name="POT 转 TXT" description="文本文件" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}