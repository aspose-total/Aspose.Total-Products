---
title: 使用 C++ 將 SXC 轉換為 DOCX 或使用免費的在線轉換器
description: 在 C++ 應用程序中將 SXC 轉換為 DOCX 或在線。在集成代碼之前快速測試免費的 CSV 到 DOC 在線轉換器。

family: total
platformtag: cpp
feature: conversion
informat: SXC
outformat: DOCX
otherformats: WORD DOC PPTX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 C++ 將 SXC 轉換為 DOCX 或在線" h2="導出 Excel<sup>&reg;</sup>全功能 C++ 應用程序中的 SXC 到 DOCX" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ 上的 SXC 到 DOCX 轉換" %}}
1. 使用[Factory](https://reference.aspose.com/cells)的[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)成員函數打開SXC文件/cpp/class/aspose.cells.factory) 類參考
2. 將 SXC 轉換為 PDF 並將 SaveFormat 設置為 Pdf
3. 用[Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)類參考加載轉換後的PDF文件
4. 使用[Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)成員函數將文檔保存為DOCX格式，並將Docx設置為SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
從命令行安裝為 ```nuget install Aspose.Total.Cpp``` 或通過 Visual Studio 的包管理器控制台安裝 ```Install-Package Aspose.Total.Cpp```。

或者，從 [下載](https://releases.aspose.com/total/cpp) 獲取 ZIP 文件中的離線 MSI 安裝程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the SXC file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.sxc");
// save SXC as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Document class reference
auto docx = MakeObject<Document>(u"pdfOutput.pdf");
// save document in DOCX format
docx->Save(u"convertedFile.docx", SaveFormat::DocxX);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>SXC 到 DOCX 在線轉換器</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=sxc" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/sxc-to-docx/">試試我們的 SXC 到 DOCX 轉換的免費應用程序</a></p>
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
              <h2>經常問的問題</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>如何在線將 SXC 轉換為 DOCX？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">上面集成了用於 SXC 轉換的在線應用程序。要開始 SXC 到 DOCX 的轉換過程，只需通過將 SXC 文件拖放到指定區域或在白框內單擊以導入文件來添加 SXC 文件。導入文件後，單擊“轉換”按鈕開始轉換過程。 SXC 到 DOCX 轉換完成後，只需單擊一下即可立即下載新轉換的 DOCX 文件。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>轉換 SXC 需要多長時間？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">此在線轉換器的速度在很大程度上取決於 SXC 文件的大小。只需幾秒鐘即可將較小的 SXC 文件轉換為 DOCX。此外，如果您已將轉換代碼集成到 C++ 應用程序中，轉換過程的效率將取決於您優化應用程序的方式。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>使用免費的 Aspose.Total 轉換器將 SXC 轉換為 DOCX 是否安全？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">當然！ SXC 到 DOCX 轉換完成後，您將能夠通過提供的下載鏈接立即下載轉換後的文件。我們會在 24 小時後刪除上傳的文件，此時間段後下載鏈接將失效。您可以放心，包括 SXC 在內的文件轉換是完全安全可靠的，因為沒有人可以訪問您的文件。上面已經集成了免費應用程序用於測試目的，允許您在集成代碼之前檢查結果。</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>我應該使用什麼瀏覽器來轉換 SXC？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">您可以使用任何現代網絡瀏覽器訪問此在線轉換器，例如 Google Chrome、Firefox、Opera 或 Safari。然而，如果您正在處理桌面應用程序，Aspose.Total SXC Conversion API 提供了一個流暢的解決方案。</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}