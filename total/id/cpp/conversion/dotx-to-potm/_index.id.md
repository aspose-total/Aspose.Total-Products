---
title: Konversi DOTX ke POTM melalui C++
description: Ekspor DOTX ke POTM di aplikasi C++ Anda tanpa menggunakan Microsoft Word dari PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: DOTX
outformat: POTM
otherformats: POTX POWERPOINT PPT PPTM PPSM ODP POT PPS PPSX PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API untuk Mengonversi DOTX ke POTM" h2="Ekspor DOTX ke POTM dalam aplikasi C++ Anda tanpa menggunakan Microsoft Word&reg; atau PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) terdiri dari API otomatisasi file canggih yang memungkinkan untuk mengotomatiskan konversi DOTX ke POTM saat menggunakan dua API-nya. Muat DOTX Anda menggunakan [Aspose.Words for C++](https://products.aspose.com/words/cpp/) dan ubah menjadi HTML, lalu muat HTML melalui manipulasi PowerPoint C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) untuk membuat presentasi baru, dan menyimpannya sebagai POTM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversi DOTX ke POTM di C++" %}}
1. Buka file DOTX menggunakan referensi kelas [Dotxument](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument)
2. Konversi DOTX ke HTML dengan menggunakan fungsi anggota [Simpan](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument#save_stdbasicostream_saveoptions)
3. Inisialisasi objek [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) baru
4. Tambahkan AutoShape di slide Anda, dan tambahkan AddTextFrame di dalamnya
5. Muat konten HTML dan tulis di file Presentasi Anda
6. Simpan dokumen ke format POTM menggunakan metode [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) dan atur Potm sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total.Cpp``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total.Cpp```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOTX file with an instance of Dotxument
Dotxument dotxument = new Dotxument("template.dotx");
System::SharedPtr<Dotxument> dotx = System::MakeObject<Dotxument>(u"sourceFile.dotx");
// save the dotxument in HTML file format
dotx->Save(u"HtmlOutput.HTML");
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
// save presentation as Potm
pres->Save(output.potm, Aspose::Slides::Export::SaveFormat::Potm);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Muat Dokumen DOTX yang Dilindungi Kata Sandi melalui C++" %}}
Selain konversi dokumen, [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API memungkinkan banyak fitur manipulasi dokumen untuk pengembang C++. Jika format file DOTX Microsoft Word Anda dilindungi kata sandi, Anda masih dapat membukanya menggunakan API. Untuk memuat dokumen terenkripsi, Anda dapat menggunakan kelebihan konstruktor khusus, yang menerima objek [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Objek ini berisi properti Kata Sandi, yang menentukan string kata sandi.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected dotxument, the password is passed to the dotxument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"dotxPassword");
// load the dotxument from the local file system by filename:
SharedPtr<Dotxument> dotx = MakeObject<Dotxument>(u"Encrypted.dotx", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Tambahkan Komentar dalam Dokumen POTM melalui C++" %}}
Saat menyimpan DOTX sebagai POTM, Anda juga dapat menggunakan [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) untuk menambahkan fitur lebih lanjut dalam dokumen POTM Anda. Misalnya, Anda dapat menambahkan komentar dalam presentasi Anda. Komentar slide presentasi dikaitkan dengan penulis tertentu. Kelas Presentasi menyimpan koleksi penulis di ICommentAuthorCollection yang bertanggung jawab untuk menambahkan komentar slide. Untuk setiap penulis, ada kumpulan komentar di ICommentCollection.
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
// save presentation as Potm
pres->Save(output.potm, Aspose::Slides::Export::SaveFormat::Potm);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/dotx-to-potx/" name="DOTX Ke POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/dotx-to-powerpoint/" name="DOTX Ke POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/dotx-to-ppt/" name="DOTX Ke PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/dotx-to-pptm/" name="DOTX Ke PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/dotx-to-ppsm/" name="DOTX Ke PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/dotx-to-potm/" name="DOTX Ke POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/dotx-to-pot/" name="DOTX Ke POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/dotx-to-pps/" name="DOTX Ke PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/dotx-to-ppsx/" name="DOTX Ke PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/dotx-to-pptx/" name="DOTX Ke PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}