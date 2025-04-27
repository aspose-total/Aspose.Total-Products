---
title: C# API untuk Mengekspor EML ke SVG
description: Konversi EML ke SVG tanpa menggunakan Microsoft Word atau Outlook di .NET
url_ignore: /id/net/conversion/eml-to-svg/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: SVG
otherformats: DOCX OTT PS DOTX WORDML GIF PNG SVG ODT RTF DOC PCL XPS MD DOT JPEG TIFF EMF TEXT PDF FLATOPC EPUB DOCM DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Ekspor EML ke SVG melalui .NET" h2=".NET API untuk Merender EML ke SVG di Windows, macOS, dan Linux tanpa menggunakan Word atau Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jika Anda adalah pengembang .NET yang ingin menambahkan fitur konversi EML ke SVG di dalam aplikasi Anda, [Aspose.Total for .NET](https://products.aspose.com/total/net/) API manipulasi format file adalah caranya maju. Dengan menggunakan [Aspose.Email for .NET](https://products.aspose.com/email/net/), Anda dapat mengonversi format file EML ke HTML. Setelah itu, dengan menggunakan [Aspose.Words for .NET](https://products.aspose.com/words/net/), Anda dapat merender HTML ke SVG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API untuk Mengonversi EML ke SVG" %}}
1. Buka file EML menggunakan kelas [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Konversi EML ke HTML dengan menggunakan metode [Simpan](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Muat HTML dengan menggunakan kelas [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Simpan dokumen ke format SVG menggunakan metode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) dan atur Svg sebagai SaveFormat
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

document.Save("output.svg", SaveFormat.Svg); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parsing File EML melalui .NET" %}}
Sebelum mengonversi EML ke SVG, jika Anda ingin memastikan bahwa Anda mengonversi eml yang benar, Anda dapat memuat dokumen EML, menguraikannya dan melihat properti yang Anda inginkan. Dengan menggunakan kelas [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) dari [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, Anda bisa mendapatkan informasi pengirim dan penerima. Misalnya, Anda dapat memeriksa eml pengirim tertentu untuk konversi dengan menggunakan properti [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EML file from disk
var outlookMessageFile = MapiMessage.FromFile("message.eml");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Batasi Pengeditan Dokumen SVG melalui .NET" %}}
Saat menyimpan dokumen dari EML ke SVG, Anda mungkin perlu melindungi dokumen keluaran Anda. Terkadang Anda mungkin perlu membatasi kemampuan untuk mengedit dokumen dan hanya mengizinkan tindakan tertentu dengannya. Ini dapat berguna untuk mencegah orang lain mengedit informasi sensitif dan rahasia dalam dokumen Anda. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, memungkinkan Anda mengontrol cara Anda membatasi konten menggunakan [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parameter enumerasi. Anda dapat mengatur dokumen Anda menjadi baca-saja dengan menggunakan baris kode berikut. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.svg", SaveFormat.Svg);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Mengubah File EML ke SVG Secara Terprogram : Contoh Penggunaan" %}}
Berikut adalah translasi dari teks tersebut ke dalam bahasa Indonesia:

**Berkas EML (Electronic Mail) digunakan untuk menyimpan pesan berbasis teks, sehingga mereka ideal untuk mengirim dan menerima surel. Namun, ketika bekerja dengan data grafis, Berkas SVG (Scalable Vector Graphics) menjadi esensial untuk membuat gambar yang dapat diskaul dan tidak tergantung pada resolusi.

Pengubahan Berkas EML ke format SVG diperlukan untuk mengaktifkan potensi penuh dalam kemampuan visualisasi dan analisis data grafis Anda. Pengubahan ini memungkinkan Anda:

**Aplikasi/Use Cases:**

* **Desain Grafik Web**: Mengkonversi Berkas EML untuk membuat gambar berbasis vektor di internet, logo, dan ikon yang dapat diskaul dengan resolusi layar yang berbeda.
* **Penggunaan dalam Penerbitan Desktop**: Menggunakan SVG untuk visualisasi data grafis kompleks seperti diagram, graf, dan informasi visual dalam publikasi dan presentasi.
* **Pengembangan Aplikasi Mobile**: Mengkonversi Berkas EML untuk membuat gambar yang dapat diskaul dan ilustrasi untuk aplikasi mobile, memastikan pengalaman pengguna yang konsisten di berbagai device.
* **Penciptaan Konten Belajar Online**: Menggunakan SVG untuk membuat visualisasi interaktif dan menarik untuk konten belajar online, seperti tutorial animasi dan simulasi.
* **Visualisasi Data dan Laporan**: Mengkonversi Berkas EML untuk membuat dashboard interaktif, laporan, dan visualisasi yang dapat digunakan oleh para stakeholder, sehingga memungkinkan keputusan yang lebih baik.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}