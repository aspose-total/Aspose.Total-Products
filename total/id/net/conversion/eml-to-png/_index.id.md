---
title: C# API untuk Mengekspor EML ke PNG
description: Konversi EML ke PNG tanpa menggunakan Microsoft Word atau Outlook di .NET
url_ignore: /id/net/conversion/eml-to-png/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: PNG
otherformats: EPUB TIFF MD EMF ODT PDF DOTX JPEG PCL DOCX FLATOPC PS DOT DOCM TEXT WORDML OTT RTF GIF SVG XPS DOC DOTM PNG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Ekspor EML ke PNG melalui .NET" h2=".NET API untuk Merender EML ke PNG di Windows, macOS, dan Linux tanpa menggunakan Word atau Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jika Anda adalah pengembang .NET yang ingin menambahkan fitur konversi EML ke PNG di dalam aplikasi Anda, [Aspose.Total for .NET](https://products.aspose.com/total/net/) API manipulasi format file adalah caranya maju. Dengan menggunakan [Aspose.Email for .NET](https://products.aspose.com/email/net/), Anda dapat mengonversi format file EML ke HTML. Setelah itu, dengan menggunakan [Aspose.Words for .NET](https://products.aspose.com/words/net/), Anda dapat merender HTML ke PNG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API untuk Mengonversi EML ke PNG" %}}
1. Buka file EML menggunakan kelas [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Konversi EML ke HTML dengan menggunakan metode [Simpan](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
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

{{% blocks/products/pf/feature-page-section  h2="Parsing File EML melalui .NET" %}}
Sebelum mengonversi EML ke PNG, jika Anda ingin memastikan bahwa Anda mengonversi eml yang benar, Anda dapat memuat dokumen EML, menguraikannya dan melihat properti yang Anda inginkan. Dengan menggunakan kelas [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) dari [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, Anda bisa mendapatkan informasi pengirim dan penerima. Misalnya, Anda dapat memeriksa eml pengirim tertentu untuk konversi dengan menggunakan properti [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Batasi Pengeditan Dokumen PNG melalui .NET" %}}
Saat menyimpan dokumen dari EML ke PNG, Anda mungkin perlu melindungi dokumen keluaran Anda. Terkadang Anda mungkin perlu membatasi kemampuan untuk mengedit dokumen dan hanya mengizinkan tindakan tertentu dengannya. Ini dapat berguna untuk mencegah orang lain mengedit informasi sensitif dan rahasia dalam dokumen Anda. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, memungkinkan Anda mengontrol cara Anda membatasi konten menggunakan [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parameter enumerasi. Anda dapat mengatur dokumen Anda menjadi baca-saja dengan menggunakan baris kode berikut. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Mengubah File EML ke PNG Secara Terprogram : Contoh Penggunaan" %}}
Berkas EML (Electronic Mail) digunakan untuk menyimpan informasi surel berbasis teks, sehingga mereka menjadi idealku untuk mengirim dan menerima pesan. Namun, ketika bekerja dengan konten visual, gambar seperti PNG menjadi esensial untuk menampilkan grafik dan ilustrasi.

Konversi berkas EML ke format PNG diperlukan untuk mengaktifkan kemampuan menampilkan konten visual Anda secara penuh. Berikut adalah manfaat yang bisa Anda nikmati:

- **Sosial Media Graphics**: Menggunakan berkas EML untuk membuat grafik sosial media yang menarik secara visual, iklan, dan bahan promosi.
- **Kampanye Pemasaran Elektronik**: Manfaatkan PNG untuk mengvisualisasikan kampanye pemasaran eletronik, mengoptimalisasi desain, dan mengukur indikator ketercapaian.
- **Grafik Web**: Mengubah berkas EML menjadi grafik interaktif web untuk menciptakan pengalaman pengguna yang meningkatkan dan memvalidasi konsep desain.
- **Ilustrasi Blog**: Manfaatkan PNG untuk mengvisualisasikan ilustrasi di blog, membuat konten yang lebih menarik bagi pembaca.
- **Bahan Presentasi**: Mengubah berkas EML menjadi bahan presentasi profesional untuk menampilkan visualisasi data, grafik, dan diagram dengan lebih baik.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}