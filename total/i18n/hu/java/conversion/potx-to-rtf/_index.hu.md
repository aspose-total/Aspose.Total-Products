---
title: Konvertálja a POTX-ot RTF-ba Java segítségével
description: Java API a POTX exportálásához RTF-ba Microsoft Word vagy PowerPoint használata nélkül
url: /hu/java/conversion/potx-to-rtf/
family: total
platformtag: net
feature: conversion
informat: POTXX
outformat: RTF
otherformats: RTF DOTM FLATOPC WORDML WORD TEXT ODT RTFM RTFX DOT DOTX OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertálja a POTX-ot RTF-ba Java segítségével" h2="On Premise Java API a PowerPoint POTX-ból RTF konvertáláshoz bármely Java J2SE, J2EE, J2ME alkalmazáson belül" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) A fájlformátum-automatizálási könyvtárak lehetővé teszik a Java-fejlesztők számára, hogy automatizálják a PowerPoint POTX-ból Word RTF-ba történő kötegelt konvertálási folyamatát. A dokumentum konvertálása kétlépéses folyamat, és két API használatát foglalja magában. Az [Aspose.Slides for Java](https://products.aspose.com/slides/java/) alkalmazást fogjuk használni, amely egy PowerPoint API a prezentációk manipulálásához és kezeléséhez a POTX HTML-lé konvertálásához. Ezt követően a funkciókban gazdag szövegszerkesztő API [Aspose.Words for Java](https://products.aspose.com/words/java/) használatával a HTML-t RTF formátumba konvertáljuk.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet a POTX-ot RTF-ba konvertálni Java-n keresztül" %}}
1. Nyissa meg a POTX-fájlt a [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) osztály használatával
2. A [mentés](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) segítségével konvertálja a POTX-ot HTML-be. ISaveOptions-) metódust, és állítsa be a HTML-t SaveFormat-ként
3. Töltse be a konvertált HTML-fájlt a [Rtfument](https://apireference.aspose.com/words/java/com.aspose.words/Rtfument) osztály használatával
4. Mentse a dokumentumot RTF formátumba a [save](https://apireference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String,int)) módszerrel
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
A POTX-ból RTF-fájlba konvertálásához egyszerűen használhatja az Aspose.Total for Java-t közvetlenül a [Maven]-ből (https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose /aspose-total) alapú projektet, és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads] webhelyről (https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
Az API segítségével POTX fájlból RTF-ba konvertálhat vízjellel. Ha vízjelet szeretne hozzáadni a RTF dokumentumhoz, először konvertálja a POTX fájlt HTML formátumba, és vízjelet adjon hozzá. Vízjel hozzáadásához töltse be az újonnan létrehozott HTML-fájlt a [Rtfument](https://apireference.aspose.com/words/java/com.aspose.words/Rtfument) osztály segítségével, hozzon létre egy TextWatermarkOptions példányt, és állítsa be. tulajdonságai, Hívja meg a Watermark.setText metódust, és adja át a vízjel szövegét és a TextWatermarkOptions objektumát.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/potx-to-word/" name="POTX Nak nek WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/potx-to-dotx/" name="POTX Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/potx-to-odt/" name="POTX Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/potx-to-ott/" name="POTX Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/potx-to-rtf/" name="POTX Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/potx-to-flatopc/" name="POTX Nak nek FLANak nekPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/potx-to-wordml/" name="POTX Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/potx-to-rtfm/" name="POTX Nak nek RTFM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/potx-to-text/" name="POTX Nak nek TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/potx-to-rtfx/" name="POTX Nak nek RTFX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/potx-to-dotm/" name="POTX Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/potx-to-dot/" name="POTX Nak nek DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}