---
title: Exportieren Sie PPSX nach OTT auf Andorid über Java
description: Konvertieren Sie PPSX in OTT in mobilen Apps, ohne Software zu installieren
url: /de/android-java/conversion/ppsx-to-ott/
family: total
platformtag: cpp
feature: conversion
informat: PPSX
outformat: OTT
otherformats: DOCM DOCX FLATOPC WORD RTF DOTX WORDML TEXT ODT DOT DOC DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendern Sie PPSX zu OTT auf Andorid über Java" h2="Dateiformat-APIs zum Konvertieren von PPSX in OTT in Android-Apps, ohne von Microsoft PowerPoint oder Word abhängig zu sein" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) ermöglicht die Manipulation von Dateiformaten in Android-Anwendungen. Durch die Verwendung der im Paket bereitgestellten APIs können Sie den Konvertierungsprozess von PowerPoint PPSX in Word OTT in Ihren Apps automatisieren.
Sie können Ihr angegebenes Dokument in zwei Schritten konvertieren. Sie können [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) verwenden, eine PowerPoint-API für Android-Anwendungen, um PPSX in HTML zu rendern. Danach können Sie mithilfe der Dokumentverarbeitungs-API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) den HTML-Code in OTT konvertieren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPSX-zu-OTT-Rendering in Android" %}}
1. Öffnen Sie die PPSX-Datei mit der Klasse [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation).
2. Konvertieren Sie PPSX in HTML mit [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) Methode und legen Sie Html als SaveFormat fest
3. Laden Sie die konvertierte HTML-Datei mit der Klasse [Ottument](https://reference.aspose.com/words/java/com.aspose.words/Ottument).
4. Speichern Sie das Dokument im OTT-Format mit der Methode [save](https://reference.aspose.com/words/java/com.aspose.words/Ottument#save(java.lang.String,int)) und legen Sie Ott als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Android ganz einfach über Java direkt von [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) und verwenden Installieren Sie [Aspose.Slides for Android via Java](https://otts.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) und [Aspose.Words für Andorid über Java](https://otts.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in Ihrem Anwendungen.

Alternativ können Sie eine ZIP-Datei von [downloads](https://downloads.aspose.com/total/androidjava) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPSX file
Presentation presentation = new Presentation("input.ppsx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Ottument
Ottument ottument = new Ottument("htmlOutput.html");
// save ottument in OTT format
ottument.save("output.ott",SaveFormat.Ott);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/ppsx-to-ottm/" name="PPSX Zu OTTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/ppsx-to-ottx/" name="PPSX Zu OTTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/ppsx-to-flatopc/" name="PPSX Zu FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/ppsx-to-word/" name="PPSX Zu WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/ppsx-to-rtf/" name="PPSX Zu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/ppsx-to-dotx/" name="PPSX Zu DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/ppsx-to-wordml/" name="PPSX Zu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/ppsx-to-text/" name="PPSX Zu TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/ppsx-to-odt/" name="PPSX Zu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/ppsx-to-dot/" name="PPSX Zu DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/ppsx-to-ott/" name="PPSX Zu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/ppsx-to-dotm/" name="PPSX Zu DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}