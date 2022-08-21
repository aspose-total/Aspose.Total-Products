---
title: Exportieren Sie EXCEL in DOCX in Android
description: Android-API zum Konvertieren von EXCEL in DOCX ohne Verwendung von Microsoft Word
url: /de/android-java/conversion/excel-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: CSV
outformat: DOCX
otherformats: WORD POWERPOINT PPTX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendern Sie EXCEL in DOCX auf Android über Java" h2="Wandeln Sie EXCEL in DOCX in Ihren Android-Anwendungen um, ohne Microsoft<sup>&reg;</sup> Excel zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) ist ein Paket leistungsstarker Dateiautomatisierungs-APIs. Durch die Verwendung von zwei seiner APIs können Sie die EXCEL-zu-DOCX-Konvertierungsfunktion in Ihre Android-Anwendungen integrieren. Im ersten Schritt können Sie EXCEL in PDF exportieren, indem Sie [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) verwenden. Danach können Sie mit [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) PDF in DOCX konvertieren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android-API zum Exportieren von EXCEL in DOCX" %}}
1. Öffnen Sie die EXCEL-Datei mit der Klasse [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
2. Konvertieren Sie EXCEL in PDF und setzen Sie SaveFormat auf AUTO
3. Laden Sie die konvertierte PDF-Datei mit der Klasse [Docxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument).
4. Speichern Sie das Dokument im DOCX-Format mit [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument#save-java.lang.String-com.aspose.pdf.SaveOptions -) Methode
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Android ganz einfach über Java direkt von [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) und verwenden Installieren Sie [Aspose.PDF for Android via Java](https://docxs.aspose.com/pdf/androidjava/installation/) und [Aspose.Cells for Android via Java](https://docxs.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) in Ihren Anwendungen.

Alternativ können Sie eine ZIP-Datei von [downloads](https://downloads.aspose.com/total/androidjava) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the EXCEL file using Workbook class
Workbook book = new Workbook("input.excel");
// save EXCEL as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Docxument class
Docxument docxument = new Docxument("pdfOutput.pdf");
// save docxument in DOCX format
docxument.save("output.docx", com.aspose.pdf.SaveFormat.DocxX);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Entfernen Sie benutzerdefinierte Eigenschaften aus der EXCEL-Datei in Android über Java" %}}
Abgesehen von der Dokumentenkonvertierung bietet [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) auch unzählige andere Funktionen. Vor dem Konvertierungsprozess können Sie benutzerdefinierte Eigenschaften des EXCEL-Dokuments entfernen. Um benutzerdefinierte Eigenschaften zu entfernen, rufen Sie die Methode [DocxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/docxumentpropertycollection#remove(java.lang.String)) auf und übergeben Sie den Namen von die zu entfernende Dokumenteigenschaft.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the EXCEL file using Workbook class
Workbook book = new Workbook("input.excel");
// retrieve a list of all custom docxument properties of the Excel file
DocxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocxumentProperties();
// remove a custom docxument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/excel-to-word/" name="EXCEL Zu WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/excel-to-powerpoint/" name="EXCEL Zu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/excel-to-pptx/" name="EXCEL Zu PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/excel-to-docx/" name="EXCEL Zu DOCX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}