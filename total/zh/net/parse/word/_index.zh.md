---
title: 使用 .NET 在线从 Word 文件中提取文本和图像
description: 在线 Word 文件解析器应用程序。 .NET API C# 代码，用于从 Word 文档中提取图像和文本内容。

family: total
platformtag: net
feature: Parse
informat: Word
otherformats: Word DOCX DOC DOTX DOT RTF ODT OTT PDF Excel XLS XLSX XLSM XLSB ODS Powerpoint PPT PPTX ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="在线以及通过 .NET 解析 Word 文件" h2="开发强大的基于 .NET 的 Word 文档解析器实用程序。列出用于 Word 文档文本提取的 C# 代码。" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过在线应用程序解析 Word 文档" %}}

1. 通过上传导入Word文件进行解析。
1. 通过拖放解析器应用程序在放置区域内单击来完成此操作。
1. 根据 Word 文件的大小和互联网速度，等待几秒钟。
1. 单击“立即解析”按钮来解析文档。
1. 下载解析的文件以立即查看。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="通过.NET解析Word文件" %}}

1. 将库引用添加到 .NET 项目
1. 使用 Document 类对象加载 Word 文件
1. 使用 GetChildNodes() 获取所有子节点
1. 使用 NodeType.Shape 作为参数
1. 遍历每个节点并保存图像
1. 对于文本提取，循环浏览每个页面
1. 调用 ExtractPages 方法
1. 使用 Node.ToString 方法将提取的文件保存为文本

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="C#代码：Word文档图像提取" offSpacer="" %}}

{{< gist "aspose-com-gists" "ab98758eea66dd544d4a7964d10ec4fc" "extract-images-from-word-document.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C#代码：Word文档文本提取" offSpacer="" %}}

{{< gist "aspose-com-gists" "ab98758eea66dd544d4a7964d10ec4fc" "extract-text-from-word-document.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}


{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>通过 .NET 开发 Word 文件解析器应用程序</h2>

需要开发 Word 解析器应用程序或软件？通过 [Aspose.Words for .NET](https://products.aspose.com/words/zh/net/)（[Aspose.Total for .NET](https://products.aspose.com/total/zh/net/) 的子 API），任何 .NET 开发人员都可以将上述 API 代码集成到其文档解析器应用程序中。强大的 .NET 库允许对任何文档解析解决方案进行编程以提取图像和文本。而且它可以支持许多流行的格式，包括Word格式。<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET 实用程序为解析器应用程序处理 Word 文件" %}}

还有其他选项可以将 Aspose.Words for .NET 或 Aspose.Total for .NET 安装到您的系统上。请选择符合您需求的一项并按照分步说明进行操作：<br /><br />

- 安装 [NuGet 包](https://www.nuget.org/packages/Aspose.Words/)。参见 [文档](https://docs.aspose.com/words/net/installation/#install-or-update-aspose-words-for-net-using-nuget)
- 在 Visual Studio IDE 中使用 [包管理器控制台](https://docs.aspose.com/words/net/installation/#install-or-update-asposewords-using-package-manager-console) 安装库
- 使用 [Windows安装程序](https://docs.aspose.com/words/net/installation/#install-asposewords-for-net-using-installer) 手动安装库

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

我们的产品完全跨平台，支持遵循“.NET Standard 2.0”规范的所有主要 .NET 实现：<br /><br />

- Microsoft .NET Framework，从最早的2.0版本开始，到最新的“.NET Framework 4.8”结束
- .NET Core，从最早的2.0开始，到最新的“.NET 6”结束
- 单声道 >= 2.6.7
<br /><br />
由于 .NET 代码不依赖于底层硬件或操作系统，而仅依赖于虚拟机，因此您可以自由地为 Windows、macOS、Android、iOS 和 Linux 开发任何类型的软件。只需确保您已安装相应版本的 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin。<br /><br />
我们建议使用 Microsoft Visual Studio、Xamarin 和 MonoDevelop IDE 创建 C#、F#、VB.NET 应用程序。
<br /><br />
欲了解更多详情，请参阅[产品文档](https://docs.aspose.com/words/net/system-requirements/)。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}
## 📄 Microsoft Word 文档 (doc, docm, docx, dot, dotm, dotx, odt, rtf) 解析用例

- 📄 **内容提取**  
  从 Word 文档中提取文字、表格和图片，用于网页显示、搜索索引或文本分析。

- 📰 **模板处理**  
  使用 .dot、.dotx、.dotm 模板，在工作流程中自动生成带有动态数据的文档。

- 🔁 **自动化工作流程**  
  在包含嵌入宏的 .docm 或 .dotm 文件中，通过自动化脚本和宏实现内容替换。

- 🧾 **报告转换**  
  将 .doc、.odt 或 .rtf 文件转换为干净的 HTML、Markdown或 PDF 格式，以便发布或作为文档使用。

- 📚 **数字归档**  
  处理旧格式文件（如 .doc 和 .rtf），通过转换和索引实现长期保存和管理。
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}


<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupWords.cloud/templates/brand/images/groupWords/conversion/groupWords_conversion-brand.png" alt="常见问题解答" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>常见问题解答</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>我可以在我的应用程序中使用上述 .NET 代码吗？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">是的，欢迎您下载此代码并使用它来开发基于 .NET 的文档解析器应用程序。此代码可以作为宝贵的资源来增强项目在后端文档处理领域的功能和能力，例如读取节点和加载文档以进行文本和图像提取。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>这个在线文档解析器应用程序只能在 Windows 上运行吗？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">您可以灵活地在任何设备上启动文档解析，无论其运行的操作系统是 Windows、Linux、Mac OS 还是 Android。所需要的只是一个现代的网络浏览器和一个活跃的互联网连接。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>使用在线应用程序解析 Word 文档安全吗？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">当然！通过我们的服务生成的输出文件将在 24 小时内安全、自动地从我们的服务器中删除。因此，与这些文件关联的显示链接将在此期限后停止运行。</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>App应该用什么浏览器？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">您可以使用任何现代 Web 浏览器（例如 Google Chrome、Firefox、Opera 或 Safari）作为在线 Word 文档解析器。但是，如果您正在开发桌面应用程序，我们建议使用 Aspose.Total 文档处理 API 进行高效管理。</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}