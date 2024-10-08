---
title: 通過 C# .NET 將 PPS 轉換為 WORDML 或使用免費的在線轉換器
description: 使用 C# 將 PowerPoint pps 文檔轉換為 Word wordml 文件。在 ASP.NET 或其他 .NET 應用程序中轉換多個文件。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="使用 C# 將 PPS 轉換為 WORDML 或在線" h2="在 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台上構建 Microsoft PowerPoint PPS 演示文稿到 Word WORDML 文檔轉換應用程序。" logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPS" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="如何使用 C# 將 PPS 轉換為 WORDML 或在線" %}}

為了使任何 PowerPoint pps 演示文稿到 Word wordml 文件批量轉換的過程自動化，我們將使用 [Aspose.Slides for .NET](https://products.aspose.com/slides/net) 和 [Aspose.Words對於 .NET](https://products.aspose.com/words/net) API。前者是一個 PowerPoint 演示文稿操作 API，可讓您創建或修改 Microsoft PowerPoint 幻燈片。而後者是用於處理或操作 Microsoft Word 文檔的文字處理 API。這兩個 API 都是 [Aspose.Total for .NET](https://products.aspose.com/total/net) 包的一部分。您可以直接從 Nuget [下載](https://releases.aspose.com/) 或使用包管理器控制台中的以下命令。

{{% blocks/products/pf/agp/code-block title="包管理器控制台命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通過 C# 將 PPS 轉換為 WORDML 的步驟" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. 添加Aspose.Slides for .NET和Aspose.Words for .NET的引用
1. 使用 [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation) 類加載 PowerPoint PPS 演示文稿
1. 將文檔保存到 [MemoryStream](https://wordmls.microsoft.com/en-us/dotnet/api/system.io.memorystream?view=net-5.0) 對像中
1. 創建[Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document)並用MemoryStream對像初始化
1. 使用[Aspose.Words.Document.Save("output.wordml", SaveFormat.Wordml)](https://apireference.aspose.com/words/net/aspose.words.document/save/methods)保存文檔/3)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或與 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台兼容的操作系統。
- Microsoft Visual Studio 等開發環境。
- Aspose.Slides for .NET 和 Aspose.Words for .NET DLL 在您的項目中引用。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="此代碼示例展示瞭如何使用 C# 將 PPS 轉換為 WORDML 或在線" offSpacer="" %}}

```cs
// Load the Microsoft PowerPoint PPS file
Aspose.Slides.Presentation pps = new Aspose.Slides.Presentation("source.pps");

var stream = new MemoryStream();

pps.Save(stream, Aspose.Slides.Export.SaveFormat.Html);
stream.Flush();
stream.Seek(0, SeekOrigin.Begin);
// stream.Position = 0;

// Load the content of the presentation to a Word document
var wordml = new Aspose.Words.Document(stream);
      
// Save the Word WORDML document
wordml.Save("output.wordml", Aspose.Words.SaveFormat.Wordml);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>PPS 到 WORDML 在線轉換器</h3>

<iframe title="pps 到 wordml 轉換在線工具" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=wordml&from=pps" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="將 PPS 轉換為 WORDML 的免費應用程序" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPS file." >}}

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
              <h2>經常問的問題</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>如何在線將 PPS 轉換為 WORDML？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">上面集成了用於 PPS 轉換的在線應用程序。要使用該應用程序，您可以通過將 PPS 文件拖放到指定區域或在區域內單擊以導入文件來添加 PPS 文件。添加文件後，單擊“轉換”按鈕啟動轉換過程。 PPS 到 WORDML 轉換完成後，您只需單擊一下即可下載新轉換的文件，它將以 WORDML 格式提供。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>轉換 PPS 需要多長時間？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">這個在線轉換器速度很快，但是 PPS 到 WORDML 轉換的速度主要取決於要轉換的 PPS 文件的大小。較小的 PPS 文件可以在幾秒鐘內渲染成 WORDML 格式。此外，如果您在 .NET 應用程序中集成了 PPS 到 WORDML 的轉換代碼，則轉換速度將取決於您針對轉換過程優化應用程序的程度。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>使用免費的 Aspose.Total 轉換器將 PPS 轉換為 WORDML 是否安全？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">當然！ PPS 到 WORDML 的轉換過程完成後，轉換後的 WORDML 文件的下載鏈接將立即可用。所有上傳的文件，包括 PPS 文件，將在 24 小時後從系統中刪除，並且下載鏈接在此時間段後停止運行。在線轉換器確保您文件的安全和隱私，並且集成的應用程序可免費用於測試目的。這允許用戶在將代碼集成到他們的項目之前檢查結果。</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>我應該使用什麼瀏覽器來轉換 PPS？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">您可以使用任何現代網絡瀏覽器（如 Google Chrome、Firefox、Opera 或 Safari）在線將 PPS 文件轉換為 WORDML。但是，如果您正在創建桌面應用程序，建議使用 Aspose.Total PPS Conversion API 以實現流暢無縫的轉換過程。</span>
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