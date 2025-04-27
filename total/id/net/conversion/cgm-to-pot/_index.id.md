---
title: Ekspor CGM ke POT melalui C# API
description: .NET API untuk Mengonversi CGM ke POT tanpa menggunakan Microsoft Word
url_ignore: /id/net/conversion/cgm-to-pot/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: POT
otherformats: PPS POWERPOINT POTX PPT POT XAML OTP PPSX POTM PPSM SWF PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Render CGM ke POT melalui .NET" h2=".NET API untuk Mengekspor CGM ke POT di Windows, macOS, dan Linux tanpa menggunakan Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Menggunakan paket API Otomatisasi Format File yang andal [Aspose.Total for .NET](https://products.aspose.com/total/net/), Anda dapat dengan mudah Render CGM ke POT dalam dua langkah sederhana. Dengan menggunakan API Pemrosesan PDF [Aspose.PDF untuk .NET](https://products.aspose.com/pdf/net/), Anda dapat mengubah format file CGM menjadi PPTX. Setelah itu, dengan menggunakan Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), Anda dapat mengonversi PPTX ke POT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API untuk Mengonversi CGM ke POT" %}}
1. Buka file CGM menggunakan kelas [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konversi CGM ke PPTX dengan menggunakan metode [Simpan](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Muat file PPTX dengan menggunakan kelas [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Simpan dokumen ke format POT menggunakan metode [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) dan setel `Pot` sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dapatkan Metadata XMP dari File CGM melalui .NET" %}}
Saat mengonversi CGM ke POT, Anda mungkin memerlukan informasi metadata XMP tambahan untuk memprioritaskan proses konversi batch Anda. Misalnya Anda bisa mendapatkan dan mengurutkan dokumen konversi Anda berdasarkan tanggal pembuatan dan memproses dokumen yang sesuai. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) memungkinkan Anda mengakses metadata XMP file CGM. Untuk mendapatkan metadata file CGM, Anda dapat membuat objek [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) dan membuka file input CGM. Setelah itu, Anda bisa mendapatkan metadata file menggunakan properti [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Buat File POT Hanya Baca melalui .NET" %}}
Dengan menggunakan [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API, Anda dapat lebih menyempurnakan fitur aplikasi konversi Anda. Salah satu fiturnya adalah membuat file output Anda hanya baca untuk meningkatkan keamanan. API memungkinkan Anda menyetel file POT ke Hanya-Baca, yang berarti pengguna (setelah mereka membuka presentasi) melihat rekomendasi Hanya-Baca. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.pot", SaveFormat.Pot);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Mengubah File CGM ke POT Secara Terprogram : Contoh Penggunaan" %}}
Pengubahan berkas Metafile Grafik Komputer (CGM) ke format Tekst Tua Biasa (POT) diperlukan untuk mengaktifkan potensi penuh dalam kemampuan visualisasi dan analisis data Anda. Pengubahan ini memungkinkan Anda:

**Apa yang bisa dilakukan:**

*   **Analisis Data Sejarah**: Mengubah berkas CGM untuk menganalisis data sejarah, mengiketahui trend, dan mengidentifikasi pola dalam data.
*   **Penghasilan Dokumentasi Teknik**: Menggunakan format POT untuk membuat dokumen teknis dari grafik yang rumit dalam berkas CGM, sehingga lebih mudah dipahami oleh developer dan insinyur untuk memahami dan menerapkan desain.
*   **Implementasi Fitur Aksesibilitas**: Mengubah berkas CGM untuk membuat fitur aksesibilitas seperti deskripsi gambar dan teks alternatif untuk elemen visual, sehingga lebih mudah digunakan oleh pengguna dengan disabilitas.
*   **Kreasi dan Desain Seni**: Menggunakan format POT untuk mengambil elemen desain spesifik dari berkas CGM, memungkinkan pelukis dan desainer untuk mengembangkan ulangnya dalam proyek kreatif baru.
*   **Penelitian dan Pengembangan**: Mengubah berkas CGM untuk visualisasi data penelitian, simulasi eksperimen, dan validasi hipotesis, sehingga ilmuwan dan peneliti dapat mendapatkan pemahaman yang lebih dalam tentang pekerjaan mereka.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}