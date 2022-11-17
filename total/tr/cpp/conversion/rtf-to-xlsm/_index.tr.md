---
title: RTF'yi C++'da XLSM'ye dönüştürün
description: Microsoft Word veya Microsoft Excel kullanmadan RTF'yi XLSM'ye dönüştürmek için C++ API

family: total
platformtag: cpp
feature: conversion
informat: RTF
outformat: XLSM
otherformats: ODS XLTX EXCEL XLSB CSV XLAM XLSX SXC XLTM TSV XLT XLS DIF FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="RTF'yi XLSM'ye Dönüştürmek için C++ API" h2="Microsoft<sup>&reg;</sup> Word veya Microsoft<sup>&reg;</sup> Excel kullanmadan RTF'yi C++ aracılığıyla XLSM'ye aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
RTF'den XLSM'ye dönüştürme özelliğini C++ uygulamalarınıza kolayca dahil edebilirsiniz. Zengin özelliklere sahip, güçlü ve kullanımı kolay belge işleme ve dönüştürme API'sini [Aspose.Words for C++](https://products.aspose.com/words/cpp/) kullanarak RTF'yi HTML'ye aktarabilirsiniz. Bundan sonra, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) kullanarak HTML'yi XLSM'ye dönüştürebilirsiniz. Her iki API de [Aspose.Total for C++](https://products.aspose.com/total/cpp/) paketi kapsamında gelir. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="RTF'yi XLSM'ye Dönüştürmek için C++ API" %}}
1. [Document](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument) sınıf referansını kullanarak RTF dosyasını açın
2. [Kaydet](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument#save_string_saveformat) üye işlevini kullanarak RTF'u HTML'ye dönüştürün
3. [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) sınıf referansını kullanarak HTML belgesini yükleyin
4. [Kaydet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) üye işlevini kullanarak belgeyi XLSM biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://downloads.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="RTF Belge Özelliklerine C++ ile Erişin" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) ayrıca RTF dosyasının belge özelliklerine erişmenizi sağlar ve dönüştürme işleminden önce bilinçli bir karar vermenizi sağlar. Belge özelliklerine erişmek için yerleşik özellikleri ve [CustomRtfumentProperties]( elde etmek için [BuiltInRtfumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_rtfument_properties) kullanabilirsiniz. referans.aspose.com/words/cpp/class/aspose.words.properties.custom_rtfument_properties) özel özellikler elde etmek için. Aşağıdaki kod örneği, bir belgedeki tüm yerleşik ve özel özelliklerin nasıl numaralandırılacağını gösterir.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-rtfument-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="XLSM Dosyasını C++ ile Akışa Kaydet" %}}
RTF'yi XLSM'ye dönüştürdükten sonra, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), belgenizi akışa kaydetmenizi sağlar. Dosyaları bir akışa kaydetmek için bir MemoryStream veya FileStream nesnesi oluşturun ve [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) öğesini çağırarak dosyayı bu akış nesnesine kaydedin. nesnenin [Kaydet](https://reference.aspose.comyöntemi. [Kaydet](https://reference.aspose.com) çağrılırken [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) numaralandırmasını kullanarak istediğiniz dosya biçimini belirtin yöntemi.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/rtf-to-ods/" name="RTF İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/rtf-to-xltx/" name="RTF İle XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/rtf-to-excel/" name="RTF İle EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/rtf-to-xlsb/" name="RTF İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/rtf-to-xlsm/" name="RTF İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/rtf-to-xlam/" name="RTF İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/rtf-to-xlsx/" name="RTF İle XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/rtf-to-sxc/" name="RTF İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/rtf-to-xltm/" name="RTF İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/rtf-to-tsv/" name="RTF İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/rtf-to-xlt/" name="RTF İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/rtf-to-xls/" name="RTF İle XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/rtf-to-dif/" name="RTF İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/rtf-to-fods/" name="RTF İle FODS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}