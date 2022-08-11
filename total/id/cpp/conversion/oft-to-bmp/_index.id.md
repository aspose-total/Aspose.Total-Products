---
title: Ekspor OFT ke BMP melalui C++
description: C++ API untuk Mengonversi OFT ke BMP tanpa menggunakan Microsoft Word atau Outlook
url: /id/cpp/conversion/oft-to-bmp/
family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: BMP
otherformats: TEXT MD DOC DOCX XPS RTF EMF PCL ODT EPUB JPEG WORDML SVG GIF FLATOPC PDF DOTM OTT TIFF DOTX DOCM DOT PNG PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API untuk Mengekspor OFT ke BMP" h2="Ubah OFT menjadi BMP dalam aplikasi C++ tanpa memerlukan Microsoft Word atau Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Apakah Anda seorang pengembang C++ yang ingin menambahkan fitur konversi oft di dalam aplikasi Anda? Menggunakan [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/) Anda dapat mengonversi format file OFT ke HTML. Setelah itu, dengan menggunakan [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API, Anda dapat mengekspor HTML ke BMP. Kedua API berada di bawah paket [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API untuk Mengonversi OFT ke BMP" %}}
1. Buka file OFT menggunakan referensi kelas [MailMessage](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message)
2. Konversi OFT ke HTML dengan menggunakan fungsi anggota [Simpan](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Muat HTML dengan menggunakan kelas [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Simpan dokumen ke format BMP menggunakan metode [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) dan atur Bmp sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total.Cpp``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total.Cpp```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the OFT file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.oft");
// save OFT as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Bmp as save format
doc->Save(u"convertedFile.Bmp");
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parsing File OFT melalui C++" %}}
Anda tidak hanya dapat mengonversi OFT ke BMP, tetapi Anda juga dapat membaca, memanipulasi, dan mengurai dokumen OFT. Anda bisa mendapatkan informasi subjek, alamat, isi, penerima oft dengan menggunakan kelas MapiMessage dari [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/) API. Misalnya, Anda dapat memeriksa oft pengirim tertentu untuk konversi dengan menggunakan properti get_SenderOftAddress().
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.oft");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderOftAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ API untuk Membatasi Pengeditan Format File BMP" %}}
Anda juga dapat menambahkan fitur perlindungan dokumen di aplikasi Anda saat mengekspor dokumen dari OFT ke BMP. Menambahkan proteksi ke dokumen Anda adalah proses yang sederhana, karena yang perlu Anda lakukan hanyalah menerapkan metode proteksi ke dokumen Anda. Anda dapat mengatur jenis proteksi ke ReadOnly untuk membatasi pengguna mengedit dokumen.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Bmp");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/oft-to-text/" name="OFT Ke TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/oft-to-md/" name="OFT Ke MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/oft-to-doc/" name="OFT Ke DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/oft-to-docx/" name="OFT Ke DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/oft-to-xps/" name="OFT Ke XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/oft-to-rtf/" name="OFT Ke RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/oft-to-emf/" name="OFT Ke EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/oft-to-pcl/" name="OFT Ke PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/oft-to-odt/" name="OFT Ke ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/oft-to-epub/" name="OFT Ke EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/oft-to-jpeg/" name="OFT Ke JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/oft-to-wordml/" name="OFT Ke WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/oft-to-svg/" name="OFT Ke SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/oft-to-gif/" name="OFT Ke GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/oft-to-flatopc/" name="OFT Ke FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/oft-to-pdf/" name="OFT Ke PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/oft-to-dotm/" name="OFT Ke DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/oft-to-ott/" name="OFT Ke OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/oft-to-tiff/" name="OFT Ke TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/oft-to-dotx/" name="OFT Ke DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/oft-to-docm/" name="OFT Ke DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/oft-to-dot/" name="OFT Ke DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/oft-to-png/" name="OFT Ke PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/oft-to-ps/" name="OFT Ke PS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}