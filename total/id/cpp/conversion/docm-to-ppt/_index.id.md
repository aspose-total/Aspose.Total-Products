---
title: Konversi DOCM ke PPT melalui C++ atau dengan Konverter Online gratis
description: Ekspor DOCM ke PPT di aplikasi C++ Anda tanpa menggunakan Microsoft Word dari PowerPoint atau daring. Uji konverter online POT ke CSV gratis dengan cepat sebelum mengintegrasikan kode.

family: total
platformtag: cpp
feature: conversion
informat: DOCM
outformat: PPT
otherformats: POWERPOINT PPS ODP PPSM POT PPTM PPTX PPSX POTM POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API untuk Mengonversi DOCM ke PPT atau Aplikasi Daring" h2="Ekspor DOCM ke PPT dalam aplikasi C++ Anda tanpa menggunakan Microsoft Word&reg; atau PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) terdiri dari API otomatisasi file canggih yang memungkinkan untuk mengotomatiskan konversi DOCM ke PPT saat menggunakan dua API-nya. Muat DOCM Anda menggunakan [Aspose.Words for C++](https://products.aspose.com/words/cpp/) dan ubah menjadi HTML, lalu muat HTML melalui manipulasi PowerPoint C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) untuk membuat presentasi baru, dan menyimpannya sebagai PPT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversi DOCM ke PPT di C++" %}}
1. Buka file DOCM menggunakan referensi kelas [Document](https://reference.aspose.com/words/cpp/class/aspose.words.docmument)
2. Konversi DOCM ke HTML dengan menggunakan fungsi anggota [Simpan](https://reference.aspose.com/words/cpp/class/aspose.words.docmument#save_stdbasicostream_saveoptions)
3. Inisialisasi objek [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) baru
4. Tambahkan AutoShape di slide Anda, dan tambahkan AddTextFrame di dalamnya
5. Muat konten HTML dan tulis di file Presentasi Anda
6. Simpan dokumen ke format PPT menggunakan metode [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) dan atur Ppt sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total.Cpp``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total.Cpp```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOCM file with an instance of Document
Document docmument = new Document("template.docm");
System::SharedPtr<Document> docm = System::MakeObject<Document>(u"sourceFile.docm");
// save the docmument in HTML file format
docm->Save(u"HtmlOutput.HTML");
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
// save presentation as Ppt
pres->Save(output.ppt, Aspose::Slides::Export::SaveFormat::Ppt);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Konverter Online Gratis untuk DOCM ke PPT</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=ppt&from=docm" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Muat Dokumen DOCM yang Dilindungi Kata Sandi melalui C++" %}}
Selain konversi dokumen, [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API memungkinkan banyak fitur manipulasi dokumen untuk pengembang C++. Jika format file DOCM Microsoft Word Anda dilindungi kata sandi, Anda masih dapat membukanya menggunakan API. Untuk memuat dokumen terenkripsi, Anda dapat menggunakan kelebihan konstruktor khusus, yang menerima objek [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Objek ini berisi properti Kata Sandi, yang menentukan string kata sandi.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected docmument, the password is passed to the docmument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"docmPassword");
// load the docmument from the local file system by filename:
SharedPtr<Document> docm = MakeObject<Document>(u"Encrypted.docm", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Tambahkan Komentar dalam Dokumen PPT melalui C++" %}}
Saat menyimpan DOCM sebagai PPT, Anda juga dapat menggunakan [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) untuk menambahkan fitur lebih lanjut dalam dokumen PPT Anda. Misalnya, Anda dapat menambahkan komentar dalam presentasi Anda. Komentar slide presentasi dikaitkan dengan penulis tertentu. Kelas Presentasi menyimpan koleksi penulis di ICommentAuthorCollection yang bertanggung jawab untuk menambahkan komentar slide. Untuk setiap penulis, ada kumpulan komentar di ICommentCollection.
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
// save presentation as Ppt
pres->Save(output.ppt, Aspose::Slides::Export::SaveFormat::Ppt);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}