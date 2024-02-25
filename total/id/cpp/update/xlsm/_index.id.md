---
title: Perbarui Mengajukan XLSM menggunakan C++
description: Modifikasi dokumen XLSM dalam aplikasi C++ tanpa menggunakan Microsoft Excel.
family: total
platformtag: C++
feature: update
informat: XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Perbarui Mengajukan XLSM melalui C++" h2="Ubah spreadsheet XLSM melalui aplikasi berbasis C++ tanpa menginstal Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Untuk seorang programmer, yang mencoba memperbarui file XLSM dalam aplikasi C++, API [Aspose.Total for C++](https://products.aspose.com/total/cpp/) dapat membantu mengotomatiskan proses pemutakhiran. Ini adalah paket lengkap dari berbagai pustaka C++ yang menangani berbagai format termasuk dokumen Microsoft Excel. API [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) yang merupakan bagian dari paket [Aspose.Total for C++](https://products.aspose.com/total/cpp/) memudahkan proses modifikasi ini. Proses memperbarui dokumen XLSM sederhana dengan terlebih dahulu mengakses sheet dan kemudian memperbarui nilai sel di excel menggunakan C++.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cara Memperbarui Mengajukan XLSM di C++" %}}

- Muat file XLSM menggunakan [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8)
- Akses [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) yang relevan menggunakan GetIWorksheets()->GetObjectByIndex(0) dan sel yang relevan menggunakan GetICells()->GetObjectByIndex
- Masukkan data baru ke dalam sel yang diakses menggunakan metode PutValue
- Simpan file sebagai file .xlsm menggunakan metode Save dengan meneruskan file dengan path sebagai parameternya

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Modifikasi" %}}

- Untuk modifikasi XLSM, berikut [Persyaratan sistem](https://docs.aspose.com/cells/cpp/system-requirements/) untuk sistem Windows dan Linux 
- Instal dari baris perintah sebagai ```nuget install Aspose.Total.Cpp```
- Atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total.Cpp```
- Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [Download](https://releases.aspose.com/cells/cpp)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kode - Perbarui Mengajukan XLSM di C++" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}