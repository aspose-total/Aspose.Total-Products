---
title: C++ API untuk Mengonversi PPTM ke DOCM
description: Ekspor PPTM ke DOCM dalam aplikasi C++ Anda

family: total
platformtag: cpp
feature: conversion
informat: PPTM
outformat: DOCM
otherformats: TEXT DOCX FLATOPC DOTX ODT RTF DOTM OTT WORD DOC DOT WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API untuk Merender PPTM ke DOCM" h2="Ekspor PPTM ke DOCM dalam aplikasi C++ tanpa ketergantungan Microsoft PowerPoint atau Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) adalah paket lengkap library C++ File Format Automation. Dengan menggunakan fitur kaya dari API yang tersedia di paket, kita dapat dengan mudah mengonversi PowerPoint PPTM ke Word DOCM. Untuk melakukan konversi, pertama-tama Anda dapat menggunakan [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API untuk mengonversi PPTM ke HTML. Setelah itu dengan menggunakan API Pemrosesan Kata yang kaya fitur [Aspose.Words for C++](https://products.aspose.com/words/cpp/) Anda dapat mengonversi HTML ke DOCM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API untuk Mengonversi PPTM ke DOCM" %}}
1. Muat file PPTM menggunakan referensi kelas [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Render PPTM ke HTML dengan menggunakan fungsi anggota [Simpan](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) dan atur Html sebagai SaveFormat
3. Muat file HTML yang dikonversi dengan menggunakan referensi kelas [Document](https://reference.aspose.com/words/cpp/class/aspose.words.docmument)
4. Simpan dokumen ke format DOCM dengan menggunakan fungsi anggota [Save](https://reference.aspose.com/words/cpp/class/aspose.words.docmument#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total.Cpp``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total.Cpp```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPTM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pptm");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Document
System::SharedPtr<Document> docm = System::MakeObject<Document>(u"htmlOutput.html");
// save docmument in DOCM format
docm->Save(u"output.docm"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/pptm-to-text/" name="PPTM Ke TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/pptm-to-docmx/" name="PPTM Ke DOCMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/pptm-to-flatopc/" name="PPTM Ke FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/pptm-to-dotx/" name="PPTM Ke DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/pptm-to-odt/" name="PPTM Ke ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/pptm-to-rtf/" name="PPTM Ke RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/pptm-to-dotm/" name="PPTM Ke DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/pptm-to-ott/" name="PPTM Ke OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/pptm-to-word/" name="PPTM Ke WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/pptm-to-docm/" name="PPTM Ke DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/pptm-to-dot/" name="PPTM Ke DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/pptm-to-wordml/" name="PPTM Ke WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}