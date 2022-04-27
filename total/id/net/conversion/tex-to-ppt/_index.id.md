---
title: Ekspor TEX ke PPT melalui C# API
description: .NET API untuk Mengonversi TEX ke PPT tanpa menggunakan Microsoft Word
url: /id/net/conversion/tex-to-ppt/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: PPT
otherformats: OTP XAML PPT PPS POWERPOINT PPTM PPSX POTX POTM SWF POT PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Render TEX ke PPT melalui .NET" h2=".NET API untuk Mengekspor TEX ke PPT di Windows, macOS, dan Linux tanpa menggunakan Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Menggunakan paket API Otomatisasi Format File yang andal [Aspose.Total for .NET](https://products.aspose.com/total/net/), Anda dapat dengan mudah Render TEX ke PPT dalam dua langkah sederhana. Dengan menggunakan API Pemrosesan PDF [Aspose.PDF untuk .NET](https://products.aspose.com/pdf/net/), Anda dapat mengubah format file TEX menjadi PPTX. Setelah itu, dengan menggunakan Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), Anda dapat mengonversi PPTX ke PPT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API untuk Mengonversi TEX ke PPT" %}}
1. Buka file TEX menggunakan kelas [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Konversi TEX ke PPTX dengan menggunakan metode [Simpan](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Muat file PPTX dengan menggunakan kelas [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
4. Simpan dokumen ke format PPT menggunakan metode [Save](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) dan setel `Ppt` sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.tex");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.ppt", SaveFormat.Ppt);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dapatkan Metadata XMP dari File TEX melalui .NET" %}}
Saat mengonversi TEX ke PPT, Anda mungkin memerlukan informasi metadata XMP tambahan untuk memprioritaskan proses konversi batch Anda. Misalnya Anda bisa mendapatkan dan mengurutkan dokumen konversi Anda berdasarkan tanggal pembuatan dan memproses dokumen yang sesuai. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) memungkinkan Anda mengakses metadata XMP file TEX. Untuk mendapatkan metadata file TEX, Anda dapat membuat objek [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) dan membuka file input TEX. Setelah itu, Anda bisa mendapatkan metadata file menggunakan properti [Metadata](https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.tex");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Buat File PPT Hanya Baca melalui .NET" %}}
Dengan menggunakan [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API, Anda dapat lebih menyempurnakan fitur aplikasi konversi Anda. Salah satu fiturnya adalah membuat file output Anda hanya baca untuk meningkatkan keamanan. API memungkinkan Anda menyetel file PPT ke Hanya-Baca, yang berarti pengguna (setelah mereka membuka presentasi) melihat rekomendasi Hanya-Baca. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.ppt", SaveFormat.Ppt);     
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Opsi Konversi Lainnya" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/tex-to-pot/" name="TEX Ke POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/tex-to-ppsx/" name="TEX Ke PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/tex-to-swf/" name="TEX Ke SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/tex-to-powerpoint/" name="TEX Ke POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/tex-to-otp/" name="TEX Ke OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/tex-to-potm/" name="TEX Ke POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/tex-to-ppt/" name="TEX Ke PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/tex-to-pps/" name="TEX Ke PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/tex-to-potx/" name="TEX Ke POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/tex-to-xaml/" name="TEX Ke XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/tex-to-ppsm/" name="TEX Ke PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/tex-to-pptm/" name="TEX Ke PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}