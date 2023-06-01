---
title: 在 Android 中將 XLSX 導出為 DOCX 或使用免費的在線轉換器
description: 無需使用 Microsoft Word 即可將 XLSX 轉換為 DOCX 的 Android API 或在線。在集成代碼之前快速測試免費的 XLSX 到 DOCX 在線轉換器。

family: total
platformtag: cpp
feature: conversion
informat: XLSX
outformat: DOCX
otherformats: POWERPOINT PPTX DOC WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 Java 在 Android 上將 XLSX 渲染為 DOCX 或在線應用程序" h2="在您的 Android 應用程序中將 XLSX 轉換為 DOCX，而無需使用 Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 是一個強大的文件自動化 API 包。通過使用它的兩個 API，您可以在 Android 應用程序中集成 XLSX 到 DOCX 的轉換功能。在第一步中，您可以使用 [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) 將 XLSX 導出為 PDF。之後，通過使用 [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)，您可以將 PDF 轉換為 DOCX。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="用於將 XLSX 導出為 DOCX 的 Android API" %}}
1. 使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 類打開 XLSX 文件
2. 將 XLSX 轉換為 PDF 並將 SaveFormat 設置為 AUTO
3. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)類加載轉換後的PDF文件
4. 使用[save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions)將文檔保存為DOCX格式 方法
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
您可以直接從 [Maven](https://releases.aspose.com/total/java/)通過 Java 輕鬆使用 Aspose.Total for Android 和安裝 [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) 和 [Aspose.Cells for Android via Java](https://docs.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) 在您的應用程序中。

或者，您可以從 [下載](https://releases.aspose.com/total/androidjava) 獲取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSX file using Workbook class
Workbook book = new Workbook("input.xlsx");
// save XLSX as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in DOCX format
document.save("output.docx", com.aspose.pdf.SaveFormat.DocxX);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>免費的 XLSX 到 DOCX 在線轉換器</h3>

<iframe title="xlsx 到 docx 轉換在線工具" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=xlsx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="通過 Java 從 Android 中的 XLSX 文件中刪除自定義屬性" %}}Document
除了文檔轉換，[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) 還提供了大量其他功能。在轉換過程之前，您可以刪除 XLSX 文檔的自定義屬性。要刪除自定義屬性，請調用 [DocxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/documentpropertycollection#remove(java.lang.String)) 方法並傳遞名稱要刪除的文檔屬性。
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSX file using Workbook class
Workbook book = new Workbook("input.xlsx");
Documentve a list of all custom document properties of the Excel fileDocument
DocxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocxumentProperties();
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
              <h2>經常問的問題</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>如何在線將 XLSX 轉換為 DOCX？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">上面集成了用於 XLSX 轉換的在線應用程序。要開始 XLSX 到 DOCX 的轉換過程，第一步是導入 XLSX 文件。這可以通過兩種方式完成：您可以將 XLSX 文件拖放到轉換工具中，或者您可以在工具的白色區域內單擊以瀏覽您的計算機並選擇要轉換的 XLSX 文件。成功導入 XLSX 文件後，您需要單擊“轉換”按鈕開始轉換過程。 <br />
在轉換過程中，XLSX 文件將轉換為 DOCX 文件。轉換工具會發揮它的魔力，當過程完成後，您將能夠下載新轉換的 DOCX 文件。這意味著您只需單擊一下即可輕鬆獲得輸出 DOCX 文件，而無需任何復雜的軟件或技術知識。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>轉換 XLSX 需要多長時間？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">此在線 XLSX 到 DOCX 轉換器的主要特點之一是其轉換速度快。但是，轉換過程的速度主要取決於您要轉換的 XLSX 文件的大小。如果您正在處理小尺寸的 XLSX 文件，您可以期望在幾秒鐘內完成轉換過程。<br />

此外，如果您已將轉換代碼集成到 Android App 應用程序中，則轉換過程的速度將取決於您優化應用程序的方式。如果您的應用程序經過良好優化，並且設計用於高效處理轉換過程，那麼轉換速度會更快。另一方面，如果您的應用程序沒有為此目的進行優化，則轉換過程可能需要更長的時間才能完成。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>使用免費的 Aspose.Total 轉換器將 XLSX 轉換為 DOCX 是否安全？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">當然！ DOCX 文件的下載鏈接將在轉換後立即可用。在我們的 XLSX 到 DOCX 轉換器中，我們非常重視您的隱私和安全。我們了解您的文件包含敏感信息和個人信息，這就是為什麼我們採取了多項措施來確保您的文件安全可靠。<br />

首先，我們會在 24 小時後自動刪除所有上傳的文件。這意味著一旦轉換過程完成並且您下載了轉換後的文件，我們將從我們的服務器中刪除原始 XLSX 文件和生成的 DOCX 文件。此外，您文件的下載鏈接將在 24 小時後停止工作，確保您的文件在此時間段後無法被任何人訪問。<br />

我們還採取措施確保您的文件免受未經授權的訪問。在轉換過程中或之後，沒有人可以訪問您的文件，並且您的計算機和我們的服務器之間的所有數據傳輸都是加密和安全的。</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>我應該使用什麼瀏覽器來轉換 XLSX？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">這個在線 XLSX 到 DOCX 轉換器可以通過任何現代瀏覽器訪問，例如 Google Chrome、Firefox、Opera 或 Safari。這意味著您可以在任何具有互聯網連接的設備上輕鬆使用此工具，而無需任何專業軟件或技術知識。<br />

但是，如果您正在開發桌面應用程序並且需要將 XLSX 文件轉換為 DOCX 文件，我們建議使用 Aspose.Total XLSX Conversion API。此 API 提供了一種在桌面應用程序中將 XLSX 文件轉換為 DOCX 文件的流暢且高效的方法。 Aspose.Total XLSX Conversion API 旨在易於使用和集成到您的應用程序中，它提供快速可靠的轉換過程。</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}