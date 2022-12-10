---
title: Exportieren Sie POTM nach DOCM auf Andorid über Java
description: Konvertieren Sie POTM in DOCM in mobilen Apps, ohne Software zu installieren

family: total
platformtag: cpp
feature: conversion
informat: POTM
outformat: DOCM
otherformats: WORDML FLATOPC OTT DOT DOC DOCX ODT DOTX TEXT DOTM WORD RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendern Sie POTM zu DOCM auf Andorid über Java" h2="Dateiformat-APIs zum Konvertieren von POTM in DOCM in Android-Apps, ohne von Microsoft PowerPoint oder Word abhängig zu sein" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) ermöglicht die Manipulation von Dateiformaten in Android-Anwendungen. Durch die Verwendung der im Paket bereitgestellten APIs können Sie den Konvertierungsprozess von PowerPoint POTM in Word DOCM in Ihren Apps automatisieren.
Sie können Ihr angegebenes Dokument in zwei Schritten konvertieren. Sie können [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) verwenden, eine PowerPoint-API für Android-Anwendungen, um POTM in HTML zu rendern. Danach können Sie mithilfe der Dokumentverarbeitungs-API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) den HTML-Code in DOCM konvertieren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="POTM-zu-DOCM-Rendering in Android" %}}
1. Öffnen Sie die POTM-Datei mit der Klasse [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation).
2. Konvertieren Sie POTM in HTML mit [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) Methode und legen Sie Html als SaveFormat fest
3. Laden Sie die konvertierte HTML-Datei mit der Klasse [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
4. Speichern Sie das Dokument im DOCM-Format mit der Methode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) und legen Sie Docm als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Android ganz einfach über Java direkt von [Maven](https://releases.aspose.com/total/java/) und verwenden Installieren Sie [Aspose.Slides for Android via Java](https://docms.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) und [Aspose.Words für Andorid über Java](https://docms.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in Ihrem Anwendungen.

Alternativ können Sie eine ZIP-Datei von [downloads](https://releases.aspose.comtotal/androidjava) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POTM file
Presentation presentation = new Presentation("input.potm");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Document
Document docmument = new Document("htmlOutput.html");
// save docmument in DOCM format
docmument.save("output.docm",SaveFormat.Docmm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/potm-to-wordml/" name="POTM Zu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/potm-to-flatopc/" name="POTM Zu FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/potm-to-ott/" name="POTM Zu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/potm-to-dot/" name="POTM Zu DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/potm-to-docm/" name="POTM Zu DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/potm-to-docmx/" name="POTM Zu DOCMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/potm-to-odt/" name="POTM Zu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/potm-to-dotx/" name="POTM Zu DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/potm-to-text/" name="POTM Zu TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/potm-to-dotm/" name="POTM Zu DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/potm-to-word/" name="POTM Zu WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/android-java/conversion/potm-to-rtf/" name="POTM Zu RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}