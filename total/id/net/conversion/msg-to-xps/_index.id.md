---
title: C# API untuk Mengekspor MSG ke XPS
description: Konversi MSG ke XPS tanpa menggunakan Microsoft Word atau Outlook di .NET
url: /id/net/conversion/msg-to-xps/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: XPS
otherformats: DOC XPS DOCX WORDML GIF PCL SVG EMF JPEG EPUB DOTM DOTX OTT RTF ODT DOT TIFF DOCM TEXT PS PNG MD PDF FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Ekspor MSG ke XPS melalui .NET" h2=".NET API untuk Merender MSG ke XPS di Windows, macOS, dan Linux tanpa menggunakan Word atau Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jika Anda adalah pengembang .NET yang ingin menambahkan fitur konversi MSG ke XPS di dalam aplikasi Anda, [Aspose.Total for .NET](https://products.aspose.com/total/net/) API manipulasi format file adalah caranya maju. Dengan menggunakan [Aspose.Msg for .NET](https://products.aspose.com/msg/net/), Anda dapat mengonversi format file MSG ke HTML. Setelah itu, dengan menggunakan [Aspose.Words for .NET](https://products.aspose.com/words/net/), Anda dapat merender HTML ke XPS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API untuk Mengonversi MSG ke XPS" %}}
1. Buka file MSG menggunakan kelas [MailMessage](https://apireference.aspose.com/msg/net/aspose.msg/mailmessage)
2. Konversi MSG ke HTML dengan menggunakan metode [Simpan](https://apireference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3)
3. Muat HTML dengan menggunakan kelas [Document](https://apireference.aspose.com/words/net/aspose.words/document)
4. Simpan dokumen ke format XPS menggunakan metode [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) dan atur Xps sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.msg");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.xps", SaveFormat.Xps); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parsing File MSG melalui .NET" %}}
Sebelum mengonversi MSG ke XPS, jika Anda ingin memastikan bahwa Anda mengonversi msg yang benar, Anda dapat memuat dokumen MSG, menguraikannya dan melihat properti yang Anda inginkan. Dengan menggunakan kelas [MapiMessage](https://apireference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) dari [Aspose.Msg for .NET](https://products.aspose.com/msg /net/) API, Anda bisa mendapatkan informasi pengirim dan penerima. Misalnya, Anda dapat memeriksa msg pengirim tertentu untuk konversi dengan menggunakan properti [SenderName](https://apireference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
.aspose.com
{{% blocks/products/pf/feature-page-section  h2="Batasi Pengeditan Dokumen XPS melalui .NET" %}}
Saat menyimpan dokumen dari MSG ke XPS, Anda mungkin perlu melindungi dokumen keluaran Anda. Terkadang Anda mungkin perlu membatasi kemampuan untuk mengedit dokumen dan hanya mengizinkan tindakan tertentu dengannya. Ini dapat berguna untuk mencegah orang lain mengedit informasi sensitif dan rahasia dalam dokumen Anda. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, memungkinkan Anda mengontrol cara Anda membatasi konten menggunakan [ProtectionType](https://apireference.aspose. com/words/net/aspose.words/protectiontype) parameter enumerasi. Anda dapat mengatur dokumen Anda menjadi baca-saja dengan menggunakan baris kode berikut. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.xps", SaveFormat.Xps);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Opsi Konversi Lainnya" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/msg-to-pcl/" name="MSG KE PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/msg-to-pdf/" name="MSG KE PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/msg-to-dot/" name="MSG KE DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/msg-to-flatopc/" name="MSG KE FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/msg-to-jpeg/" name="MSG KE JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/msg-to-png/" name="PNG MSG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/msg-to-rtf/" name="MSG KE RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/msg-to-tiff/" name="MSG KE TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/msg-to-docm/" name="MSG KE DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/msg-to-ps/" name="MSG KE PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/msg-to-gif/" name="MSG KE GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/msg-to-xps/" name="MSG KE XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/msg-to-odt/" name="MSG KE ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/msg-to-docx/" name="MSG KE DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/msg-to-doc/" name="MSG KE DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/msg-to-wordml/" name="MSG KE WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/msg-to-svg/" name="MSG KE SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/msg-to-epub/" name="MSG KE EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/msg-to-md/" name="MSG KE MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/msg-to-emf/" name="MSG KE EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/msg-to-dotm/" name="MSG KE DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/msg-to-ott/" name="MSG KE OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/msg-to-dotx/" name="MSG KE DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/msg-to-text/" name="MSG KE TEKS" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}