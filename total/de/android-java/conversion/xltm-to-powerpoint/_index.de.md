---
title: Exportieren Sie XLTM in POWERPOINT in Android
description: Android-API zum Konvertieren von XLTM in POWERPOINT ohne Verwendung von Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: XLTM
outformat: PPTX
otherformats: DOC DOCX PPTX WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendern Sie XLTM in POWERPOINT auf Android über Java" h2="Wandeln Sie XLTM in POWERPOINT in Ihren Android-Anwendungen um, ohne Microsoft<sup>&reg;</sup> Excel zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) ist ein Paket leistungsstarker Dateiautomatisierungs-APIs. Durch die Verwendung von zwei seiner APIs können Sie die XLTM-zu-POWERPOINT-Konvertierungsfunktion in Ihre Android-Anwendungen integrieren. Im ersten Schritt können Sie XLTM in PDF exportieren, indem Sie [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) verwenden. Danach können Sie mit [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) PDF in POWERPOINT konvertieren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android-API zum Exportieren von XLTM in POWERPOINT" %}}
1. Öffnen Sie die XLTM-Datei mit der Klasse [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
2. Konvertieren Sie XLTM in PDF und setzen Sie SaveFormat auf AUTO
3. Laden Sie die konvertierte PDF-Datei mit der Klasse [Powerpointument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument).
4. Speichern Sie das Dokument im POWERPOINT-Format mit [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument#save-java.lang.String-com.aspose.pdf.SaveOptions -) Methode
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Android ganz einfach über Java direkt von [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) und verwenden Installieren Sie [Aspose.PDF for Android via Java](https://powerpoints.aspose.com/pdf/androidjava/installation/) und [Aspose.Cells for Android via Java](https://powerpoints.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) in Ihren Anwendungen.

Alternativ können Sie eine ZIP-Datei von [downloads](https://downloads.aspose.com/total/androidjava) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLTM file using Workbook class
Workbook book = new Workbook("input.xltm");
// save XLTM as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Powerpointument class
Powerpointument powerpointument = new Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Entfernen Sie benutzerdefinierte Eigenschaften aus der XLTM-Datei in Android über Java" %}}
Abgesehen von der Dokumentenkonvertierung bietet [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) auch unzählige andere Funktionen. Vor dem Konvertierungsprozess können Sie benutzerdefinierte Eigenschaften des XLTM-Dokuments entfernen. Um benutzerdefinierte Eigenschaften zu entfernen, rufen Sie die Methode [PowerpointumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/powerpointumentpropertycollection#remove(java.lang.String)) auf und übergeben Sie den Namen von die zu entfernende Dokumenteigenschaft.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLTM file using Workbook class
Workbook book = new Workbook("input.xltm");
// retrieve a list of all custom powerpointument properties of the Excel file
PowerpointumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPowerpointumentProperties();
// remove a custom powerpointument property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xltm-to-powerpoint/" name="XLTM Zu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xltm-to-powerpointx/" name="XLTM Zu POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xltm-to-pptx/" name="XLTM Zu PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xltm-to-word/" name="XLTM Zu WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}