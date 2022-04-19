---
title: C# API untuk Mengekspor SVG ke DOCM
description: Konversi SVG ke DOCM tanpa menggunakan Microsoft Word
url: /id/net/conversion/svg-to-docm/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: DOCM
otherformats: MHTML XAMLFLOW MARKDOWN WORDML PCL DOTM PS FLATOPC DOT OTT RTF DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Render SVG ke DOCM melalui .NET" h2=".NET API untuk Mengekspor SVG ke DOCM di Windows, macOS, dan Linux tanpa menggunakan Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) adalah API yang kuat untuk menambahkan fitur manipulasi dan konversi dokumen di dalam aplikasi .NET Anda. Dengan menggunakan API Pemrosesan PDF lanjutan [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), Anda dapat mengonversi format file SVG ke DOC. Setelah itu, dengan menggunakan API Pemrosesan Dokumen yang kuat [Aspose.Words for .NET](https://products.aspose.com/words/net/), Anda dapat merender DOC ke DOCM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API untuk Mengonversi SVG ke DOCM" %}}
1. Buka file SVG menggunakan kelas [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Konversi SVG ke Dokumen dengan menggunakan metode [Simpan](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Muat file Doc dengan menggunakan [Document](https://apireference.aspose.com/words/net/aspose.words/document) kelas Aspose.Words
4. Simpan dokumen ke format DOCM menggunakan metode [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) dan atur Docm sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.svg");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.docm", SaveFormat.Docm);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dekripsi File SVG menggunakan Kata Sandi Pemilik melalui .NET" %}}
Sebelum mengkonversi SVG ke DOCM, jika Anda ingin mendekripsi dokumen Anda, Anda dapat melakukannya dengan menggunakan API. Untuk mendekripsi file PDF, Anda harus terlebih dahulu membuat objek [Dokumen](https://apireference.aspose.com/pdf/net/aspose.pdf/document) dan membuka SVG menggunakan sandi pemilik. Setelah itu, Anda perlu memanggil metode [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) dari objek Dokumen. Terakhir, simpan file yang diperbarui menggunakan metode Simpan dari objek Dokumen.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.svg", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Buat ReadOnly DOCM- File melalui .NET" %}}
Untuk melindungi DOCM Anda dari pengeditan dan untuk mencegah orang lain mengedit informasi sensitif dan rahasia dalam dokumen Anda, Anda juga dapat mengatur perlindungan dokumen menggunakan API. Anda dapat membatasi kemampuan untuk mengedit dokumen dan hanya mengizinkan tindakan tertentu dengannya. Ini dapat dilakukan menggunakan [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. Ini memungkinkan Anda mengontrol cara Anda membatasi konten menggunakan parameter enumerasi [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype). Anda dapat mengatur dokumen Anda menjadi baca-saja dengan menggunakan baris kode berikut. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.docm", SaveFormat.Docm);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Opsi Konversi Lainnya" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/svg-to-ott/" name="SVG Ke OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/svg-to-mhtml/" name="SVG Ke MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/svg-to-wordml/" name="SVG Ke WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/svg-to-dot/" name="SVG Ke DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/svg-to-odt/" name="SVG Ke ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/svg-to-rtf/" name="SVG Ke RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/svg-to-ps/" name="SVG Ke PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/svg-to-flatopc/" name="SVG Ke FLAKePC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/svg-to-pcl/" name="SVG Ke PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/svg-to-markdown/" name="SVG Ke MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/svg-to-xamlflow/" name="SVG Ke XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/svg-to-dotx/" name="SVG Ke DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}