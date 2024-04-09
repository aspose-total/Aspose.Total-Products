---
title: 在线删除 DOCX 注释或通过 C++ 管理注释
description: 通过在线应用程序免费删除 DOCX 文件中的注释。C++ API 代码用于管理 DOCX 文件的注释。

family: total
platformtag: cpp
feature: Annotate
informat: DOCX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="在线清除 DOCX 文档中的注释或通过 C++ 进行管理" h2="开发基于 C++ 的强大的 DOCX 文档注释实用应用程序。列出的代码用于通过 C++ 管理 DOCX 文件的注释。" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="在线删除DOCX注释" %}}

1. 导入DOCX文件，上传即可删除评论
1. 通过注释应用程序的拖放操作单击放置区域内部即可完成
1. 根据 DOCX 文件的大小和互联网速度等待几秒钟
1. 点击“删除”按钮清除评论
1. 立即下载文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="通过 C++ 删除 DOCX 文档注释" %}}

1. 向 C++ 项目添加库引用
1. 加载 DOCX 文件
1. 使用以 NodeType::Comment 为参数的 GetChildNodes 获取所有节点
1. 在评论集合上调用 NodeCollection.Clear

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="C++ 代码：从 DOCX 文件中删除注释" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "remove-word-document-comments.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="通过 C++ 添加评论" %}}

1. 创建 Document 和 DocumentBuilder 类对象
1. 或者加载文档
1. 使用 Comment 类添加评论
1. 使用 AppendChild 方法并以注释 obj 作为参数
1. 使用相关方法，如 get_Paragraphs()->Add
1. 或者另一种方法是使用 CommentRangeStart 和 CommentRangeEnd 类
1. 调用 save 方法保存添加注释的文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="提取所有评论" %}}

1. 通过 Document 类对象加载文档
1. 获取 NodeCollection 中的所有 GetChildNodes
1. 遍历每个集合并收集有关它们的信息

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="C++ 代码：向 DOCX 文件添加注释" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "word-document-annotations.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C++ Code: 提取所有评论" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "extract-all-comments-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>通过 C++ 开发 DOCX 文档注释应用程序</h2>

需要开发 DOCX 注释应用程序或实用程序来提供反馈、提出建议或与其他人合作处理文档吗？借助 [Aspose.Words for C++](https://products.aspose.com/words/cpp/)（[Aspose.Total for C++](https://products.aspose.com/total/zh/cpp/) 的子 API），任何 C++ 开发人员都可以将上述 API 代码集成到其文档注释应用程序中。强大的 C++ 库允许编写任何文档注释解决方案。此外，它还可以支持许多流行格式，包括 DOCX 格式。<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="用于注释 DOCX 文件的 C++ 库" %}}

有三个选项可以将 Aspose.Words for C++ 安装到您的开发环境中。请选择一个符合您需求的方案并按照分步说明进行操作：<br /><br />

- Install a [NuGet 包](https://www.nuget.org/packages/Aspose.Words.Cpp/). See [文档](https://docs.aspose.com/words/cpp/installation/#install-or-update-aspose-words-for-cpp-using-nuget)
- 在 Visual Studio IDE 中使用 [程序包管理器控制台](https://docs.aspose.com/words/cpp/installation/#install-or-update-asposewords-using-package-manager-console) 安装库
- 使用 [Windows 安装程序](https://docs.aspose.com/words/cpp/installation/#install-asposewords-for-c-by%20hand) 手动安装库

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}
您可以使用此 C++ 库在 Microsoft Windows、Linux 和 macOS 操作系统上开发软件：<br /><br />

- Linux 需要 GCC >= 6.3.0 和 Clang >= 3.9.1
- macOS 需要 Xcode >= 12.5.1、Clang 和 libc++

<br /><br />
如果您为 Linux 或 macOS 开发软件，请检查 [产品文档](https://docs.aspose.com/words/cpp/system-requirements/) 中有关附加库依赖项（fontconfig 和 mesa-glu 开源包）的信息。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

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
                          <span itemprop="name"><b>我可以在我的应用程序中使用上述 C++ 代码吗？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">是的，欢迎您下载此代码并将其用于开发基于 C++ 的文档注释应用程序。该代码可以作为宝贵的资源来增强您的项目在后端文档处理和操作领域的功能和能力。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>这个在线文档注释应用程序仅适用于 Windows 吗？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">您可以灵活地在任何设备上启动文档注释以删除注释，无论它运行的是哪种操作系统，无论是 Windows、Linux、Mac OS 还是 Android。所需的只是一个现代的网络浏览器和一个有效的互联网连接。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>使用在线应用程序注释 DOCX 文档安全吗？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">当然！通过我们的服务生成的输出文件将在 24 小时内安全自动地从我们的服务器中删除。因此，在此期间之后，与这些文件相关的显示链接将不再起作用。</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>应该使用什么浏览器来使用App？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">您可以使用任何现代网络浏览器（如 Google Chrome、Firefox、Opera 或 Safari）进行在线 DOCX 文档注释。但是，如果您正在开发桌面应用程序，我们建议使用 Aspose.Total 文档处理 API 进行高效管理。</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}