---
title: Konvertálja a PPSX-ot ODT-ba Java segítségével
description: Java API a PPSX exportálásához ODT-ba Microsoft Word vagy PowerPoint használata nélkül
url: /hu/java/conversion/ppsx-to-odt/
family: total
platformtag: net
feature: conversion
informat: PPSX
outformat: ODT
otherformats: DOT ODT RTF TEXT DOTX WORD FLATOPC ODTM OTT DOTM ODTX WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertálja a PPSX-ot ODT-ba Java segítségével" h2="On Premise Java API a PowerPoint PPSX-ból ODT konvertáláshoz bármely Java J2SE, J2EE, J2ME alkalmazáson belül" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) A fájlformátum-automatizálási könyvtárak lehetővé teszik a Java-fejlesztők számára, hogy automatizálják a PowerPoint PPSX-ból Word ODT-ba történő kötegelt konvertálási folyamatát. A dokumentum konvertálása kétlépéses folyamat, és két API használatát foglalja magában. Az [Aspose.Slides for Java](https://products.aspose.com/slides/java/) alkalmazást fogjuk használni, amely egy PowerPoint API a prezentációk manipulálásához és kezeléséhez a PPSX HTML-lé konvertálásához. Ezt követően a funkciókban gazdag szövegszerkesztő API [Aspose.Words for Java] (https://products.aspose.com/words/java/) használatával a HTML-t ODT formátumba konvertáljuk.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet a PPSX-ot ODT-ba konvertálni Java-n keresztül" %}}
1. Nyissa meg a PPSX-fájlt a [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) osztály használatával
2. A [mentés](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) segítségével konvertálja a PPSX-ot HTML-be. ISaveOptions-) metódust, és állítsa be a HTML-t SaveFormat-ként
3. Töltse be a konvertált HTML-fájlt a [Odtument](https://apireference.aspose.com/words/java/com.aspose.words/Odtument) osztály használatával
4. Mentse a dokumentumot ODT formátumba a [save](https://apireference.aspose.com/words/java/com.aspose.words/Odtument#save(java.lang.String,int)) módszerrel
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
A PPSX-ból ODT-fájlba konvertálásához egyszerűen használhatja az Aspose.Total for Java-t közvetlenül a [Maven]-ből (https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose /aspose-total) alapú projektet, és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads] webhelyről (https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
Az API segítségével PPSX fájlból ODT-ba konvertálhat vízjellel. Ha vízjelet szeretne hozzáadni a ODT dokumentumhoz, először konvertálja a PPSX fájlt HTML formátumba, és vízjelet adjon hozzá. Vízjel hozzáadásához töltse be az újonnan létrehozott HTML-fájlt a [Odtument](https://apireference.aspose.com/words/java/com.aspose.words/Odtument) osztály segítségével, hozzon létre egy TextWatermarkOptions példányt, és állítsa be. tulajdonságai, Hívja meg a Watermark.setText metódust, és adja át a vízjel szövegét és a TextWatermarkOptions objektumát.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsx-to-word/" name="PPSX Nak nek WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsx-to-dotx/" name="PPSX Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsx-to-odt/" name="PPSX Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsx-to-ott/" name="PPSX Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsx-to-rtf/" name="PPSX Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsx-to-flatopc/" name="PPSX Nak nek FLANak nekPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsx-to-wordml/" name="PPSX Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsx-to-odtm/" name="PPSX Nak nek ODTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsx-to-text/" name="PPSX Nak nek TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsx-to-odtx/" name="PPSX Nak nek ODTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsx-to-dotm/" name="PPSX Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ppsx-to-dot/" name="PPSX Nak nek DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}