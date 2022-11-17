---
title: C++ API untuk Mengekspor MD ke DOTM
description: Konversi MD ke DOTM dalam aplikasi C++.

family: total
platformtag: cpp
feature: conversion
informat: MD
outformat: DOTM
otherformats: DOTX PS PCL DOCM FLATOPC WORDML RTF DOT XAMLFLOW MHTML OTT ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API untuk Mengekspor MD ke DOTM" h2="Render MD ke DOTM dalam aplikasi C++ tanpa memerlukan aplikasi pihak ketiga" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) pustaka otomatisasi format file memungkinkan pengembang C++ untuk mengonversi MD ke DOTM dalam dua langkah sederhana. Pertama, Anda dapat menggunakan [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API untuk mengonversi format file MD ke DOC. Kedua, dengan menggunakan API Pemrosesan Dokumen Word tingkat lanjut [Aspose.Words for C++](https://products.aspose.com/words/cpp/), Anda dapat mengekspor DOC ke DOTM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API untuk Merender MD ke DOTM" %}}
1. Buka file MD menggunakan referensi kelas [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Konversi MD ke DOC dengan menggunakan fungsi anggota [Simpan](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Muat file DOC dengan menggunakan referensi kelas [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) dari Aspose.Words API
4. Simpan dokumen ke format DOTM menggunakan fungsi anggota [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total.Cpp``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total.Cpp```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load MD file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.md");
// save MD as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Dotm
wordDoc->Save(u"output.Dotm");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ubah Kata Sandi Dokumen MD melalui C++" %}}
Dalam proses rendering MD ke DOTM, Anda dapat membuka MD yang dilindungi kata sandi dan juga mengubah kata sandinya. Untuk mengubah kata sandi file MD, Anda harus mengetahui kata sandi pemilik dokumen itu. Anda dapat memuat dokumen PDF yang dilindungi kata sandi dengan [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) dengan menentukan kata sandi pemiliknya dan menggunakan metode ChangePasswords untuk mengubah kata sandi.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing MD Document
auto doc = MakeObject<Document>(L"input.md", L"owner");
// change password of MD Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Batasi Pengeditan File DOTM melalui C++" %}}
Anda juga dapat membatasi pengeditan file DOTM menggunakan [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API. Terkadang Anda mungkin perlu membatasi kemampuan untuk mengedit dokumen dan hanya mengizinkan tindakan tertentu dengannya. API memungkinkan Anda mengontrol cara Anda membatasi konten menggunakan parameter enumerasi [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). Contoh kode berikut menunjukkan cara membatasi pengeditan dalam dokumen sehingga hanya pengeditan di bidang formulir yang dimungkinkan.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Dotm");  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/md-to-dotx/" name="MD Ke DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/md-to-ps/" name="MD Ke PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/md-to-pcl/" name="MD Ke PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/md-to-dotm/" name="MD Ke DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/md-to-flatopc/" name="MD Ke FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/md-to-wordml/" name="MD Ke WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/md-to-rtf/" name="MD Ke RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/md-to-dot/" name="MD Ke DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/md-to-xamlflow/" name="MD Ke XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/md-to-mhtml/" name="MD Ke MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/md-to-ott/" name="MD Ke OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/md-to-odt/" name="MD Ke ODT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}