---
title: Ekspor SVG ke PPTM melalui C# API
description: .NET API untuk Mengonversi SVG ke PPTM tanpa menggunakan Microsoft Word
url: /id/net/conversion/svg-to-pptm/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: PPTM
otherformats: PPS XAML PPSX OTP POTM POT PPSM PPTM POTX SWF PPT POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Render SVG ke PPTM melalui .NET" h2=".NET API untuk Mengekspor SVG ke PPTM di Windows, macOS, dan Linux tanpa menggunakan Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Menggunakan paket API Otomatisasi Format File yang andal [Aspose.Total for .NET](https://products.aspose.com/total/net/), Anda dapat dengan mudah Render SVG ke PPTM dalam dua langkah sederhana. Dengan menggunakan API Pemrosesan PDF [Aspose.PDF untuk .NET](https://products.aspose.com/pdf/net/), Anda dapat mengubah format file SVG menjadi PPTX. Setelah itu, dengan menggunakan Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), Anda dapat mengonversi PPTX ke PPTM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API untuk Mengonversi SVG ke PPTM" %}}
1. Buka file SVG menggunakan kelas [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Konversi SVG ke PPTX dengan menggunakan metode [Simpan](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Muat file PPTX dengan menggunakan kelas [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
4. Simpan dokumen ke format PPTM menggunakan metode [Save](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) dan setel `Pptm` sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.svg");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.pptm", SaveFormat.Pptm);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dapatkan Metadata XMP dari File SVG melalui .NET" %}}
Saat mengonversi SVG ke PPTM, Anda mungkin memerlukan informasi metadata XMP tambahan untuk memprioritaskan proses konversi batch Anda. Misalnya Anda bisa mendapatkan dan mengurutkan dokumen konversi Anda berdasarkan tanggal pembuatan dan memproses dokumen yang sesuai. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) memungkinkan Anda mengakses metadata XMP file SVG. Untuk mendapatkan metadata file SVG, Anda dapat membuat objek [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) dan membuka file input SVG. Setelah itu, Anda bisa mendapatkan metadata file menggunakan properti [Metadata](https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.svg");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Buat File PPTM Hanya Baca melalui .NET" %}}
Dengan menggunakan [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API, Anda dapat lebih menyempurnakan fitur aplikasi konversi Anda. Salah satu fiturnya adalah membuat file output Anda hanya baca untuk meningkatkan keamanan. API memungkinkan Anda menyetel file PPTM ke Hanya-Baca, yang berarti pengguna (setelah mereka membuka presentasi) melihat rekomendasi Hanya-Baca. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.pptm", SaveFormat.Pptm);     
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Opsi Konversi Lainnya" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/svg-to-pot/" name="SVG Ke POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/svg-to-ppsx/" name="SVG Ke PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/svg-to-swf/" name="SVG Ke SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/svg-to-powerpoint/" name="SVG Ke POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/svg-to-otp/" name="SVG Ke OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/svg-to-potm/" name="SVG Ke POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/svg-to-ppt/" name="SVG Ke PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/svg-to-pps/" name="SVG Ke PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/svg-to-potx/" name="SVG Ke POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/svg-to-xaml/" name="SVG Ke XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/svg-to-ppsm/" name="SVG Ke PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/svg-to-pptm/" name="SVG Ke PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}