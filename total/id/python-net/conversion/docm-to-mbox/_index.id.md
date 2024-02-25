---
title: Konversi DOCM ke MBOX dengan Python
description: Simpan DOCM ke MBOX dalam aplikasi Python tanpa menggunakan Microsoft Word atau Outlook

family: total
platformtag: Python
feature: conversion
informat: DOCM
outformat: MBOX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konversi DOCM ke MBOX menggunakan Python" h2="Konversi DOCM ke MBOX di Aplikasi Python Anda tanpa menginstal Microsoft Word<sup>&reg;</sup> atau Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}

Untuk pengembang Python, siapa yang mencoba menambahkan fitur konversi DOCM ke MBOX dalam aplikasi? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API dapat membantu mengotomatiskan proses konversi. Ini adalah paket lengkap dari berbagai API yang menangani berbagai format termasuk format Email, Gambar, dan Microsoft Word. API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) dan [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) yang merupakan bagian dari paket [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) memudahkan konversi ini menggunakan Python. Ini adalah proses dua langkah, pertama-tama muat file DOCM dan render ke HTML melalui [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/). Kedua, muat HTML yang dikonversi menggunakan [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) dan simpan ke dalam format MBOX.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cara Mengonversi DOCM ke MBOX dengan Python" %}}

- Buka file DOCM sumber menggunakan kelas [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Panggil metode `save` saat menentukan jalur file HTML keluaran dan opsi Simpan HTML yang relevan sebagai parameter. Jadi file DOCM Anda dikonversi ke HTML di jalur yang ditentukan
- Sekarang Muat file HTML yang disimpan menggunakan MailMessage.load
- Panggil metode simpan dengan jalur file yang relevan. Jadi akhirnya DOCM dikonversi

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}

- Untuk konversi DOCM ke MBOX, Python 3.5 atau lebih baru diperlukan
- Referensi API dalam proyek langsung dari PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) dan [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Atau gunakan perintah pip berikut ```pip install aspose.words``` dan ```pip install Aspose.Email-for-Python-via-NET``` 
- Selain itu, OS berbasis Microsoft Windows atau Linux (lihat lebih lanjut untuk [Words](https://docs.aspose.com/words/python-net/system-requirements/) dan [Email](https://docs.aspose.com/email/python-net/system-requirements/)) dan untuk Linux periksa persyaratan tambahan untuk gcc dan libpython dan ikuti petunjuk langkah demi langkah [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Simpan DOCM Ke MBOX dengan Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}