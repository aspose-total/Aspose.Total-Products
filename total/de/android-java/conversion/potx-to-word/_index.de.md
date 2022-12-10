---
title: Exportieren Sie POTX nach WORD auf Andorid über Java
description: Konvertieren Sie POTX in WORD in mobilen Apps, ohne Software zu installieren

family: total
platformtag: cpp
feature: conversion
informat: POTX
outformat: DOCX
otherformats: FLATOPC RTF DOCX ODT TEXT DOC DOTX DOCM DOTM OTT WORDML DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendern Sie POTX zu WORD auf Andorid über Java" h2="Dateiformat-APIs zum Konvertieren von POTX in WORD in Android-Apps, ohne von Microsoft PowerPoint oder Word abhängig zu sein" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) ermöglicht die Manipulation von Dateiformaten in Android-Anwendungen. Durch die Verwendung der im Paket bereitgestellten APIs können Sie den Konvertierungsprozess von PowerPoint POTX in Word WORD in Ihren Apps automatisieren.
Sie können Ihr angegebenes Dokument in zwei Schritten konvertieren. Sie können [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) verwenden, eine PowerPoint-API für Android-Anwendungen, um POTX in HTML zu rendern. Danach können Sie mithilfe der Dokumentverarbeitungs-API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) den HTML-Code in WORD konvertieren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="POTX-zu-WORD-Rendering in Android" %}}
1. Öffnen Sie die POTX-Datei mit der Klasse [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation).
2. Konvertieren Sie POTX in HTML mit [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) Methode und legen Sie Html als SaveFormat fest
3. Laden Sie die konvertierte HTML-Datei mit der Klasse [Wordument](https://reference.aspose.com/words/java/com.aspose.words/Wordument).
4. Speichern Sie das Dokument im WORD-Format mit der Methode [save](https://reference.aspose.com/words/java/com.aspose.words/Wordument#save(java.lang.String,int)) und legen Sie Word als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Android ganz einfach über Java direkt von [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) und verwenden Installieren Sie [Aspose.Slides for Android via Java](https://words.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) und [Aspose.Words für Andorid über Java](https://words.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in Ihrem Anwendungen.

Alternativ können Sie eine ZIP-Datei von [downloads](https://releases.aspose.comtotal/androidjava) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POTX file
Presentation presentation = new Presentation("input.potx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Wordument
Wordument wordument = new Wordument("htmlOutput.html");
// save wordument in WORDX format
wordument.save("output.wordx",SaveFormat.Wordx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/potx-to-flatopc/" name="POTX Zu FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/potx-to-rtf/" name="POTX Zu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/potx-to-wordx/" name="POTX Zu WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/potx-to-odt/" name="POTX Zu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/potx-to-text/" name="POTX Zu TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/potx-to-word/" name="POTX Zu WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/potx-to-dotx/" name="POTX Zu DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/potx-to-wordm/" name="POTX Zu WORDM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/potx-to-dotm/" name="POTX Zu DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/potx-to-ott/" name="POTX Zu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/potx-to-wordml/" name="POTX Zu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/potx-to-dot/" name="POTX Zu DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}