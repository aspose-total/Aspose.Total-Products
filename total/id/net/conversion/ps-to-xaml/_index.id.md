---
title: Ekspor PS ke XAML melalui C# API
description: .NET API untuk Mengonversi PS ke XAML tanpa menggunakan Microsoft Word
url_ignore: /id/net/conversion/ps-to-xaml/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: XAML
otherformats: XAML OTP POT SWF POTM PPSM POTX PPT PPSX PPS PPTM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Render PS ke XAML melalui .NET" h2=".NET API untuk Mengekspor PS ke XAML di Windows, macOS, dan Linux tanpa menggunakan Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Menggunakan paket API Otomatisasi Format File yang andal [Aspose.Total for .NET](https://products.aspose.com/total/net/), Anda dapat dengan mudah Render PS ke XAML dalam dua langkah sederhana. Dengan menggunakan API Pemrosesan PDF [Aspose.PDF untuk .NET](https://products.aspose.com/pdf/net/), Anda dapat mengubah format file PS menjadi PPTX. Setelah itu, dengan menggunakan Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), Anda dapat mengonversi PPTX ke XAML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API untuk Mengonversi PS ke XAML" %}}
1. Buka file PS menggunakan kelas [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konversi PS ke PPTX dengan menggunakan metode [Simpan](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Muat file PPTX dengan menggunakan kelas [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Simpan dokumen ke format XAML menggunakan metode [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) dan setel `Xaml` sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dapatkan Metadata XMP dari File PS melalui .NET" %}}
Saat mengonversi PS ke XAML, Anda mungkin memerlukan informasi metadata XMP tambahan untuk memprioritaskan proses konversi batch Anda. Misalnya Anda bisa mendapatkan dan mengurutkan dokumen konversi Anda berdasarkan tanggal pembuatan dan memproses dokumen yang sesuai. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) memungkinkan Anda mengakses metadata XMP file PS. Untuk mendapatkan metadata file PS, Anda dapat membuat objek [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) dan membuka file input PS. Setelah itu, Anda bisa mendapatkan metadata file menggunakan properti [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Buat File XAML Hanya Baca melalui .NET" %}}
Dengan menggunakan [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API, Anda dapat lebih menyempurnakan fitur aplikasi konversi Anda. Salah satu fiturnya adalah membuat file output Anda hanya baca untuk meningkatkan keamanan. API memungkinkan Anda menyetel file XAML ke Hanya-Baca, yang berarti pengguna (setelah mereka membuka presentasi) melihat rekomendasi Hanya-Baca. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.xaml", SaveFormat.Xaml);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Mengubah File PS ke XAML Secara Terprogram : Contoh Penggunaan" %}}
PS (Portable Document Format) digunakan untuk menyimpan informasi visual vector, sehingga cocok untuk membuat grafik statis, logo, dan ilustrasi. Namun, ketika bekerja dengan data dinamis, XAML (Extensible Application Markup Language) menjadi esensial untuk membangun antarmuka pengguna dan aplikasi.

Konversi dari file PS ke format XAML diperlukan untuk mengaktifkan potensi kapasitas pengembangan aplikasi Anda. Konversi ini memungkinkan Anda:

**Aplikasi Penggunaan:**

*   **Pengembangan Aplikasi Mobile**: Ubah file PS menjadi aplikasi mobile native dengan antarmuka pengguna yang intuitif, manfaatkan kuasa XAML untuk pengalaman pengguna yang halus.
*   **Pengembangan Aplikasi Desktop**: Manfaatkan XAML untuk membangun aplikasi desktop yang kuat dan skala, mengambil keuntungan dari kemampuan dalam binding data, animasi, dan templating.
*   **Perpustakaan Komponen UI**: Ubah file PS menjadi komponen UI yang dapat diulang seperti tombol, bidang teks, dan menu, menggunakan XAML untuk desain yang efisien dan mudah di-maintain.
*   **Grafik 3D dan Animasi**: Manfaatkan XAML untuk memberikan kehidupan pada grafik 3D dan animasi dalam aplikasi Anda, menggabungkan kuasa grafik vector dengan fleksibilitas bahasa markup.
*   **Aksesibilitas dan Personalisasi**: Ubah file PS menjadi elemen UI yang dapat diakses dan disesuaikan, memastikan bahwa aplikasi Anda menyediakan kebutuhan dan preferensi pengguna yang beragam.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}