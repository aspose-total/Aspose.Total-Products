---
title: 在线删除 RTF 注释或通过 .NET 管理注释
description: 通过在线应用程序免费删除 RTF 文件中的注释。用于管理 RTF 文件注释的 .NET API 代码。

family: total
platformtag: net
feature: Annotate
informat: RTF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="清除来自 RTF 在线文档的注释或通过 .NET 管理" h2="开发功能强大的基于 .NET 的 RTF 文档注释实用程序。列出用于通过 .NET 管理 RTF 文件注释的代码。" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="在线删除 RTF 注释" %}}

1. 导入RTF文件上传删除评论
1. 通过拖放注释应用程序在放置区域内单击来完成此操作
1. 根据 RTF 文件的大小和互联网速度等待几秒钟
1. 点击“删除”按钮清除评论
1. 立即下载文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="通过 .NET 删除特定作者 RTF 文档注释" %}}

1. 将库引用添加到 .NET 项目
1. 通过Document类对象加载Document
1. 使用具有 NodeType.Comment 的 GetChildNodes 获取所有节点注释
1. 遍历所有评论并匹配作者姓名
1. 调用Remove方法删除特定作者评论

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="C# 代码：从 RTF 文件中删除特定作者注释" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "remove-comments-of-a-specific-author-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="通过 .NET 添加评论" %}}

1. 创建文档类对象
1. 使用评论类
1. 使用 Paragraphs.Add 添加新段落
1. 使用 FirstParagraph.Runs.Add 添加注释
1. 或者另一种方法是使用 CommentRangeStart 和 CommentRangeEnd 类
1. 调用save方法保存添加注释的文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="提取所有评论" %}}

1. 通过Document类对象加载Document
1. 创建一个ArrayList对象
1. 获取 NodeCollection 中的所有 GetChildNode
1. 遍历每个集合并在ArrayList中添加注释

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title=".NET 代码：从 RTF 文件添加注释" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "add-comments-in-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C# Code: 提取所有评论" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "extract-all-comments-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>通过.NET开发RTF文档注释应用程序</h2>

需要开发 RTF 注释应用程序或实用程序来提供反馈、提出建议或与其他人协作处理文档？通过 [Aspose.Words for .NET](https://products.aspose.com/words/net/)（[Aspose.Total for .NET](https://products.aspose.com/total/net/) 的子 API），任何 .NET 开发人员都可以将上述 API 代码集成到其文档注释应用程序中。强大的.NET 库允许对任何文档注释解决方案进行编程。而且它可以支持许多流行的格式，包括RTF格式。<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="用于注释 RTF 文件的 .NET 库" %}}

可以通过三个替代选项将“Aspose.Words for .NET”或“Aspose.Total for .NET”安装到您的系统上。请选择符合您需求的一项并按照分步说明进行操作：<br /><br />

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
RTF（富文本格式）是一种在各个平台和文字处理软件中都得到广泛支持的通用文件格式。注释 RTF 文件可以增强协作、文档记录以及清晰度，尤其是在需要格式中立和广泛兼容性的环境中。

#### RTF 文件注释用于跨平台文档协作的应用场景：

- **跨平台编辑审阅**  
  在 RTF 文件上添加注释或修订备注，以确保无论用户使用何种操作系统或文字处理软件，都能访问到这些注释。

- **法规环境下的文档记录**  
  在法律、医疗或学术文件中添加与监管或合规相关的注释，以便追踪并提高清晰度。

- **协同教育内容**  
  在教师和学生之间共享的教材、试卷或学习指南中插入解释性注释。

- **版本跟踪和反馈**  
  使用注释来标记在多阶段内容开发过程中的更改或添加。

- **本地化内容审阅**  
  在多语言文档中突出需要翻译或文化适应于不同地区的区域。
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}


<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="常见问题解答" width="335" height="283">
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
                          <span itemprop="text">是的，欢迎您下载此代码并使用它来开发基于 .NET 的文档注释应用程序。此代码可以作为宝贵的资源来增强项目在后端文档处理和操作领域的功能和能力。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>这个在线文档注释应用程序只能在 Windows 上运行吗？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">您可以灵活地在任何设备上启动文档注释以删除注释，无论其运行何种操作系统，无论是 Windows、Linux、Mac OS 还是 Android。所需要的只是一个现代的网络浏览器和一个活跃的互联网连接。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>使用在线应用程序注释 RTF 文档是否安全？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">当然！通过我们的服务生成的输出文件将在 24 小时内安全地自动从我们的服务器中删除。因此，与这些文件关联的显示链接将在此期限后停止运行。</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>App应该用什么浏览器？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">您可以使用任何现代网络浏览器（例如 Google Chrome、Firefox、Opera 或 Safari）进行在线 RTF 文档注释。但是，如果您正在开发桌面应用程序，我们建议使用 Aspose.Total 文档处理 API 进行高效管理。</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}