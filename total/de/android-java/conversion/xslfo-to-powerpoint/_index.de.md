---
title: Exportieren Sie XSLFO in POWERPOINT in Android
description: Android-API zum Konvertieren von XSLFO in POWERPOINT ohne Verwendung von Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: XSLFO
outformat: PPT
otherformats: POT PPSX PPT OTP SWF POTX PPTM PPSM ODP PPS XAML POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertieren Sie XSLFO in POWERPOINT auf Android über Java" h2="Wandeln Sie XSLFO innerhalb Ihrer Android-Anwendungen in POWERPOINT um, ohne Microsoft<sup>&reg;</sup> PowerPoint oder Adobe<sup>&reg;</sup> Acrobat Reader zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sie können die XSLFO-zu-POWERPOINT-Konvertierungsfunktion in Ihre Android-Anwendungen integrieren, indem Sie zwei einfache Schritte ausführen. Im ersten Schritt können Sie XSLFO nach PPTX exportieren, indem Sie [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) verwenden. Danach können Sie mit [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) PPTX in POWERPOINT konvertieren. Beide APIs sind im Paket [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) enthalten. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android-API zum Exportieren von XSLFO in POWERPOINT" %}}
1. Öffnen Sie die XSLFO-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Konvertieren Sie XSLFO in PPTX, indem Sie die Methode [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) verwenden
3. Laden Sie das PPTX-Dokument mithilfe der Klasse [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation).
4. Speichern Sie das Dokument im POWERPOINT-Format mit der Methode [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) und setzen Sie ` Powerpoint` als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Android ganz einfach über Java direkt von [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) und verwenden Installieren Sie [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) und [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) in Ihren Anwendungen.

Alternativ können Sie eine ZIP-Datei von [downloads](https://releases.aspose.comtotal/androidjava) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XSLFO file with an instance of Document class
Document document = new Document("template.xslfo");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Öffnen Sie eine passwortgeschützte XSLFO-Datei in Android über Java" %}}
Beim Laden des XSLFO-Dateiformats ist Ihr Dokument möglicherweise passwortgeschützt. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) ermöglicht Ihnen auch verschlüsselte Dokumente zu öffnen. Um die verschlüsselte Datei zu öffnen, können Sie eine neue Instanz des [Dokuments](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) Klasse und übergeben Sie Dateiname und Passwort als Argumente.
{{% blocks/products/pf/feature-page-code %}}

```java
// open XSLFO document
Document doc = new Document("input.xslfo", "Your@Password");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Erstellen Sie ein Miniaturbild der POWERPOINT-Datei in Android-Anwendungen" %}}
Nach der Konvertierung von XSLFO in POWERPOINT können Sie auch Miniaturbilder Ihres Ausgabedokuments erstellen. Durch die Verwendung von [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) mit vielen Funktionen können Sie Miniaturbilder der Folien erstellen, indem Sie eine Instanz der [Präsentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) Klasse. Danach können Sie die Referenz jeder gewünschten Folie abrufen, indem Sie ihre ID oder ihren Index verwenden und das Miniaturbild der referenzierten Folie in einem bestimmten Maßstab erhalten.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a POWERPOINT file
Presentation presentation = new Presentation("output.powerpoint");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xslfo-to-pot/" name="XSLFO Zu POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xslfo-to-ppsx/" name="XSLFO Zu PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xslfo-to-ppt/" name="XSLFO Zu PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xslfo-to-otp/" name="XSLFO Zu OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xslfo-to-swf/" name="XSLFO Zu SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xslfo-to-potx/" name="XSLFO Zu POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xslfo-to-pptm/" name="XSLFO Zu PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xslfo-to-ppsm/" name="XSLFO Zu PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xslfo-to-powerpoint/" name="XSLFO Zu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xslfo-to-pps/" name="XSLFO Zu PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xslfo-to-xaml/" name="XSLFO Zu XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/xslfo-to-potm/" name="XSLFO Zu POTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}