---
title: Converti XLSM in POWERPOINT usando Java o con il convertitore online gratuito
description: API Java per esportare XLSM in POWERPOINT o in linea utilizzando Excel o Word o in linea. Prova rapidamente il convertitore online gratuito da CSV a DOC prima di integrare il codice.
url_ignore: /it/java/conversion/xlsm-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: XLSM
outformat: PPTX
otherformats: WORD POWERPOINTX POWERPOINT PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java per esportare XLSM in POWERPOINT o in linea" h2="API Java in loco per esportare XLSM in POWERPOINT senza fare affidamento su Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Il rendering di XLSM in POWERPOINT è un processo in due fasi. Utilizzerai prima l'API [Aspose.Cells for Java](https://products.aspose.com/cells/java) per convertire il documento XLSM specificato in PDF, quindi utilizzerai [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API, puoi convertire facilmente il tuo documento PDF in POWERPOINT. Entrambe le API rientrano nella raccolta di librerie di automazione dei formati di file [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Come convertire XLSM in POWERPOINT tramite API Java" %}}
1. Aprire il file XLSM utilizzando la classe [Workbook](https://apiference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Converti XLSM in PDF e imposta SaveFormat su AUTO
3. Caricare il file PDF convertito utilizzando la classe [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Salvare il documento in formato POWERPOINT utilizzando [save](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) e imposta Powerpoint come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Devi usare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://releases.aspose.com/total/java/) e includi le librerie nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSM file using Workbook class
Workbook book = new Workbook("input.xlsm");
// save XLSM as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in PPTX format
document.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Convertitore online da XLSM a POWERPOINT</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=xlsm" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/xlsm-to-pptx/">Prova la nostra app gratuita per la conversione da XLSM a POWERPOINT</a></p>
</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}