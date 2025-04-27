---
title: Ekspor CGM ke POTM melalui C# API
description: .NET API untuk Mengonversi CGM ke POTM tanpa menggunakan Microsoft Word
url_ignore: /id/net/conversion/cgm-to-potm/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: POTM
otherformats: POWERPOINT PPSX SWF POT POTX PPSM PPTM PPS PPT OTP XAML POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Render CGM ke POTM melalui .NET" h2=".NET API untuk Mengekspor CGM ke POTM di Windows, macOS, dan Linux tanpa menggunakan Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Menggunakan paket API Otomatisasi Format File yang andal [Aspose.Total for .NET](https://products.aspose.com/total/net/), Anda dapat dengan mudah Render CGM ke POTM dalam dua langkah sederhana. Dengan menggunakan API Pemrosesan PDF [Aspose.PDF untuk .NET](https://products.aspose.com/pdf/net/), Anda dapat mengubah format file CGM menjadi PPTX. Setelah itu, dengan menggunakan Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), Anda dapat mengonversi PPTX ke POTM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API untuk Mengonversi CGM ke POTM" %}}
1. Buka file CGM menggunakan kelas [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konversi CGM ke PPTX dengan menggunakan metode [Simpan](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Muat file PPTX dengan menggunakan kelas [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Simpan dokumen ke format POTM menggunakan metode [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) dan setel `Potm` sebagai SaveFormat
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
Saat mengonversi CGM ke POTM, Anda mungkin memerlukan informasi metadata XMP tambahan untuk memprioritaskan proses konversi batch Anda. Misalnya Anda bisa mendapatkan dan mengurutkan dokumen konversi Anda berdasarkan tanggal pembuatan dan memproses dokumen yang sesuai. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) memungkinkan Anda mengakses metadata XMP file CGM. Untuk mendapatkan metadata file CGM, Anda dapat membuat objek [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) dan membuka file input CGM. Setelah itu, Anda bisa mendapatkan metadata file menggunakan properti [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Buat File POTM Hanya Baca melalui .NET" %}}
Dengan menggunakan [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API, Anda dapat lebih menyempurnakan fitur aplikasi konversi Anda. Salah satu fiturnya adalah membuat file output Anda hanya baca untuk meningkatkan keamanan. API memungkinkan Anda menyetel file POTM ke Hanya-Baca, yang berarti pengguna (setelah mereka membuka presentasi) melihat rekomendasi Hanya-Baca. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.potm", SaveFormat.Potm);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Mengubah File CGM ke POTM Secara Terprogram : Contoh Penggunaan" %}}
Konversi berkas CGM ke format POTM (Microsoft Office Template) diperlukan untuk memungkinkan penggunaan maksimal kemampuan desain dan layout presentasi Anda. Konversi ini memungkinkan Anda:

**Apa yang bisa dilakukan dengan format POTM:**

*   **Konsistensi Brand**: Konversi berkas CGM untuk mempertahankan konsistensi brand dalam presentasi, sehingga semua elemen visual sesuai dengan identitas korporat.
*   **Pengembangan Template**: Manfaatkan template POTM untuk membuat template yang dapat di-reuse dan disesuaikan, sehingga lebih mudah menghasilkan konten secara konsisten.
*   **Efisiensi Desain**: Konversi berkas CGM untuk mempercepat proses desain presentasi, sehingga Anda bisa fokus pada pembuatan konten daripada pekerjaan yang membosankan seperti formatting.
*   **Tool Kolaborasi**: Manfaatkan format POTM untuk membuat alat kolaboratif yang memungkinkan umpan balasan waktu nyata dan penyuntingan bersama antara rekan kerja.
*   **Standar dan Komplian**: Konversi berkas CGM untuk memenuhi standar industri dan persyaratan regulatori, sehingga semua presentasi sesuai dengan pedoman tertentu.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}