---
title: ODT'yi C++ ile PPTX'ye dönüştürün
description: Microsoft Word of PowerPoint kullanmadan C++ uygulamalarınızda ODT'yi PPTX'ye aktarın

family: total
platformtag: cpp
feature: conversion
informat: ODT
outformat: PPTX
otherformats: POWERPOINT PPTM POT POTX PPSX ODP PPT POTM PPS PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="ODT'yi PPTX'ye Dönüştürmek için C++ API" h2="Microsoft Word&reg; kullanmadan C++ uygulamalarınız içinde ODT'yi PPTX'ye aktarın veya PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/), iki API'sini kullanırken ODT'den PPTX'ye dönüştürmeyi otomatikleştirmeye izin veren güçlü dosya otomasyon API'lerinden oluşur. [Aspose.Words for C++](https://products.aspose.com/words/cpp/) kullanarak ODT'nizi yükleyin ve HTML'ye dönüştürün, ardından HTML'yi PowerPoint manipülasyonu C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) yeni bir sunum oluşturun ve PPTX olarak kaydedin. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++'da ODT'den PPTX'ye Dönüştürme" %}}
1. [Document](https://reference.aspose.com/words/cpp/class/aspose.words.odtument) sınıf referansını kullanarak ODT dosyasını açın
2. [Kaydet](https://reference.aspose.com/words/cpp/class/aspose.words.odtument#save_stdbasicostream_saveoptions) üye işlevini kullanarak ODT'yi HTML'ye dönüştürün
3. Yeni bir [Sunum](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) nesnesini başlatın
4. Slaytınıza bir Otomatik Şekil ekleyin ve buna AddTextFrame ekleyin
5. HTML içeriğini yükleyin ve Sunum dosyanıza yazın
6. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) yöntemini kullanarak belgeyi PPTX formatına kaydedin ve Pptx'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://downloads.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
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
// save presentation as Pptx
pres->Save(output.pptx, Aspose::Slides::Export::SaveFormat::Pptx);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parola Korumalı ODT Belgesini C++ ile Yükleyin" %}}
Belge dönüştürmenin yanı sıra, [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API, C++ geliştiricileri için tonlarca belge işleme özelliğine izin verir. Microsoft Word ODT dosya biçiminiz parola korumalıysa, API'yi kullanarak yine de açabilirsiniz. Şifrelenmiş belgeyi yüklemek için, bir [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options) nesnesini kabul eden özel bir kurucu aşırı yüklemesi kullanabilirsiniz. Bu nesne, parola dizesini belirten Parola özelliğini içerir.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected odtument, the password is passed to the odtument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"odtPassword");
// load the odtument from the local file system by filename:
SharedPtr<Odtument> odt = MakeObject<Odtument>(u"Encrypted.odt", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ ile PPTX Belgesine Yorum Ekleme" %}}
ODT'yi PPTX olarak kaydederken, PPTX belgenize daha fazla özellik eklemek için [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) kullanabilirsiniz. Örneğin, sunumunuza yorum ekleyebilirsiniz. Sunum slayt yorumu belirli bir yazarla ilişkilendirilir. Presentation sınıfı, ICommentAuthorCollection'da slayt yorumları eklemekten sorumlu yazarların koleksiyonunu tutar. Her yazar için ICommentCollection'da bir yorum koleksiyonu vardır.
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
// save presentation as Pptx
pres->Save(output.pptx, Aspose::Slides::Export::SaveFormat::Pptx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/odt-to-powerpoint/" name="ODT İle POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/odt-to-pptm/" name="ODT İle PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/odt-to-pot/" name="ODT İle POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/odt-to-potx/" name="ODT İle POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/odt-to-ppsx/" name="ODT İle PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/odt-to-pptx/" name="ODT İle PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/odt-to-ppt/" name="ODT İle PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/odt-to-potm/" name="ODT İle POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/odt-to-pps/" name="ODT İle PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/odt-to-ppsm/" name="ODT İle PPSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}