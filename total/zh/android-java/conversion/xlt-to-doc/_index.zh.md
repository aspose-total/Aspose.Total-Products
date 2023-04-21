---
title: 在 Android 中将 XLT 导出为 DOC 或使用免费的在线转换器
description: 无需使用 Microsoft Word 即可将 XLT 转换为 DOC 的 Android API 或在线。在集成代码之前快速测试免费的  XLT 到 DOC 在线转换器。

family: total
platformtag: cpp
feature: conversion
informat: XLT
outformat: DOC
otherformats: PPTX WORD POWERPOINT DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 Java 在 Android 上将 XLT 渲染为 DOC 或在线应用程序" h2="在您的 Android 应用程序中将 XLT 转换为 DOC，而无需使用 Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 是一个强大的文件自动化 API 包。通过使用它的两个 API，您可以在 Android 应用程序中集成  XLT 到 DOC 的转换功能。在第一步中，您可以使用 [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) 将 XLT 导出为 PDF。之后，通过使用 [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)，您可以将 PDF 转换为 DOC。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="用于将 XLT 导出为 DOC 的 Android API" %}}
1. 使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 类打开 XLT 文件
2. 将 XLT 转换为 PDF 并将 SaveFormat 设置为 AUTO
3. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类加载转换后的PDF文件
4. 使用 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions) 将文档保存为 DOC 格式-) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您可以直接从 [Maven](https://releases.aspose.com/total/java/)通过 Java 轻松使用 Aspose.Total for Android 和安装 [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) 和 [Aspose.Cells for Android via Java](https://docs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) 在您的应用程序中。

或者，您可以从 [下载](https://releases.aspose.com/total/androidjava) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLT file using Workbook class
Workbook book = new Workbook("input.xlt");
// save XLT as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in DOC format
document.save("output.doc", com.aspose.pdf.SaveFormat.Doc);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>免费的  XLT 到 DOC 在线转换器</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=doc&from=xlt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="通过 Java 从 Android 中的 XLT 文件中删除自定义属性" %}}
除了文档转换之外，[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) 还提供了大量其他功能。在转换过程之前，您可以删除 XLT 文档的自定义属性。要删除自定义属性，请调用 [DocumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/documentpropertycollection#remove(java.lang.String)) 方法并传递名称要删除的文档属性。
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLT file using Workbook class
Workbook book = new Workbook("input.xlt");
// retrieve a list of all custom document properties of the Excel file
DocumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocumentProperties();
// remove a custom document property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
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
                          <span itemprop="name"><b>如何在线将 XLT 转换为 DOC？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">上面集成了用于 XLT 转换的在线应用程序。要开始  XLT 到 DOC 的转换过程，第一步是导入 XLT 文件。这可以通过两种方式完成：您可以将 XLT 文件拖放到转换工具中，或者您可以在工具的白色区域内单击以浏览您的计算机并选择要转换的 XLT 文件。成功导入 XLT 文件后，您需要单击“转换”按钮开始转换过程。 <br />
在转换过程中，XLT 文件将转换为 DOC 文件。转换工具会发挥它的魔力，当过程完成后，您将能够下载新转换的 DOC 文件。这意味着您只需单击一下即可轻松获得输出 DOC 文件，而无需任何复杂的软件或技术知识。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>转换 XLT 需要多长时间？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">此在线  XLT 到 DOC 转换器的主要特点之一是其转换速度快。但是，转换过程的速度主要取决于您要转换的 XLT 文件的大小。如果您正在处理小尺寸的 XLT 文件，您可以期望在几秒钟内完成转换过程。<br />

此外，如果您已将转换代码集成到 Android App 应用程序中，则转换过程的速度将取决于您优化应用程序的方式。如果您的应用程序经过良好优化，并且设计用于高效处理转换过程，那么转换速度会更快。另一方面，如果您的应用程序没有为此目的进行优化，则转换过程可能需要更长的时间才能完成。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>使用免费的 Aspose.Total 转换器将 XLT 转换为 DOC 是否安全？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">当然！ DOC 文件的下载链接将在转换后立即可用。在我们的  XLT 到 DOC 转换器中，我们非常重视您的隐私和安全。我们了解您的文件包含敏感信息和个人信息，因此我们采取了多项措施来确保您的文件安全无虞。<br />

首先，我们会在 24 小时后自动删除所有上传的文件。这意味着一旦转换过程完成并且您下载了转换后的文件，我们将从我们的服务器中删除原始 XLT 文件和生成的 DOC 文件。此外，您的文件的下载链接将在 24 小时后停止工作，确保您的文件在此时间段后无法被任何人访问。<br />

我们还采取措施确保您的文件免受未经授权的访问。在转换过程中或之后，没有人可以访问您的文件，并且您的计算机和我们的服务器之间的所有数据传输都是加密和安全的。</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>我应该使用什么浏览器来转换 XLT？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">这个在线  XLT 到 DOC 转换器可以通过任何现代浏览器访问，例如 Google Chrome、Firefox、Opera 或 Safari。这意味着您可以在任何具有互联网连接的设备上轻松使用此工具，而无需任何专业软件或技术知识。<br />

但是，如果您正在开发桌面应用程序并且需要将 XLT 文件转换为 DOC 文件，我们建议使用 Aspose.Total XLT Conversion API。此 API 提供了一种在桌面应用程序中将 XLT 文件转换为 DOC 文件的流畅且高效的方法。 Aspose.Total XLT Conversion API 旨在易于使用和集成到您的应用程序中，它提供快速可靠的转换过程。</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}