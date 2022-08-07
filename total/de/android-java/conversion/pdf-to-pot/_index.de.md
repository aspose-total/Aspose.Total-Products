---
title: Exportieren Sie PDF in POT in Android
description: Android-API zum Konvertieren von PDF in POT ohne Verwendung von Microsoft Word
url: /de/android-java/conversion/pdf-to-pot/
family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: POT
otherformats: PPSM PPS POTX POWERPOINT SWF XAML POTM PPTM OTP PPSX ODP PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertieren Sie PDF in POT auf Android über Java" h2="Wandeln Sie PDF innerhalb Ihrer Android-Anwendungen in POT um, ohne Microsoft<sup>&reg;</sup> PowerPoint oder Adobe<sup>&reg;</sup> Acrobat Reader zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sie können die PDF-zu-POT-Konvertierungsfunktion in Ihre Android-Anwendungen integrieren, indem Sie zwei einfache Schritte ausführen. Im ersten Schritt können Sie PDF nach PPTX exportieren, indem Sie [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) verwenden. Danach können Sie mit [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) PPTX in POT konvertieren. Beide APIs sind im Paket [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) enthalten. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android-API zum Exportieren von PDF in POT" %}}
1. Öffnen Sie die PDF-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Konvertieren Sie PDF in PPTX, indem Sie die Methode [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) verwenden
3. Laden Sie das PPTX-Dokument mithilfe der Klasse [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation).
4. Speichern Sie das Dokument im POT-Format mit der Methode [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) und setzen Sie ` Pot` als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Android ganz einfach über Java direkt von [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) und verwenden Installieren Sie [Aspose.PDF für Android über Java](https://docs.aspose.com/pdf/androidjava/installation/) und [Aspose.Slides für Android über Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) in Ihren Anwendungen.

Alternativ können Sie eine ZIP-Datei von [downloads](https://downloads.aspose.com/total/androidjava) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PDF file with an instance of Document class
Document document = new Document("template.pdf");
// save PDF as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pot format
presentation.save("output.pot", SaveFormat.Pot);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Öffnen Sie eine passwortgeschützte PDF-Datei in Android über Java" %}}
Beim Laden des PDF-Dateiformats ist Ihr Dokument möglicherweise passwortgeschützt. [Aspose.PDF für Android über Java](https://products.aspose.com/pdf/android-java/) ermöglicht Ihnen auch verschlüsselte Dokumente zu öffnen. Um die verschlüsselte Datei zu öffnen, können Sie eine neue Instanz des [Dokuments](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) Klasse und übergeben Sie Dateiname und Passwort als Argumente.
{{% blocks/products/pf/feature-page-code %}}

```java
// open PDF document
Document doc = new Document("input.pdf", "Your@Password");
// save PDF as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Erstellen Sie ein Miniaturbild der POT-Datei in Android-Anwendungen" %}}
Nach der Konvertierung von PDF in POT können Sie auch Miniaturbilder Ihres Ausgabedokuments erstellen. Durch die Verwendung von [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) mit vielen Funktionen können Sie Miniaturbilder der Folien erstellen, indem Sie eine Instanz der [Präsentation]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) Klasse. Danach können Sie die Referenz jeder gewünschten Folie abrufen, indem Sie ihre ID oder ihren Index verwenden und das Miniaturbild der referenzierten Folie in einem bestimmten Maßstab erhalten.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a POT file
Presentation presentation = new Presentation("output.pot");
// access the first slide
ISlide sld = pres.getSlides().get_Item(0);
// create a full scale image
BufferedImage image = sld.getThumbnail(1f, 1f);
 // save the image to disk in PNG format
ImageIO.write(image, "PNG", new java.io.File("Thumbnail_out.png"));
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/pdf-to-ppsm/" name="PDF Zu PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/pdf-to-pps/" name="PDF Zu PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/pdf-to-potx/" name="PDF Zu POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/pdf-to-powerpoint/" name="PDF Zu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/pdf-to-swf/" name="PDF Zu SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/pdf-to-xaml/" name="PDF Zu XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/pdf-to-potm/" name="PDF Zu POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/pdf-to-pptm/" name="PDF Zu PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/pdf-to-otp/" name="PDF Zu OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/pdf-to-ppsx/" name="PDF Zu PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/pdf-to-pot/" name="PDF Zu POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/pdf-to-ppt/" name="PDF Zu PPT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}