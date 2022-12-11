---
title: Konversikan XLTX ke DOCX menggunakan Python
description: Konversi XLTX ke DOCX di aplikasi Python Anda tanpa menggunakan Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: XLTX
outformat: DOCX
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konversikan XLTX ke DOCX melalui Python" h2="Konversi XLTX ke DOCX di aplikasi Python Anda tanpa menginstal Microsoft Excel<sup>&reg;</sup> atau Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

Untuk pengembang Python, yang mencoba menambahkan fitur konversi XLTX ke DOCX di dalam aplikasi. API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) dapat membantu mengotomatiskan proses konversi. Ini adalah paket lengkap dari berbagai API yang menangani berbagai format termasuk file XLTX dan DOCX.

Ini terutama dalam dua langkah. Pertama gunakan API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) untuk mengonversi file XLTX ke HTML. Setelah itu dengan menggunakan Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/), simpan HTML yang telah dibuat ke dalam format Microsoft Word yang diinginkan. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cara Mengonversi XLTX ke DOCX dengan Python" %}}
- **Langkah 1** Buka file XLTX sumber menggunakan kelas Workbook
- Simpan file XLTX ke HTML dengan menggunakan metode save(file, SaveFormat.HTML) dengan memberikan nama file dan jalur direktori yang diinginkan
-  **Langkah 2** Muat file HTML dengan instance kelas [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
-  Panggil metode `save` sambil menentukan jalur file DOCX keluaran. Jadi file XLTX Anda dikonversi ke DOCX di jalur yang ditentukan

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}

- Untuk konversi XLTX ke DOCX, diperlukan Python 3.5 atau lebih baru
- Referensi API dalam proyek langsung dari PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) dan [Aspose.Words](https://pypi.org/project/aspose-words/))
-  Atau gunakan perintah pip berikut ```pip install aspose-cells-python``` dan ```pip install aspose.words```
-  Selain itu, OS berbasis Microsoft Windows atau Linux (lihat lebih lanjut untuk [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) dan [Words](https://docs.aspose.com/words/python-net/system-requirements/)) dan untuk Linux periksa persyaratan tambahan untuk gcc dan libpython dan ikuti [petunjuk langkah demi langkah](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Simpan XLTX ke HTML dengan Python - Langkah 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Simpan HTML Ke DOCX dengan Python - Langkah 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}