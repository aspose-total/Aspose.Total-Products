---
title: C# API untuk Mengekspor PS ke RTF
description: Konversi PS ke RTF tanpa menggunakan Microsoft Word
url_ignore: /id/net/conversion/ps-to-rtf/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: RTF
otherformats: DOTM ODT PCL FLATOPC OTT DOT DOTX WORDML MHTML MARKDOWN XAMLFLOW RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Render PS ke RTF melalui .NET" h2=".NET API untuk Mengekspor PS ke RTF di Windows, macOS, dan Linux tanpa menggunakan Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) adalah API yang kuat untuk menambahkan fitur manipulasi dan konversi dokumen di dalam aplikasi .NET Anda. Dengan menggunakan API Pemrosesan PDF lanjutan [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), Anda dapat mengonversi format file PS ke DOC. Setelah itu, dengan menggunakan API Pemrosesan Dokumen yang kuat [Aspose.Words for .NET](https://products.aspose.com/words/net/), Anda dapat merender DOC ke RTF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API untuk Mengonversi PS ke RTF" %}}
1. Buka file PS menggunakan kelas [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konversi PS ke Dokumen dengan menggunakan metode [Simpan](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Muat file Doc dengan menggunakan [Document](https://reference.aspose.com/words/net/aspose.words/document) kelas Aspose.Words
4. Simpan dokumen ke format RTF menggunakan metode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) dan atur Rtf sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dekripsi File PS menggunakan Kata Sandi Pemilik melalui .NET" %}}
Sebelum mengkonversi PS ke RTF, jika Anda ingin mendekripsi dokumen Anda, Anda dapat melakukannya dengan menggunakan API. Untuk mendekripsi file PDF, Anda harus terlebih dahulu membuat objek [Dokumen](https://reference.aspose.com/pdf/net/aspose.pdf/document) dan membuka PS menggunakan sandi pemilik. Setelah itu, Anda perlu memanggil metode [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) dari objek Dokumen. Terakhir, simpan file yang diperbarui menggunakan metode Simpan dari objek Dokumen.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
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

{{% blocks/products/pf/feature-page-section  h2="Mengubah File PS ke RTF Secara Terprogram : Contoh Penggunaan" %}}
**PS ( Portable Document Format )**

Berkas-berkas PS (Portable Document Format) digunakan untuk menyimpan informasi dokumen, sehingga menjadi pilihan yang tepat untuk membuat dokumen dengan tampilan profesional dan presentasi.

Namun, ketika bekerja dengan konten multimedia, berkas-berkas Rich Text Format (RTF) menjadi esensial untuk mengatur format teks dan melakukan penyuntingan.

Konversi berkas-berkas PS ke format RTF diperlukan untuk memungkinkan Anda mengaktifkan potensi penuh dalam keterampilan pengaturan format teks dan penyuntingan.

**Manfaat Konversi:**

* **Penyuntingan Dokumen:** Mengkonversi berkas-berkas PS untuk menyunting teks, tata letak, dan format dengan cara yang lebih intuitif.
* **Pembuatan PDF:** Manfaatkan RTF untuk membuat dokumen PDF dengan tampilan profesional dan render huruf yang akurat serta tata letak yang tepat.
* **Impor Teks:** Mengkonversi berkas-berkas PS untuk mengimpor konten teks dalam jumlah besar ke dalam aplikasi lainnya untuk penyuntingan yang lebih efisien.
* **Pertahankan Format:** Manfaatkan RTF untuk mempertahankan format dokumen, termasuk huruf, jarak, dan penyesuaianan, saat dokumen dibagikan dan dikolaborasi.
* **Perbaikan Kompatibilitas:** Mengkonversi berkas-berkas PS untuk meningkatkan kompatibilitas dengan berbagai aplikasi dan platform, memastikan pertukaran dokumen yang halus.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}