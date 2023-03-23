---
title: Konvertieren Sie XLSB in DOCX mit Java oder mit dem kostenlosen Online Converter
description: Java-API zum Exportieren von XLSB in DOCX oder online mit Excel oder Word oder online. Testen Sie schnell den kostenlosen CSV-zu-DOC-Online-Konverter, bevor Sie den Code integrieren.
url_ignore: /de/java/conversion/xlsb-to-docx/
family: total
platformtag: net
feature: conversion
informat: XLSB
outformat: DOCX
otherformats: PPTX WORD DOCX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java-API zum Exportieren von XLSB in DOCX oder online" h2="On-Premise-Java-API zum Exportieren von XLSB in DOCX oder online, ohne auf Microsoft Excel angewiesen zu sein&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Das Rendern von XLSB in DOCX ist ein zweistufiger Prozess. Sie verwenden zuerst die API [Aspose.Cells for Java](https://products.aspose.com/cells/java), um das angegebene XLSB-Dokument in PDF zu konvertieren, und verwenden dann [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API können Sie Ihr PDF-Dokument einfach in DOCX konvertieren. Beide APIs gehören zur Sammlung von [Aspose.Total for Java](https://products.aspose.com/total/java/) Dateiformat-Automatisierungsbibliotheken.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="So konvertieren Sie XLSB in DOCX über die Java-API" %}}
1. Öffnen Sie die XLSB-Datei mit der Klasse [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
2. Konvertieren Sie XLSB in PDF und setzen Sie SaveFormat auf AUTO
3. Laden Sie die konvertierte PDF-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
4. Speichern Sie das Dokument im DOCX-Format mit [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) Methode und legen Sie Docx als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie müssen Aspose.Total für Java direkt aus einem [Maven](https://releases.aspose.com/total/java/)-basierten Projekt verwenden und fügen Sie Bibliotheken in Ihre pom.xml ein.

Alternativ können Sie eine ZIP-Datei von [downloads](https://releases.aspose.com/total/java) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSB file using Workbook class
Workbook book = new Workbook("input.xlsb");
// save XLSB as PDF
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
<div class="demobox tc col-md-12 padding-0">

<h3>Online-Konverter für XLSB zu DOCX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=xlsb" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/xlsb-to-docx/">Testen Sie unsere kostenlose App für die Konvertierung von XLSB in DOCX</a></p>
</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}DOCX
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xlsb-to-docxx/" name="XLSB Zu DOCXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xlsb-to-pptx/" name="XLSB Zu PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xlsb-to-powerpoint/" name="XLSB Zu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xlsb-to-word/" name="XLSB Zu WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}