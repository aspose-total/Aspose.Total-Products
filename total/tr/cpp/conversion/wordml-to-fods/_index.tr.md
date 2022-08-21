---
title: WORDML'yi C++'da FODS'ye dönüştürün
description: Microsoft Word veya Microsoft Excel kullanmadan WORDML'yi FODS'ye dönüştürmek için C++ API
url: /tr/cpp/conversion/wordml-to-fods/
family: total
platformtag: cpp
feature: conversion
informat: WORDML
outformat: FODS
otherformats: ODS XLSB EXCEL DIF XLTX CSV XLSM XLSX TSV XLT XLAM XLTM SXC XLS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="WORDML'yi FODS'ye Dönüştürmek için C++ API" h2="Microsoft<sup>&reg;</sup> Word veya Microsoft<sup>&reg;</sup> Excel kullanmadan WORDML'yi C++ aracılığıyla FODS'ye aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
WORDML'den FODS'ye dönüştürme özelliğini C++ uygulamalarınıza kolayca dahil edebilirsiniz. Zengin özelliklere sahip, güçlü ve kullanımı kolay belge işleme ve dönüştürme API'sini [Aspose.Words for C++](https://products.aspose.com/words/cpp/) kullanarak WORDML'yi HTML'ye aktarabilirsiniz. Bundan sonra, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) kullanarak HTML'yi FODS'ye dönüştürebilirsiniz. Her iki API de [Aspose.Total for C++](https://products.aspose.com/total/cpp/) paketi kapsamında gelir. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="WORDML'yi FODS'ye Dönüştürmek için C++ API" %}}
1. [Document](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument) sınıf referansını kullanarak WORDML dosyasını açın
2. [Kaydet](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument#save_string_saveformat) üye işlevini kullanarak WORDML'u HTML'ye dönüştürün
3. [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) sınıf referansını kullanarak HTML belgesini yükleyin
4. [Kaydet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) üye işlevini kullanarak belgeyi FODS biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://downloads.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="WORDML Belge Özelliklerine C++ ile Erişin" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) ayrıca WORDML dosyasının belge özelliklerine erişmenizi sağlar ve dönüştürme işleminden önce bilinçli bir karar vermenizi sağlar. Belge özelliklerine erişmek için yerleşik özellikleri ve [CustomWordmlumentProperties]( elde etmek için [BuiltInWordmlumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_wordmlument_properties) kullanabilirsiniz. referans.aspose.com/words/cpp/class/aspose.words.properties.custom_wordmlument_properties) özel özellikler elde etmek için. Aşağıdaki kod örneği, bir belgedeki tüm yerleşik ve özel özelliklerin nasıl numaralandırılacağını gösterir.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-wordmlument-properties.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="FODS Dosyasını C++ ile Akışa Kaydet" %}}
WORDML'yi FODS'ye dönüştürdükten sonra, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), belgenizi akışa kaydetmenizi sağlar. Dosyaları bir akışa kaydetmek için bir MemoryStream veya FileStream nesnesi oluşturun ve [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) öğesini çağırarak dosyayı bu akış nesnesine kaydedin. nesnenin [Kaydet](https://reference.aspose.comyöntemi. [Kaydet](https://reference.aspose.com) çağrılırken [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) numaralandırmasını kullanarak istediğiniz dosya biçimini belirtin yöntemi.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/wordml-to-ods/" name="WORDML İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/wordml-to-xlsb/" name="WORDML İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/wordml-to-excel/" name="WORDML İle EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/wordml-to-dif/" name="WORDML İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/wordml-to-xltx/" name="WORDML İle XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/wordml-to-fods/" name="WORDML İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/wordml-to-xlsm/" name="WORDML İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/wordml-to-xlsx/" name="WORDML İle XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/wordml-to-tsv/" name="WORDML İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/wordml-to-xlt/" name="WORDML İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/wordml-to-xlam/" name="WORDML İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/wordml-to-xltm/" name="WORDML İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/wordml-to-sxc/" name="WORDML İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/wordml-to-xls/" name="WORDML İle XLS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}