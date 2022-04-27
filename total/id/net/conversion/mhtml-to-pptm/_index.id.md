---
title: Ekspor MHTML ke PPTM melalui C# API
description: .NET API untuk Mengonversi MHTML ke PPTM tanpa menggunakan Microsoft Word
url: /id/net/conversion/mhtml-to-pptm/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: PPTM
otherformats: POWERPOINT XAML POT PPSM PPSX POTX OTP POTM PPTM SWF PPT PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Render MHTML ke PPTM melalui .NET" h2=".NET API untuk Mengekspor MHTML ke PPTM di Windows, macOS, dan Linux tanpa menggunakan Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Menggunakan paket API Otomatisasi Format File yang andal [Aspose.Total for .NET](https://products.aspose.com/total/net/), Anda dapat dengan mudah Render MHTML ke PPTM dalam dua langkah sederhana. Dengan menggunakan API Pemrosesan PDF [Aspose.PDF untuk .NET](https://products.aspose.com/pdf/net/), Anda dapat mengubah format file MHTML menjadi PPTX. Setelah itu, dengan menggunakan Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), Anda dapat mengonversi PPTX ke PPTM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API untuk Mengonversi MHTML ke PPTM" %}}
1. Buka file MHTML menggunakan kelas [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Konversi MHTML ke PPTX dengan menggunakan metode [Simpan](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Muat file PPTX dengan menggunakan kelas [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
4. Simpan dokumen ke format PPTM menggunakan metode [Save](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) dan setel `Pptm` sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.mhtml");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.pptm", SaveFormat.Pptm);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dapatkan Metadata XMP dari File MHTML melalui .NET" %}}
Saat mengonversi MHTML ke PPTM, Anda mungkin memerlukan informasi metadata XMP tambahan untuk memprioritaskan proses konversi batch Anda. Misalnya Anda bisa mendapatkan dan mengurutkan dokumen konversi Anda berdasarkan tanggal pembuatan dan memproses dokumen yang sesuai. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) memungkinkan Anda mengakses metadata XMP file MHTML. Untuk mendapatkan metadata file MHTML, Anda dapat membuat objek [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) dan membuka file input MHTML. Setelah itu, Anda bisa mendapatkan metadata file menggunakan properti [Metadata](https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.mhtml");

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

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/mhtml-to-pot/" name="MHTML Ke POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/mhtml-to-ppsx/" name="MHTML Ke PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/mhtml-to-swf/" name="MHTML Ke SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/mhtml-to-powerpoint/" name="MHTML Ke POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/mhtml-to-otp/" name="MHTML Ke OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/mhtml-to-potm/" name="MHTML Ke POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/mhtml-to-ppt/" name="MHTML Ke PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/mhtml-to-pps/" name="MHTML Ke PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/mhtml-to-potx/" name="MHTML Ke POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/mhtml-to-xaml/" name="MHTML Ke XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/mhtml-to-ppsm/" name="MHTML Ke PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/mhtml-to-pptm/" name="MHTML Ke PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}