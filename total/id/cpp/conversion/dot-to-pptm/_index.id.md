---
title: Konversi DOT ke PPTM melalui C++
description: Ekspor DOT ke PPTM di aplikasi C++ Anda tanpa menggunakan Microsoft Word dari PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: DOT
outformat: PPTM
otherformats: POTM ODP PPSM PPTX POWERPOINT PPSX PPT PPS POT POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API untuk Mengonversi DOT ke PPTM" h2="Ekspor DOT ke PPTM dalam aplikasi C++ Anda tanpa menggunakan Microsoft Word&reg; atau PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) terdiri dari API otomatisasi file canggih yang memungkinkan untuk mengotomatiskan konversi DOT ke PPTM saat menggunakan dua API-nya. Muat DOT Anda menggunakan [Aspose.Words for C++](https://products.aspose.com/words/cpp/) dan ubah menjadi HTML, lalu muat HTML melalui manipulasi PowerPoint C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) untuk membuat presentasi baru, dan menyimpannya sebagai PPTM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversi DOT ke PPTM di C++" %}}
1. Buka file DOT menggunakan referensi kelas [Dotument](https://reference.aspose.com/words/cpp/class/aspose.words.dotument)
2. Konversi DOT ke HTML dengan menggunakan fungsi anggota [Simpan](https://reference.aspose.com/words/cpp/class/aspose.words.dotument#save_stdbasicostream_saveoptions)
3. Inisialisasi objek [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) baru
4. Tambahkan AutoShape di slide Anda, dan tambahkan AddTextFrame di dalamnya
5. Muat konten HTML dan tulis di file Presentasi Anda
6. Simpan dokumen ke format PPTM menggunakan metode [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) dan atur Pptm sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total.Cpp``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total.Cpp```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOT file with an instance of Dotument
Dotument dotument = new Dotument("template.dot");
System::SharedPtr<Dotument> dot = System::MakeObject<Dotument>(u"sourceFile.dot");
// save the dotument in HTML file format
dot->Save(u"HtmlOutput.HTML");
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
// save presentation as Pptm
pres->Save(output.pptm, Aspose::Slides::Export::SaveFormat::Pptm);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Muat Dokumen DOT yang Dilindungi Kata Sandi melalui C++" %}}
Selain konversi dokumen, [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API memungkinkan banyak fitur manipulasi dokumen untuk pengembang C++. Jika format file DOT Microsoft Word Anda dilindungi kata sandi, Anda masih dapat membukanya menggunakan API. Untuk memuat dokumen terenkripsi, Anda dapat menggunakan kelebihan konstruktor khusus, yang menerima objek [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Objek ini berisi properti Kata Sandi, yang menentukan string kata sandi.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected dotument, the password is passed to the dotument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"dotPassword");
// load the dotument from the local file system by filename:
SharedPtr<Dotument> dot = MakeObject<Dotument>(u"Encrypted.dot", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Tambahkan Komentar dalam Dokumen PPTM melalui C++" %}}
Saat menyimpan DOT sebagai PPTM, Anda juga dapat menggunakan [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) untuk menambahkan fitur lebih lanjut dalam dokumen PPTM Anda. Misalnya, Anda dapat menambahkan komentar dalam presentasi Anda. Komentar slide presentasi dikaitkan dengan penulis tertentu. Kelas Presentasi menyimpan koleksi penulis di ICommentAuthorCollection yang bertanggung jawab untuk menambahkan komentar slide. Untuk setiap penulis, ada kumpulan komentar di ICommentCollection.
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
// save presentation as Pptm
pres->Save(output.pptm, Aspose::Slides::Export::SaveFormat::Pptm);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/dot-to-potm/" name="DOT Ke POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/dot-to-pptm/" name="DOT Ke PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/dot-to-ppsm/" name="DOT Ke PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/dot-to-pptx/" name="DOT Ke PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/dot-to-powerpoint/" name="DOT Ke POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/dot-to-ppsx/" name="DOT Ke PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/dot-to-ppt/" name="DOT Ke PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/dot-to-pps/" name="DOT Ke PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/dot-to-pot/" name="DOT Ke POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/dot-to-potx/" name="DOT Ke POTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}