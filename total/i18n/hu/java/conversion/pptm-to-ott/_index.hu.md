---
title: Konvertálja a PPTM-ot OTT-ba Java segítségével
description: Java API a PPTM exportálásához OTT-ba Microsoft Word vagy PowerPoint használata nélkül
url: /hu/java/conversion/pptm-to-ott/
family: total
platformtag: net
feature: conversion
informat: PPTM
outformat: OTT
otherformats: TEXT OTTX FLATOPC DOTX RTF DOTM OTTM WORD ODT DOT WORDML OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertálja a PPTM-ot OTT-ba Java segítségével" h2="On Premise Java API a PowerPoint PPTM-ból OTT konvertáláshoz bármely Java J2SE, J2EE, J2ME alkalmazáson belül" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) A fájlformátum-automatizálási könyvtárak lehetővé teszik a Java-fejlesztők számára, hogy automatizálják a PowerPoint PPTM-ból Word OTT-ba történő kötegelt konvertálási folyamatát. A dokumentum konvertálása kétlépéses folyamat, és két API használatát foglalja magában. Az [Aspose.Slides for Java](https://products.aspose.com/slides/java/) alkalmazást fogjuk használni, amely egy PowerPoint API a prezentációk manipulálásához és kezeléséhez a PPTM HTML-lé konvertálásához. Ezt követően a funkciókban gazdag szövegszerkesztő API [Aspose.Words for Java](https://products.aspose.com/words/java/) használatával a HTML-t OTT formátumba konvertáljuk.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet a PPTM-ot OTT-ba konvertálni Java-n keresztül" %}}
1. Nyissa meg a PPTM-fájlt a [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) osztály használatával
2. A [mentés](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) segítségével konvertálja a PPTM-ot HTML-be. ISaveOptions-) metódust, és állítsa be a HTML-t SaveFormat-ként
3. Töltse be a konvertált HTML-fájlt a [Ottument](https://apireference.aspose.com/words/java/com.aspose.words/Ottument) osztály használatával
4. Mentse a dokumentumot OTT formátumba a [save](https://apireference.aspose.com/words/java/com.aspose.words/Ottument#save(java.lang.String,int)) módszerrel
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
A PPTM-ból OTT-fájlba konvertálásához egyszerűen használhatja az Aspose.Total for Java-t közvetlenül a [Maven]-ből (https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose /aspose-total) alapú projektet, és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads] webhelyről (https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
Az API segítségével PPTM fájlból OTT-ba konvertálhat vízjellel. Ha vízjelet szeretne hozzáadni a OTT dokumentumhoz, először konvertálja a PPTM fájlt HTML formátumba, és vízjelet adjon hozzá. Vízjel hozzáadásához töltse be az újonnan létrehozott HTML-fájlt a [Ottument](https://apireference.aspose.com/words/java/com.aspose.words/Ottument) osztály segítségével, hozzon létre egy TextWatermarkOptions példányt, és állítsa be. tulajdonságai, Hívja meg a Watermark.setText metódust, és adja át a vízjel szövegét és a TextWatermarkOptions objektumát.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptm-to-word/" name="PPTM Nak nek WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptm-to-dotx/" name="PPTM Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptm-to-odt/" name="PPTM Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptm-to-ott/" name="PPTM Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptm-to-rtf/" name="PPTM Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptm-to-flatopc/" name="PPTM Nak nek FLANak nekPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptm-to-wordml/" name="PPTM Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptm-to-ottm/" name="PPTM Nak nek OTTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptm-to-text/" name="PPTM Nak nek TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptm-to-ottx/" name="PPTM Nak nek OTTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptm-to-dotm/" name="PPTM Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pptm-to-dot/" name="PPTM Nak nek DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}