---
title: C++ API untuk Mengonversi EPUB ke POWERPOINT
description: Konversi EPUB ke POWERPOINT melalui C++ tanpa menggunakan Microsoft Word atau Adobe Acrobat Reader

family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: PPT
otherformats: POTX POTM SWF PPS PPSM POT XAML ODP PPSX PPTM PPT OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render EPUB ke POWERPOINT dalam Aplikasi C++" h2="Konversi EPUB ke POWERPOINT dalam Aplikasi C++ Anda tanpa menggunakan Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Apakah Anda seorang pengembang C++ yang ingin menambahkan fitur konversi EPUB ke POWERPOINT di dalam aplikasi C++ Anda? Anda dapat melakukannya dalam dua langkah sederhana. Anda dapat mengekspor EPUB ke PPTX dengan menggunakan [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). Kedua, dengan menggunakan [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), Anda dapat mengonversi PPTX ke POWERPOINT. Kedua API berada di bawah paket [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API untuk Mengekspor EPUB ke POWERPOINT" %}}
1. Buka file EPUB menggunakan referensi kelas [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Konversi EPUB ke PPTX dengan menggunakan fungsi metode [Simpan](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)
3. Muat dokumen PPTX dengan menggunakan referensi kelas [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Simpan dokumen ke format POWERPOINT menggunakan fungsi anggota [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) dan setel `Powerpoint` sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total.Cpp``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total.Cpp```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load EPUB file with an instance of Document class
auto doc = MakeObject<Document>(u"template.epub");
// save EPUB as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Ppt format
prs->Save(u"output.ppt", Aspose::Slides::Export::SaveFormat::Ppt);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ubah Kata Sandi Dokumen EPUB melalui C++" %}}
Dalam proses rendering EPUB ke POWERPOINT, Anda dapat membuka EPUB yang dilindungi kata sandi dan juga mengubah kata sandinya. Untuk mengubah kata sandi file EPUB, Anda harus mengetahui kata sandi pemilik dokumen itu. Anda dapat memuat dokumen PDF yang dilindungi kata sandi dengan [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) dengan menentukan kata sandi pemiliknya dan menggunakan metode ChangePasswords untuk mengubah kata sandi.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing EPUB Document
auto doc = MakeObject<Document>(L"input.epub", L"owner");
// change password of EPUB Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Tambahkan Gambar Dari Web dalam File POWERPOINT melalui C++" %}}
Setelah mengonversi EPUB ke POWERPOINT, Anda juga dapat menambahkan gambar dari web ke dokumen keluaran Anda. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) mendukung operasi dengan gambar dalam format populer berikut: JPEG, PNG, BMP, GIF, dan lainnya. Anda dapat menambahkan satu atau beberapa gambar di komputer Anda ke slide dalam presentasi. Kode contoh di C++ ini menunjukkan cara menambahkan gambar ke file POWERPOINT
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a POWERPOINT file
auto pres = System::MakeObject<Presentation>("output.powerpoint");
// get slide
auto slide = pres->get_Slides()->idx_get(0);
// initialize Web Client    
auto webClient = System::MakeObject<WebClient>();
// get image data
auto imageData = webClient->DownloadData(System::MakeObject<Uri>(u"[REPLACE WITH URL]"));
// add image
auto image = pres->get_Images()->AddImage(imageData);
// add picture frame
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
// save updated file
pres->Save(u"updated.powerpoint", SaveFormat::Ppt);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/epub-to-potx/" name="EPUB Ke POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/epub-to-potm/" name="EPUB Ke POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/epub-to-swf/" name="EPUB Ke SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/epub-to-pps/" name="EPUB Ke PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/epub-to-ppsm/" name="EPUB Ke PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/epub-to-pot/" name="EPUB Ke POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/epub-to-xaml/" name="EPUB Ke XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/epub-to-powerpoint/" name="EPUB Ke POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/epub-to-ppsx/" name="EPUB Ke PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/epub-to-pptm/" name="EPUB Ke PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/epub-to-ppt/" name="EPUB Ke PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/epub-to-otp/" name="EPUB Ke OTP" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}