---
title: 使用 Java 将 XLSM 转换为 WORD 或使用免费的在线转换器
description: 使用 Excel 或 Word 将 XLSM 导出为 WORD 的 Java API 或在线。在集成代码之前快速测试免费的 CSV 到 DOC 在线转换器。
url_ignore: /zh/java/conversion/xlsm-to-word/
family: total
platformtag: net
feature: conversion
informat: XLSM
outformat: WORD
otherformats: WORD WORDX PPTX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="用于将 XLSM 导出为 WORD 的 Java API 或在线" h2="无需依赖 Microsoft Excel 即可将 XLSM 导出为 WORD 的 On Premise Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
将 XLSM 渲染到 WORD 是一个两步过程。您将首先使用 [Aspose.Cells for Java](https://products.aspose.com/cells/java) API 将给定的 XLSM 文档转换为 PDF，然后使用 [Aspose.PDF for Java](https://products.aspose.com/pdf/java) API，您可以轻松地将您的 PDF 文档转换为 WORD。这两个 API 都属于 [Aspose.Total for Java](https://products.aspose.com/total/java/) 文件格式自动化库的集合。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何通过 Java API 将 XLSM 转换为 WORD" %}}
1. 使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 类打开 XLSM 文件
2. 将 XLSM 转换为 PDF 并将 SaveFormat 设置为 AUTO
3. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类加载转换后的PDF文件
4. 使用[save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions)将文档保存为WORD格式-) 方法并将 Word 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您必须直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目中使用 Aspose.Total for Java并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSM file using Workbook class
Workbook book = new Workbook("input.xlsm");
// save XLSM as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in WORD format
document.save("output.word", com.aspose.pdf.SaveFormat.Word);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>XLSM 到 WORD 在线转换器</h3>

<iframe title="xlsm 到 docx 转换在线工具" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=xlsm" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/xlsm-to-docx/">试试我们的 XLSM 到 WORD 转换的免费应用程序</a></p>
</div></div>
</div></div>
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
                          <span itemprop="name"><b>如何在线将 XLSM 转换为 WORD？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">上面集成了用于 XLSM 转换的在线应用程序。转换过程包括通过将 XLSM 文件拖放到白色区域或在该区域内单击以导入文件来添加 XLSM 文件。添加文件后，只需单击“转换”按钮即可开始转换过程。完成后，您只需单击一下即可下载新转换的 WORD 文件。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>转换 XLSM 需要多长时间？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">此在线转换器的速度在很大程度上取决于要转换的 XLSM 文件的大小。只需几秒钟即可将较小的 XLSM 文件转换为 WORD。此外，如果您将转换代码合并到 Java 应用程序中，应用程序的效率也会影响转换过程。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>使用免费的 Aspose.Total 转换器将 XLSM 转换为 WORD 是否安全？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">当然！转换过程完成后，将立即提供 WORD 文件的下载链接。上传的文件会在 24 小时后自动删除，超过该时间范围后下载链接将不再有效。您可以放心，您的文件是安全的，并且文件转换（包括 XLSM）是完全安全的。集成免费应用程序主要用于测试目的，允许您在将代码集成到您的项目之前验证结果。</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>我应该使用什么浏览器来转换 XLSM？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">对于在线转换，您可以使用任何现代网络浏览器，例如 Google Chrome、Firefox、Opera 或 Safari。然而，如果您正在开发桌面应用程序，Aspose.Total XLSM Conversion API 是一个很好的选择，因为它被设计为在这样的环境中无缝工作。</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}