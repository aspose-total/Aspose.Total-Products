---
title: .NET ile FODS'yi PPTX'ye dönüştürün 
description: .NET Framework, .NET Core, Mono veya Xamarin Platformlarında FODS'yi PPTX'ye dönüştürün
url: /tr/net/conversion/fods-to-pptx/
family: total
platformtag: net
feature: conversion
informat: FODS
outformat: PPTX
otherformats: DOC DOCX WORD POWERPOINT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="C# ile FODS'yi PPTX'ye dönüştürün" h2="Excel'i Dışa Aktar&reg; .NET Framework, .NET Core, Mono veya Xamarin Platformlarında FODS'den PPTX'ye">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=".NET'te FODS'den PPTX'ye Dönüştürme" %}}
1. [Çalışma Kitabı](https://apireference.aspose.com/cells/net/aspose.cells/workbook) sınıfını kullanarak FODS dosyasını açın
2. FODS'yi PDF'ye dönüştürün ve SaveFormat'ı Otomatik olarak ayarlayın
3. Dönüştürülen PDF dosyasını [Pptxument](https://apireference.aspose.com/pdf/net/aspose.pdf/pptxument) sınıfını kullanarak yükleyin
4. [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.pptxument/save/methods/5) yöntemini kullanarak dokümanı PPTX formatına kaydedin ve Dokümanı SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://downloads.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="FODS'den PPTX'ye Dönüştürme için .NET C# Kodu" gistPath="" %}}
```cs
// load the FODS file using Workbook class
var book = new Aspose.Cells.Workbook("input.fods");
// save FODS as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Pptxument class
var pptxument = new Aspose.Pdf.Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.Save("output.pptx", SaveFormat.Pptx); 
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