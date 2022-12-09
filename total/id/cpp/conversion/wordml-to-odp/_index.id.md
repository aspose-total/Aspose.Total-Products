---
title: Konversi WORDML ke ODP melalui C++
description: Ekspor WORDML ke ODP di aplikasi C++ Anda tanpa menggunakan Microsoft Word dari PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: WORDML
outformat: ODP
otherformats: PPT PPTX PPSM POT PPSX POTM POWERPOINT PPTM POTX PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API untuk Mengonversi WORDML ke ODP" h2="Ekspor WORDML ke ODP dalam aplikasi C++ Anda tanpa menggunakan Microsoft Word&reg; atau PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) terdiri dari API otomatisasi file canggih yang memungkinkan untuk mengotomatiskan konversi WORDML ke ODP saat menggunakan dua API-nya. Muat WORDML Anda menggunakan [Aspose.Words for C++](https://products.aspose.com/words/cpp/) dan ubah menjadi HTML, lalu muat HTML melalui manipulasi PowerPoint C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) untuk membuat presentasi baru, dan menyimpannya sebagai ODP. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversi WORDML ke ODP di C++" %}}
1. Buka file WORDML menggunakan referensi kelas [Wordmlument](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument)
2. Konversi WORDML ke HTML dengan menggunakan fungsi anggota [Simpan](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument#save_stdbasicostream_saveoptions)
3. Inisialisasi objek [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) baru
4. Tambahkan AutoShape di slide Anda, dan tambahkan AddTextFrame di dalamnya
5. Muat konten HTML dan tulis di file Presentasi Anda
6. Simpan dokumen ke format ODP menggunakan metode [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) dan atur Odp sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total.Cpp``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total.Cpp```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load WORDML file with an instance of Wordmlument
Wordmlument wordmlument = new Wordmlument("template.wordml");
System::SharedPtr<Wordmlument> wordml = System::MakeObject<Wordmlument>(u"sourceFile.wordml");
// save the wordmlument in HTML file format
wordml->Save(u"HtmlOutput.HTML");
// load the desired the presentation
SharedPtr<Presentation> pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ISlide> sld = pres->get_Slides()->idx_get(0);
// add an AutoShape of Rectangle type
SharedPtr<IAutoShape>  ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10, 10, 700, 500);
// reset default fill color
ashp->get_FillFormat()->set_FillType(FillType::NoFill);
// add TextFrame to the Rectangle
ashp->AddTextFrame(u" ");
// access the text frame
SharedPtr<ITextFrame>  txtFrame = ashp->get_TextFrame();
// get Paragraphs collection
SharedPtr<Aspose::Slides::IParagraphCollection>ParaCollection = txtFrame->get_Paragraphs();
// clear all paragraphs in added text frame
ParaCollection->Clear();
// load the HTML file using stream reader
SharedPtr<System::IO::StreamReader>  tr = MakeObject<System::IO::StreamReader>(HtmlOutput.HTML);
// add text from HTML stream reader in text frame
ParaCollection->AddFromHtml(tr->ReadToEnd());
// save presentation as Odp
pres->Save(output.odp, Aspose::Slides::Export::SaveFormat::Odp);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Muat Dokumen WORDML yang Dilindungi Kata Sandi melalui C++" %}}
Selain konversi dokumen, [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API memungkinkan banyak fitur manipulasi dokumen untuk pengembang C++. Jika format file WORDML Microsoft Word Anda dilindungi kata sandi, Anda masih dapat membukanya menggunakan API. Untuk memuat dokumen terenkripsi, Anda dapat menggunakan kelebihan konstruktor khusus, yang menerima objek [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Objek ini berisi properti Kata Sandi, yang menentukan string kata sandi.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected wordmlument, the password is passed to the wordmlument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"wordmlPassword");
// load the wordmlument from the local file system by filename:
SharedPtr<Wordmlument> wordml = MakeObject<Wordmlument>(u"Encrypted.wordml", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Tambahkan Komentar dalam Dokumen ODP melalui C++" %}}
Saat menyimpan WORDML sebagai ODP, Anda juga dapat menggunakan [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) untuk menambahkan fitur lebih lanjut dalam dokumen ODP Anda. Misalnya, Anda dapat menambahkan komentar dalam presentasi Anda. Komentar slide presentasi dikaitkan dengan penulis tertentu. Kelas Presentasi menyimpan koleksi penulis di ICommentAuthorCollection yang bertanggung jawab untuk menambahkan komentar slide. Untuk setiap penulis, ada kumpulan komentar di ICommentCollection.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate Presentation class
SharedPtr<Presentation>pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ILayoutSlide>layout = pres->get_LayoutSlides()->idx_get(0);
// add empty slide
pres->get_Slides()->AddEmptySlide(layout);
// adding Author
SharedPtr<ICommentAuthor> author = pres->get_CommentAuthors()->AddAuthor(u"John Doe", u"MF");
// set position of comments
System::Drawing::PointF point = System::Drawing::PointF(0.2f, 0.2f);
// add slide comment for an author on slide 1
author->get_Comments()->AddComment(u"Hello John, this is a slide comment", pres->get_Slides()->idx_get(1), point, DateTime::get_Now());
// access ISlide 1
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);
// save presentation as Odp
pres->Save(output.odp, Aspose::Slides::Export::SaveFormat::Odp);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/wordml-to-ppt/" name="WORDML Ke PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/wordml-to-pptx/" name="WORDML Ke PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/wordml-to-ppsm/" name="WORDML Ke PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/wordml-to-pot/" name="WORDML Ke POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/wordml-to-ppsx/" name="WORDML Ke PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/wordml-to-potm/" name="WORDML Ke POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/wordml-to-powerpoint/" name="WORDML Ke POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/wordml-to-pptm/" name="WORDML Ke PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/wordml-to-potx/" name="WORDML Ke POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/wordml-to-pps/" name="WORDML Ke PPS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}