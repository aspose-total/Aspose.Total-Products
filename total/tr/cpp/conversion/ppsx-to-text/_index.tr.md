---
title: PPSX'u TEXT'a Dönüştürmek için C++ API
description: C++ uygulamalarınızda PPSX'u TEXT'a aktarın

family: total
platformtag: cpp
feature: conversion
informat: PPSX
outformat: TEXT
otherformats: FLATOPC RTF WORDML DOCX DOTX DOTM DOC WORD DOCM OTT ODT DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="PPSX'u TEXT'ye Dönüştürmek için C++ API" h2="Microsoft PowerPoint veya Word bağımlılığı olmadan C++ uygulamalarında PPSX'u TEXT'a aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/), C++ Dosya Formatı Otomasyonu kitaplıklarının eksiksiz paketidir. Pakette bulunan API'lerin zengin özelliklerini kullanarak PowerPoint PPSX'u Word TEXT'a kolayca dönüştürebiliriz. Dönüştürmeyi gerçekleştirmek için önce PPSX'u HTML'ye dönüştürmek için [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API'sini kullanabilirsiniz. Bundan sonra, zengin özelliklere sahip Kelime İşlem API'sini [Aspose.Words for C++](https://products.aspose.com/words/cpp/) kullanarak HTML'yi TEXT'ye dönüştürebilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPSX'u TEXT'a Dönüştürmek için C++ API" %}}
1. [Sunum](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) sınıf referansını kullanarak PPSX dosyasını yükleyin
2. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) üye işlevini kullanarak PPSX'u HTML'ye dönüştürün ve Html'yi SaveFormat olarak ayarlayın
3. Dönüştürülen HTML dosyasını [Document](https://reference.aspose.com/words/cpp/class/aspose.words.textument) sınıf referansını kullanarak yükleyin
4. [Kaydet](https://reference.aspose.com/words/cpp/class/aspose.words.textument#save_string) üye işlevini kullanarak belgeyi TEXT biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://downloads.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPSX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.ppsx");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Textument
System::SharedPtr<Textument> text = System::MakeObject<Textument>(u"htmlOutput.html");
// save textument in TEXT format
text->Save(u"output.text"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ppsx-to-flatopc/" name="PPSX İle FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ppsx-to-rtf/" name="PPSX İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ppsx-to-wordml/" name="PPSX İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ppsx-to-textx/" name="PPSX İle TEXTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ppsx-to-dotx/" name="PPSX İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ppsx-to-dotm/" name="PPSX İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ppsx-to-text/" name="PPSX İle TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ppsx-to-word/" name="PPSX İle WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ppsx-to-textm/" name="PPSX İle TEXTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ppsx-to-ott/" name="PPSX İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ppsx-to-odt/" name="PPSX İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ppsx-to-dot/" name="PPSX İle DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}