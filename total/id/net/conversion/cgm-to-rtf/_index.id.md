---
title: C# API untuk Mengekspor CGM ke RTF
description: Konversi CGM ke RTF tanpa menggunakan Microsoft Word
url_ignore: /id/net/conversion/cgm-to-rtf/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: RTF
otherformats: MHTML WORDML OTT PS XAMLFLOW DOT ODT PCL RTF DOTX FLATOPC DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Render CGM ke RTF melalui .NET" h2=".NET API untuk Mengekspor CGM ke RTF di Windows, macOS, dan Linux tanpa menggunakan Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) adalah API yang kuat untuk menambahkan fitur manipulasi dan konversi dokumen di dalam aplikasi .NET Anda. Dengan menggunakan API Pemrosesan PDF lanjutan [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), Anda dapat mengonversi format file CGM ke DOC. Setelah itu, dengan menggunakan API Pemrosesan Dokumen yang kuat [Aspose.Words for .NET](https://products.aspose.com/words/net/), Anda dapat merender DOC ke RTF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API untuk Mengonversi CGM ke RTF" %}}
1. Buka file CGM menggunakan kelas [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konversi CGM ke Dokumen dengan menggunakan metode [Simpan](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Muat file Doc dengan menggunakan [Document](https://reference.aspose.com/words/net/aspose.words/document) kelas Aspose.Words
4. Simpan dokumen ke format RTF menggunakan metode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) dan atur Rtf sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dekripsi File CGM menggunakan Kata Sandi Pemilik melalui .NET" %}}
Sebelum mengkonversi CGM ke RTF, jika Anda ingin mendekripsi dokumen Anda, Anda dapat melakukannya dengan menggunakan API. Untuk mendekripsi file PDF, Anda harus terlebih dahulu membuat objek [Dokumen](https://reference.aspose.com/pdf/net/aspose.pdf/document) dan membuka CGM menggunakan sandi pemilik. Setelah itu, Anda perlu memanggil metode [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) dari objek Dokumen. Terakhir, simpan file yang diperbarui menggunakan metode Simpan dari objek Dokumen.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Buat ReadOnly RTF- File melalui .NET" %}}
Untuk melindungi RTF Anda dari pengeditan dan untuk mencegah orang lain mengedit informasi sensitif dan rahasia dalam dokumen Anda, Anda juga dapat mengatur perlindungan dokumen menggunakan API. Anda dapat membatasi kemampuan untuk mengedit dokumen dan hanya mengizinkan tindakan tertentu dengannya. Ini dapat dilakukan menggunakan [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. Ini memungkinkan Anda mengontrol cara Anda membatasi konten menggunakan parameter enumerasi [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). Anda dapat mengatur dokumen Anda menjadi baca-saja dengan menggunakan baris kode berikut. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.rtf", SaveFormat.Rtf);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Mengubah File CGM ke RTF Secara Terprogram : Contoh Penggunaan" %}}
CGM (Computer Graphics Metafile) digunakan untuk menyimpan informasi grafik vector, sehingga cocok untuk membuat gambar statis dan ilustrasi. Namun, ketika bekerja dengan data dinamis, spreadsheet seperti Excel menjadi esensial untuk visualisasi data dan analisis.

Konversi file CGM ke format RTF (Rich Text Format) diperlukan untuk mengaktifkan kemampuan text Anda secara penuh. Konversi ini memungkinkan Anda:

**Apa yang bisa dilakukan:**

*   **Pembuatan Dokumen**: Mengkonversi file CGM untuk membuat dokumen dengan format profesional, laporan, dan presentasi.
*   **Editing dan Format Text**: Menggunakan RTF untuk mengedit dan memformat teks dengan kendali yang jelas atas gaya font, ukuran, warna, dan tata letak.
*   **Template Surat Elektron dan Surat Bisnis**: Mengkonversi file CGM untuk membuat template surat yang dapat disesuaikan, surat bisnis, dan korrespondensi lainnya.
*   **Penggunaan Desktop Publishing**: Menggunakan RTF untuk membuat dokumen berkualitas tinggi, broshur, dan bahan publikasi lainnya untuk distribusi internal atau eksternal.
*   **Penulisan Teknik**: Mengkonversi file CGM untuk membuat dokumen teknis, manual pengguna, dan panduan dengan formatting dan tata letak yang akurat.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}