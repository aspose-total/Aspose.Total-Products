---
title: Ekspor CGM ke SWF melalui C# API
description: .NET API untuk Mengonversi CGM ke SWF tanpa menggunakan Microsoft Word
url: /id/net/conversion/cgm-to-swf/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: SWF
otherformats: PPSM PPS PPT POTX PPSX SWF OTP POWERPOINT XAML POTM POT PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Render CGM ke SWF melalui .NET" h2=".NET API untuk Mengekspor CGM ke SWF di Windows, macOS, dan Linux tanpa menggunakan Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Menggunakan paket API Otomatisasi Format File yang andal [Aspose.Total for .NET](https://products.aspose.com/total/net/), Anda dapat dengan mudah Render CGM ke SWF dalam dua langkah sederhana. Dengan menggunakan API Pemrosesan PDF [Aspose.PDF untuk .NET](https://products.aspose.com/pdf/net/), Anda dapat mengubah format file CGM menjadi PPTX. Setelah itu, dengan menggunakan Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), Anda dapat mengonversi PPTX ke SWF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API untuk Mengonversi CGM ke SWF" %}}
1. Buka file CGM menggunakan kelas [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Konversi CGM ke PPTX dengan menggunakan metode [Simpan](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Muat file PPTX dengan menggunakan kelas [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
4. Simpan dokumen ke format SWF menggunakan metode [Save](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) dan setel `Swf` sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.cgm");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.swf", SaveFormat.Swf);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dapatkan Metadata XMP dari File CGM melalui .NET" %}}
Saat mengonversi CGM ke SWF, Anda mungkin memerlukan informasi metadata XMP tambahan untuk memprioritaskan proses konversi batch Anda. Misalnya Anda bisa mendapatkan dan mengurutkan dokumen konversi Anda berdasarkan tanggal pembuatan dan memproses dokumen yang sesuai. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) memungkinkan Anda mengakses metadata XMP file CGM. Untuk mendapatkan metadata file CGM, Anda dapat membuat objek [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) dan membuka file input CGM. Setelah itu, Anda bisa mendapatkan metadata file menggunakan properti [Metadata](https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.cgm");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Buat File SWF Hanya Baca melalui .NET" %}}
Dengan menggunakan [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API, Anda dapat lebih menyempurnakan fitur aplikasi konversi Anda. Salah satu fiturnya adalah membuat file output Anda hanya baca untuk meningkatkan keamanan. API memungkinkan Anda menyetel file SWF ke Hanya-Baca, yang berarti pengguna (setelah mereka membuka presentasi) melihat rekomendasi Hanya-Baca. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.swf", SaveFormat.Swf);     
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Opsi Konversi Lainnya" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/cgm-to-pot/" name="CGM Ke POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/cgm-to-ppsx/" name="CGM Ke PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/cgm-to-swf/" name="CGM Ke SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/cgm-to-powerpoint/" name="CGM Ke POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/cgm-to-otp/" name="CGM Ke OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/cgm-to-potm/" name="CGM Ke POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/cgm-to-ppt/" name="CGM Ke PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/cgm-to-pps/" name="CGM Ke PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/cgm-to-potx/" name="CGM Ke POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/cgm-to-xaml/" name="CGM Ke XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/cgm-to-ppsm/" name="CGM Ke PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/cgm-to-pptm/" name="CGM Ke PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}