---
title: DOCX'yi .NET aracılığıyla JSON formatına dönüştürün
description: Microsoft Excel veya Adobe Reader kullanmadan DOCX'yi C#'ta JSON'a dönüştürün
url_ignore: /tr/net/conversion/docx-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCX
outformat: JSON
otherformats: FODS XLTX XLSM XLS XLT XLSB ODS CSV TSV XLTM EXCEL SXC XLAM DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="DOCX'yi C# ile JSON Formatına Dönüştür" h2="Microsoft<sup>&reg;</sup> Word veya Excel kullanmadan DOCX'yi C# aracılığıyla JSON'a ayrıştırın" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) kullanarak herhangi bir .NET, C#, ASP.NET ve VB.NET uygulamasında DOCX'u JSON formatına iki şekilde dönüştürebilirsiniz. basit adımlar. İlk olarak, [Aspose.Words for .NET](https://products.aspose.com/words/net/) kullanarak DOCX'yi HTML'ye aktarabilirsiniz. Bundan sonra, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Elektronik Tablo Programlama API'sini kullanarak HTML'yi JSON'a dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOCX'yi C# ile JSON Formatına Dönüştür" %}}
1. DOCX dosyasını [Document](https://reference.aspose.com/words/net/aspose.words/Document) sınıfını kullanarak açın
2. [Save](https://reference.aspose.com/words/net/aspose.words.Document/save/methods/4) yöntemini kullanarak DOCX'u HTML'ye dönüştürün
3. [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) sınıfını kullanarak HTML belgesini yükleyin
4. [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) yöntemini kullanarak belgeyi JSON biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Korumalı DOCX'yi C# ile JSON Formatına Dönüştür" %}}
API'yi kullanarak parola korumalı belgeyi de açabilirsiniz. Girdiğiniz DOCX belgeniz parola korumalıysa, parolayı kullanmadan JSON biçimine dönüştüremezsiniz. API, bir LoadOptions nesnesinde doğru parolayı ileterek şifrelenmiş belgeyi açmanıza olanak tanır. Aşağıdaki kod örneği, şifreli bir belgeyi parola ile açmanın nasıl deneneceğini gösterir:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="DOCX'yi C# ile Aralıkta JSON'a Dönüştür" %}}
DOCX'yi JSON'a dönüştürürken, aralığı JSON çıktı biçiminize de ayarlayabilirsiniz. Aralığı ayarlamak için dönüştürülen HTML'yi Workbook sınıfını kullanarak açabilir, verileri içeren Çalışma Sayfasının CellsCollection'ını alabilir, satır ve sütun indekslerini belirterek CellsCollection'dan bir aralık oluşturabilir ve Range & ExportRangeToJsonOptions nesnelerine referanslarla ExportRangeToJson yöntemini çağırabilirsiniz. Son olarak, JSON verilerini File.WriteAllText yöntemi ile dosyaya kaydedebilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-csv/" name="DOCX İle CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-xlam/" name="DOCX İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-sxc/" name="DOCX İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-tsv/" name="DOCX İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-xlt/" name="DOCX İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-excel/" name="DOCX İle EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-dif/" name="DOCX İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-xlsm/" name="DOCX İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-xltm/" name="DOCX İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-xlsx/" name="DOCX İle XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-xlsb/" name="DOCX İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-fods/" name="DOCX İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-ods/" name="DOCX İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-xltx/" name="DOCX İle XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}