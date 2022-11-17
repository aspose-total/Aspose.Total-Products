---
title: CGM'yi POT'ye Dönüştürmek için C++ API
description: Microsoft Word veya Adobe Acrobat Reader kullanmadan CGM'yi C++ aracılığıyla POT'ye dönüştürün

family: total
platformtag: cpp
feature: conversion
informat: CGM
outformat: POT
otherformats: SWF POWERPOINT POTM PPSM OTP XAML PPTM PPSX PPS POTX ODP PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ Uygulamalarında CGM'yi POT'ye Render" h2="Microsoft<sup>&reg;</sup> PowerPoint kullanmadan C++ Uygulamalarınız içinde CGM'yi POT'ye dönüştürün" >}}

{{% blocks/products/pf/feature-page-summary %}}
C++ uygulamalarınızda CGM'den POT'ye dönüştürme özelliğini entegre etmek isteyen bir C++ geliştiricisi misiniz? Bunu iki basit adımda yapabilirsiniz. [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) kullanarak CGM'yi PPTX'e aktarabilirsiniz. İkinci olarak, [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) kullanarak PPTX'i POT'ye dönüştürebilirsiniz. Her iki API de [Aspose.Total for C++](https://products.aspose.com/total/cpp/) paketi kapsamında gelir. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM'yi POT'ye Dışa Aktarmak için C++ API" %}}
1. [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) sınıf referansını kullanarak CGM dosyasını açın
2. [Kaydet](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) yöntem işlevini kullanarak CGM'yi PPTX'e dönüştürün
3. [Sunum](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) sınıf referansını kullanarak PPTX belgesini yükleyin
4. [Kaydet](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) üye işlevini kullanarak belgeyi POT biçiminde kaydedin ve 'Pot'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://downloads.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load CGM file with an instance of Document class
auto doc = MakeObject<Document>(u"template.cgm");
// save CGM as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Pot format
prs->Save(u"output.pot", Aspose::Slides::Export::SaveFormat::Pot);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="CGM Belgesinin Şifresini C++ ile Değiştirin" %}}
CGM'yi POT'ye oluşturma sürecinde, parola korumalı bir CGM açabilir ve ayrıca parolasını değiştirebilirsiniz. Bir CGM dosyasının şifresini değiştirmek için o belgenin sahip şifresini bilmeniz gerekir. [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) ile parola korumalı PDF belgesini sahip parolasını belirterek yükleyebilir ve parolayı değiştirmek için ChangePasswords yöntemini kullanabilirsiniz.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing CGM Document
auto doc = MakeObject<Document>(L"input.cgm", L"owner");
// change password of CGM Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ ile POT Dosyasında Web'den Görüntüler Ekleme" %}}
CGM'yi POT'ye dönüştürdükten sonra, çıktı belgenize web'den görüntüler de ekleyebilirsiniz. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) şu popüler formatlardaki resimlerle işlemleri destekler: JPEG, PNG, BMP, GIF ve diğerleri. Bir sunumdaki bir slayta bilgisayarınızdaki bir veya birkaç resim ekleyebilirsiniz. C++'daki bu örnek kod, bir POT dosyasına nasıl resim ekleneceğini gösterir.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a POT file
auto pres = System::MakeObject<Presentation>("output.pot");
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
pres->Save(u"updated.pot", SaveFormat::Pot);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/cgm-to-swf/" name="CGM İle SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/cgm-to-powerpoint/" name="CGM İle POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/cgm-to-potm/" name="CGM İle POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/cgm-to-ppsm/" name="CGM İle PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/cgm-to-otp/" name="CGM İle OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/cgm-to-xaml/" name="CGM İle XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/cgm-to-pptm/" name="CGM İle PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/cgm-to-ppsx/" name="CGM İle PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/cgm-to-pps/" name="CGM İle PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/cgm-to-potx/" name="CGM İle POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/cgm-to-pot/" name="CGM İle POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/cgm-to-ppt/" name="CGM İle PPT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}