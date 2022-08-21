---
title: WORD'yi C++'da EXCEL'ye dönüştürün
description: Microsoft Word veya Microsoft Excel kullanmadan WORD'yi EXCEL'ye dönüştürmek için C++ API
url: /tr/cpp/conversion/word-to-excel/
family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: XLSX
otherformats: DIF ODS XLS XLTM TSV CSV XLSM XLSB XLAM XLT FODS XLTX SXC XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="WORD'yi EXCEL'ye Dönüştürmek için C++ API" h2="Microsoft<sup>&reg;</sup> Word veya Microsoft<sup>&reg;</sup> Excel kullanmadan WORD'yi C++ aracılığıyla EXCEL'ye aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
WORD'den EXCEL'ye dönüştürme özelliğini C++ uygulamalarınıza kolayca dahil edebilirsiniz. Zengin özelliklere sahip, güçlü ve kullanımı kolay belge işleme ve dönüştürme API'sini [Aspose.Words for C++](https://products.aspose.com/words/cpp/) kullanarak WORD'yi HTML'ye aktarabilirsiniz. Bundan sonra, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) kullanarak HTML'yi EXCEL'ye dönüştürebilirsiniz. Her iki API de [Aspose.Total for C++](https://products.aspose.com/total/cpp/) paketi kapsamında gelir. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="WORD'yi EXCEL'ye Dönüştürmek için C++ API" %}}
1. [Document](https://reference.aspose.com/words/cpp/class/aspose.words.wordument) sınıf referansını kullanarak WORD dosyasını açın
2. [Kaydet](https://reference.aspose.com/words/cpp/class/aspose.words.wordument#save_string_saveformat) üye işlevini kullanarak WORD'u HTML'ye dönüştürün
3. [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) sınıf referansını kullanarak HTML belgesini yükleyin
4. [Kaydet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) üye işlevini kullanarak belgeyi EXCEL biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://downloads.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="WORD Belge Özelliklerine C++ ile Erişin" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) ayrıca WORD dosyasının belge özelliklerine erişmenizi sağlar ve dönüştürme işleminden önce bilinçli bir karar vermenizi sağlar. Belge özelliklerine erişmek için yerleşik özellikleri ve [CustomWordumentProperties]( elde etmek için [BuiltInWordumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_wordument_properties) kullanabilirsiniz. referans.aspose.com/words/cpp/class/aspose.words.properties.custom_wordument_properties) özel özellikler elde etmek için. Aşağıdaki kod örneği, bir belgedeki tüm yerleşik ve özel özelliklerin nasıl numaralandırılacağını gösterir.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-wordument-properties.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EXCEL Dosyasını C++ ile Akışa Kaydet" %}}
WORD'yi EXCEL'ye dönüştürdükten sonra, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), belgenizi akışa kaydetmenizi sağlar. Dosyaları bir akışa kaydetmek için bir MemoryStream veya FileStream nesnesi oluşturun ve [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) öğesini çağırarak dosyayı bu akış nesnesine kaydedin. nesnenin [Kaydet](https://reference.aspose.comyöntemi. [Kaydet](https://reference.aspose.com) çağrılırken [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) numaralandırmasını kullanarak istediğiniz dosya biçimini belirtin yöntemi.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/word-to-dif/" name="WORD İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/word-to-ods/" name="WORD İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/word-to-xls/" name="WORD İle XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/word-to-xltm/" name="WORD İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/word-to-tsv/" name="WORD İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/word-to-excel/" name="WORD İle EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/word-to-xlsm/" name="WORD İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/word-to-xlsb/" name="WORD İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/word-to-xlam/" name="WORD İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/word-to-xlt/" name="WORD İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/word-to-fods/" name="WORD İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/word-to-xltx/" name="WORD İle XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/word-to-sxc/" name="WORD İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/word-to-xlsx/" name="WORD İle XLSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}