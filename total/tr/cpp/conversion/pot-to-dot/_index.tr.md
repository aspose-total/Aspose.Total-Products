---
title: POT'u DOT'a Dönüştürmek için C++ API
description: C++ uygulamalarınızda POT'u DOT'a aktarın

family: total
platformtag: cpp
feature: conversion
informat: POT
outformat: DOT
otherformats: FLATOPC WORD ODT DOC DOCM DOTM TEXT DOCX RTF DOTX OTT WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="POT'u DOT'ye Dönüştürmek için C++ API" h2="Microsoft PowerPoint veya Word bağımlılığı olmadan C++ uygulamalarında POT'u DOT'a aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/), C++ Dosya Formatı Otomasyonu kitaplıklarının eksiksiz paketidir. Pakette bulunan API'lerin zengin özelliklerini kullanarak PowerPoint POT'u Word DOT'a kolayca dönüştürebiliriz. Dönüştürmeyi gerçekleştirmek için önce POT'u HTML'ye dönüştürmek için [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API'sini kullanabilirsiniz. Bundan sonra, zengin özelliklere sahip Kelime İşlem API'sini [Aspose.Words for C++](https://products.aspose.com/words/cpp/) kullanarak HTML'yi DOT'ye dönüştürebilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="POT'u DOT'a Dönüştürmek için C++ API" %}}
1. [Sunum](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) sınıf referansını kullanarak POT dosyasını yükleyin
2. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) üye işlevini kullanarak POT'u HTML'ye dönüştürün ve Html'yi SaveFormat olarak ayarlayın
3. Dönüştürülen HTML dosyasını [Document](https://reference.aspose.com/words/cpp/class/aspose.words.dotument) sınıf referansını kullanarak yükleyin
4. [Kaydet](https://reference.aspose.com/words/cpp/class/aspose.words.dotument#save_string) üye işlevini kullanarak belgeyi DOT biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://downloads.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POT file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pot");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Dotument
System::SharedPtr<Dotument> dot = System::MakeObject<Dotument>(u"htmlOutput.html");
// save dotument in DOT format
dot->Save(u"output.dot"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pot-to-flatopc/" name="POT İle FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pot-to-word/" name="POT İle WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pot-to-odt/" name="POT İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pot-to-dot/" name="POT İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pot-to-dotm/" name="POT İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pot-to-dotm/" name="POT İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pot-to-text/" name="POT İle TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pot-to-dotx/" name="POT İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pot-to-rtf/" name="POT İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pot-to-dotx/" name="POT İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pot-to-ott/" name="POT İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/pot-to-wordml/" name="POT İle WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}