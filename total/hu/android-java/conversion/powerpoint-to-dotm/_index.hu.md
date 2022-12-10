---
title: Exportálja a POWERPOINT-ot DOTM-ba Andoridon Java-n keresztül
description: Konvertálja a POWERPOINT-ot DOTM-ba mobilalkalmazásokban szoftver telepítése nélkül

family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: DOTM
otherformats: WORDML OTT DOTX TEXT RTF FLATOPC DOCX WORD DOCM DOT ODT DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderelje le a POWERPOINT-ot DOTM-ba Andoridon Java-n keresztül" h2="Fájlformátumú API-k, amelyek a POWERPOINT-t DOTM-ba konvertálják Android-alkalmazásokon belül, anélkül, hogy a Microsoft PowerPointtól vagy a Wordtől függnének" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for Android Java segítségével](https://products.aspose.com/total/android-java/) lehetővé teszi a fájlformátumok manipulálását az Android-alkalmazásokon belül. A csomagban található API-k használatával automatizálhatja a PowerPoint POWERPOINT–Word DOTM konverziós folyamatát alkalmazásaiban.
A megadott dokumentumot két lépésben konvertálhatja. Az [Aspose.Slides for Andorid Java-n keresztül](https://products.aspose.com/slides/android-java/) segítségével, amely egy PowerPoint API Android-alkalmazásokhoz, a POWERPOINT-ot HTML-be rendereli. Ezt követően a dokumentumfeldolgozó API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) használatával konvertálhatja a HTML-t DOTM formátumba. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="POWERPOINT to DOTM renderelés Androidon" %}}
1. Nyissa meg a POWERPOINT-fájlt a [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) osztály használatával
2. A [mentés](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) segítségével konvertálja a POWERPOINT-ot HTML-be.ISaveOptions-) metódust, és állítsa be a HTML-t SaveFormat-ként
3. Töltse be a konvertált HTML-fájlt a [Dotmument](https://reference.aspose.com/words/java/com.aspose.words/Dotmument) osztály használatával
4. Mentse a dokumentumot DOTM formátumba a [save](https://reference.aspose.com/words/java/com.aspose.words/Dotmument#save(java.lang.String,int)) módszerrel, és állítsa be a Dotm beállítást mint SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Könnyedén használhatja az Aspose.Total for Android rendszert Java-n keresztül közvetlenül a [Maven](https://releases.aspose.com/total/java/) webhelyről és telepítse az [Aspose.Slides for Android via Java](https://dotms.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) és az [Aspose.Words for Andorid via Java] alkalmazást. (https://dotms.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) alkalmazások.

Másik megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/androidjava) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POWERPOINT file
Presentation presentation = new Presentation("input.pptx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Dotmument
Dotmument dotmument = new Dotmument("htmlOutput.html");
// save dotmument in DOTM format
dotmument.save("output.dotm",SaveFormat.Dotm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pptx-to-wordml/" name="PPTX Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pptx-to-ott/" name="PPTX Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pptx-to-dotx/" name="PPTX Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pptx-to-text/" name="PPTX Nak nek TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pptx-to-rtf/" name="PPTX Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pptx-to-flatopc/" name="PPTX Nak nek FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pptx-to-dotmx/" name="PPTX Nak nek DOTMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pptx-to-word/" name="PPTX Nak nek WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pptx-to-dotmm/" name="PPTX Nak nek DOTMM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pptx-to-dot/" name="PPTX Nak nek DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pptx-to-odt/" name="PPTX Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pptx-to-dotm/" name="PPTX Nak nek DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}