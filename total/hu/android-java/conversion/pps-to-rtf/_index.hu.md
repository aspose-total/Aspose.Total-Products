---
title: Exportálja a PPS-ot RTF-ba Andoridon Java-n keresztül
description: Konvertálja a PPS-ot RTF-ba mobilalkalmazásokban szoftver telepítése nélkül
url: /hu/android-java/conversion/pps-to-rtf/
family: total
platformtag: cpp
feature: conversion
informat: PPS
outformat: RTF
otherformats: DOTM DOT ODT WORD TEXT WORDML DOTX DOCM DOC OTT FLATOPC DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderelje le a PPS-ot RTF-ba Andoridon Java-n keresztül" h2="Fájlformátumú API-k, amelyek a PPS-t RTF-ba konvertálják Android-alkalmazásokon belül, anélkül, hogy a Microsoft PowerPointtól vagy a Wordtől függnének" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for Android Java segítségével](https://products.aspose.com/total/android-java/) lehetővé teszi a fájlformátumok manipulálását az Android-alkalmazásokon belül. A csomagban található API-k használatával automatizálhatja a PowerPoint PPS–Word RTF konverziós folyamatát alkalmazásaiban.
A megadott dokumentumot két lépésben konvertálhatja. Az [Aspose.Slides for Andorid Java-n keresztül](https://products.aspose.com/slides/android-java/) segítségével, amely egy PowerPoint API Android-alkalmazásokhoz, a PPS-ot HTML-be rendereli. Ezt követően a dokumentumfeldolgozó API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) használatával konvertálhatja a HTML-t RTF formátumba. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPS to RTF renderelés Androidon" %}}
1. Nyissa meg a PPS-fájlt a [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) osztály használatával
2. A [mentés](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) segítségével konvertálja a PPS-ot HTML-be.ISaveOptions-) metódust, és állítsa be a HTML-t SaveFormat-ként
3. Töltse be a konvertált HTML-fájlt a [Rtfument](https://reference.aspose.com/words/java/com.aspose.words/Rtfument) osztály használatával
4. Mentse a dokumentumot RTF formátumba a [save](https://reference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String,int)) módszerrel, és állítsa be a Rtf beállítást mint SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Könnyedén használhatja az Aspose.Total for Android rendszert Java-n keresztül közvetlenül a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) webhelyről és telepítse az [Aspose.Slides for Android via Java](https://rtfs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) és az [Aspose.Words for Andorid via Java] alkalmazást. (https://rtfs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) alkalmazások.

Másik megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://downloads.aspose.com/total/androidjava) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPS file
Presentation presentation = new Presentation("input.pps");
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
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pps-to-dotm/" name="PPS Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pps-to-dot/" name="PPS Nak nek DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pps-to-odt/" name="PPS Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pps-to-word/" name="PPS Nak nek WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pps-to-text/" name="PPS Nak nek TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pps-to-wordml/" name="PPS Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pps-to-dotx/" name="PPS Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pps-to-rtfm/" name="PPS Nak nek RTFM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pps-to-rtf/" name="PPS Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pps-to-ott/" name="PPS Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pps-to-flatopc/" name="PPS Nak nek FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pps-to-rtfx/" name="PPS Nak nek RTFX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}