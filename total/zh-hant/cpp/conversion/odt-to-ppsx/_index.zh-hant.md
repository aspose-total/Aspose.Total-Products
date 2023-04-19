---
title: 通過 C++ 將 ODT 轉換為 PPSX 或使用免費的在線轉換器
description: 在您的 C++ 應用程序中將 ODT 導出為 PPSX，而無需使用 Microsoft Word of PowerPoint 或在線。在集成代碼之前快速測試免費的 POT 到 CSV 在線轉換器。

family: total
platformtag: cpp
feature: conversion
informat: ODT
outformat: PPSX
otherformats: PPTX PPTM PPT ODP POT PPS POTX PPSM POTM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="將 ODT 轉換為 PPSX 的 C++ API 或在線應用程序" h2="在您的 C++ 應用程序中將 ODT 導出為 PPSX，而無需使用 Microsoft Word&reg;或 PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) 包含強大的文件自動化 API，允許在使用其中兩個 API 時自動進行 ODT 到 PPSX 的轉換。使用 [Aspose.Words for C++](https://products.aspose.com/words/cpp/) 加載您的 ODT 並將其轉換為 HTML，然後通過 PowerPoint 操作 C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) 加載 HTML 創建一個新的演示文稿，並將其保存為 PPSX。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ 上的 ODT 到 PPSX 轉換" %}}
1. 用[Odtument](https://reference.aspose.com/words/cpp/class/aspose.words.odtument)類參考打開ODT文件
2. 使用 [Save](https://reference.aspose.com/words/cpp/class/aspose.words.odtument#save_stdbasicostream_saveoptions) 成員函數將 ODT 轉換為 HTML
3. 始化一個新的[Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)對象
4. 在你的幻燈片中添加一個自選圖形，並在其中添加 AddTextFrame
5. 加載 HTML 內容並將其寫入您的 Presentation 文件中
6. 使用 [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) 方法將文檔保存為 PPSX 格式，並將 Ppsx 設置為 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
從命令行安裝為 ```nuget install Aspose.Total.Cpp``` 或通過 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp```。

或者，從 [下載](https://releases.aspose.com/total/cpp) 獲取 ZIP 文件中的離線 MSI 安裝程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load ODT file with an instance of Odtument
Odtument odtument = new Odtument("template.odt");
System::SharedPtr<Odtument> odt = System::MakeObject<Odtument>(u"sourceFile.odt");
// save the odtument in HTML file format
odt->Save(u"HtmlOutput.HTML");
// load the desired the presentation
SharedPtr<Presentation> pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ISlide> sld = pres->get_Slides()->idx_get(0);
// add an AutoShape of Rectangle type
SharedPtr<IAutoShape>  ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10, 10, 700, 500);
// reset default fill color
ashp->get_FillFormat()->set_FillType(FillType::NoFill);
// add TextFrame to the Rectangle
ashp->AddTextFrame(u" ");
// access the text frame
SharedPtr<ITextFrame>  txtFrame = ashp->get_TextFrame();
// get Paragraphs collection
SharedPtr<Aspose::Slides::IParagraphCollection>ParaCollection = txtFrame->get_Paragraphs();
// clear all paragraphs in added text frame
ParaCollection->Clear();
// load the HTML file using stream reader
SharedPtr<System::IO::StreamReader>  tr = MakeObject<System::IO::StreamReader>(HtmlOutput.HTML);
// add text from HTML stream reader in text frame
ParaCollection->AddFromHtml(tr->ReadToEnd());
// save presentation as Ppsx
pres->Save(output.ppsx, Aspose::Slides::Export::SaveFormat::Ppsx);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>免費的 ODT 到 PPSX 在線轉換器</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=ppsx&from=odt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="通過 C++ 加載受密碼保護的 ODT 文檔" %}}
除了文檔轉換，[Aspose.Words for C++](https://products.aspose.com/words/cpp/) API 為 C++ 開發人員提供了大量的文檔操作功能。如果您的 Microsoft Word ODT 文件格式受密碼保護，您仍然可以使用 API 打開它。為了加載加密文檔，您可以使用特殊的構造函數重載，它接受 [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options) 對象。此對象包含 Password 屬性，該屬性指定密碼字符串。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected odtument, the password is passed to the odtument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"odtPassword");
// load the odtument from the local file system by filename:
SharedPtr<Odtument> odt = MakeObject<Odtument>(u"Encrypted.odt", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通過 C++ 在 PPSX 文檔中添加註釋" %}}
在將 ODT 保存為 PPSX 的同時，您還可以使用 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) 在您的 PPSX 文檔中添加更多功能。例如，您可以在演示文稿中添加評論。演示幻燈片註釋與特定作者相關聯。 Presentation 類在 ICommentAuthorCollection 中保存負責添加幻燈片註釋的作者集合。對於每個作者，ICommentCollection 中都有一組評論。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate Presentation class
SharedPtr<Presentation>pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ILayoutSlide>layout = pres->get_LayoutSlides()->idx_get(0);
// add empty slide
pres->get_Slides()->AddEmptySlide(layout);
// adding Author
SharedPtr<ICommentAuthor> author = pres->get_CommentAuthors()->AddAuthor(u"John Doe", u"MF");
// set position of comments
System::Drawing::PointF point = System::Drawing::PointF(0.2f, 0.2f);
// add slide comment for an author on slide 1
author->get_Comments()->AddComment(u"Hello John, this is a slide comment", pres->get_Slides()->idx_get(1), point, DateTime::get_Now());
// access ISlide 1
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);
// save presentation as Ppsx
pres->Save(output.ppsx, Aspose::Slides::Export::SaveFormat::Ppsx);  
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
                          <span itemprop="name"><b>如何在線將 ODT 轉換為 PPSX？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">您可以在上面找到用於 ODT 轉換的在線應用程序。要開始轉換過程，您可以通過拖放或在白色區域內單擊以導入文檔來添加 ODT 文件。添加文件後，只需單擊“轉換”按鈕即可。 ODT 到 PPSX 轉換完成後，您只需單擊一下即可下載轉換後的文件。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>轉換 ODT 需要多長時間？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">此在線轉換器的速度在很大程度上取決於正在轉換的 ODT 文件的大小。只需幾秒鐘即可將小型 ODT 文件轉換為 PPSX。如果您在 C++ 應用程序中使用轉換代碼，轉換速度將取決於您對應用程序的優化程度。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>使用免費的 Aspose.Total 轉換器將 ODT 轉換為 PPSX 是否安全？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">當然！使用我們的在線轉換器將您的 ODT 文件轉換為 PPSX 後，PPSX 文件的下載鏈接將立即可用。我們非常重視您上傳文件的安全和隱私，並會在轉換過程完成 24 小時後將其刪除。請放心，沒有人可以訪問您的文件。我們的轉換過程，包括 ODT 轉換，是完全安全的。我們提供了一個用於測試目的的免費應用程序，以便您可以在集成代碼之前驗證結果。</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>我應該使用什麼瀏覽器來轉換 ODT？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">對於在線 ODT 轉換，您可以使用任何現代瀏覽器，例如 Google Chrome、Firefox、Opera 或 Safari。但是，如果您正在開發桌面應用程序，建議使用 Aspose.Total ODT Conversion API 以獲得流暢的性能。</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}