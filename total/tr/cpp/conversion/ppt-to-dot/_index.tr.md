---
title: PPT'u DOT'a Dönüştürmek için C++ API
description: C++ uygulamalarınızda PPT'u DOT'a aktarın

family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: DOT
otherformats: DOC ODT RTF DOCM WORDML DOTM DOCX OTT DOTX WORD FLATOPC TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="PPT'u DOT'ye Dönüştürmek için C++ API" h2="Microsoft PowerPoint veya Word bağımlılığı olmadan C++ uygulamalarında PPT'u DOT'a aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/), C++ Dosya Formatı Otomasyonu kitaplıklarının eksiksiz paketidir. Pakette bulunan API'lerin zengin özelliklerini kullanarak PowerPoint PPT'u Word DOT'a kolayca dönüştürebiliriz. Dönüştürmeyi gerçekleştirmek için önce PPT'u HTML'ye dönüştürmek için [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API'sini kullanabilirsiniz. Bundan sonra, zengin özelliklere sahip Kelime İşlem API'sini [Aspose.Words for C++](https://products.aspose.com/words/cpp/) kullanarak HTML'yi DOT'ye dönüştürebilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPT'u DOT'a Dönüştürmek için C++ API" %}}
1. [Sunum](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) sınıf referansını kullanarak PPT dosyasını yükleyin
2. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) üye işlevini kullanarak PPT'u HTML'ye dönüştürün ve Html'yi SaveFormat olarak ayarlayın
3. Dönüştürülen HTML dosyasını [Document](https://reference.aspose.com/words/cpp/class/aspose.words.dotument) sınıf referansını kullanarak yükleyin
4. [Kaydet](https://reference.aspose.com/words/cpp/class/aspose.words.dotument#save_string) üye işlevini kullanarak belgeyi DOT biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://downloads.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPT file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.ppt");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ppt-to-dot/" name="PPT İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ppt-to-odt/" name="PPT İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ppt-to-rtf/" name="PPT İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ppt-to-dotm/" name="PPT İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ppt-to-wordml/" name="PPT İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ppt-to-dotm/" name="PPT İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ppt-to-dotx/" name="PPT İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ppt-to-ott/" name="PPT İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ppt-to-dotx/" name="PPT İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ppt-to-word/" name="PPT İle WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ppt-to-flatopc/" name="PPT İle FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ppt-to-text/" name="PPT İle TEXT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}