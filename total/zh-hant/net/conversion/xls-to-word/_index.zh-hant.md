---
title: 使用 .NET 將 XLS 轉換為 WORD 或使用免費的在線轉換器
description: 在 .NET Framework、.NET Core、Mono 或 Xamarin 平台上將 XLS 轉換為 WORD 或在線。在集成代碼之前快速測試免費的 XLS 到 WORD 在線轉換器。

family: total
platformtag: net
feature: conversion
informat: XLS
outformat: DOC
otherformats: DOCX DOC PPTX POWERPOINT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="通過 C# 將 XLS 轉換為 WORD 或在線應用程序" h2="導出 Excel<sup>&reg;</sup> .NET Framework、.NET Core、Mono 或 Xamarin 平台上的 XLS 到 WORD">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=".NET 上的 XLS 到 WORD 轉換" %}}
1. 使用 [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) 類打開 XLS 文件
2. 將 XLS 轉換為 PDF 並將 SaveFormat 設置為 Auto
3. 用[Wordument](https://apireference.aspose.com/pdf/net/aspose.pdf/wordument)類加載轉換後的PDF文件
4. 使用[Save](https://apireference.aspose.com/pdf/net/aspose.pdf.wordument/save/methods/5)方法將文檔保存為WORD格式，並將Word設置為SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
從命令行安裝為 ```nuget install Aspose.Total``` 或通過 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，從 [下載](https://releases.aspose.com/total/net) 獲取 ZIP 文件中的離線 MSI 安裝程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="用於 XLS 到 WORD 轉換的 .NET C# 代碼" gistPath="" %}}
```cs
// load the XLS file using Workbook class
var book = new Aspose.Cells.Workbook("input.xls");
// save XLS as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Wordument class
var wordument = new Aspose.Pdf.Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.Save("output.word", SaveFormat.Word); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>免費的 XLS 到 WORD 在線轉換器</h3>

<iframe title="xls 到 docx 轉換在線工具" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=docx&from=xls" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

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
                          <span itemprop="name"><b>如何在線將 XLS 轉換為 WORD？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">上面集成了用於 XLS 轉換的在線應用程序。要開始轉換過程，您可以拖放 XLS 文件或在指定區域內單擊以導入文檔。接下來，單擊“轉換”按鈕以啟動 XLS 到 WORD 的轉換。該過程完成後，您只需單擊一下即可輕鬆下載轉換後的文件，以 WORD 格式獲得所需的輸出。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>轉換 XLS 需要多長時間？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">這個在線轉換器的速度很快，但它主要取決於 XLS 文件的大小。如果你有一個小的 XLS 文件，它可以在幾秒鐘內轉換成 WORD。此外，如果您已將轉換代碼集成到您的 .NET 應用程序中，則轉換過程的速度取決於您對應用程序的優化程度。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>使用免費的 Aspose.Total 轉換器將 XLS 轉換為 WORD 是否安全？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">當然！ XLS 到 WORD 的轉換過程完成後，會立即生成 WORD 文件的下載鏈接。我們將您文件的安全放在首位，這就是為什麼所有上傳的文件都會在 24 小時後被刪除，並且下載鏈接會在該時間段後停止工作。您可以確信您的文件在轉換過程中是安全的，包括 XLS 文件。以上免費應用程序用於測試目的，允許您在集成代碼之前檢查結果。</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>我應該使用什麼瀏覽器來轉換 XLS？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">您可以靈活地使用任何最新的網絡瀏覽器進行 XLS 到 WORD 的在線轉換，例如 Google Chrome、Firefox、Opera、Safari。但是，如果您正在構建桌面應用程序，則可以無縫集成 Aspose.Total XLS Conversion API。</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}