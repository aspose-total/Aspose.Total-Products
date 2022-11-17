---
title: C++ API untuk Mengonversi POTM ke DOC
description: Ekspor POTM ke DOC dalam aplikasi C++ Anda

family: total
platformtag: cpp
feature: conversion
informat: POTM
outformat: DOC
otherformats: DOTX TEXT FLATOPC WORD DOCM WORDML RTF DOCX OTT ODT DOT DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API untuk Merender POTM ke DOC" h2="Ekspor POTM ke DOC dalam aplikasi C++ tanpa ketergantungan Microsoft PowerPoint atau Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) adalah paket lengkap library C++ File Format Automation. Dengan menggunakan fitur kaya dari API yang tersedia di paket, kita dapat dengan mudah mengonversi PowerPoint POTM ke Word DOC. Untuk melakukan konversi, pertama-tama Anda dapat menggunakan [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API untuk mengonversi POTM ke HTML. Setelah itu dengan menggunakan API Pemrosesan Kata yang kaya fitur [Aspose.Words for C++](https://products.aspose.com/words/cpp/) Anda dapat mengonversi HTML ke DOC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API untuk Mengonversi POTM ke DOC" %}}
1. Muat file POTM menggunakan referensi kelas [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Render POTM ke HTML dengan menggunakan fungsi anggota [Simpan](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) dan atur Html sebagai SaveFormat
3. Muat file HTML yang dikonversi dengan menggunakan referensi kelas [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Simpan dokumen ke format DOC dengan menggunakan fungsi anggota [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total.Cpp``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total.Cpp```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POTM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.potm");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"htmlOutput.html");
// save document in DOC format
doc->Save(u"output.doc"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/potm-to-dotx/" name="POTM Ke DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/potm-to-text/" name="POTM Ke TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/potm-to-flatopc/" name="POTM Ke FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/potm-to-word/" name="POTM Ke WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/potm-to-docm/" name="POTM Ke DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/potm-to-wordml/" name="POTM Ke WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/potm-to-rtf/" name="POTM Ke RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/potm-to-docx/" name="POTM Ke DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/potm-to-ott/" name="POTM Ke OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/potm-to-odt/" name="POTM Ke ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/potm-to-dot/" name="POTM Ke DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/potm-to-dotm/" name="POTM Ke DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}