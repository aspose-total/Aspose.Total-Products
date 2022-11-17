---
title: PPTM'u FLATOPC'a Dönüştürmek için C++ API
description: C++ uygulamalarınızda PPTM'u FLATOPC'a aktarın

family: total
platformtag: cpp
feature: conversion
informat: PPTM
outformat: FLATOPC
otherformats: DOTM WORDML RTF ODT DOT OTT WORD DOC TEXT DOCM DOTX DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="PPTM'u FLATOPC'ye Dönüştürmek için C++ API" h2="Microsoft PowerPoint veya Word bağımlılığı olmadan C++ uygulamalarında PPTM'u FLATOPC'a aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/), C++ Dosya Formatı Otomasyonu kitaplıklarının eksiksiz paketidir. Pakette bulunan API'lerin zengin özelliklerini kullanarak PowerPoint PPTM'u Word FLATOPC'a kolayca dönüştürebiliriz. Dönüştürmeyi gerçekleştirmek için önce PPTM'u HTML'ye dönüştürmek için [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API'sini kullanabilirsiniz. Bundan sonra, zengin özelliklere sahip Kelime İşlem API'sini [Aspose.Words for C++](https://products.aspose.com/words/cpp/) kullanarak HTML'yi FLATOPC'ye dönüştürebilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPTM'u FLATOPC'a Dönüştürmek için C++ API" %}}
1. [Sunum](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) sınıf referansını kullanarak PPTM dosyasını yükleyin
2. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) üye işlevini kullanarak PPTM'u HTML'ye dönüştürün ve Html'yi SaveFormat olarak ayarlayın
3. Dönüştürülen HTML dosyasını [Document](https://reference.aspose.com/words/cpp/class/aspose.words.flatopcument) sınıf referansını kullanarak yükleyin
4. [Kaydet](https://reference.aspose.com/words/cpp/class/aspose.words.flatopcument#save_string) üye işlevini kullanarak belgeyi FLATOPC biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://downloads.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPTM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pptm");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Flatopcument
System::SharedPtr<Flatopcument> flatopc = System::MakeObject<Flatopcument>(u"htmlOutput.html");
// save flatopcument in FLATOPC format
flatopc->Save(u"output.flatopc"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pptm-to-dotm/" name="PPTM İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pptm-to-wordml/" name="PPTM İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pptm-to-rtf/" name="PPTM İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pptm-to-odt/" name="PPTM İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pptm-to-dot/" name="PPTM İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pptm-to-ott/" name="PPTM İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pptm-to-word/" name="PPTM İle WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pptm-to-flatopc/" name="PPTM İle FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pptm-to-text/" name="PPTM İle TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pptm-to-flatopcm/" name="PPTM İle FLATOPCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pptm-to-dotx/" name="PPTM İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pptm-to-flatopcx/" name="PPTM İle FLATOPCX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}