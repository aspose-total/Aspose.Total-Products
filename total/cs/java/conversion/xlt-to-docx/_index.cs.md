---
title: Převeďte XLT na DOCX pomocí Java
description: Java API pro export XLT do DOCX pomocí Excelu nebo Wordu
url_ignore: /cs/java/conversion/xlt-to-docx/
family: total
platformtag: net
feature: conversion
informat: XLT
outformat: DOCXX
otherformats: POWERPOINT WORD PPTX DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API pro export XLT do DOCX" h2="On Premise Java API pro export XLT do DOCX bez spoléhání se na Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Vykreslení XLT do DOCX je dvoufázový proces. Nejprve použijete [Aspose.Cells for Java](https://products.aspose.com/cells/java) API k převodu daného XLT dokumentu do PDF a poté pomocí [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API, můžete snadno převést dokument PDF na DOCX. Obě rozhraní API spadají do kolekce knihoven automatizace formátu souborů [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak převést XLT na DOCX přes Java API" %}}
1. Otevřete soubor XLT pomocí třídy [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Převeďte XLT na PDF a nastavte SaveFormat na AUTO
3. Načtěte převedený soubor PDF pomocí třídy [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Uložte dokument ve formátu DOCX pomocí [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) a nastavte Docx jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Musíte použít Aspose.Total pro Javu přímo z projektu založeného na [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a zahrňte knihovny do vašeho pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLT file using Workbook class
Workbook book = new Workbook("input.xlt");
// save XLT as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document Document = new Document("pdfOutput.pdf");
// save Document in DOCXX format
Document.save("output.docxx", com.aspose.pdf.SaveFormat.DocxX);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xlt-to-docxx/" name="XLT Na DOCXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xlt-to-pptx/" name="XLT Na PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xlt-to-powerpoint/" name="XLT Na POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xlt-to-word/" name="XLT Na WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}