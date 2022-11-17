---
title: C++ API untuk Mengonversi PPT ke RTF
description: Ekspor PPT ke RTF dalam aplikasi C++ Anda

family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: RTF
otherformats: DOT TEXT WORDML WORD DOCM FLATOPC DOTX DOCX DOTM DOC ODT OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API untuk Merender PPT ke RTF" h2="Ekspor PPT ke RTF dalam aplikasi C++ tanpa ketergantungan Microsoft PowerPoint atau Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) adalah paket lengkap library C++ File Format Automation. Dengan menggunakan fitur kaya dari API yang tersedia di paket, kita dapat dengan mudah mengonversi PowerPoint PPT ke Word RTF. Untuk melakukan konversi, pertama-tama Anda dapat menggunakan [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API untuk mengonversi PPT ke HTML. Setelah itu dengan menggunakan API Pemrosesan Kata yang kaya fitur [Aspose.Words for C++](https://products.aspose.com/words/cpp/) Anda dapat mengonversi HTML ke RTF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API untuk Mengonversi PPT ke RTF" %}}
1. Muat file PPT menggunakan referensi kelas [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Render PPT ke HTML dengan menggunakan fungsi anggota [Simpan](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) dan atur Html sebagai SaveFormat
3. Muat file HTML yang dikonversi dengan menggunakan referensi kelas [Rtfument](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument)
4. Simpan dokumen ke format RTF dengan menggunakan fungsi anggota [Save](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total.Cpp``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total.Cpp```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPT file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.ppt");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Rtfument
System::SharedPtr<Rtfument> rtf = System::MakeObject<Rtfument>(u"htmlOutput.html");
// save rtfument in RTF format
rtf->Save(u"output.rtf"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/ppt-to-dot/" name="PPT Ke DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/ppt-to-text/" name="PPT Ke TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/ppt-to-wordml/" name="PPT Ke WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/ppt-to-word/" name="PPT Ke WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/ppt-to-rtfm/" name="PPT Ke RTFM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/ppt-to-flatopc/" name="PPT Ke FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/ppt-to-dotx/" name="PPT Ke DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/ppt-to-rtfx/" name="PPT Ke RTFX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/ppt-to-dotm/" name="PPT Ke DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/ppt-to-rtf/" name="PPT Ke RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/ppt-to-odt/" name="PPT Ke ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/ppt-to-ott/" name="PPT Ke OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}