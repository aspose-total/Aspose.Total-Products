---
title: Převeďte ODS na WORD pomocí Java
description: Java API pro export ODS do WORD pomocí Excelu nebo Wordu
url_ignore: /cs/java/conversion/ods-to-word/
family: total
platformtag: net
feature: conversion
informat: ODS
outformat: WORD
otherformats: WORDX WORD PPTX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API pro export ODS do WORD" h2="On Premise Java API pro export ODS do WORD bez spoléhání se na Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Vykreslení ODS do WORD je dvoufázový proces. Nejprve použijete [Aspose.Cells for Java](https://products.aspose.com/cells/java) API k převodu daného ODS dokumentu do PDF a poté pomocí [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API, můžete snadno převést dokument PDF na WORD. Obě rozhraní API spadají do kolekce knihoven automatizace formátu souborů [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak převést ODS na WORD přes Java API" %}}
1. Otevřete soubor ODS pomocí třídy [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Převeďte ODS na PDF a nastavte SaveFormat na AUTO
3. Načtěte převedený soubor PDF pomocí třídy [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Uložte dokument ve formátu WORD pomocí [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) a nastavte Word jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Musíte použít Aspose.Total pro Javu přímo z projektu založeného na [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a zahrňte knihovny do vašeho pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the ODS file using Workbook class
Workbook book = new Workbook("input.ods");
// save ODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in WORD format
document.save("output.word", com.aspose.pdf.SaveFormat.Word);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ods-to-wordx/" name="ODS Na WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ods-to-pptx/" name="ODS Na PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ods-to-powerpoint/" name="ODS Na POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ods-to-word/" name="ODS Na WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}