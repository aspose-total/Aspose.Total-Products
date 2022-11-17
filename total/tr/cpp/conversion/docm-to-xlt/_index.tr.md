---
title: DOCM'yi C++'da XLT'ye dönüştürün
description: Microsoft Word veya Microsoft Excel kullanmadan DOCM'yi XLT'ye dönüştürmek için C++ API

family: total
platformtag: cpp
feature: conversion
informat: DOCM
outformat: XLT
otherformats: EXCEL TSV ODS XLTX XLS DIF CSV XLSB XLSX FODS XLSM SXC XLAM XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="DOCM'yi XLT'ye Dönüştürmek için C++ API" h2="Microsoft<sup>&reg;</sup> Word veya Microsoft<sup>&reg;</sup> Excel kullanmadan DOCM'yi C++ aracılığıyla XLT'ye aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
DOCM'den XLT'ye dönüştürme özelliğini C++ uygulamalarınıza kolayca dahil edebilirsiniz. Zengin özelliklere sahip, güçlü ve kullanımı kolay belge işleme ve dönüştürme API'sini [Aspose.Words for C++](https://products.aspose.com/words/cpp/) kullanarak DOCM'yi HTML'ye aktarabilirsiniz. Bundan sonra, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) kullanarak HTML'yi XLT'ye dönüştürebilirsiniz. Her iki API de [Aspose.Total for C++](https://products.aspose.com/total/cpp/) paketi kapsamında gelir. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOCM'yi XLT'ye Dönüştürmek için C++ API" %}}
1. [Document](https://reference.aspose.com/words/cpp/class/aspose.words.docmument) sınıf referansını kullanarak DOCM dosyasını açın
2. [Kaydet](https://reference.aspose.com/words/cpp/class/aspose.words.docmument#save_string_saveformat) üye işlevini kullanarak DOCM'u HTML'ye dönüştürün
3. [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) sınıf referansını kullanarak HTML belgesini yükleyin
4. [Kaydet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) üye işlevini kullanarak belgeyi XLT biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://downloads.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="DOCM Belge Özelliklerine C++ ile Erişin" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) ayrıca DOCM dosyasının belge özelliklerine erişmenizi sağlar ve dönüştürme işleminden önce bilinçli bir karar vermenizi sağlar. Belge özelliklerine erişmek için yerleşik özellikleri ve [CustomDocumentProperties]( elde etmek için [BuiltInDocumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_docmument_properties) kullanabilirsiniz. özel özellikler elde etmek için. Aşağıdaki kod örneği, bir belgedeki tüm yerleşik ve özel özelliklerin nasıl numaralandırılacağını gösterir.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-docmument-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="XLT Dosyasını C++ ile Akışa Kaydet" %}}
DOCM'yi XLT'ye dönüştürdükten sonra, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), belgenizi akışa kaydetmenizi sağlar. Dosyaları bir akışa kaydetmek için bir MemoryStream veya FileStream nesnesi oluşturun ve [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) öğesini çağırarak dosyayı bu akış nesnesine kaydedin. nesnenin [Kaydet](https://reference.aspose.comyöntemi. [Kaydet](https://reference.aspose.com) çağrılırken [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) numaralandırmasını kullanarak istediğiniz dosya biçimini belirtin yöntemi.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/docm-to-excel/" name="DOCM İle EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/docm-to-tsv/" name="DOCM İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/docm-to-ods/" name="DOCM İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/docm-to-xltx/" name="DOCM İle XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/docm-to-xls/" name="DOCM İle XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/docm-to-dif/" name="DOCM İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/docm-to-xlt/" name="DOCM İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/docm-to-xlsb/" name="DOCM İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/docm-to-xlsx/" name="DOCM İle XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/docm-to-fods/" name="DOCM İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/docm-to-xlsm/" name="DOCM İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/docm-to-sxc/" name="DOCM İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/docm-to-xlam/" name="DOCM İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/docm-to-xltm/" name="DOCM İle XLTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}