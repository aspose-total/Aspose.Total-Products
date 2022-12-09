---
title: Exportálja a PPT-ot WORD-ba Andoridon Java-n keresztül
description: Konvertálja a PPT-ot WORD-ba mobilalkalmazásokban szoftver telepítése nélkül

family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: DOCX
otherformats: DOTX DOC DOTM ODT DOCM RTF DOCX OTT WORDML TEXT FLATOPC DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderelje le a PPT-ot WORD-ba Andoridon Java-n keresztül" h2="Fájlformátumú API-k, amelyek a PPT-t WORD-ba konvertálják Android-alkalmazásokon belül, anélkül, hogy a Microsoft PowerPointtól vagy a Wordtől függnének" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for Android Java segítségével](https://products.aspose.com/total/android-java/) lehetővé teszi a fájlformátumok manipulálását az Android-alkalmazásokon belül. A csomagban található API-k használatával automatizálhatja a PowerPoint PPT–Word WORD konverziós folyamatát alkalmazásaiban.
A megadott dokumentumot két lépésben konvertálhatja. Az [Aspose.Slides for Andorid Java-n keresztül](https://products.aspose.com/slides/android-java/) segítségével, amely egy PowerPoint API Android-alkalmazásokhoz, a PPT-ot HTML-be rendereli. Ezt követően a dokumentumfeldolgozó API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) használatával konvertálhatja a HTML-t WORD formátumba. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPT to WORD renderelés Androidon" %}}
1. Nyissa meg a PPT-fájlt a [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) osztály használatával
2. A [mentés](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) segítségével konvertálja a PPT-ot HTML-be.ISaveOptions-) metódust, és állítsa be a HTML-t SaveFormat-ként
3. Töltse be a konvertált HTML-fájlt a [Wordument](https://reference.aspose.com/words/java/com.aspose.words/Wordument) osztály használatával
4. Mentse a dokumentumot WORD formátumba a [save](https://reference.aspose.com/words/java/com.aspose.words/Wordument#save(java.lang.String,int)) módszerrel, és állítsa be a Word beállítást mint SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Könnyedén használhatja az Aspose.Total for Android rendszert Java-n keresztül közvetlenül a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) webhelyről és telepítse az [Aspose.Slides for Android via Java](https://words.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) és az [Aspose.Words for Andorid via Java] alkalmazást. (https://words.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) alkalmazások.

Másik megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/androidjava) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPT file
Presentation presentation = new Presentation("input.ppt");
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
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/ppt-to-dotx/" name="PPT Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/ppt-to-word/" name="PPT Nak nek WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/ppt-to-dotm/" name="PPT Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/ppt-to-odt/" name="PPT Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/ppt-to-wordm/" name="PPT Nak nek WORDM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/ppt-to-rtf/" name="PPT Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/ppt-to-wordx/" name="PPT Nak nek WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/ppt-to-ott/" name="PPT Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/ppt-to-wordml/" name="PPT Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/ppt-to-text/" name="PPT Nak nek TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/ppt-to-flatopc/" name="PPT Nak nek FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/ppt-to-dot/" name="PPT Nak nek DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}