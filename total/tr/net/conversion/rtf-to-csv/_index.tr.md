---
title: RTF'yi CSV'ye Dönüştürmek için .NET API
description: Microsoft Excel veya Adobe Reader kullanmadan RTF'yi CSV'ye dönüştürmek için C# API'si
url: /tr/net/conversion/rtf-to-csv/
family: total
platformtag: net
feature: conversion
informat: RTF
outformat: CSV
otherformats: FODS XLSB XLTM XLS TSV XLAM DIF XLTX SXC XLT XLSM ODS XLSX EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="RTF'yi CSV'ye Dönüştürmek için C# API" h2="Microsoft<sup>&reg;</sup> Word veya Microsoft<sup>&reg;</sup> Excel kullanmadan RTF'yi C# aracılığıyla CSV'ye aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) kullanarak RTF'den CSV'ye dönüştürme özelliğini herhangi bir .NET, C#, ASP.NET ve VB.NET uygulamasına dahil edebilirsiniz. iki basit adım. İlk olarak, [Aspose.Words for .NET](https://products.aspose.com/words/net/) kullanarak RTF'yi HTML'ye aktarabilirsiniz. Bundan sonra, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Elektronik Tablo Programlama API'sini kullanarak HTML'yi CSV'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="RTF'yi CSV'ye Dönüştürmek için .NET API" %}}
1. RTF dosyasını [Rtfument](https://apireference.aspose.com/words/net/aspose.words/rtfument) sınıfını kullanarak açın
2. [Save](https://apireference.aspose.com/words/net/aspose.words.rtfument/save/methods/4) yöntemini kullanarak RTF'u HTML'ye dönüştürün
3. [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) sınıfını kullanarak HTML belgesini yükleyin
4. [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) yöntemini kullanarak belgeyi CSV formatına kaydedin ve 'CSV'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://downloads.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="RTF Belgesini Akıştan C# ile Yükle" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) ayrıca akış yoluyla RTF belgesini yüklemenizi sağlar. Bir akıştan bir belge açmak için belgeyi içeren bir akış nesnesini [Rtfument](https://apireference.aspose.com/words/net/aspose.words/rtfument) yapıcısına iletmeniz yeterlidir. Aşağıdaki kod örneği, bir akıştan bir belgenin nasıl açılacağını gösterir:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C# ile CSV Dosyasına Özel Özellikler Ekleme" %}}
RTF'yi CSV'ye dönüştürürken, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), CSV belgelerinize özel özellikler eklemenizi sağlar. Özel bir özellik eklemek için [CustomRtfumentPropertyCollection]( için [Add](https://apireference.aspose.com/cells/net/aspose.cells.properties/customrtfumentpropertycollection/methods/add/index) yöntemini kullanabilirsiniz. https://apireference.aspose.com/cells/net/aspose.cells.properties/customrtfumentpropertycollection) sınıfı. Add yöntemi, özelliği Excel dosyasına ekler ve yeni belge özelliği için [Aspose.Cells.Properties.RtfumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties) olarak bir başvuru döndürür. /rtfumentproperty) nesnesi. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-dif/" name="RTF İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-xlsb/" name="RTF İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-tsv/" name="RTF İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-fods/" name="RTF İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-xlt/" name="RTF İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-excel/" name="RTF İle EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-xlsx/" name="RTF İle XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-ods/" name="RTF İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-sxc/" name="RTF İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-xlam/" name="RTF İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-xltm/" name="RTF İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-xlsm/" name="RTF İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-xls/" name="RTF İle XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-xltx/" name="RTF İle XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}