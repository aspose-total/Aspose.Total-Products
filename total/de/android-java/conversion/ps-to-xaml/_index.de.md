---
title: Exportieren Sie PS in XAML in Android
description: Android-API zum Konvertieren von PS in XAML ohne Verwendung von Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: PS
outformat: XAML
otherformats: POTX PPTM SWF OTP PPSX PPT POT PPS PPSM ODP POTM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertieren Sie PS in XAML auf Android über Java" h2="Wandeln Sie PS innerhalb Ihrer Android-Anwendungen in XAML um, ohne Microsoft<sup>&reg;</sup> PowerPoint oder Adobe<sup>&reg;</sup> Acrobat Reader zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sie können die PS-zu-XAML-Konvertierungsfunktion in Ihre Android-Anwendungen integrieren, indem Sie zwei einfache Schritte ausführen. Im ersten Schritt können Sie PS nach PPTX exportieren, indem Sie [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) verwenden. Danach können Sie mit [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) PPTX in XAML konvertieren. Beide APIs sind im Paket [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) enthalten. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android-API zum Exportieren von PS in XAML" %}}
1. Öffnen Sie die PS-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Konvertieren Sie PS in PPTX, indem Sie die Methode [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) verwenden
3. Laden Sie das PPTX-Dokument mithilfe der Klasse [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation).
4. Speichern Sie das Dokument im XAML-Format mit der Methode [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) und setzen Sie ` Xaml` als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Android ganz einfach über Java direkt von [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) und verwenden Installieren Sie [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) und [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) in Ihren Anwendungen.

Alternativ können Sie eine ZIP-Datei von [downloads](https://downloads.aspose.com/total/androidjava) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PS file with an instance of Document class
Document document = new Document("template.ps");
// save PS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Xaml format
presentation.save("output.xaml", SaveFormat.Xaml);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Öffnen Sie eine passwortgeschützte PS-Datei in Android über Java" %}}
Beim Laden des PS-Dateiformats ist Ihr Dokument möglicherweise passwortgeschützt. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) ermöglicht Ihnen auch verschlüsselte Dokumente zu öffnen. Um die verschlüsselte Datei zu öffnen, können Sie eine neue Instanz des [Dokuments](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) Klasse und übergeben Sie Dateiname und Passwort als Argumente.
{{% blocks/products/pf/feature-page-code %}}

```java
// open PS document
Document doc = new Document("input.ps", "Your@Password");
// save PS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Erstellen Sie ein Miniaturbild der XAML-Datei in Android-Anwendungen" %}}
Nach der Konvertierung von PS in XAML können Sie auch Miniaturbilder Ihres Ausgabedokuments erstellen. Durch die Verwendung von [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) mit vielen Funktionen können Sie Miniaturbilder der Folien erstellen, indem Sie eine Instanz der [Präsentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) Klasse. Danach können Sie die Referenz jeder gewünschten Folie abrufen, indem Sie ihre ID oder ihren Index verwenden und das Miniaturbild der referenzierten Folie in einem bestimmten Maßstab erhalten.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a XAML file
Presentation presentation = new Presentation("output.xaml");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/ps-to-potx/" name="PS Zu POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/ps-to-pptm/" name="PS Zu PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/ps-to-swf/" name="PS Zu SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/ps-to-otp/" name="PS Zu OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/ps-to-ppsx/" name="PS Zu PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/ps-to-ppt/" name="PS Zu PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/ps-to-pot/" name="PS Zu POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/ps-to-pps/" name="PS Zu PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/ps-to-ppsm/" name="PS Zu PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/ps-to-xaml/" name="PS Zu XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/ps-to-potm/" name="PS Zu POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/ps-to-powerpoint/" name="PS Zu POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}