---
title: Perbarui File Excel menggunakan C++ 

description: Edit dokumen Microsoft Excel XLSX, XLS, CSV tanpa menginstal Microsoft Office dengan aplikasi berbasis C++.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Perbarui Dokumen Excel melalui C++" h2="Ubah file Microsoft Excel XLSX, XLS dalam aplikasi berbasis C++ tanpa menginstal Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Sudah umum bagi organisasi untuk memperbarui data mereka, disimpan dalam file excel seperti data siswa, catatan pasien dan daftar item gudang dll melalui perangkat lunak perusahaan. API [Aspose.Total for C++](https://products.aspose.com/total/cpp/) menyediakan fungsionalitas untuk memodifikasi spreadsheet menggunakan perangkat lunak. Pemrogram dapat meningkatkan perangkat lunak dengan kemampuan modifikasi hanya dengan menulis beberapa baris kode API. API [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) yang merupakan bagian dari paket [Aspose.Total for C++](https://products.aspose.com/total/cpp/) memudahkan proses modifikasi ini. Di bawah ini adalah proses pemutakhiran dokumen Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Perbarui Dokumen Excel menggunakan C++" %}}

Menggunakan [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API, muat dokumen sumber menggunakan [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8). Akses [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) menggunakan GetIWorksheets()->GetObjectByIndex(0) dan sel yang diperlukan menggunakan GetICells()->GetObjectByIndex. Dengan menggunakan metode PutValue, ubah konten di sel yang diakses. Terakhir aktifkan metode save() untuk menyimpan dokumen.

{{% blocks/products/pf/feature-page-code h3="Kode C++ - Perbarui Dokumen Excel" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Memperbarui">}}