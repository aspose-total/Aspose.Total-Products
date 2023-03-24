---
title: JSON Formatını C++ ile WORD'ye Dönüştür
description: C++ API t0 Microsoft Word kullanmadan JSON'u WORD'ye ayrıştırma

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: DOC
otherformats: PS PCL DOCM WORDML FLATOPC OTT ODT MOBI CHM DOC DOT DOTX EPUB RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="JSON Formatını C++ ile WORD'ye Dönüştür" h2="Microsoft<sup>&reg;</sup> Word kullanmadan JSON'u C++ uygulamaları içinde WORD'ye ayrıştırın" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) kullanarak, iki basit adımda C++ uygulamalarınızda JSON'u WORD'ye ayrıştırabilirsiniz. İlk olarak, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) kullanarak JSON'u PDF'ye aktarabilirsiniz. Bundan sonra, [Aspose.Words for C++](https://products.aspose.com/words/cppp/) kullanarak PDF'yi WORD'ye dönüştürebilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="JSON Formatını C++'da WORD'ye Dönüştür" %}}
1. Yeni bir [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) nesnesi oluşturun ve dosyadan geçerli JSON verilerini okuyun
2. [Kaydet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) yöntemini kullanarak JSON'u PDF olarak kaydedin
3. [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) sınıfını kullanarak PDF belgesi yükleyin
4. [Kaydet](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) yöntemini kullanarak dokümanı WORD formatına kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Visual Studio'nun Paket Yönetici Konsolu aracılığıyla ```Install-Package Aspose.Total.Cpp``` ile yükleyin.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://releases.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Düzeni Ayarla ve JSON Formatını C++'da WORD'ye Dönüştür" %}}
JSON'u WORD'ye ayrıştırırken, JSON'u [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) sınıfıyla yükleyerek satır ve sütunların boyutunu da ayarlayabilirsiniz. Çalışma sayfasındaki tüm satırlar için aynı satır yüksekliğini ayarlamanız gerekiyorsa, bunu [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f) kullanarak yapabilirsiniz. ) [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell) koleksiyonunun yöntemi. Benzer şekilde, çalışma sayfasındaki tüm sütunlar için aynı sütun genişliğini ayarlamak için ICells koleksiyonunun [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) yöntemini kullanın.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++'da Filigran ile JSON Formatını WORD'ye Dönüştürme" %}}
API'yi kullanarak JSON'u WORD'ye filigranla ayrıştırabilirsiniz. WORD belgenize filigran eklemek için önce JSON'u PDF'ye dönüştürebilir ve ona bir filigran ekleyebilirsiniz. Filigran eklemek için yeni oluşturulan PDF dosyasını [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) sınıfını kullanarak yükleyin, metin filigranı için farklı özellikler ayarlayın,
SetText yöntemini çağırın ve filigran metnini ve TextWatermarkOptions nesnesini iletin. Filigranı ekledikten sonra belgeyi WORD'ye kaydedebilirsiniz.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}