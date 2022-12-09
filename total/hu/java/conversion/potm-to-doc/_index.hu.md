---
title: Konvertálja a POTM-ot DOC-ba Java segítségével
description: Java API a POTM exportálásához DOC-ba Microsoft Word vagy PowerPoint használata nélkül
url_ignore: /hu/java/conversion/potm-to-doc/
family: total
platformtag: net
feature: conversion
informat: POTMM
outformat: DOC
otherformats: WORDML DOCX OTT ODT FLATOPC DOTM DOTX DOT DOCM RTF TEXT WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertálja a POTM-ot DOC-ba Java segítségével" h2="On Premise Java API a PowerPoint POTM-ból DOC konvertáláshoz bármely Java J2SE, J2EE, J2ME alkalmazáson belül" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) A fájlformátum-automatizálási könyvtárak lehetővé teszik a Java-fejlesztők számára, hogy automatizálják a PowerPoint POTM-ból Word DOC-ba történő kötegelt konvertálási folyamatát. A dokumentum konvertálása kétlépéses folyamat, és két API használatát foglalja magában. Az [Aspose.Slides for Java](https://products.aspose.com/slides/java/) alkalmazást fogjuk használni, amely egy PowerPoint API a prezentációk manipulálásához és kezeléséhez a POTM HTML-lé konvertálásához. Ezt követően a funkciókban gazdag szövegszerkesztő API [Aspose.Words for Java](https://products.aspose.com/words/java/) használatával a HTML-t DOC formátumba konvertáljuk.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet a POTM-ot DOC-ba konvertálni Java-n keresztül" %}}
1. Nyissa meg a POTM-fájlt a [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) osztály használatával
2. A [mentés](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) segítségével konvertálja a POTM-ot HTML-be. ISaveOptions-) metódust, és állítsa be a HTML-t SaveFormat-ként
3. Töltse be a konvertált HTML-fájlt a [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) osztály használatával
4. Mentse a dokumentumot DOC formátumba a [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) módszerrel
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
A POTM-ból DOC-fájlba konvertálásához egyszerűen használhatja az Aspose.Total for Java-t közvetlenül a [Maven]-ből (https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) alapú projektet, és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
Az API segítségével POTM fájlból DOC-ba konvertálhat vízjellel. Ha vízjelet szeretne hozzáadni a DOC dokumentumhoz, először konvertálja a POTM fájlt HTML formátumba, és vízjelet adjon hozzá. Vízjel hozzáadásához töltse be az újonnan létrehozott HTML-fájlt a [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) osztály segítségével, hozzon létre egy TextWatermarkOptions példányt, és állítsa be. tulajdonságai, Hívja meg a Watermark.setText metódust, és adja át a vízjel szövegét és a TextWatermarkOptions objektumát.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/potm-to-word/" name="POTM Nak nek WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/potm-to-dotx/" name="POTM Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/potm-to-odt/" name="POTM Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/potm-to-ott/" name="POTM Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/potm-to-rtf/" name="POTM Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/potm-to-flatopc/" name="POTM Nak nek FLANak nekPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/potm-to-wordml/" name="POTM Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/potm-to-docm/" name="POTM Nak nek DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/potm-to-text/" name="POTM Nak nek TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/potm-to-docx/" name="POTM Nak nek DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/potm-to-dotm/" name="POTM Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/potm-to-dot/" name="POTM Nak nek DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}