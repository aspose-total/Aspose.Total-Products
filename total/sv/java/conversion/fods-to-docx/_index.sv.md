---
title: Konvertera FODS till DOCX med Java eller med gratis Online Converter
description: Java API för att exportera FODS till DOCX eller online med hjälp av Excel eller Word eller online. Testa gratis CSV till DOC online-omvandlare snabbt innan du integrerar koden.
url_ignore: /sv/java/conversion/fods-to-docx/
family: total
platformtag: net
feature: conversion
informat: FODS
outformat: DOCX
otherformats: POWERPOINT WORD DOCX PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API för att exportera FODS till DOCX eller online" h2="On Premise Java API för att exportera FODS till DOCX eller online utan att förlita sig på Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Att rendera FODS till DOCX är en process i två steg. Du använder först [Aspose.Cells for Java](https://products.aspose.com/cells/java) API för att konvertera det givna FODS-dokumentet till PDF och sedan genom att använda [Aspose.Pdf för Java](https://products.aspose.com/pdf/java) API kan du enkelt konvertera ditt PDF-dokument till DOCX. Båda API:erna ingår i samlingen av [Aspose.Total for Java](https://products.aspose.com/total/java/) filformatsautomatiseringsbibliotek.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hur man konverterar FODS till DOCX via Java API" %}}
1. Öppna FODS-filen med klassen [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Konvertera FODS till PDF och ställ in SaveFormat till AUTO
3. Ladda den konverterade PDF-filen med klassen [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Spara dokumentet i DOCX-format med [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) och ställ in Docx som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du måste använda Aspose.Total för Java direkt från ett [Maven](https://releases.aspose.com/total/java/) baserat projekt och inkludera bibliotek i din pom.xml.

Alternativt kan du få en ZIP-fil från [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the FODS file using Workbook class
Workbook book = new Workbook("input.fods");
// save FODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document Document = new Document("pdfOutput.pdf");
// save Document in DOCX format
Document.save("output.docxx", com.aspose.pdf.SaveFormat.DocxX);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Online-omvandlare för FODS till DOCX</h3>

<iframe title="fods till docx Conversion Online Tool" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=fods" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/fods-to-docx/">Prova vår gratisapp för FODS till DOCX-konvertering</a></p>
</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra konverteringsalternativ" subTitle="" >}}DOCX
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/fods-to-docxx/" name="FODS Till DOCXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/fods-to-pptx/" name="FODS Till PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/fods-to-powerpoint/" name="FODS Till POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/fods-to-word/" name="FODS Till WORD" description="" >}}



{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}