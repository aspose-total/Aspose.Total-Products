---
title: ODT'yi C++'da FODS'ye dönüştürün veya ücretsiz Çevrimiçi Dönüştürücü ile
description: Microsoft Word veya Microsoft Excel kullanmadan ODT'yi FODS'ye dönüştürmek için C++ API veya çevrimiçi. Kodu entegre etmeden önce ücretsiz POT'den CSV'e çevrimiçi dönüştürücüyü hızlı bir şekilde test edin.

family: total
platformtag: cpp
feature: conversion
informat: ODT
outformat: FODS
otherformats: XLSB ODS TSV XLSM XLAM XLTX XLS XLTM XLSX SXC XLT EXCEL CSV DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="ODT'yi FODS'ye Dönüştürmek için C++ API veya Çevrimiçi Uygulama" h2="Microsoft<sup>&reg;</sup> Word veya Microsoft<sup>&reg;</sup> Excel kullanmadan ODT'yi C++ aracılığıyla FODS'ye aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
ODT'den FODS'ye dönüştürme özelliğini C++ uygulamalarınıza kolayca dahil edebilirsiniz. Zengin özelliklere sahip, güçlü ve kullanımı kolay belge işleme ve dönüştürme API'sini [Aspose.Words for C++](https://products.aspose.com/words/cpp/) kullanarak ODT'yi HTML'ye aktarabilirsiniz. Bundan sonra, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) kullanarak HTML'yi FODS'ye dönüştürebilirsiniz. Her iki API de [Aspose.Total for C++](https://products.aspose.com/total/cpp/) paketi kapsamında gelir. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ODT'yi FODS'ye Dönüştürmek için C++ API veya Çevrimiçi Uygulama" %}}
1. [Document](https://reference.aspose.com/words/cpp/class/aspose.words.odtument) sınıf referansını kullanarak ODT dosyasını açın
2. [Kaydet](https://reference.aspose.com/words/cpp/class/aspose.words.odtument#save_string_saveformat) üye işlevini kullanarak ODT'u HTML'ye dönüştürün
3. [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) sınıf referansını kullanarak HTML belgesini yükleyin
4. [Kaydet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) üye işlevini kullanarak belgeyi FODS biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://releases.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="ODT Belge Özelliklerine C++ ile Erişin" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) ayrıca ODT dosyasının belge özelliklerine erişmenizi sağlar ve dönüştürme işleminden önce bilinçli bir karar vermenizi sağlar. Belge özelliklerine erişmek için yerleşik özellikleri ve [CustomOdtumentProperties]( elde etmek için [BuiltInOdtumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_odtument_properties) kullanabilirsiniz. referans.aspose.com/words/cpp/class/aspose.words.properties.custom_odtument_properties) özel özellikler elde etmek için. Aşağıdaki kod örneği, bir belgedeki tüm yerleşik ve özel özelliklerin nasıl numaralandırılacağını gösterir.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-odtument-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="FODS Dosyasını C++ ile Akışa Kaydet" %}}
ODT'yi FODS'ye dönüştürdükten sonra, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), belgenizi akışa kaydetmenizi sağlar. Dosyaları bir akışa kaydetmek için bir MemoryStream veya FileStream nesnesi oluşturun ve [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) öğesini çağırarak dosyayı bu akış nesnesine kaydedin. nesnenin [Kaydet](https://reference.aspose.comyöntemi. [Kaydet](https://reference.aspose.com) çağrılırken [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) numaralandırmasını kullanarak istediğiniz dosya biçimini belirtin yöntemi.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/odt-to-xlsb/" name="ODT İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/odt-to-ods/" name="ODT İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/odt-to-tsv/" name="ODT İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/odt-to-xlsm/" name="ODT İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/odt-to-xlam/" name="ODT İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/odt-to-xltx/" name="ODT İle XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/odt-to-xls/" name="ODT İle XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/odt-to-xltm/" name="ODT İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/odt-to-xlsx/" name="ODT İle XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/odt-to-sxc/" name="ODT İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/odt-to-xlt/" name="ODT İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/odt-to-excel/" name="ODT İle EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/odt-to-fods/" name="ODT İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/odt-to-dif/" name="ODT İle DIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}