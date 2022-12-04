---
title: Konversikan DOTX ke XLS menggunakan Python
description: Konversi DOTX ke XLS dalam aplikasi Python Anda tanpa menggunakan Microsoft Word atau Excel 

family: total
platformtag: Python
feature: conversion
informat: DOTX
outformat: XLS
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konversikan DOTX ke XLS melalui Python" h2="Konversi DOTX ke XLS di aplikasi Python Anda tanpa menginstal Microsoft Word<sup>&reg;</sup> atau Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

Untuk pengembang Python, yang mencoba menambahkan fitur konversi DOTX ke XLS di dalam aplikasi. API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) dapat membantu mengotomatiskan proses konversi. Ini adalah paket lengkap dari berbagai API yang menangani berbagai format.

Ini terutama dalam dua langkah. Pertama gunakan API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) untuk mengonversi file DOTX ke HTML. Setelah itu dengan menggunakan Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), simpan HTML yang telah dibuat ke dalam format Microsoft Excel yang diinginkan. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cara Mengonversi DOTX ke XLS dengan Python" %}}
- **Langkah 1** Buka file DOTX sumber menggunakan kelas [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Simpan file DOTX ke HTML dengan menggunakan metode [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) dengan memberikan nama file dan jalur direktori yang diinginkan
-  **Langkah 2** Muat file HTML dengan instance kelas Workbook dengan file dan LoadOptions sebagai parameter
-  Panggil metode `save` sambil menentukan jalur file XLS keluaran. Jadi file DOTX Anda dikonversi ke XLS di jalur yang ditentukan

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}

- Untuk konversi DOTX ke XLS, diperlukan Python 3.5 atau lebih baru
- Referensi API dalam proyek langsung dari PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) dan [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Atau gunakan perintah pip berikut ```pip install aspose.words``` dan ```pip install aspose-cells-python``` 
-  Selain itu, OS berbasis Microsoft Windows atau Linux (lihat lebih lanjut untuk [Words](https://docs.aspose.com/words/python-net/system-requirements/) dan [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation)) dan untuk Linux periksa persyaratan tambahan untuk gcc dan libpython dan ikuti [petunjuk langkah demi langkah](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Simpan DOTX ke HTML dengan Python - Langkah 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Simpan HTML Ke XLS dengan Python - Langkah 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}