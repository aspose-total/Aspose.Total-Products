---
title: Převeďte TSV na PPTX pomocí Java
description: Java API pro export TSV do PPTX pomocí Excelu nebo Wordu
url_ignore: /cs/java/conversion/tsv-to-pptx/
family: total
platformtag: net
feature: conversion
informat: TSV
outformat: PPTX
otherformats: PPTX WORD POWERPOINT PPTXX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API pro export TSV do PPTX" h2="On Premise Java API pro export TSV do PPTX bez spoléhání se na Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Vykreslení TSV do PPTX je dvoufázový proces. Nejprve použijete [Aspose.Cells for Java](https://products.aspose.com/cells/java) API k převodu daného TSV dokumentu do PDF a poté pomocí [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API, můžete snadno převést dokument PDF na PPTX. Obě rozhraní API spadají do kolekce knihoven automatizace formátu souborů [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak převést TSV na PPTX přes Java API" %}}
1. Otevřete soubor TSV pomocí třídy [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Převeďte TSV na PDF a nastavte SaveFormat na AUTO
3. Načtěte převedený soubor PDF pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Uložte dokument ve formátu PPTX pomocí [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) a nastavte Pptx jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Musíte použít Aspose.Total pro Javu přímo z projektu založeného na [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a zahrňte knihovny do vašeho pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the TSV file using Workbook class
Workbook book = new Workbook("input.tsv");
// save TSV as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in PPTX format
document.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tsv-to-pptxx/" name="TSV Na PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tsv-to-pptx/" name="TSV Na PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tsv-to-powerpoint/" name="TSV Na POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/tsv-to-word/" name="TSV Na WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}