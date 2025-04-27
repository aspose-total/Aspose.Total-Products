---
title: C# API untuk Mengekspor EMAIL ke PNG
description: Konversi EMAIL ke PNG tanpa menggunakan Microsoft Word atau Outlook di .NET
url_ignore: /id/net/conversion/email-to-png/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PNG
otherformats: RTF DOTM DOCM GIF OTT PDF EMF PNG XPS FLATOPC TEXT MD EPUB PCL WORDML DOTX JPEG TIFF SVG DOC PS DOCX DOT ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Ekspor EMAIL ke PNG melalui .NET" h2=".NET API untuk Merender EMAIL ke PNG di Windows, macOS, dan Linux tanpa menggunakan Word atau Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jika Anda adalah pengembang .NET yang ingin menambahkan fitur konversi EMAIL ke PNG di dalam aplikasi Anda, [Aspose.Total for .NET](https://products.aspose.com/total/net/) API manipulasi format file adalah caranya maju. Dengan menggunakan [Aspose.Email for .NET](https://products.aspose.com/email/net/), Anda dapat mengonversi format file EMAIL ke HTML. Setelah itu, dengan menggunakan [Aspose.Words for .NET](https://products.aspose.com/words/net/), Anda dapat merender HTML ke PNG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API untuk Mengonversi EMAIL ke PNG" %}}
1. Buka file EMAIL menggunakan kelas [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Konversi EMAIL ke HTML dengan menggunakan metode [Simpan](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Muat HTML dengan menggunakan kelas [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Simpan dokumen ke format PNG menggunakan metode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) dan atur Png sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parsing File EMAIL melalui .NET" %}}
Sebelum mengonversi EMAIL ke PNG, jika Anda ingin memastikan bahwa Anda mengonversi email yang benar, Anda dapat memuat dokumen EMAIL, menguraikannya dan melihat properti yang Anda inginkan. Dengan menggunakan kelas [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) dari [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, Anda bisa mendapatkan informasi pengirim dan penerima. Misalnya, Anda dapat memeriksa email pengirim tertentu untuk konversi dengan menggunakan properti [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Batasi Pengeditan Dokumen PNG melalui .NET" %}}
Saat menyimpan dokumen dari EMAIL ke PNG, Anda mungkin perlu melindungi dokumen keluaran Anda. Terkadang Anda mungkin perlu membatasi kemampuan untuk mengedit dokumen dan hanya mengizinkan tindakan tertentu dengannya. Ini dapat berguna untuk mencegah orang lain mengedit informasi sensitif dan rahasia dalam dokumen Anda. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, memungkinkan Anda mengontrol cara Anda membatasi konten menggunakan [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parameter enumerasi. Anda dapat mengatur dokumen Anda menjadi baca-saja dengan menggunakan baris kode berikut. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Mengubah File EMAIL ke PNG Secara Terprogram : Contoh Penggunaan" %}}
Konversi File Email ke Gambar PNG diperlukan untuk mengaktifkan potensi penuh konten visual dan analisis Anda. Dengan konversi ini, Anda dapat:

**Aplikasi (Use Cases):**

*   **Merek dan Iklan**: Konversi file email untuk menganalisis pesan branding, melacak kampanye iklan, dan mengidentifikasi pola interaksi pengguna.
*   **Manajemen Hubungan Pelanggan**: Menggunakan gambar PNG untuk visualisasi interaksi pelanggan, memperbaiki strategi komunikasi, dan mengukur tingkat kenyamanan pelanggan.
*   **Monиторing Media Sosial**: Konversi file email untuk membuat ringkasan visual dari percakapan media sosial, mendeteksi trend, dan melakukan analisis sentiment.
*   **Manajemen Aset Digital**: Menggunakan gambar PNG untuk mengorganisasi dan optimesi aset digital seperti logo, grafik, dan ikon untuk penggunaan web.
*   **Desain Grafis dan Ilustrasi**: Konversi file email untuk membuat visual yang menarik, ilustrasi, dan grafik untuk bahan pemasaran, presentasi, dan publikasi.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}