---
title: C# API untuk Mengekspor CGM ke OTT
description: Konversi CGM ke OTT tanpa menggunakan Microsoft Word
url_ignore: /id/net/conversion/cgm-to-ott/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: OTT
otherformats: OTT XAMLFLOW FLATOPC DOTX MHTML ODT DOTM PS WORDML RTF MARKDOWN DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Render CGM ke OTT melalui .NET" h2=".NET API untuk Mengekspor CGM ke OTT di Windows, macOS, dan Linux tanpa menggunakan Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) adalah API yang kuat untuk menambahkan fitur manipulasi dan konversi dokumen di dalam aplikasi .NET Anda. Dengan menggunakan API Pemrosesan PDF lanjutan [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), Anda dapat mengonversi format file CGM ke DOC. Setelah itu, dengan menggunakan API Pemrosesan Dokumen yang kuat [Aspose.Words for .NET](https://products.aspose.com/words/net/), Anda dapat merender DOC ke OTT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API untuk Mengonversi CGM ke OTT" %}}
1. Buka file CGM menggunakan kelas [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konversi CGM ke Dokumen dengan menggunakan metode [Simpan](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Muat file Doc dengan menggunakan [Document](https://reference.aspose.com/words/net/aspose.words/document) kelas Aspose.Words
4. Simpan dokumen ke format OTT menggunakan metode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) dan atur Ott sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.cgm");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.ott", SaveFormat.Ott);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dekripsi File CGM menggunakan Kata Sandi Pemilik melalui .NET" %}}
Sebelum mengkonversi CGM ke OTT, jika Anda ingin mendekripsi dokumen Anda, Anda dapat melakukannya dengan menggunakan API. Untuk mendekripsi file PDF, Anda harus terlebih dahulu membuat objek [Dokumen](https://reference.aspose.com/pdf/net/aspose.pdf/document) dan membuka CGM menggunakan sandi pemilik. Setelah itu, Anda perlu memanggil metode [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) dari objek Dokumen. Terakhir, simpan file yang diperbarui menggunakan metode Simpan dari objek Dokumen.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.cgm", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Buat ReadOnly OTT- File melalui .NET" %}}
Untuk melindungi OTT Anda dari pengeditan dan untuk mencegah orang lain mengedit informasi sensitif dan rahasia dalam dokumen Anda, Anda juga dapat mengatur perlindungan dokumen menggunakan API. Anda dapat membatasi kemampuan untuk mengedit dokumen dan hanya mengizinkan tindakan tertentu dengannya. Ini dapat dilakukan menggunakan [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. Ini memungkinkan Anda mengontrol cara Anda membatasi konten menggunakan parameter enumerasi [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). Anda dapat mengatur dokumen Anda menjadi baca-saja dengan menggunakan baris kode berikut. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.ott", SaveFormat.Ott);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Mengubah File CGM ke OTT Secara Terprogram : Contoh Penggunaan" %}}
Konversi file CGM (Computer Graphics Metafile) menjadi format OTT (OpenType Text) diperlukan untuk memungkinkan potensi penuh dalam visualisasi dan analisis data berbasis teks Anda. Konversi ini memungkinkan Anda:

**Aplikasi atau Kasus:**

*   **Desain Logotype**: Mengkonversi file CGM menjadi logotype skalabel yang memastikan tipografi tetap jelas dan bersih di berbagai medium.
*   **Analisis Tipografi**: Menggunakan format OTT untuk menganalisis karakteristik font, mengiketika pola penggunaan, dan mengidentifikasi trend dalam tipografi.
*   **Pembangunan Merek dan Identitas**: Mengkonversi file CGM untuk membuat identitas merek yang konsisten, termasuk logo, tipografi, dan skema warna.
*   **Desain Cetak dan Penerbitan**: Mengkonversi file CGM untuk membuat bahan cetak profesional seperti brosur, flysheet, dan poster.
*   **Laporan Data dan Dashboard Interaktif**: Mengkonversi file CGM untuk membuat dashboard interaktif, laporan, dan visualisasi yang dapat digunakan oleh para stakeholder untuk memfasilitasi keputusan yang lebih baik.

Dengan mengkonversi file CGM menjadi format OTT, Anda dapat memungkinkan potensi penuh dalam visualisasi dan analisis data berbasis teks Anda.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}