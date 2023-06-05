---
title: 通过 C# .NET 将 ODP 转换为 DOTX 或使用免费的在线转换器
url_ignore: /zh/net/conversion/odp-to-dotx/ 
description: 使用 C# 将 PowerPoint odp 文档转换为 Word dotx 文件。在 ASP.NET 或其他 .NET 应用程序中转换多个文件。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="使用 C# 将 ODP 转换为 DOTX 或在线" h2="在 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台上构建 Microsoft PowerPoint ODP 演示文稿到 Word DOTX 文档转换应用程序。" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOTX" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="如何使用 C# 将 ODP 转换为 DOTX 或在线" %}}

 为了使任何 PowerPoint odp 演示文稿到 Word dotx 文件批量转换的过程自动化，我们将使用 [Aspose.Slides for .NET](https://products.aspose.com/slides/net) 和 [Aspose.Words对于 .NET](https://products.aspose.com/words/net) API。前者是一个 PowerPoint 演示文稿操作 API，可让您创建或修改 Microsoft PowerPoint 幻灯片。而后者是用于处理或操作 Microsoft Word 文档的文字处理 API。这两个 API 都是 [Aspose.Total for .NET](https://products.aspose.com/total/net) 包的一部分。您可以直接从 Nuget [下载](https://releases.aspose.com/) 或使用包管理器控制台中的以下命令。

{{% blocks/products/pf/agp/code-block title="包管理器控制台命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通过 C# 将 ODP 转换为 DOTX 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Total 使开发人员只需几行代码即可轻松加载 ODP 文件并将其转换为 DOTX。

{{% /blocks/products/pf/agp/text %}}

1. 添加 Aspose.Slides for .NET 和 Aspose.Words for .NET 的引用
1. 使用 [Aspose.Slides.Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) 类加载 PowerPoint ODP 演示文稿
1. 将文档保存到 [MemoryStream](https://docs.microsoft.com/en-us/dotnet/api/system.io.memorystream?view=net-5.0) 对象中
1. 创建 [Aspose.Words.Document](https://reference.aspose.com/words/net/aspose.words/document) 并使用 MemoryStream 对象对其进行初始化
1. 使用 [Aspose.Words.Document.Save("output.dotx", SaveFormat.Dotx)](https://reference.aspose.com/words/net/aspose.words.document/save/methods/3) 保存文档)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

{{% blocks/products/pf/agp/text %}}

 所有主要操作系统都支持 Aspose.Total for .NET。只需确保您具有以下先决条件。 

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows 或与 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台兼容的操作系统。
-  Microsoft Visual Studio 等开发环境。
-  Aspose.Slides for .NET 和 Aspose.Words for .NET DLL 在您的项目中引用。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="此代码示例展示了如何使用 C# 将 ODP 转换为 DOTX 或在线" offSpacer="" %}}

```cs
// 加载 Microsoft PowerPoint ODP 文件
Aspose.Slides.Presentation odp = new Aspose.Slides.Presentation("source.odp");

var stream = new MemoryStream();

odp.Save(stream, Aspose.Slides.Export.SaveFormat.Html);
stream.Flush();
stream.Seek(0, SeekOrigin.Begin);
// stream.Position = 0;

// 将演示文稿的内容加载到 Word 文档中
var dotx = new Aspose.Words.Document(stream);
      
// 保存 Word DOTX 文档
dotx.Save("output.dotx", Aspose.Words.SaveFormat.Dotx);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class="demobox tc col-md-12 padding-0" align="center">
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>ODP 到 DOTX 在线转换器</h3>

<iframe title="odp 到 dotx 转换在线工具" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=dotx&from=odp" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="将 ODP 转换为 DOTX 的免费应用程序" sectionDescription="查看我们的 [ODP 到 DOTX 转换](https://products.aspose.app/slides/conversion/) 的现场演示，具有以下优势。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 无需下载或设置任何东西。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 无需编写任何代码。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上传您的 ODP 文件并点击“转换”按钮。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 您将立即获得生成的 DOTX 文件的下载链接。" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

Aspose.Total for .NET 是完整的文档操作 API 包。 API 可轻松集成到任何基于 .NET 的应用程序中，以操作 Microsoft Word、Excel、PowerPoint、Outlook、PDF、图像、条形码和 100 多种其他格式。程序员可以轻松地使用它们在任何 .NET、C#、ASP.NET 和 VB.NET 应用程序中创建、修改、渲染、打印和转换最流行的文件格式，而无需任何其他软件。

    {{% /blocks/products/pf/agp/content %}} 

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>经常问的问题</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>如何在线将 ODP 转换为 DOTX？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">上面集成了用于 ODP 转换的在线应用程序。要使用该应用程序，您可以通过将 ODP 文件拖放到指定区域或在区域内单击以导入文件来添加 ODP 文件。添加文件后，单击“转换”按钮启动转换过程。 ODP 到 DOTX 转换完成后，您只需单击一下即可下载新转换的文件，它将以 DOTX 格式提供。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>转换 ODP 需要多长时间？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">这个在线转换器速度很快，但是 ODP 到 DOTX 转换的速度主要取决于要转换的 ODP 文件的大小。较小的 ODP 文件可以在几秒钟内渲染成 DOTX 格式。此外，如果您在 .NET 应用程序中集成了 ODP 到 DOTX 的转换代码，则转换速度将取决于您针对转换过程优化应用程序的程度。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>使用免费的 Aspose.Total 转换器将 ODP 转换为 DOTX 是否安全？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">当然！ ODP 到 DOTX 的转换过程完成后，转换后的 DOTX 文件的下载链接将立即可用。所有上传的文件，包括 ODP 文件，将在 24 小时后从系统中删除，并且下载链接在此时间段后停止运行。在线转换器确保您文件的安全和隐私，并且集成的应用程序可免费用于测试目的。这允许用户在将代码集成到他们的项目之前检查结果。</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>我应该使用什么浏览器来转换 ODP？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">您可以使用任何现代网络浏览器（如 Google Chrome、Firefox、Opera 或 Safari）在线将 ODP 文件转换为 DOTX。但是，如果您正在创建桌面应用程序，建议使用 Aspose.Total ODP Conversion API 以实现流畅无缝的转换过程。</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}