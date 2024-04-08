---
title: 使用 C++ 在线从 DOC 文件提取文本和图像
description: 在线 DOC 文件解析器应用程序。C++ API 代码用于从 DOC 文档中提取图像和文本内容。

family: total
platformtag: cpp
feature: Parse
informat: DOC
otherformats: Word DOCX DOC DOTX DOT RTF ODT OTT PDF Excel XLS XLSX XLSM XLSB ODS Powerpoint PPT PPTX ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="在线解析 DOC 文件以及通过 C++ 解析" h2="开发功能强大的基于 C++ 的 DOC 文档解析器实用应用程序。列出了 DOC 文档文本提取的 C++ 代码。" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过在线应用程序解析DOC文档" %}}

1. 通过上传的方式导入DOC文件进行解析。
1. 通过拖放解析器应用程序单击放置区域内部来完成此操作。
1. 根据 DOC 文件的大小和互联网速度等待几秒钟。
1. 单击“立即解析”按钮来解析文档。
1. 下载已解析的文件以供立即查看。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="通过C++解析DOC文件" %}}

1. 向 C++ 项目添加库引用
1. 加载DOC文件
1. 使用 GetChildNodes 获取所有子节点
1. 使用 NodeType::Shape 作为参数
1. 遍历每个节点并保存图像
1. 使用 shape->get_ImageData()->Save 方法保存提取的文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="C++ 代码：DOC 文档图像提取" offSpacer="" %}}

{{< gist "aspose-com-gists" "0916cd11f2eb51ded9c1c14a8a1a3f68" "parse-word-document-by-extracting-images.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>通过 C++ 开发 DOC 文件解析器应用程序</h2>

需要开发 DOC 解析器应用程序或软件吗？借助 [Aspose.Words for C++](https://products.aspose.com/words/cpp/)（[Aspose.Total for C++](https://products.aspose.com/total/zh/cpp/) 的子 API），任何 C++ 开发人员都可以将上述 API 代码集成到其文档解析器应用程序中。强大的 C++ 库允许编写任何文档解析解决方案来提取图像和文本。此外，它还可以支持许多流行格式，包括 DOC 格式。<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="用于处理解析器应用程序的 DOC 文件的 C++ 实用程序" %}}

有三个选项可以将 Aspose.Words for C++ 或 Aspose.Total for C++ 安装到您的开发环境中。请选择一个符合您需求的方案并按照分步说明进行操作：<br /><br />

- 安装 [NuGet 包](https://www.nuget.org/packages/Aspose.Words.Cpp/)。查看 [文档](https://docs.aspose.com/words/cpp/installation/#install-or-update-aspose-words-for-cpp-using-nuget)
- 在 Visual Studio IDE 中使用 [程序包管理器控制台](https://docs.aspose.com/words/cpp/installation/#install-or-update-asposewords-using-package-manager-console) 安装库
- 使用 [Windows 安装程序](https://docs.aspose.com/words/cpp/installation/#install-asposewords-for-c-by%20hand) 手动安装库

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}
您可以使用此 C++ 库在 Microsoft Windows、Linux 和 macOS 操作系统上开发软件：<br /><br />

- Linux 需要 GCC >= 6.3.0 和 Clang >= 3.9.1
- macOS 需要 Xcode >= 12.5.1、Clang 和 libc++

<br /><br />
如果您为 Linux 或 macOS 开发软件，请查看 [产品文档](https://docs.aspose.com/words/cpp/system-requirements/) 中有关附加库依赖项（fontconfig 和 mesa-glu 开源包）的信息。

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
                          <span itemprop="text">是的，欢迎您下载此代码并将其用于开发基于 C++ 的文档解析器应用程序。该代码可以作为宝贵的资源，以增强您的项目在后端文档处理领域的功能和能力，例如读取节点和加载文档以进行文本和图像提取。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>这个在线文档解析器应用程序仅适用于 Windows 吗？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">您可以灵活地在任何设备上运行启动解析文档，无论它运行的操作系统是什么，无论是 Windows、Linux、Mac OS 还是 Android。所需的只是一个现代的网络浏览器和一个有效的互联网连接。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>使用在线应用程序解析 DOC 文档是否安全？</b></span>
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
                          <span itemprop="text">您可以使用任何现代网络浏览器（如 Google Chrome、Firefox、Opera 或 Safari）来使用在线 DOC 文档解析器。但是，如果您正在开发桌面应用程序，我们建议使用 Aspose.Total 文档处理 API 进行高效管理。</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}