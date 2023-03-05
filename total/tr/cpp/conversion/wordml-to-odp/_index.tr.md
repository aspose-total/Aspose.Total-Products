---
title: WORDML'yi C++ ile ODP'ye dönüştürün veya ücretsiz Çevrimiçi Dönüştürücü ile
description: Microsoft Word of PowerPoint kullanmadan C++ uygulamalarınızda WORDML'yi ODP'ye aktarın veya çevrimiçi. Kodu entegre etmeden önce ücretsiz POT'den CSV'e çevrimiçi dönüştürücüyü hızlı bir şekilde test edin.

family: total
platformtag: cpp
feature: conversion
informat: WORDML
outformat: ODP
otherformats: PPT PPTX PPSM POT PPSX POTM POWERPOINT PPTM POTX PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="WORDML'yi ODP'ye Dönüştürmek için C++ API veya Çevrimiçi Uygulama" h2="Microsoft Word&reg; kullanmadan C++ uygulamalarınız içinde WORDML'yi ODP'ye aktarın veya PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/), iki API'sini kullanırken WORDML'den ODP'ye dönüştürmeyi otomatikleştirmeye izin veren güçlü dosya otomasyon API'lerinden oluşur. [Aspose.Words for C++](https://products.aspose.com/words/cpp/) kullanarak WORDML'nizi yükleyin ve HTML'ye dönüştürün, ardından HTML'yi PowerPoint manipülasyonu C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) yeni bir sunum oluşturun ve ODP olarak kaydedin. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++'da WORDML'den ODP'ye Dönüştürme" %}}
1. [Document](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument) sınıf referansını kullanarak WORDML dosyasını açın
2. [Kaydet](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument#save_stdbasicostream_saveoptions) üye işlevini kullanarak WORDML'yi HTML'ye dönüştürün
3. Yeni bir [Sunum](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) nesnesini başlatın
4. Slaytınıza bir Otomatik Şekil ekleyin ve buna AddTextFrame ekleyin
5. HTML içeriğini yükleyin ve Sunum dosyanıza yazın
6. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) yöntemini kullanarak belgeyi ODP formatına kaydedin ve Odp'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://releases.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load WORDML file with an instance of Wordmlument
Wordmlument wordmlument = new Wordmlument("template.wordml");
System::SharedPtr<Wordmlument> wordml = System::MakeObject<Wordmlument>(u"sourceFile.wordml");
// save the wordmlument in HTML file format
wordml->Save(u"HtmlOutput.HTML");
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
// save presentation as Odp
pres->Save(output.odp, Aspose::Slides::Export::SaveFormat::Odp);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>WORDML'den ODP'e Ücretsiz Çevrimiçi Dönüştürücü</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=odp&from=wordml" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Parola Korumalı WORDML Belgesini C++ ile Yükleyin" %}}
Belge dönüştürmenin yanı sıra, [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API, C++ geliştiricileri için tonlarca belge işleme özelliğine izin verir. Microsoft Word WORDML dosya biçiminiz parola korumalıysa, API'yi kullanarak yine de açabilirsiniz. Şifrelenmiş belgeyi yüklemek için, bir [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options) nesnesini kabul eden özel bir kurucu aşırı yüklemesi kullanabilirsiniz. Bu nesne, parola dizesini belirten Parola özelliğini içerir.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected wordmlument, the password is passed to the wordmlument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"wordmlPassword");
// load the wordmlument from the local file system by filename:
SharedPtr<Wordmlument> wordml = MakeObject<Wordmlument>(u"Encrypted.wordml", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ ile ODP Belgesine Yorum Ekleme" %}}
WORDML'yi ODP olarak kaydederken, ODP belgenize daha fazla özellik eklemek için [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) kullanabilirsiniz. Örneğin, sunumunuza yorum ekleyebilirsiniz. Sunum slayt yorumu belirli bir yazarla ilişkilendirilir. Presentation sınıfı, ICommentAuthorCollection'da slayt yorumları eklemekten sorumlu yazarların koleksiyonunu tutar. Her yazar için ICommentCollection'da bir yorum koleksiyonu vardır.
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
// save presentation as Odp
pres->Save(output.odp, Aspose::Slides::Export::SaveFormat::Odp);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/wordml-to-ppt/" name="WORDML İle PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/wordml-to-pptx/" name="WORDML İle PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/wordml-to-ppsm/" name="WORDML İle PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/wordml-to-pot/" name="WORDML İle POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/wordml-to-ppsx/" name="WORDML İle PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/wordml-to-potm/" name="WORDML İle POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/wordml-to-powerpoint/" name="WORDML İle POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/wordml-to-pptm/" name="WORDML İle PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/wordml-to-potx/" name="WORDML İle POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/wordml-to-pps/" name="WORDML İle PPS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}