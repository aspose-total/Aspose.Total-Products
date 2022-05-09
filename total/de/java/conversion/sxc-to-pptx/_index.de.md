---
title: Konvertieren Sie SXC in PPTX mit Java
description: Java-API zum Exportieren von SXC in PPTX mit Excel oder Word
url_ignore: /de/java/conversion/sxc-to-pptx/
family: total
platformtag: net
feature: conversion
informat: SXC
outformat: PPTX
otherformats: PPTXX PPTX POWERPOINT WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java-API zum Exportieren von SXC in PPTX" h2="On-Premise-Java-API zum Exportieren von SXC in PPTX, ohne auf Microsoft Excel angewiesen zu sein&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Das Rendern von SXC in PPTX ist ein zweistufiger Prozess. Sie verwenden zuerst die API [Aspose.Cells for Java](https://products.aspose.com/cells/java), um das angegebene SXC-Dokument in PDF zu konvertieren, und verwenden dann [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API können Sie Ihr PDF-Dokument einfach in PPTX konvertieren. Beide APIs gehören zur Sammlung von [Aspose.Total for Java](https://products.aspose.com/total/java/) Dateiformat-Automatisierungsbibliotheken.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="So konvertieren Sie SXC in PPTX über die Java-API" %}}
1. Öffnen Sie die SXC-Datei mit der Klasse [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook).
2. Konvertieren Sie SXC in PDF und setzen Sie SaveFormat auf AUTO
3. Laden Sie die konvertierte PDF-Datei mit der Klasse [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document).
4. Speichern Sie das Dokument im PPTX-Format mit [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) Methode und legen Sie Pptx als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie müssen Aspose.Total für Java direkt aus einem [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)-basierten Projekt verwenden und fügen Sie Bibliotheken in Ihre pom.xml ein.

Alternativ können Sie eine ZIP-Datei von [downloads](https://downloads.aspose.com/total/java) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the SXC file using Workbook class
Workbook book = new Workbook("input.sxc");
// save SXC as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in PPTX format
document.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/sxc-to-pptxx/" name="SXC Zu PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/sxc-to-pptx/" name="SXC Zu PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/sxc-to-powerpoint/" name="SXC Zu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/sxc-to-word/" name="SXC Zu WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}