---
title: Perbarui File Excel menggunakan .NET 

description: Edit dokumen Microsoft Excel XLSX, XLS, CSV tanpa menginstal Microsoft Office dengan aplikasi berbasis C# .NET.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Perbarui Dokumen Excel melalui .NET" h2="Ubah file Microsoft Excel XLSX, XLS dalam aplikasi berbasis .NET tanpa menginstal Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Sudah umum bagi organisasi untuk memperbarui data mereka, disimpan dalam file excel seperti data siswa, catatan pasien dan daftar item gudang dll melalui perangkat lunak perusahaan. API [Aspose.Total for .NET](https://products.aspose.com/total/net/) menyediakan fungsionalitas untuk memodifikasi spreadsheet menggunakan perangkat lunak. Pemrogram dapat meningkatkan perangkat lunak dengan kemampuan modifikasi hanya dengan menulis beberapa baris kode API. API [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) yang merupakan bagian dari paket [Aspose.Total for .NET](https://products.aspose.com/total/net/) memudahkan proses modifikasi ini. Di bawah ini adalah proses pemutakhiran dokumen Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Perbarui Dokumen Excel menggunakan .NET" %}}

[Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API menyediakan kelas Workbook yang menangani pemuatan spreadsheet Excel. Prosesnya sederhana. Buat objek [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook/) dengan menyediakan file sumber sebagai parameter. Akses Lembar Kerja yang relevan dengan memberikan indeksnya menggunakan metode [Worksheets[0].Cells[column]](https://reference.aspose.com/cells/net/aspose.cells/worksheet/cells/). Gunakan metode [PutValue(data)](https://reference.aspose.com/cells/net/aspose.cells/cell/putvalue/) untuk memodifikasi konten dalam sel yang diakses dan terakhir panggil metode save() untuk menyimpan dokumen.

{{% blocks/products/pf/feature-page-code h3="Kode .NET - Perbarui Dokumen Excel" %}}

{{< gist "aspose-com-gists" "800f8b626c3129d4682bc58338b93ecc" "update-excel-file-using-net.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Memperbarui">}}