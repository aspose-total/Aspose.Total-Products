---
title: Exportieren Sie SXC in PPTX in Android
description: Android-API zum Konvertieren von SXC in PPTX ohne Verwendung von Microsoft Word
url: /de/android-java/conversion/sxc-to-pptx/
family: total
platformtag: cpp
feature: conversion
informat: SXC
outformat: PPTX
otherformats: POWERPOINT WORD DOC DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendern Sie SXC in PPTX auf Android über Java" h2="Wandeln Sie SXC in PPTX in Ihren Android-Anwendungen um, ohne Microsoft<sup>&reg;</sup> Excel zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) ist ein Paket leistungsstarker Dateiautomatisierungs-APIs. Durch die Verwendung von zwei seiner APIs können Sie die SXC-zu-PPTX-Konvertierungsfunktion in Ihre Android-Anwendungen integrieren. Im ersten Schritt können Sie SXC in PDF exportieren, indem Sie [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) verwenden. Danach können Sie mit [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) PDF in PPTX konvertieren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android-API zum Exportieren von SXC in PPTX" %}}
1. Öffnen Sie die SXC-Datei mit der Klasse [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
2. Konvertieren Sie SXC in PDF und setzen Sie SaveFormat auf AUTO
3. Laden Sie die konvertierte PDF-Datei mit der Klasse [Pptxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument).
4. Speichern Sie das Dokument im PPTX-Format mit [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument#save-java.lang.String-com.aspose.pdf.SaveOptions -) Methode
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Android ganz einfach über Java direkt von [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) und verwenden Installieren Sie [Aspose.PDF for Android via Java](https://pptxs.aspose.com/pdf/androidjava/installation/) und [Aspose.Cells for Android via Java](https://pptxs.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) in Ihren Anwendungen.

Alternativ können Sie eine ZIP-Datei von [downloads](https://downloads.aspose.com/total/androidjava) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the SXC file using Workbook class
Workbook book = new Workbook("input.sxc");
// save SXC as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Pptxument class
Pptxument pptxument = new Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Entfernen Sie benutzerdefinierte Eigenschaften aus der SXC-Datei in Android über Java" %}}
Abgesehen von der Dokumentenkonvertierung bietet [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) auch unzählige andere Funktionen. Vor dem Konvertierungsprozess können Sie benutzerdefinierte Eigenschaften des SXC-Dokuments entfernen. Um benutzerdefinierte Eigenschaften zu entfernen, rufen Sie die Methode [PptxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/pptxumentpropertycollection#remove(java.lang.String)) auf und übergeben Sie den Namen von die zu entfernende Dokumenteigenschaft.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the SXC file using Workbook class
Workbook book = new Workbook("input.sxc");
// retrieve a list of all custom pptxument properties of the Excel file
PptxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPptxumentProperties();
// remove a custom pptxument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/sxc-to-powerpoint/" name="SXC Zu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/sxc-to-word/" name="SXC Zu WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/sxc-to-pptx/" name="SXC Zu PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/sxc-to-pptxx/" name="SXC Zu PPTXX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}