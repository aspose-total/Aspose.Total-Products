---
title: Exportieren Sie PPTX nach WORD auf Andorid über Java oder mit dem kostenlosen Online Converter
description: Konvertieren Sie PPTX in WORD in mobilen Apps, ohne Software zu installieren oder online. Testen Sie schnell den kostenlosen CSV-zu-DOC-Online-Konverter, bevor Sie den Code integrieren.

family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: DOCX
otherformats: ODT DOTX DOT DOC FLATOPC WORDML RTF DOCM TEXT DOTM OTT DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendern Sie PPTX zu WORD auf Andorid über Java oder Online-App" h2="Dateiformat-APIs zum Konvertieren von PPTX in WORD in Android-Apps, ohne von Microsoft PowerPoint oder Word abhängig zu sein" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) ermöglicht die Manipulation von Dateiformaten in Android-Anwendungen. Durch die Verwendung der im Paket bereitgestellten APIs können Sie den Konvertierungsprozess von PowerPoint PPTX in Word WORD in Ihren Apps automatisieren.
Sie können Ihr angegebenes Dokument in zwei Schritten konvertieren. Sie können [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) verwenden, eine PowerPoint-API für Android-Anwendungen, um PPTX in HTML zu rendern. Danach können Sie mithilfe der Dokumentverarbeitungs-API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) den HTML-Code in WORD konvertieren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPTX-zu-WORD-Rendering in Android" %}}
1. Öffnen Sie die PPTX-Datei mit der Klasse [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation).
2. Konvertieren Sie PPTX in HTML mit [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) Methode und legen Sie Html als SaveFormat fest
3. Laden Sie die konvertierte HTML-Datei mit der Klasse [Wordument](https://reference.aspose.com/words/java/com.aspose.words/Wordument).
4. Speichern Sie das Dokument im WORD-Format mit der Methode [save](https://reference.aspose.com/words/java/com.aspose.words/Wordument#save(java.lang.String,int)) und legen Sie Word als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Android ganz einfach über Java direkt von [Maven](https://releases.aspose.com/total/java/) und verwenden Installieren Sie [Aspose.Slides for Android via Java](https://words.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) und [Aspose.Words für Andorid über Java](https://words.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in Ihrem Anwendungen.

Alternativ können Sie eine ZIP-Datei von [downloads](https://releases.aspose.comtotal/androidjava) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("input.pptx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Wordument
Wordument wordument = new Wordument("htmlOutput.html");
// save wordument in WORDX format
wordument.save("output.wordx",SaveFormat.Wordx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Kostenloser Online-Konverter für PPTX zu WORD</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=pptx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}