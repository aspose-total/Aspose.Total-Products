---
title: C# API untuk Mengekspor EMAIL ke RTF
description: Konversi EMAIL ke RTF tanpa menggunakan Microsoft Word atau Outlook di .NET
url_ignore: /id/net/conversion/email-to-rtf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: RTF
otherformats: PS TIFF EPUB SVG WORDML OTT PNG JPEG XPS GIF MD EMF ODT TEXT DOTX PCL FLATOPC DOTM DOCM DOCX RTF DOT DOC PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Ekspor EMAIL ke RTF melalui .NET" h2=".NET API untuk Merender EMAIL ke RTF di Windows, macOS, dan Linux tanpa menggunakan Word atau Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jika Anda adalah pengembang .NET yang ingin menambahkan fitur konversi EMAIL ke RTF di dalam aplikasi Anda, [Aspose.Total for .NET](https://products.aspose.com/total/net/) API manipulasi format file adalah caranya maju. Dengan menggunakan [Aspose.Email for .NET](https://products.aspose.com/email/net/), Anda dapat mengonversi format file EMAIL ke HTML. Setelah itu, dengan menggunakan [Aspose.Words for .NET](https://products.aspose.com/words/net/), Anda dapat merender HTML ke RTF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API untuk Mengonversi EMAIL ke RTF" %}}
1. Buka file EMAIL menggunakan kelas [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Konversi EMAIL ke HTML dengan menggunakan metode [Simpan](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Muat HTML dengan menggunakan kelas [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Simpan dokumen ke format RTF menggunakan metode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) dan atur Rtf sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parsing File EMAIL melalui .NET" %}}
Sebelum mengonversi EMAIL ke RTF, jika Anda ingin memastikan bahwa Anda mengonversi email yang benar, Anda dapat memuat dokumen EMAIL, menguraikannya dan melihat properti yang Anda inginkan. Dengan menggunakan kelas [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) dari [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, Anda bisa mendapatkan informasi pengirim dan penerima. Misalnya, Anda dapat memeriksa email pengirim tertentu untuk konversi dengan menggunakan properti [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Batasi Pengeditan Dokumen RTF melalui .NET" %}}
Saat menyimpan dokumen dari EMAIL ke RTF, Anda mungkin perlu melindungi dokumen keluaran Anda. Terkadang Anda mungkin perlu membatasi kemampuan untuk mengedit dokumen dan hanya mengizinkan tindakan tertentu dengannya. Ini dapat berguna untuk mencegah orang lain mengedit informasi sensitif dan rahasia dalam dokumen Anda. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, memungkinkan Anda mengontrol cara Anda membatasi konten menggunakan [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parameter enumerasi. Anda dapat mengatur dokumen Anda menjadi baca-saja dengan menggunakan baris kode berikut. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.rtf", SaveFormat.Rtf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Mengubah File EMAIL ke RTF Secara Terprogram : Contoh Penggunaan" %}}
**Konversi File Email ke Format Rich Text Format (RTF)**

File email digunakan untuk menyimpan konten teks berbasis teks, sehingga cocok untuk membuat pesan sederhana dan komunikasi. Namun, ketika datang pada format dan tata letak, file RTF menjadi esensial untuk mencapai tampilan yang profesional.

Konversi file email ke format RTF diperlukan untuk mengaktifkan potensi penuh dokumen Anda dalam hal tampilan visual dan kemampuan presentasi. Konversi ini memungkinkan Anda:

**Aplikasi:**

*   **Korespondensi Profesional**: Ubah file email menjadi surat, memo, atau komunikasi formal dengan tampilan yang menarik.
*   **Bisnis Report Writing**: Gunakan RTF untuk mengatur laporan, usulan, dan presentasi untuk klien, stakeholders, atau manajemen.
*   **Bahan Pemasaran**: Ubah file email menjadi suren newsletter, brosur, dan bahan pemasaran yang menarik.
*   **Karya Ilmiah**: Gunakan RTF untuk mengatur kertas penelitian, tesis, dan disertasi dengan tata letak yang tepat.
*   **Dokumentasi Teknis**: Ubah file email menjadi manual pengguna, panduan instruksi, dan dokumentasi teknis untuk produk atau software.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}