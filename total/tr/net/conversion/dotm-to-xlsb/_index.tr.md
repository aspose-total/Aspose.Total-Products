---
title: DOTM'yi XLSB'ye Dönüştürmek için .NET API
description: Microsoft Excel veya Adobe Reader kullanmadan DOTM'yi XLSB'ye dönüştürmek için C# API'si
url_ignore: /tr/net/conversion/dotm-to-xlsb/
family: total
platformtag: net
feature: conversion
informat: DOTM
outformat: XLSB
otherformats: TSV XLAM SXC XLSB EXCEL ODS FODS XLSM XLTX XLS XLSX DIF XLSB XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="DOTM'yi XLSB'ye Dönüştürmek için C# API" h2="Microsoft<sup>&reg;</sup> Word veya Microsoft<sup>&reg;</sup> Excel kullanmadan DOTM'yi C# aracılığıyla XLSB'ye aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) kullanarak DOTM'den XLSB'ye dönüştürme özelliğini herhangi bir .NET, C#, ASP.NET ve VB.NET uygulamasına dahil edebilirsiniz. iki basit adım. İlk olarak, [Aspose.Words for .NET](https://products.aspose.com/words/net/) kullanarak DOTM'yi HTML'ye aktarabilirsiniz. Bundan sonra, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Elektronik Tablo Programlama API'sini kullanarak HTML'yi XLSB'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOTM'yi XLSB'ye Dönüştürmek için .NET API" %}}
1. DOTM dosyasını [Dotmument](https://reference.aspose.com/words/net/aspose.words/dotmument) sınıfını kullanarak açın
2. [Save](https://reference.aspose.com/words/net/aspose.words.dotmument/save/methods/4) yöntemini kullanarak DOTM'u HTML'ye dönüştürün
3. [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) sınıfını kullanarak HTML belgesini yükleyin
4. [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) yöntemini kullanarak belgeyi XLSB formatına kaydedin ve 'XLSB'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://downloads.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="DOTM Belgesini Akıştan C# ile Yükle" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) ayrıca akış yoluyla DOTM belgesini yüklemenizi sağlar. Bir akıştan bir belge açmak için belgeyi içeren bir akış nesnesini [Dotmument](https://reference.aspose.com/words/net/aspose.words/dotmument) yapıcısına iletmeniz yeterlidir. Aşağıdaki kod örneği, bir akıştan bir belgenin nasıl açılacağını gösterir:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-protected-word-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C# ile XLSB Dosyasına Özel Özellikler Ekleme" %}}
DOTM'yi XLSB'ye dönüştürürken, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), XLSB belgelerinize özel özellikler eklemenizi sağlar. Özel bir özellik eklemek için [CustomDotmumentPropertyCollection]( için [Add](https://reference.aspose.com/cells/net/aspose.cells.properties/customdotmumentpropertycollection/methods/add/index) yöntemini kullanabilirsiniz. https://reference.aspose.com/cells/net/aspose.cells.properties/customdotmumentpropertycollection) sınıfı. Add yöntemi, özelliği Excel dosyasına ekler ve yeni belge özelliği için [Aspose.Cells.Properties.DotmumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties) olarak bir başvuru döndürür. /dotmumentproperty) nesnesi. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-protected-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-dif/" name="DOTM İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-xlsb/" name="DOTM İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-tsv/" name="DOTM İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-fods/" name="DOTM İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-xlt/" name="DOTM İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-excel/" name="DOTM İle EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-xlsx/" name="DOTM İle XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-ods/" name="DOTM İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-sxc/" name="DOTM İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-xlam/" name="DOTM İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-xltm/" name="DOTM İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-xlsm/" name="DOTM İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-xls/" name="DOTM İle XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-xltx/" name="DOTM İle XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}