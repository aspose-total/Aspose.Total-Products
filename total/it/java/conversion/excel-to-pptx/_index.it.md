---
title: Converti EXCEL in PPTX usando Java
description: API Java per esportare EXCEL in PPTX utilizzando Excel o Word
url_ignore: /it/java/conversion/excel-to-pptx/
family: total
platformtag: net
feature: conversion
informat: EXCEL
outformat: PPTX
otherformats: WORD PPTX POWERPOINT PPTXX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java per esportare EXCEL in PPTX" h2="API Java in loco per esportare EXCEL in PPTX senza fare affidamento su Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Il rendering di EXCEL in PPTX è un processo in due fasi. Utilizzerai prima l'API [Aspose.Cells for Java](https://products.aspose.com/cells/java) per convertire il documento EXCEL specificato in PDF, quindi utilizzerai [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API, puoi convertire facilmente il tuo documento PDF in PPTX. Entrambe le API rientrano nella raccolta di librerie di automazione dei formati di file [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Come convertire EXCEL in PPTX tramite API Java" %}}
1. Aprire il file EXCEL utilizzando la classe [Workbook](https://apiference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Converti EXCEL in PDF e imposta SaveFormat su AUTO
3. Caricare il file PDF convertito utilizzando la classe [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Salvare il documento in formato PPTX utilizzando [save](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) e imposta Pptx come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Devi usare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e includi le librerie nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EXCEL file using Workbook class
Workbook book = new Workbook("input.excel");
// save EXCEL as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in PPTX format
document.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre opzioni di conversione" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/excel-to-pptxx/" name="EXCEL A PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/excel-to-pptx/" name="EXCEL A PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/excel-to-powerpoint/" name="EXCEL A POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/excel-to-word/" name="EXCEL A WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}