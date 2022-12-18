---
title: Konversikan PPTX ke XLSM menggunakan Python
description: Konversi PPTX ke XLSM di aplikasi Python Anda tanpa menggunakan Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: PPTX
outformat: XLSM
otherformats: Excel XLS XLSX XLSB XLTX XLTM XLSM CSV TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konversikan PPTX ke XLSM melalui Python" h2="Konversi PPTX ke XLSM di aplikasi Python Anda tanpa menginstal Microsoft PowerPoint<sup>&reg;</sup> atau Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

Untuk pengembang Python, yang mencoba menambahkan fitur konversi PPTX ke XLSM di dalam aplikasi. API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) dapat membantu mengotomatiskan proses konversi. Ini adalah paket lengkap dari berbagai API yang menangani berbagai format termasuk file PPTX dan XLSM.

Ini terutama dalam dua langkah. Pertama gunakan API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) untuk mengonversi file PPTX ke HTML. Setelah itu dengan menggunakan Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), simpan HTML yang telah dibuat ke dalam format Microsoft Excel yang diinginkan. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cara Mengonversi PPTX ke XLSM dengan Python" %}}
- **Langkah 1** Gunakan instance kelas [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) untuk membuka file PPTX sumber 
- Simpan file PPTX ke HTML dengan menggunakan metode [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) dengan memberikan nama file dan jalur direktori yang diinginkan
-  **Langkah 2** Muat file HTML dengan instance kelas Workbook
-  Panggil metode `save` sambil menentukan jalur file XLSM keluaran. Jadi file PPTX Anda dikonversi ke XLSM di jalur yang ditentukan

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}

- Untuk konversi PPTX ke XLSM, diperlukan Python 3.5 atau lebih baru
- Referensi API dalam proyek langsung dari PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) dan [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Atau gunakan perintah pip berikut ```pip install aspose.slides``` dan ```pip install aspose-cells-python```
-  Selain itu, OS berbasis Microsoft Windows atau Linux (lihat lebih lanjut untuk [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) dan [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Simpan PPTX ke HTML dengan Python - Langkah 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "convert-microsoft-powerpoint-presentations-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Simpan HTML Ke XLSM dengan Python - Langkah 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "html-documents-to-excel-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}