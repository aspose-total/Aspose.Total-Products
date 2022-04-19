---
title: Ekspor XML ke PPSM melalui C# API
description: .NET API untuk Mengonversi XML ke PPSM tanpa menggunakan Microsoft Word
url: /id/net/conversion/xml-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: XML
outformat: PPSM
otherformats: XAML PPS POWERPOINT SWF POTM PPTM OTP PPT PPSX PPSM POTX POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Render XML ke PPSM melalui .NET" h2=".NET API untuk Mengekspor XML ke PPSM di Windows, macOS, dan Linux tanpa menggunakan Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Menggunakan paket API Otomatisasi Format File yang andal [Aspose.Total for .NET](https://products.aspose.com/total/net/), Anda dapat dengan mudah Render XML ke PPSM dalam dua langkah sederhana. Dengan menggunakan API Pemrosesan PDF [Aspose.PDF untuk .NET](https://products.aspose.com/pdf/net/), Anda dapat mengubah format file XML menjadi PPTX. Setelah itu, dengan menggunakan Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), Anda dapat mengonversi PPTX ke PPSM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API untuk Mengonversi XML ke PPSM" %}}
1. Buka file XML menggunakan kelas [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Konversi XML ke PPTX dengan menggunakan metode [Simpan](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Muat file PPTX dengan menggunakan kelas [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
4. Simpan dokumen ke format PPSM menggunakan metode [Save](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) dan setel `Ppsm` sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.xml");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.ppsm", SaveFormat.Ppsm);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dapatkan Metadata XMP dari File XML melalui .NET" %}}
Saat mengonversi XML ke PPSM, Anda mungkin memerlukan informasi metadata XMP tambahan untuk memprioritaskan proses konversi batch Anda. Misalnya Anda bisa mendapatkan dan mengurutkan dokumen konversi Anda berdasarkan tanggal pembuatan dan memproses dokumen yang sesuai. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) memungkinkan Anda mengakses metadata XMP file XML. Untuk mendapatkan metadata file XML, Anda dapat membuat objek [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) dan membuka file input XML. Setelah itu, Anda bisa mendapatkan metadata file menggunakan properti [Metadata](https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.xml");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Buat File PPSM Hanya Baca melalui .NET" %}}
Dengan menggunakan [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API, Anda dapat lebih menyempurnakan fitur aplikasi konversi Anda. Salah satu fiturnya adalah membuat file output Anda hanya baca untuk meningkatkan keamanan. API memungkinkan Anda menyetel file PPSM ke Hanya-Baca, yang berarti pengguna (setelah mereka membuka presentasi) melihat rekomendasi Hanya-Baca. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.ppsm", SaveFormat.Ppsm);     
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Opsi Konversi Lainnya" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xml-to-pot/" name="XML Ke POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xml-to-ppsx/" name="XML Ke PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xml-to-swf/" name="XML Ke SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xml-to-powerpoint/" name="XML Ke POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xml-to-otp/" name="XML Ke OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xml-to-potm/" name="XML Ke POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xml-to-ppt/" name="XML Ke PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xml-to-pps/" name="XML Ke PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xml-to-potx/" name="XML Ke POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xml-to-xaml/" name="XML Ke XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xml-to-ppsm/" name="XML Ke PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xml-to-pptm/" name="XML Ke PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}