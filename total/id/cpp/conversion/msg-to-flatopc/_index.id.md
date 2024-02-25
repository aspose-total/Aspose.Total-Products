---
title: Ekspor MSG ke FLATOPC melalui C++
description: C++ API untuk Mengonversi MSG ke FLATOPC tanpa menggunakan Microsoft Word atau Outlook

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: FLATOPC
otherformats: DOTX TIFF XPS JPEG OTT EMF TEXT DOC SVG GIF EPUB PDF ODT DOCX DOTM PNG PCL RTF BMP DOT PS MD DOCM WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API untuk Mengekspor MSG ke FLATOPC" h2="Ubah MSG menjadi FLATOPC dalam aplikasi C++ tanpa memerlukan Microsoft Word atau Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Apakah Anda seorang pengembang C++ yang ingin menambahkan fitur konversi msg di dalam aplikasi Anda? Menggunakan [Aspose.Msg for C++](https://products.aspose.com/msg/cpp/) Anda dapat mengonversi format file MSG ke HTML. Setelah itu, dengan menggunakan [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API, Anda dapat mengekspor HTML ke FLATOPC. Kedua API berada di bawah paket [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API untuk Mengonversi MSG ke FLATOPC" %}}
1. Buka file MSG menggunakan referensi kelas [MailMessage](https://reference.aspose.com/msg/cpp/class/aspose.msg.mail_message)
2. Konversi MSG ke HTML dengan menggunakan fungsi anggota [Simpan](https://reference.aspose.com/msg/cpp/class/aspose.msg.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Muat HTML dengan menggunakan kelas [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Simpan dokumen ke format FLATOPC menggunakan metode [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) dan atur Flatopc sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total.Cpp``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total.Cpp```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the MSG file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.msg");
// save MSG as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing FlatOpc as save format
doc->Save(u"convertedFile.FlatOpc");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parsing File MSG melalui C++" %}}
Anda tidak hanya dapat mengonversi MSG ke FLATOPC, tetapi Anda juga dapat membaca, memanipulasi, dan mengurai dokumen MSG. Anda bisa mendapatkan informasi subjek, alamat, isi, penerima msg dengan menggunakan kelas MapiMessage dari [Aspose.Msg for C++](https://products.aspose.com/msg/cpp/) API. Misalnya, Anda dapat memeriksa msg pengirim tertentu untuk konversi dengan menggunakan properti get_SenderMsgAddress().
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.msg");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderMsgAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ API untuk Membatasi Pengeditan Format File FLATOPC" %}}
Anda juga dapat menambahkan fitur perlindungan dokumen di aplikasi Anda saat mengekspor dokumen dari MSG ke FLATOPC. Menambahkan proteksi ke dokumen Anda adalah proses yang sederhana, karena yang perlu Anda lakukan hanyalah menerapkan metode proteksi ke dokumen Anda. Anda dapat mengatur jenis proteksi ke ReadOnly untuk membatasi pengguna mengedit dokumen.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.FlatOpc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}