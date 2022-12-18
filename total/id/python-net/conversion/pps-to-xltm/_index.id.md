---
title: Konversikan PPS ke XLTM menggunakan Python
description: Konversi PPS ke XLTM di aplikasi Python Anda tanpa menggunakan Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: PPS
outformat: XLTM
otherformats: Excel XLS XLSX XLSB XLTX XLTM XLSM CSV TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konversikan PPS ke XLTM melalui Python" h2="Konversi PPS ke XLTM di aplikasi Python Anda tanpa menginstal Microsoft PowerPoint<sup>&reg;</sup> atau Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

Untuk pengembang Python, yang mencoba menambahkan fitur konversi PPS ke XLTM di dalam aplikasi. API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) dapat membantu mengotomatiskan proses konversi. Ini adalah paket lengkap dari berbagai API yang menangani berbagai format termasuk file PPS dan XLTM.

Ini terutama dalam dua langkah. Pertama gunakan API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) untuk mengonversi file PPS ke HTML. Setelah itu dengan menggunakan Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), simpan HTML yang telah dibuat ke dalam format Microsoft Excel yang diinginkan. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cara Mengonversi PPS ke XLTM dengan Python" %}}
- **Langkah 1** Gunakan instance kelas [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) untuk membuka file PPS sumber 
- Simpan file PPS ke HTML dengan menggunakan metode [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) dengan memberikan nama file dan jalur direktori yang diinginkan
-  **Langkah 2** Muat file HTML dengan instance kelas Workbook
-  Panggil metode `save` sambil menentukan jalur file XLTM keluaran. Jadi file PPS Anda dikonversi ke XLTM di jalur yang ditentukan

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}

- Untuk konversi PPS ke XLTM, diperlukan Python 3.5 atau lebih baru
- Referensi API dalam proyek langsung dari PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) dan [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Atau gunakan perintah pip berikut ```pip install aspose.slides``` dan ```pip install aspose-cells-python```
-  Selain itu, OS berbasis Microsoft Windows atau Linux (lihat lebih lanjut untuk [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) dan [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Simpan PPS ke HTML dengan Python - Langkah 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "convert-microsoft-powerpoint-presentations-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Simpan HTML Ke XLTM dengan Python - Langkah 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "html-documents-to-excel-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}