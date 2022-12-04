---
title: Konversikan MOBI ke FODS menggunakan Python
description: Konversi MOBI ke FODS dalam aplikasi Python Anda tanpa menggunakan Microsoft Word atau Excel 

family: total
platformtag: Python
feature: conversion
informat: MOBI
outformat: FODS
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konversikan MOBI ke FODS melalui Python" h2="Konversi MOBI ke FODS di aplikasi Python Anda tanpa menginstal Microsoft Word<sup>&reg;</sup> atau Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

Untuk pengembang Python, yang mencoba menambahkan fitur konversi MOBI ke FODS di dalam aplikasi. API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) dapat membantu mengotomatiskan proses konversi. Ini adalah paket lengkap dari berbagai API yang menangani berbagai format.

Ini terutama dalam dua langkah. Pertama gunakan API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) untuk mengonversi file MOBI ke HTML. Setelah itu dengan menggunakan Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), simpan HTML yang telah dibuat ke dalam format Microsoft Excel yang diinginkan. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cara Mengonversi MOBI ke FODS dengan Python" %}}
- **Langkah 1** Buka file MOBI sumber menggunakan kelas [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Simpan file MOBI ke HTML dengan menggunakan metode [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) dengan memberikan nama file dan jalur direktori yang diinginkan
-  **Langkah 2** Muat file HTML dengan instance kelas Workbook dengan file dan LoadOptions sebagai parameter
-  Panggil metode `save` sambil menentukan jalur file FODS keluaran. Jadi file MOBI Anda dikonversi ke FODS di jalur yang ditentukan

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}

- Untuk konversi MOBI ke FODS, diperlukan Python 3.5 atau lebih baru
- Referensi API dalam proyek langsung dari PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) dan [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Atau gunakan perintah pip berikut ```pip install aspose.words``` dan ```pip install aspose-cells-python``` 
-  Selain itu, OS berbasis Microsoft Windows atau Linux (lihat lebih lanjut untuk [Words](https://docs.aspose.com/words/python-net/system-requirements/) dan [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation)) dan untuk Linux periksa persyaratan tambahan untuk gcc dan libpython dan ikuti [petunjuk langkah demi langkah](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Simpan MOBI ke HTML dengan Python - Langkah 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Simpan HTML Ke FODS dengan Python - Langkah 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}