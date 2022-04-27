---
title: DOTM'yi .NET aracılığıyla JSON formatına dönüştürün
description: Microsoft Excel veya Adobe Reader kullanmadan DOTM'yi C#'ta JSON'a dönüştürün
url: /tr/net/conversion/dotm-to-json/
family: total
platformtag: net
feature: conversion
informat: DOTM
outformat: JSON
otherformats: XLAM SXC XLTM TSV DIF FODS XLSM XLSX ODS XLTX XLS EXCEL XLSB XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="DOTM'yi C# ile JSON Formatına Dönüştür" h2="Microsoft<sup>&reg;</sup> Word veya Excel kullanmadan DOTM'yi C# aracılığıyla JSON'a ayrıştırın" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) kullanarak herhangi bir .NET, C#, ASP.NET ve VB.NET uygulamasında DOTM'u JSON formatına iki şekilde dönüştürebilirsiniz. basit adımlar. İlk olarak, [Aspose.Words for .NET](https://products.aspose.com/words/net/) kullanarak DOTM'yi HTML'ye aktarabilirsiniz. Bundan sonra, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Elektronik Tablo Programlama API'sini kullanarak HTML'yi JSON'a dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOTM'yi C# ile JSON Formatına Dönüştür" %}}
1. DOTM dosyasını [Dotmument](https://apireference.aspose.com/words/net/aspose.words/dotmument) sınıfını kullanarak açın
2. [Save](https://apireference.aspose.com/words/net/aspose.words.dotmument/save/methods/4) yöntemini kullanarak DOTM'u HTML'ye dönüştürün
3. [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) sınıfını kullanarak HTML belgesini yükleyin
4. [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) yöntemini kullanarak belgeyi JSON biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://downloads.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Korumalı DOTM'yi C# ile JSON Formatına Dönüştür" %}}
API'yi kullanarak parola korumalı belgeyi de açabilirsiniz. Girdiğiniz DOTM belgeniz parola korumalıysa, parolayı kullanmadan JSON biçimine dönüştüremezsiniz. API, bir LoadOptions nesnesinde doğru parolayı ileterek şifrelenmiş belgeyi açmanıza olanak tanır. Aşağıdaki kod örneği, şifreli bir belgeyi parola ile açmanın nasıl deneneceğini gösterir:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="DOTM'yi C# ile Aralıkta JSON'a Dönüştür" %}}
DOTM'yi JSON'a dönüştürürken, aralığı JSON çıktı biçiminize de ayarlayabilirsiniz. Aralığı ayarlamak için dönüştürülen HTML'yi Workbook sınıfını kullanarak açabilir, verileri içeren Çalışma Sayfasının CellsCollection'ını alabilir, satır ve sütun indekslerini belirterek CellsCollection'dan bir aralık oluşturabilir ve Range & ExportRangeToJsonOptions nesnelerine referanslarla ExportRangeToJson yöntemini çağırabilirsiniz. Son olarak, JSON verilerini File.WriteAllText yöntemi ile dosyaya kaydedebilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-csv/" name="DOTM İle CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-xlam/" name="DOTM İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-sxc/" name="DOTM İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-tsv/" name="DOTM İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-xlt/" name="DOTM İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-excel/" name="DOTM İle EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-dif/" name="DOTM İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-xlsm/" name="DOTM İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-xltm/" name="DOTM İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-xlsx/" name="DOTM İle XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-xlsb/" name="DOTM İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-fods/" name="DOTM İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-ods/" name="DOTM İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/dotm-to-xltx/" name="DOTM İle XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}