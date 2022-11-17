---
title: MD'yi PPT'ye Dönüştürmek için C++ API
description: Microsoft Word veya Adobe Acrobat Reader kullanmadan MD'yi C++ aracılığıyla PPT'ye dönüştürün

family: total
platformtag: cpp
feature: conversion
informat: MD
outformat: PPT
otherformats: XAML PPSX POTM SWF ODP PPTM POWERPOINT POTX PPS OTP POT PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ Uygulamalarında MD'yi PPT'ye Render" h2="Microsoft<sup>&reg;</sup> PowerPoint kullanmadan C++ Uygulamalarınız içinde MD'yi PPT'ye dönüştürün" >}}

{{% blocks/products/pf/feature-page-summary %}}
C++ uygulamalarınızda MD'den PPT'ye dönüştürme özelliğini entegre etmek isteyen bir C++ geliştiricisi misiniz? Bunu iki basit adımda yapabilirsiniz. [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) kullanarak MD'yi PPTX'e aktarabilirsiniz. İkinci olarak, [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) kullanarak PPTX'i PPT'ye dönüştürebilirsiniz. Her iki API de [Aspose.Total for C++](https://products.aspose.com/total/cpp/) paketi kapsamında gelir. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MD'yi PPT'ye Dışa Aktarmak için C++ API" %}}
1. [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) sınıf referansını kullanarak MD dosyasını açın
2. [Kaydet](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) yöntem işlevini kullanarak MD'yi PPTX'e dönüştürün
3. [Sunum](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) sınıf referansını kullanarak PPTX belgesini yükleyin
4. [Kaydet](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) üye işlevini kullanarak belgeyi PPT biçiminde kaydedin ve 'Ppt'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://downloads.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load MD file with an instance of Document class
auto doc = MakeObject<Document>(u"template.md");
// save MD as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Ppt format
prs->Save(u"output.ppt", Aspose::Slides::Export::SaveFormat::Ppt);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="MD Belgesinin Şifresini C++ ile Değiştirin" %}}
MD'yi PPT'ye oluşturma sürecinde, parola korumalı bir MD açabilir ve ayrıca parolasını değiştirebilirsiniz. Bir MD dosyasının şifresini değiştirmek için o belgenin sahip şifresini bilmeniz gerekir. [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) ile parola korumalı PDF belgesini sahip parolasını belirterek yükleyebilir ve parolayı değiştirmek için ChangePasswords yöntemini kullanabilirsiniz.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing MD Document
auto doc = MakeObject<Document>(L"input.md", L"owner");
// change password of MD Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ ile PPT Dosyasında Web'den Görüntüler Ekleme" %}}
MD'yi PPT'ye dönüştürdükten sonra, çıktı belgenize web'den görüntüler de ekleyebilirsiniz. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) şu popüler formatlardaki resimlerle işlemleri destekler: JPEG, PNG, BMP, GIF ve diğerleri. Bir sunumdaki bir slayta bilgisayarınızdaki bir veya birkaç resim ekleyebilirsiniz. C++'daki bu örnek kod, bir PPT dosyasına nasıl resim ekleneceğini gösterir.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a PPT file
auto pres = System::MakeObject<Presentation>("output.ppt");
// get slide
auto slide = pres->get_Slides()->idx_get(0);
// initialize Web Client    
auto webClient = System::MakeObject<WebClient>();
// get image data
auto imageData = webClient->DownloadData(System::MakeObject<Uri>(u"[REPLACE WITH URL]"));
// add image
auto image = pres->get_Images()->AddImage(imageData);
// add picture frame
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
// save updated file
pres->Save(u"updated.ppt", SaveFormat::Ppt);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/md-to-xaml/" name="MD İle XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/md-to-ppsx/" name="MD İle PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/md-to-potm/" name="MD İle POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/md-to-swf/" name="MD İle SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/md-to-ppt/" name="MD İle PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/md-to-pptm/" name="MD İle PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/md-to-powerpoint/" name="MD İle POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/md-to-potx/" name="MD İle POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/md-to-pps/" name="MD İle PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/md-to-otp/" name="MD İle OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/md-to-pot/" name="MD İle POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/md-to-ppsm/" name="MD İle PPSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}