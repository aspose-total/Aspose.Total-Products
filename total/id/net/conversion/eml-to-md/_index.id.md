---
title: C# API untuk Mengekspor EML ke MD
description: Konversi EML ke MD tanpa menggunakan Microsoft Word atau Outlook di .NET
url_ignore: /id/net/conversion/eml-to-md/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: MD
otherformats: MD RTF FLATOPC PS ODT DOCM DOTX EMF GIF XPS WORDML OTT DOCX TIFF PNG SVG TEXT JPEG EPUB DOC PCL DOT PDF DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Ekspor EML ke MD melalui .NET" h2=".NET API untuk Merender EML ke MD di Windows, macOS, dan Linux tanpa menggunakan Word atau Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jika Anda adalah pengembang .NET yang ingin menambahkan fitur konversi EML ke MD di dalam aplikasi Anda, [Aspose.Total for .NET](https://products.aspose.com/total/net/) API manipulasi format file adalah caranya maju. Dengan menggunakan [Aspose.Email for .NET](https://products.aspose.com/email/net/), Anda dapat mengonversi format file EML ke HTML. Setelah itu, dengan menggunakan [Aspose.Words for .NET](https://products.aspose.com/words/net/), Anda dapat merender HTML ke MD.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API untuk Mengonversi EML ke MD" %}}
1. Buka file EML menggunakan kelas [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Konversi EML ke HTML dengan menggunakan metode [Simpan](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Muat HTML dengan menggunakan kelas [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Simpan dokumen ke format MD menggunakan metode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) dan atur Md sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.eml");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.md", SaveFormat.Md); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parsing File EML melalui .NET" %}}
Sebelum mengonversi EML ke MD, jika Anda ingin memastikan bahwa Anda mengonversi eml yang benar, Anda dapat memuat dokumen EML, menguraikannya dan melihat properti yang Anda inginkan. Dengan menggunakan kelas [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) dari [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, Anda bisa mendapatkan informasi pengirim dan penerima. Misalnya, Anda dapat memeriksa eml pengirim tertentu untuk konversi dengan menggunakan properti [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EML file from disk
var outlookMessageFile = MapiMessage.FromFile("message.eml");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Batasi Pengeditan Dokumen MD melalui .NET" %}}
Saat menyimpan dokumen dari EML ke MD, Anda mungkin perlu melindungi dokumen keluaran Anda. Terkadang Anda mungkin perlu membatasi kemampuan untuk mengedit dokumen dan hanya mengizinkan tindakan tertentu dengannya. Ini dapat berguna untuk mencegah orang lain mengedit informasi sensitif dan rahasia dalam dokumen Anda. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, memungkinkan Anda mengontrol cara Anda membatasi konten menggunakan [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parameter enumerasi. Anda dapat mengatur dokumen Anda menjadi baca-saja dengan menggunakan baris kode berikut. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.md", SaveFormat.Md);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Mengubah File EML ke MD Secara Terprogram : Contoh Penggunaan" %}}
Berkas EML (Electronic Mail) digunakan untuk menyimpan informasi berbasis teks, sehingga menjadi ideal untuk membuat suren email sederhana dan komunikasi. Namun, ketika bekerja dengan data yang rumit dan visualisasi, format Markdown (MD) menjadi esensial untuk dokumentasi dan presentasi.

Konversi berkas EML ke format Markdown diperlukan untuk memungkinkan penggunaan maksimal kemampuan dokumenasi dan presentasi Anda. Konversi ini memungkinkan Anda untuk:

**Apa yang bisa dilakukan dengan konversi ini:**

*   **Dokumentasi Email**: Mengkonversi berkas EML untuk membuat dokumentasi yang dapat dibaca, termasuk header, footer, dan konten.
*   **Pembuatan Artikel Blog**: Menggunakan Markdown untuk menulis dan mengatur artikel blog, sehingga mudah disaring dan dikolaborasikan antara penulis.
*   **Tulis Teknisi**: Mengkonversi berkas EML untuk membuat manual pengguna, panduan, atau instruksi dalam bentuk yang jelas dan padat.
*   **Postingan Media Sosial**: Menggunakan Markdown untuk mengatur postingan media sosial, termasuk gambar, tautan, dan video, untuk meningkatkan engagement dan visibilitas.
*   **Presentasi dan Laporan**: Mengkonversi berkas EML untuk membuat presentasi interaktif dan laporan menggunakan sintaks Markdown, sehingga mudah disaring dan dikolaborasikan antara pihak yang terkait.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}