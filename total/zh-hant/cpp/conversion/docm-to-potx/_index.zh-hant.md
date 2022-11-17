---
title: 通過 C++ 將 DOCM 轉換為 POTX
description: 在您的 C++ 應用程序中將 DOCM 導出為 POTX，而無需使用 Microsoft Word of PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: DOCM
outformat: POTX
otherformats: PPT PPTM PPTX POWERPOINT ODP POT PPSX PPSM POTM PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="將 DOCM 轉換為 POTX 的 C++ API" h2="在您的 C++ 應用程序中將 DOCM 導出為 POTX，而無需使用 Microsoft Word&reg;或 PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) 包含強大的文件自動化 API，允許在使用其中兩個 API 時自動進行 DOCM 到 POTX 的轉換。使用 [Aspose.Words for C++](https://products.aspose.com/words/cpp/) 加載您的 DOCM 並將其轉換為 HTML，然後通過 PowerPoint 操作 C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) 加載 HTML 創建一個新的演示文稿，並將其保存為 POTX。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ 上的 DOCM 到 POTX 轉換" %}}
1.使用[Document](https://reference.aspose.com/words/cpp/class/aspose.words.docmument)類參考打開DOCM文件
2. 使用 [Save](https://reference.aspose.com/words/cpp/class/aspose.words.docmument#save_stdbasicostream_saveoptions) 成員函數將 DOCM 轉換為 HTML
3.初始化一個新的[Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)對象
4. 在你的幻燈片中添加一個自選圖形，並在其中添加 AddTextFrame
5. 加載 HTML 內容並將其寫入您的 Presentation 文件中
6. 使用 [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) 方法將文檔保存為 POTX 格式，並將 Potx 設置為 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
從命令行安裝為 ```nuget install Aspose.Total.Cpp``` 或通過 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp``。

或者，從 [下載](https://downloads.aspose.com/total/cpp) 獲取 ZIP 文件中的離線 MSI 安裝程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOCM file with an instance of Document
Document docmument = new Document("template.docm");
System::SharedPtr<Document> docm = System::MakeObject<Document>(u"sourceFile.docm");
// save the docmument in HTML file format
docm->Save(u"HtmlOutput.HTML");
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
// save presentation as Potx
pres->Save(output.potx, Aspose::Slides::Export::SaveFormat::Potx);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通過 C++ 加載受密碼保護的 DOCM 文檔" %}}
除了文檔轉換，[Aspose.Words for C++](https://products.aspose.com/words/cpp/) API 為 C++ 開發人員提供了大量的文檔操作功能。如果您的 Microsoft Word DOCM 文件格式受密碼保護，您仍然可以使用 API 打開它。為了加載加密文檔，您可以使用特殊的構造函數重載，它接受 [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options) 對象。此對象包含 Password 屬性，該屬性指定密碼字符串。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected docmument, the password is passed to the docmument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"docmPassword");
// load the docmument from the local file system by filename:
SharedPtr<Document> docm = MakeObject<Document>(u"Encrypted.docm", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通過 C++ 在 POTX 文檔中添加註釋" %}}
在將 DOCM 保存為 POTX 的同時，您還可以使用 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) 在您的 POTX 文檔中添加更多功能。例如，您可以在演示文稿中添加評論。演示幻燈片註釋與特定作者相關聯。 Presentation 類在 ICommentAuthorCollection 中保存負責添加幻燈片註釋的作者集合。對於每個作者，ICommentCollection 中都有一組評論。
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
// save presentation as Potx
pres->Save(output.potx, Aspose::Slides::Export::SaveFormat::Potx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/docm-to-ppt/" name="DOCM 至 PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/docm-to-pptm/" name="DOCM 至 PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/docm-to-pptx/" name="DOCM 至 PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/docm-to-powerpoint/" name="DOCM 至 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/docm-to-potx/" name="DOCM 至 POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/docm-to-pot/" name="DOCM 至 POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/docm-to-ppsx/" name="DOCM 至 PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/docm-to-ppsm/" name="DOCM 至 PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/docm-to-potm/" name="DOCM 至 POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/docm-to-pps/" name="DOCM 至 PPS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}