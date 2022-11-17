---
title: XSLFO'yi POTM'ye Dönüştürmek için C++ API
description: Microsoft Word veya Adobe Acrobat Reader kullanmadan XSLFO'yi C++ aracılığıyla POTM'ye dönüştürün

family: total
platformtag: cpp
feature: conversion
informat: XSLFO
outformat: POTM
otherformats: ODP POWERPOINT SWF PPS PPSX POTX PPTM POT OTP XAML PPSM PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ Uygulamalarında XSLFO'yi POTM'ye Render" h2="Microsoft<sup>&reg;</sup> PowerPoint kullanmadan C++ Uygulamalarınız içinde XSLFO'yi POTM'ye dönüştürün" >}}

{{% blocks/products/pf/feature-page-summary %}}
C++ uygulamalarınızda XSLFO'den POTM'ye dönüştürme özelliğini entegre etmek isteyen bir C++ geliştiricisi misiniz? Bunu iki basit adımda yapabilirsiniz. [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) kullanarak XSLFO'yi PPTX'e aktarabilirsiniz. İkinci olarak, [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) kullanarak PPTX'i POTM'ye dönüştürebilirsiniz. Her iki API de [Aspose.Total for C++](https://products.aspose.com/total/cpp/) paketi kapsamında gelir. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XSLFO'yi POTM'ye Dışa Aktarmak için C++ API" %}}
1. [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) sınıf referansını kullanarak XSLFO dosyasını açın
2. [Kaydet](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) yöntem işlevini kullanarak XSLFO'yi PPTX'e dönüştürün
3. [Sunum](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) sınıf referansını kullanarak PPTX belgesini yükleyin
4. [Kaydet](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) üye işlevini kullanarak belgeyi POTM biçiminde kaydedin ve 'Potm'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://downloads.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load XSLFO file with an instance of Document class
auto doc = MakeObject<Document>(u"template.xslfo");
// save XSLFO as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Potm format
prs->Save(u"output.potm", Aspose::Slides::Export::SaveFormat::Potm);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="XSLFO Belgesinin Şifresini C++ ile Değiştirin" %}}
XSLFO'yi POTM'ye oluşturma sürecinde, parola korumalı bir XSLFO açabilir ve ayrıca parolasını değiştirebilirsiniz. Bir XSLFO dosyasının şifresini değiştirmek için o belgenin sahip şifresini bilmeniz gerekir. [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) ile parola korumalı PDF belgesini sahip parolasını belirterek yükleyebilir ve parolayı değiştirmek için ChangePasswords yöntemini kullanabilirsiniz.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing XSLFO Document
auto doc = MakeObject<Document>(L"input.xslfo", L"owner");
// change password of XSLFO Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ ile POTM Dosyasında Web'den Görüntüler Ekleme" %}}
XSLFO'yi POTM'ye dönüştürdükten sonra, çıktı belgenize web'den görüntüler de ekleyebilirsiniz. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) şu popüler formatlardaki resimlerle işlemleri destekler: JPEG, PNG, BMP, GIF ve diğerleri. Bir sunumdaki bir slayta bilgisayarınızdaki bir veya birkaç resim ekleyebilirsiniz. C++'daki bu örnek kod, bir POTM dosyasına nasıl resim ekleneceğini gösterir.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a POTM file
auto pres = System::MakeObject<Presentation>("output.potm");
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
pres->Save(u"updated.potm", SaveFormat::Potm);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xslfo-to-potm/" name="XSLFO İle POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xslfo-to-powerpoint/" name="XSLFO İle POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xslfo-to-swf/" name="XSLFO İle SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xslfo-to-pps/" name="XSLFO İle PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xslfo-to-ppsx/" name="XSLFO İle PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xslfo-to-potx/" name="XSLFO İle POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xslfo-to-pptm/" name="XSLFO İle PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xslfo-to-pot/" name="XSLFO İle POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xslfo-to-otp/" name="XSLFO İle OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xslfo-to-xaml/" name="XSLFO İle XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xslfo-to-ppsm/" name="XSLFO İle PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xslfo-to-ppt/" name="XSLFO İle PPT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}