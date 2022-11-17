---
title: Ekspor EML ke DOC melalui C++
description: C++ API untuk Mengonversi EML ke DOC tanpa menggunakan Microsoft Word atau Outlook

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: DOC
otherformats: EMF DOTX EPUB DOT DOCX GIF DOTM PS PDF JPEG ODT WORDML RTF MD OTT PCL SVG XPS TEXT BMP PNG FLATOPC DOCM TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API untuk Mengekspor EML ke DOC" h2="Ubah EML menjadi DOC dalam aplikasi C++ tanpa memerlukan Microsoft Word atau Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Apakah Anda seorang pengembang C++ yang ingin menambahkan fitur konversi eml di dalam aplikasi Anda? Menggunakan [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) Anda dapat mengonversi format file EML ke HTML. Setelah itu, dengan menggunakan [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API, Anda dapat mengekspor HTML ke DOC. Kedua API berada di bawah paket [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API untuk Mengonversi EML ke DOC" %}}
1. Buka file EML menggunakan referensi kelas [MailMessage](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message)
2. Konversi EML ke HTML dengan menggunakan fungsi anggota [Simpan](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Muat HTML dengan menggunakan kelas [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Simpan dokumen ke format DOC menggunakan metode [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) dan atur Doc sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total.Cpp``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total.Cpp```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EML file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.eml");
// save EML as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Doc as save format
doc->Save(u"convertedFile.Doc");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parsing File EML melalui C++" %}}
Anda tidak hanya dapat mengonversi EML ke DOC, tetapi Anda juga dapat membaca, memanipulasi, dan mengurai dokumen EML. Anda bisa mendapatkan informasi subjek, alamat, isi, penerima eml dengan menggunakan kelas MapiMessage dari [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) API. Misalnya, Anda dapat memeriksa eml pengirim tertentu untuk konversi dengan menggunakan properti get_SenderEmlAddress().
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.eml");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmlAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ API untuk Membatasi Pengeditan Format File DOC" %}}
Anda juga dapat menambahkan fitur perlindungan dokumen di aplikasi Anda saat mengekspor dokumen dari EML ke DOC. Menambahkan proteksi ke dokumen Anda adalah proses yang sederhana, karena yang perlu Anda lakukan hanyalah menerapkan metode proteksi ke dokumen Anda. Anda dapat mengatur jenis proteksi ke ReadOnly untuk membatasi pengguna mengedit dokumen.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/eml-to-emf/" name="EML Ke EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/eml-to-dotx/" name="EML Ke DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/eml-to-epub/" name="EML Ke EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/eml-to-dot/" name="EML Ke DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/eml-to-docx/" name="EML Ke DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/eml-to-gif/" name="EML Ke GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/eml-to-dotm/" name="EML Ke DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/eml-to-ps/" name="EML Ke PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/eml-to-pdf/" name="EML Ke PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/eml-to-jpeg/" name="EML Ke JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/eml-to-odt/" name="EML Ke ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/eml-to-wordml/" name="EML Ke WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/eml-to-rtf/" name="EML Ke RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/eml-to-md/" name="EML Ke MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/eml-to-ott/" name="EML Ke OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/eml-to-pcl/" name="EML Ke PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/eml-to-svg/" name="EML Ke SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/eml-to-xps/" name="EML Ke XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/eml-to-text/" name="EML Ke TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/eml-to-doc/" name="EML Ke DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/eml-to-png/" name="EML Ke PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/eml-to-flatopc/" name="EML Ke FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/eml-to-docm/" name="EML Ke DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/eml-to-tiff/" name="EML Ke TIFF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}