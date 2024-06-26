---
title: Konversi XLSB ke Gambar menggunakan Python
description: Konversi XLSB ke gambar TIFF BMP PNG JPEG GIF EMF SVG dalam aplikasi Python Anda tanpa menggunakan Microsoft Excel 

family: total
platformtag: Python
feature: conversion
informat: XLSB
outformat: Image
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konversi XLSB ke Gambar Melalui Python" h2="Konversi gambar XLSB ke JPG, TIFF, BMP, PNG, GIF di Aplikasi Python Anda tanpa menginstal Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Untuk pengembang Python, yang mencoba menambahkan fitur konversi Gambar XLSB ke PNG, BMP, TIFF, JPEG dan GIF dalam aplikasi. Karena terkadang diperlukan untuk menyematkan spreadsheet Excel di web atau aplikasi desktop. Dalam kasus seperti itu, mengekspor spreadsheet ke gambar adalah satu-satunya pilihan. [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API dapat membantu mengekspor file Excel ke gambar serta mengotomatiskan proses konversi. Ini adalah paket lengkap dari berbagai API yang menangani berbagai format termasuk format Microsoft Excel melalui API [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) turunannya. Saat ini Python Excel to Image Converter API mendukung konversi File Excel ke EMF, WMF, JPEG, PNG, BMP, GIF, TIFF, SVG, GLTF, PICT, SVM dan Office Kompatibel EMF atau periksa [Format](https://docs.aspose.com/cells/python-java/supported-file-formats/) yang didukung. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Bagaimana Mengonversi XLSB ke Gambar dengan Python" %}}

- Buat objek kelas [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) untuk memuat file XLSB
- Gunakan kelas [ImageOrPrintOptions](https://reference.aspose.com/cells/python-java/asposecells.api/ImageOrPrintOptions) dan tentukan opsi gambar keluaran yang relevan
- Dapatkan akses lembar kerja untuk konversi menggunakan metode [Workbook.getWorksheets().get(index)](https://reference.aspose.com//cells/python-java/asposecells.api/worksheetcollection#Item%20(int))
- Create the instance of [SheetRender](https://reference.aspose.com/cells/python/asposecells.api/SheetRender) class object and initialize it with Worksheet and ImageOrPrintOptions objects
- Simpan semua halaman lembar kerja sebagai gambar menggunakan metode [SheetRender.toImage(pageIndex, fileName)](https://reference.aspose.com//cells/python-java/asposecells.api/sheetrender#toImage(int,%20java.lang.String)). Sekarang file XLSB dikonversi ke Gambar di jalur yang ditentukan

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}

- Untuk konversi XLSB ke Gambar (JPG, PNG, GIF, BMP, TIFF), API referensi dalam proyek langsung dari PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Atau gunakan perintah pip berikut ```pip install aspose.cells``` 
- Selain itu, Unduh paket API dari bagian [Unduhan](https://releases.aspose.com/cells/python-java) 
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Konversi XLSB Ke Gambar melalui Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "5d33fa768a61d24704a7350432266781" "convert-excel-to-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}