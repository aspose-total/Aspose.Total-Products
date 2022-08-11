---
title: XML'yi POTX'ye Dönüştürmek için C++ API
description: Microsoft Word veya Adobe Acrobat Reader kullanmadan XML'yi C++ aracılığıyla POTX'ye dönüştürün
url: /tr/cpp/conversion/xml-to-potx/
family: total
platformtag: cpp
feature: conversion
informat: XML
outformat: POTX
otherformats: ODP SWF PPSX PPS POTM XAML PPT PPTM OTP POWERPOINT PPSM POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ Uygulamalarında XML'yi POTX'ye Render" h2="Microsoft<sup>&reg;</sup> PowerPoint kullanmadan C++ Uygulamalarınız içinde XML'yi POTX'ye dönüştürün" >}}

{{% blocks/products/pf/feature-page-summary %}}
C++ uygulamalarınızda XML'den POTX'ye dönüştürme özelliğini entegre etmek isteyen bir C++ geliştiricisi misiniz? Bunu iki basit adımda yapabilirsiniz. [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) kullanarak XML'yi PPTX'e aktarabilirsiniz. İkinci olarak, [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) kullanarak PPTX'i POTX'ye dönüştürebilirsiniz. Her iki API de [Aspose.Total for C++](https://products.aspose.com/total/cpp/) paketi kapsamında gelir. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XML'yi POTX'ye Dışa Aktarmak için C++ API" %}}
1. [Belge](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) sınıf referansını kullanarak XML dosyasını açın
2. [Kaydet](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) yöntem işlevini kullanarak XML'yi PPTX'e dönüştürün
3. [Sunum](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) sınıf referansını kullanarak PPTX belgesini yükleyin
4. [Kaydet](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) üye işlevini kullanarak belgeyi POTX biçiminde kaydedin ve 'Potx'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://downloads.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load XML file with an instance of Document class
auto doc = MakeObject<Document>(u"template.xml");
// save XML as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Potx format
prs->Save(u"output.potx", Aspose::Slides::Export::SaveFormat::Potx);  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="XML Belgesinin Şifresini C++ ile Değiştirin" %}}
XML'yi POTX'ye oluşturma sürecinde, parola korumalı bir XML açabilir ve ayrıca parolasını değiştirebilirsiniz. Bir XML dosyasının şifresini değiştirmek için o belgenin sahip şifresini bilmeniz gerekir. [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) ile parola korumalı PDF belgesini sahip parolasını belirterek yükleyebilir ve parolayı değiştirmek için ChangePasswords yöntemini kullanabilirsiniz.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing XML Document
auto doc = MakeObject<Document>(L"input.xml", L"owner");
// change password of XML Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ ile POTX Dosyasında Web'den Görüntüler Ekleme" %}}
XML'yi POTX'ye dönüştürdükten sonra, çıktı belgenize web'den görüntüler de ekleyebilirsiniz. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) şu popüler formatlardaki resimlerle işlemleri destekler: JPEG, PNG, BMP, GIF ve diğerleri. Bir sunumdaki bir slayta bilgisayarınızdaki bir veya birkaç resim ekleyebilirsiniz. C++'daki bu örnek kod, bir POTX dosyasına nasıl resim ekleneceğini gösterir.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a POTX file
auto pres = System::MakeObject<Presentation>("output.potx");
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
pres->Save(u"updated.potx", SaveFormat::Potx);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xml-to-potx/" name="XML İle POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xml-to-swf/" name="XML İle SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xml-to-ppsx/" name="XML İle PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xml-to-pps/" name="XML İle PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xml-to-potm/" name="XML İle POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xml-to-xaml/" name="XML İle XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xml-to-ppt/" name="XML İle PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xml-to-pptm/" name="XML İle PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xml-to-otp/" name="XML İle OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xml-to-powerpoint/" name="XML İle POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xml-to-ppsm/" name="XML İle PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xml-to-pot/" name="XML İle POT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}