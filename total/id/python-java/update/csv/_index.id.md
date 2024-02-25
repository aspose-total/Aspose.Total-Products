---
title: Perbarui Mengajukan CSV Menggunakan Python
description: Memodifikasi dokumen CSV dalam aplikasi Python tanpa menggunakan Microsoft Excel. 

family: total
platformtag: Python
feature: update
informat: CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Perbarui Mengajukan CSV Melalui Python" h2="Ubah spreadsheet CSV melalui Aplikasi Python Anda tanpa menginstal Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Untuk pengembang, siapa yang mencoba memperbarui file CSV melalui aplikasi Python? [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API dapat membantu mengotomatiskan proses pembaruan. Ini adalah paket lengkap dari berbagai API yang menangani berbagai format termasuk file Microsoft Excel. ASPOSE.CELL API yang merupakan bagian dari paket [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) memudahkan proses modifikasi ini. Di bawah ini adalah proses pemutakhiran dokumen CSV.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cara Memperbarui Mengajukan CSV dengan Python" %}}

- Buat objek kelas [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) baru yang memiliki file CSV sumber sebagai parameter
- Akses Lembar Kerja yang relevan menggunakan metode [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets)
- Masukkan data baru di sel yang diakses menggunakan metode [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)
- Simpan file sebagai file .csv menggunakan metode save() dengan melewatkan file dengan path sebagai parameter

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Modifikasi" %}}

- Untuk modifikasi CSV, referensi API dalam proyek langsung dari PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Atau gunakan perintah pip berikut ```pip install aspose.cells``` 
- Selain itu, Unduh paket API dari bagian [Unduhan](https://releases.aspose.com/cells/python-java)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kode - Perbarui Mengajukan CSV dengan Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}