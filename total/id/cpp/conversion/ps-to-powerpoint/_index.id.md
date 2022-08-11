---
title: C++ API untuk Mengonversi PS ke POWERPOINT
description: Konversi PS ke POWERPOINT melalui C++ tanpa menggunakan Microsoft Word atau Adobe Acrobat Reader
url: /id/cpp/conversion/ps-to-powerpoint/
family: total
platformtag: cpp
feature: conversion
informat: PS
outformat: PPT
otherformats: ODP XAML PPT OTP SWF POT PPSX PPS PPTM PPSM POTM POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PS ke POWERPOINT dalam Aplikasi C++" h2="Konversi PS ke POWERPOINT dalam Aplikasi C++ Anda tanpa menggunakan Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Apakah Anda seorang pengembang C++ yang ingin menambahkan fitur konversi PS ke POWERPOINT di dalam aplikasi C++ Anda? Anda dapat melakukannya dalam dua langkah sederhana. Anda dapat mengekspor PS ke PPTX dengan menggunakan [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). Kedua, dengan menggunakan [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), Anda dapat mengonversi PPTX ke POWERPOINT. Kedua API berada di bawah paket [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API untuk Mengekspor PS ke POWERPOINT" %}}
1. Buka file PS menggunakan referensi kelas [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Konversi PS ke PPTX dengan menggunakan fungsi metode [Simpan](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)
3. Muat dokumen PPTX dengan menggunakan referensi kelas [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Simpan dokumen ke format POWERPOINT menggunakan fungsi anggota [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) dan setel `Powerpoint` sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total.Cpp``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total.Cpp```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load PS file with an instance of Document class
auto doc = MakeObject<Document>(u"template.ps");
// save PS as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Ppt format
prs->Save(u"output.ppt", Aspose::Slides::Export::SaveFormat::Ppt);  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ubah Kata Sandi Dokumen PS melalui C++" %}}
Dalam proses rendering PS ke POWERPOINT, Anda dapat membuka PS yang dilindungi kata sandi dan juga mengubah kata sandinya. Untuk mengubah kata sandi file PS, Anda harus mengetahui kata sandi pemilik dokumen itu. Anda dapat memuat dokumen PDF yang dilindungi kata sandi dengan [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) dengan menentukan kata sandi pemiliknya dan menggunakan metode ChangePasswords untuk mengubah kata sandi.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing PS Document
auto doc = MakeObject<Document>(L"input.ps", L"owner");
// change password of PS Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Tambahkan Gambar Dari Web dalam File POWERPOINT melalui C++" %}}
Setelah mengonversi PS ke POWERPOINT, Anda juga dapat menambahkan gambar dari web ke dokumen keluaran Anda. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) mendukung operasi dengan gambar dalam format populer berikut: JPEG, PNG, BMP, GIF, dan lainnya. Anda dapat menambahkan satu atau beberapa gambar di komputer Anda ke slide dalam presentasi. Kode contoh di C++ ini menunjukkan cara menambahkan gambar ke file POWERPOINT
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/ps-to-powerpoint/" name="PS Ke POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/ps-to-xaml/" name="PS Ke XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/ps-to-ppt/" name="PS Ke PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/ps-to-otp/" name="PS Ke OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/ps-to-swf/" name="PS Ke SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/ps-to-pot/" name="PS Ke POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/ps-to-ppsx/" name="PS Ke PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/ps-to-pps/" name="PS Ke PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/ps-to-pptm/" name="PS Ke PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/ps-to-ppsm/" name="PS Ke PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/ps-to-potm/" name="PS Ke POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/ps-to-potx/" name="PS Ke POTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}