---
title: PCL'yi OTP'ye Dönüştürmek için C++ API
description: Microsoft Word veya Adobe Acrobat Reader kullanmadan PCL'yi C++ aracılığıyla OTP'ye dönüştürün

family: total
platformtag: cpp
feature: conversion
informat: PCL
outformat: OTP
otherformats: POTX ODP PPSM PPS PPT POTM PPTM PPSX XAML POWERPOINT POT SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ Uygulamalarında PCL'yi OTP'ye Render" h2="Microsoft<sup>&reg;</sup> PowerPoint kullanmadan C++ Uygulamalarınız içinde PCL'yi OTP'ye dönüştürün" >}}

{{% blocks/products/pf/feature-page-summary %}}
C++ uygulamalarınızda PCL'den OTP'ye dönüştürme özelliğini entegre etmek isteyen bir C++ geliştiricisi misiniz? Bunu iki basit adımda yapabilirsiniz. [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) kullanarak PCL'yi PPTX'e aktarabilirsiniz. İkinci olarak, [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) kullanarak PPTX'i OTP'ye dönüştürebilirsiniz. Her iki API de [Aspose.Total for C++](https://products.aspose.com/total/cpp/) paketi kapsamında gelir. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PCL'yi OTP'ye Dışa Aktarmak için C++ API" %}}
1. [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) sınıf referansını kullanarak PCL dosyasını açın
2. [Kaydet](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) yöntem işlevini kullanarak PCL'yi PPTX'e dönüştürün
3. [Sunum](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) sınıf referansını kullanarak PPTX belgesini yükleyin
4. [Kaydet](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) üye işlevini kullanarak belgeyi OTP biçiminde kaydedin ve 'Otp'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://downloads.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load PCL file with an instance of Document class
auto doc = MakeObject<Document>(u"template.pcl");
// save PCL as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Otp format
prs->Save(u"output.otp", Aspose::Slides::Export::SaveFormat::Otp);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="PCL Belgesinin Şifresini C++ ile Değiştirin" %}}
PCL'yi OTP'ye oluşturma sürecinde, parola korumalı bir PCL açabilir ve ayrıca parolasını değiştirebilirsiniz. Bir PCL dosyasının şifresini değiştirmek için o belgenin sahip şifresini bilmeniz gerekir. [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) ile parola korumalı PDF belgesini sahip parolasını belirterek yükleyebilir ve parolayı değiştirmek için ChangePasswords yöntemini kullanabilirsiniz.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing PCL Document
auto doc = MakeObject<Document>(L"input.pcl", L"owner");
// change password of PCL Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ ile OTP Dosyasında Web'den Görüntüler Ekleme" %}}
PCL'yi OTP'ye dönüştürdükten sonra, çıktı belgenize web'den görüntüler de ekleyebilirsiniz. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) şu popüler formatlardaki resimlerle işlemleri destekler: JPEG, PNG, BMP, GIF ve diğerleri. Bir sunumdaki bir slayta bilgisayarınızdaki bir veya birkaç resim ekleyebilirsiniz. C++'daki bu örnek kod, bir OTP dosyasına nasıl resim ekleneceğini gösterir.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a OTP file
auto pres = System::MakeObject<Presentation>("output.otp");
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
pres->Save(u"updated.otp", SaveFormat::Otp);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pcl-to-potx/" name="PCL İle POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pcl-to-otp/" name="PCL İle OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pcl-to-ppsm/" name="PCL İle PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pcl-to-pps/" name="PCL İle PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pcl-to-ppt/" name="PCL İle PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pcl-to-potm/" name="PCL İle POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pcl-to-pptm/" name="PCL İle PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pcl-to-ppsx/" name="PCL İle PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pcl-to-xaml/" name="PCL İle XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pcl-to-powerpoint/" name="PCL İle POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pcl-to-pot/" name="PCL İle POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pcl-to-swf/" name="PCL İle SWF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}