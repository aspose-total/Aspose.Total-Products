---
title: .NET ile XLSB'yi DOC'ye dönüştürün 
description: .NET Framework, .NET Core, Mono veya Xamarin Platformlarında XLSB'yi DOC'ye dönüştürün
url: /tr/net/conversion/xlsb-to-doc/
family: total
platformtag: net
feature: conversion
informat: XLSB
outformat: DOC
otherformats: DOCX PPTX POWERPOINT WORD
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="C# ile XLSB'yi DOC'ye dönüştürün" h2="Excel'i Dışa Aktar&reg; .NET Framework, .NET Core, Mono veya Xamarin Platformlarında XLSB'den DOC'ye">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=".NET'te XLSB'den DOC'ye Dönüştürme" %}}
1. [Çalışma Kitabı](https://apireference.aspose.com/cells/net/aspose.cells/workbook) sınıfını kullanarak XLSB dosyasını açın
2. XLSB'yi PDF'ye dönüştürün ve SaveFormat'ı Otomatik olarak ayarlayın
3. Dönüştürülen PDF dosyasını [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak yükleyin
4. [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) yöntemini kullanarak dokümanı DOC formatına kaydedin ve Dokümanı SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://downloads.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="XLSB'den DOC'ye Dönüştürme için .NET C# Kodu" gistPath="" %}}
```cs
// load the XLSB file using Workbook class
var book = new Aspose.Cells.Workbook("input.xlsb");
// save XLSB as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOC format
document.Save("output.doc", SaveFormat.Doc); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/csv-to-word/" name="CSV İle WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/csv-to-powerpoint/" name="CSV İle POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/csv-to-pptx/" name="CSV İle PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/csv-to-docx/" name="CSV İle DOCX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}