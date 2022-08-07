---
title: Exportieren Sie FODS in WORD in Android
description: Android-API zum Konvertieren von FODS in WORD ohne Verwendung von Microsoft Word
url: /de/android-java/conversion/fods-to-word/
family: total
platformtag: cpp
feature: conversion
informat: FODS
outformat: DOC
otherformats: PPTX DOCX POWERPOINT DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendern Sie FODS in WORD auf Android über Java" h2="Wandeln Sie FODS in WORD in Ihren Android-Anwendungen um, ohne Microsoft<sup>&reg;</sup> Excel zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total für Android über Java](https://products.aspose.com/total/android-java/) ist ein Paket leistungsstarker Dateiautomatisierungs-APIs. Durch die Verwendung von zwei seiner APIs können Sie die FODS-zu-WORD-Konvertierungsfunktion in Ihre Android-Anwendungen integrieren. Im ersten Schritt können Sie FODS in PDF exportieren, indem Sie [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) verwenden. Danach können Sie mit [Aspose.PDF für Android über Java](https://products.aspose.com/pdf/android-java/) PDF in WORD konvertieren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android-API zum Exportieren von FODS in WORD" %}}
1. Öffnen Sie die FODS-Datei mit der Klasse [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
2. Konvertieren Sie FODS in PDF und setzen Sie SaveFormat auf AUTO
3. Laden Sie die konvertierte PDF-Datei mit der Klasse [Wordument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument).
4. Speichern Sie das Dokument im WORD-Format mit [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument#save-java.lang.String-com.aspose.pdf.SaveOptions -) Methode
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Android ganz einfach über Java direkt von [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) und verwenden Installieren Sie [Aspose.PDF für Android über Java](https://words.aspose.com/pdf/androidjava/installation/) und [Aspose.Cells für Android über Java](https://words.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) in Ihren Anwendungen.

Alternativ können Sie eine ZIP-Datei von [downloads](https://downloads.aspose.com/total/androidjava) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the FODS file using Workbook class
Workbook book = new Workbook("input.fods");
// save FODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Wordument class
Wordument wordument = new Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.save("output.word", com.aspose.pdf.SaveFormat.Word);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Entfernen Sie benutzerdefinierte Eigenschaften aus der FODS-Datei in Android über Java" %}}
Abgesehen von der Dokumentenkonvertierung bietet [Aspose.Cells für Android über Java](https://products.aspose.com/cells/android-java/) auch unzählige andere Funktionen. Vor dem Konvertierungsprozess können Sie benutzerdefinierte Eigenschaften des FODS-Dokuments entfernen. Um benutzerdefinierte Eigenschaften zu entfernen, rufen Sie die Methode [WordumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/wordumentpropertycollection#remove(java.lang.String)) auf und übergeben Sie den Namen von die zu entfernende Dokumenteigenschaft.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the FODS file using Workbook class
Workbook book = new Workbook("input.fods");
// retrieve a list of all custom wordument properties of the Excel file
WordumentPropertyCollection customProperties = workbook.getWorksheets().getCustomWordumentProperties();
// remove a custom wordument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/fods-to-pptx/" name="FODS Zu PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/fods-to-wordx/" name="FODS Zu WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/fods-to-powerpoint/" name="FODS Zu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/fods-to-word/" name="FODS Zu WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}