---
title: Exportieren Sie PPTX nach RTF auf Andorid über Java
description: Konvertieren Sie PPTX in RTF in mobilen Apps, ohne Software zu installieren
url: /de/android-java/conversion/pptx-to-rtf/
family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: RTF
otherformats: FLATOPC DOTX WORD TEXT DOCM ODT OTT DOCX WORDML DOC DOTM DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendern Sie PPTX zu RTF auf Andorid über Java" h2="Dateiformat-APIs zum Konvertieren von PPTX in RTF in Android-Apps, ohne von Microsoft PowerPoint oder Word abhängig zu sein" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) ermöglicht die Manipulation von Dateiformaten in Android-Anwendungen. Durch die Verwendung der im Paket bereitgestellten APIs können Sie den Konvertierungsprozess von PowerPoint PPTX in Word RTF in Ihren Apps automatisieren.
Sie können Ihr angegebenes Dokument in zwei Schritten konvertieren. Sie können [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) verwenden, eine PowerPoint-API für Android-Anwendungen, um PPTX in HTML zu rendern. Danach können Sie mithilfe der Dokumentverarbeitungs-API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) den HTML-Code in RTF konvertieren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPTX-zu-RTF-Rendering in Android" %}}
1. Öffnen Sie die PPTX-Datei mit der Klasse [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation).
2. Konvertieren Sie PPTX in HTML mit [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) Methode und legen Sie Html als SaveFormat fest
3. Laden Sie die konvertierte HTML-Datei mit der Klasse [Rtfument](https://reference.aspose.com/words/java/com.aspose.words/Rtfument).
4. Speichern Sie das Dokument im RTF-Format mit der Methode [save](https://reference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String,int)) und legen Sie Rtf als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Android ganz einfach über Java direkt von [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) und verwenden Installieren Sie [Aspose.Slides for Android via Java](https://rtfs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) und [Aspose.Words für Andorid über Java](https://rtfs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in Ihrem Anwendungen.

Alternativ können Sie eine ZIP-Datei von [downloads](https://downloads.aspose.com/total/androidjava) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("input.pptx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Rtfument
Rtfument rtfument = new Rtfument("htmlOutput.html");
// save rtfument in RTF format
rtfument.save("output.rtf",SaveFormat.Rtf);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/pptx-to-flatopc/" name="PPTX Zu FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/pptx-to-dotx/" name="PPTX Zu DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/pptx-to-word/" name="PPTX Zu WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/pptx-to-text/" name="PPTX Zu TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/pptx-to-rtfm/" name="PPTX Zu RTFM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/pptx-to-odt/" name="PPTX Zu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/pptx-to-ott/" name="PPTX Zu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/pptx-to-rtfx/" name="PPTX Zu RTFX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/pptx-to-wordml/" name="PPTX Zu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/pptx-to-rtf/" name="PPTX Zu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/pptx-to-dotm/" name="PPTX Zu DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/pptx-to-dot/" name="PPTX Zu DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}