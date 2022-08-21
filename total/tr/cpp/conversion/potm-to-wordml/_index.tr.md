---
title: POTM'u WORDML'a Dönüştürmek için C++ API
description: C++ uygulamalarınızda POTM'u WORDML'a aktarın
url: /tr/cpp/conversion/potm-to-wordml/
family: total
platformtag: cpp
feature: conversion
informat: POTM
outformat: WORDML
otherformats: OTT DOT DOCX RTF DOTX TEXT WORD FLATOPC DOC DOTM DOCM ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="POTM'u WORDML'ye Dönüştürmek için C++ API" h2="Microsoft PowerPoint veya Word bağımlılığı olmadan C++ uygulamalarında POTM'u WORDML'a aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/), C++ Dosya Formatı Otomasyonu kitaplıklarının eksiksiz paketidir. Pakette bulunan API'lerin zengin özelliklerini kullanarak PowerPoint POTM'u Word WORDML'a kolayca dönüştürebiliriz. Dönüştürmeyi gerçekleştirmek için önce POTM'u HTML'ye dönüştürmek için [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API'sini kullanabilirsiniz. Bundan sonra, zengin özelliklere sahip Kelime İşlem API'sini [Aspose.Words for C++](https://products.aspose.com/words/cpp/) kullanarak HTML'yi WORDML'ye dönüştürebilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="POTM'u WORDML'a Dönüştürmek için C++ API" %}}
1. [Sunum](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) sınıf referansını kullanarak POTM dosyasını yükleyin
2. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) üye işlevini kullanarak POTM'u HTML'ye dönüştürün ve Html'yi SaveFormat olarak ayarlayın
3. Dönüştürülen HTML dosyasını [Document](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument) sınıf referansını kullanarak yükleyin
4. [Kaydet](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument#save_string) üye işlevini kullanarak belgeyi WORDML biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://downloads.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POTM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.potm");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Wordmlument
System::SharedPtr<Wordmlument> wordml = System::MakeObject<Wordmlument>(u"htmlOutput.html");
// save wordmlument in WORDML format
wordml->Save(u"output.wordml"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/potm-to-ott/" name="POTM İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/potm-to-dot/" name="POTM İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/potm-to-wordmlx/" name="POTM İle WORDMLX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/potm-to-rtf/" name="POTM İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/potm-to-dotx/" name="POTM İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/potm-to-text/" name="POTM İle TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/potm-to-word/" name="POTM İle WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/potm-to-flatopc/" name="POTM İle FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/potm-to-wordml/" name="POTM İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/potm-to-dotm/" name="POTM İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/potm-to-wordmlm/" name="POTM İle WORDMLM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/potm-to-odt/" name="POTM İle ODT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}