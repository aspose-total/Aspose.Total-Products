---
title: C# API untuk Mengekspor TEX ke DOTX
description: Konversi TEX ke DOTX tanpa menggunakan Microsoft Word
url: /id/net/conversion/tex-to-dotx/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: DOTX
otherformats: OTT DOT MARKDOWN ODT PS DOTM MHTML XAMLFLOW DOTX PCL WORDML FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Render TEX ke DOTX melalui .NET" h2=".NET API untuk Mengekspor TEX ke DOTX di Windows, macOS, dan Linux tanpa menggunakan Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) adalah API yang kuat untuk menambahkan fitur manipulasi dan konversi dokumen di dalam aplikasi .NET Anda. Dengan menggunakan API Pemrosesan PDF lanjutan [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), Anda dapat mengonversi format file TEX ke DOC. Setelah itu, dengan menggunakan API Pemrosesan Dokumen yang kuat [Aspose.Words for .NET](https://products.aspose.com/words/net/), Anda dapat merender DOC ke DOTX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API untuk Mengonversi TEX ke DOTX" %}}
1. Buka file TEX menggunakan kelas [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Konversi TEX ke Dokumen dengan menggunakan metode [Simpan](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Muat file Doc dengan menggunakan [Document](https://apireference.aspose.com/words/net/aspose.words/document) kelas Aspose.Words
4. Simpan dokumen ke format DOTX menggunakan metode [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) dan atur Dotx sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.tex");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.dotx", SaveFormat.Dotx);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dekripsi File TEX menggunakan Kata Sandi Pemilik melalui .NET" %}}
Sebelum mengkonversi TEX ke DOTX, jika Anda ingin mendekripsi dokumen Anda, Anda dapat melakukannya dengan menggunakan API. Untuk mendekripsi file PDF, Anda harus terlebih dahulu membuat objek [Dokumen](https://apireference.aspose.com/pdf/net/aspose.pdf/document) dan membuka TEX menggunakan sandi pemilik. Setelah itu, Anda perlu memanggil metode [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) dari objek Dokumen. Terakhir, simpan file yang diperbarui menggunakan metode Simpan dari objek Dokumen.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.tex", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Buat ReadOnly DOTX- File melalui .NET" %}}
Untuk melindungi DOTX Anda dari pengeditan dan untuk mencegah orang lain mengedit informasi sensitif dan rahasia dalam dokumen Anda, Anda juga dapat mengatur perlindungan dokumen menggunakan API. Anda dapat membatasi kemampuan untuk mengedit dokumen dan hanya mengizinkan tindakan tertentu dengannya. Ini dapat dilakukan menggunakan [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. Ini memungkinkan Anda mengontrol cara Anda membatasi konten menggunakan parameter enumerasi [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype). Anda dapat mengatur dokumen Anda menjadi baca-saja dengan menggunakan baris kode berikut. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dotx", SaveFormat.Dotx);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Opsi Konversi Lainnya" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/tex-to-ott/" name="TEX Ke OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/tex-to-mhtml/" name="TEX Ke MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/tex-to-wordml/" name="TEX Ke WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/tex-to-dot/" name="TEX Ke DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/tex-to-odt/" name="TEX Ke ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/tex-to-rtf/" name="TEX Ke RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/tex-to-ps/" name="TEX Ke PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/tex-to-flatopc/" name="TEX Ke FLAKePC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/tex-to-pcl/" name="TEX Ke PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/tex-to-markdown/" name="TEX Ke MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/tex-to-xamlflow/" name="TEX Ke XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/tex-to-dotx/" name="TEX Ke DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}