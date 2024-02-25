---
title: C++ API untuk Mengekspor SVG ke DOCM
description: Konversi SVG ke DOCM dalam aplikasi C++.

family: total
platformtag: cpp
feature: conversion
informat: SVG
outformat: DOCM
otherformats: DOTX MARKDOWN FLATOPC WORDML OTT DOTM XAMLFLOW MHTML PS DOT PCL ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API untuk Mengekspor SVG ke DOCM" h2="Render SVG ke DOCM dalam aplikasi C++ tanpa memerlukan aplikasi pihak ketiga" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) pustaka otomatisasi format file memungkinkan pengembang C++ untuk mengonversi SVG ke DOCM dalam dua langkah sederhana. Pertama, Anda dapat menggunakan [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API untuk mengonversi format file SVG ke DOC. Kedua, dengan menggunakan API Pemrosesan Dokumen Word tingkat lanjut [Aspose.Words for C++](https://products.aspose.com/words/cpp/), Anda dapat mengekspor DOC ke DOCM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API untuk Merender SVG ke DOCM" %}}
1. Buka file SVG menggunakan referensi kelas [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Konversi SVG ke DOC dengan menggunakan fungsi anggota [Simpan](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Muat file DOC dengan menggunakan referensi kelas [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) dari Aspose.Words API
4. Simpan dokumen ke format DOCM menggunakan fungsi anggota [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total.Cpp``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total.Cpp```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load SVG file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.svg");
// save SVG as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Docm
wordDoc->Save(u"output.Docm");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ubah Kata Sandi Dokumen SVG melalui C++" %}}
Dalam proses rendering SVG ke DOCM, Anda dapat membuka SVG yang dilindungi kata sandi dan juga mengubah kata sandinya. Untuk mengubah kata sandi file SVG, Anda harus mengetahui kata sandi pemilik dokumen itu. Anda dapat memuat dokumen PDF yang dilindungi kata sandi dengan [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) dengan menentukan kata sandi pemiliknya dan menggunakan metode ChangePasswords untuk mengubah kata sandi.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing SVG Document
auto doc = MakeObject<Document>(L"input.svg", L"owner");
// change password of SVG Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Batasi Pengeditan File DOCM melalui C++" %}}
Anda juga dapat membatasi pengeditan file DOCM menggunakan [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API. Terkadang Anda mungkin perlu membatasi kemampuan untuk mengedit dokumen dan hanya mengizinkan tindakan tertentu dengannya. API memungkinkan Anda mengontrol cara Anda membatasi konten menggunakan parameter enumerasi [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). Contoh kode berikut menunjukkan cara membatasi pengeditan dalam dokumen sehingga hanya pengeditan di bidang formulir yang dimungkinkan.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Docm");  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}