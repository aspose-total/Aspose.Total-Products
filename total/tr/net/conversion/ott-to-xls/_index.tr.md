---
title: OTT'yi XLS'ye Dönüştürmek için .NET API
description: Microsoft Excel veya Adobe Reader kullanmadan OTT'yi XLS'ye dönüştürmek için C# API'si
url: /tr/net/conversion/ott-to-xls/
family: total
platformtag: net
feature: conversion
informat: OTT
outformat: XLS
otherformats: FODS XLAM XLSB XLT EXCEL SXC DIF XLTM XLSX ODS TSV XLS XLSM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="OTT'yi XLS'ye Dönüştürmek için C# API" h2="Microsoft<sup>&reg;</sup> Word veya Microsoft<sup>&reg;</sup> Excel kullanmadan OTT'yi C# aracılığıyla XLS'ye aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) kullanarak OTT'den XLS'ye dönüştürme özelliğini herhangi bir .NET, C#, ASP.NET ve VB.NET uygulamasına dahil edebilirsiniz. iki basit adım. İlk olarak, [Aspose.Words for .NET](https://products.aspose.com/words/net/) kullanarak OTT'yi HTML'ye aktarabilirsiniz. Bundan sonra, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Elektronik Tablo Programlama API'sini kullanarak HTML'yi XLS'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="OTT'yi XLS'ye Dönüştürmek için .NET API" %}}
1. OTT dosyasını [Document](https://apireference.aspose.com/words/net/aspose.words/ottument) sınıfını kullanarak açın
2. [Save](https://apireference.aspose.com/words/net/aspose.words.ottument/save/methods/4) yöntemini kullanarak OTT'u HTML'ye dönüştürün
3. [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) sınıfını kullanarak HTML belgesini yükleyin
4. [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) yöntemini kullanarak belgeyi XLS formatına kaydedin ve 'XLS'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://downloads.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="OTT Belgesini Akıştan C# ile Yükle" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) ayrıca akış yoluyla OTT belgesini yüklemenizi sağlar. Bir akıştan bir belge açmak için belgeyi içeren bir akış nesnesini [Document](https://apireference.aspose.com/words/net/aspose.words/ottument) yapıcısına iletmeniz yeterlidir. Aşağıdaki kod örneği, bir akıştan bir belgenin nasıl açılacağını gösterir:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C# ile XLS Dosyasına Özel Özellikler Ekleme" %}}
OTT'yi XLS'ye dönüştürürken, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), XLS belgelerinize özel özellikler eklemenizi sağlar. Özel bir özellik eklemek için [CustomOttumentPropertyCollection]( için [Add](https://apireference.aspose.com/cells/net/aspose.cells.properties/customottumentpropertycollection/methods/add/index) yöntemini kullanabilirsiniz. https://apireference.aspose.com/cells/net/aspose.cells.properties/customottumentpropertycollection) sınıfı. Add yöntemi, özelliği Excel dosyasına ekler ve yeni belge özelliği için [Aspose.Cells.Properties.OttumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties) olarak bir başvuru döndürür. /ottumentproperty) nesnesi. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ott-to-dif/" name="OTT İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ott-to-xlsb/" name="OTT İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ott-to-tsv/" name="OTT İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ott-to-fods/" name="OTT İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ott-to-xlt/" name="OTT İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ott-to-excel/" name="OTT İle EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ott-to-xlsx/" name="OTT İle XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ott-to-ods/" name="OTT İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ott-to-sxc/" name="OTT İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ott-to-xlam/" name="OTT İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ott-to-xltm/" name="OTT İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ott-to-xlsm/" name="OTT İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ott-to-xls/" name="OTT İle XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ott-to-xltx/" name="OTT İle XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}