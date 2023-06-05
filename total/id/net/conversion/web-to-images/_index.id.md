---
title: Konversi Halaman Web HTML ke Gambar menggunakan C#
description: Kikis halaman web situs web dan ekspor HTML ke Gambar. Kembangkan aplikasi .NET untuk mengikis data situs web menjadi JPEG, PNG, GIF, BMP, dll. 
family: total
platformtag: net
feature: conversion
informat: WEB
outformat: IMAGE
otherformats: WORD EXCEL POWERPOINT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konversi Halaman Web ke Gambar melalui C#" h2="Ekstrak data situs web dari halaman web HTML. Ubah HTML menjadi gambar JPG, GIF, PNG, BMP dalam aplikasi .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">Mengapa Mengonversi Halaman Web ke Gambar?</h2>
<p>Mengonversi halaman web menjadi gambar dapat bermanfaat dalam berbagai situasi. Ini adalah persyaratan umum untuk banyak aplikasi. Dalam beberapa skenario, seluruh halaman web perlu diambil sebagai gambar, termasuk bagian yang tidak terlihat di layar. Ini dapat berguna untuk menghasilkan pratinjau situs web, menangkap tanda terima dan faktur, atau mengarsipkan halaman web untuk tujuan hukum. Ini dapat digunakan untuk membuat tangkapan layar halaman web untuk tujuan dokumentasi atau pengujian. Itu juga dapat digunakan untuk membuat thumbnail atau pratinjau halaman web untuk digunakan dalam hasil pencarian atau galeri gambar. Apakah Anda sedang membangun aplikasi desktop atau aplikasi web, ada banyak opsi yang tersedia untuk mengonversi halaman web menjadi gambar menggunakan C#.</p><br />

<p>Mengonversi halaman web menjadi gambar menggunakan C# dapat memberikan beberapa manfaat, antara lain:</p><br />
<ul>
<li>Aksesibilitas yang ditingkatkan: Gambar dapat lebih mudah dibaca dan dipahami oleh penyandang disabilitas penglihatan atau disabilitas lainnya.</li>
<li>Peningkatan portabilitas: Gambar dapat dengan mudah dibagikan atau disematkan di dokumen atau aplikasi lain.</li>
</ul>
<p>Mengonversi halaman web menjadi gambar menggunakan C# juga dapat menghadirkan beberapa tantangan, termasuk:</p><br />
<ul>
<li>Dukungan format terbatas: Beberapa API atau alat mungkin tidak mendukung semua format gambar atau mungkin memiliki batasan pada ukuran atau resolusi gambar keluaran.</li>
<li>Masalah kompatibilitas: Beberapa halaman web mungkin tidak ditampilkan dengan benar di semua browser atau mungkin memerlukan pengaturan atau plugin khusus untuk ditampilkan dengan benar.</li>
</ul>
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Bagaimana Mengonversi Halaman Web ke Gambar menggunakan C#?" %}}
Untuk mengonversi halaman web menjadi gambar menggunakan C#, Anda dapat menggunakan Aspose.HTML untuk .NET API yang menyediakan fungsionalitas ini untuk mengonversi halaman HTML ke format gambar, termasuk JPEG, PNG, dan TIFF.</p>

1. Muat dokumen HTML menggunakan salah satu konstruktor yang tersedia di [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/). Anda dapat memuat HTML dari file, kode HTML, aliran, atau URL.
2. Buat instance baru dari [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) dan atur properti ImageFormat ke JPEG. Secara default, properti Format diatur ke PNG.
3. Memanfaatkan [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) metode dari kelas Converter untuk menyimpan dokumen HTML sebagai file JPEG. Anda perlu menyediakan HTMLDocument, ImageSaveOptions, dan jalur file keluaran sebagai parameter untuk metode ConvertHTML().
4. File JPEG yang dihasilkan akan disimpan ke jalur file yang ditentukan.
 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Memo Web dan Persyaratan Konversi Gambar" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau instal langsung dari Package Manager Console Visual Studio.

Dua [Aspose.Total for .NET](https://products.aspose.com/total/net/) API anak, [Aspose.HTML for .NET](https://products.aspose.com/html/net/) akan terintegrasi.

Alternatifnya, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "convert-web-pages-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}