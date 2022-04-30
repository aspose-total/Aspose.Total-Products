---
title: A WORDML konvertálása POT-re Java segítségével
description: Java API a WORDML exportálásához POT-be Microsoft Word vagy PowerPoint használata nélkül
url: /hu/java/conversion/wordml-to-pot/
family: total
platformtag: net
feature: conversion
informat: WORDML
outformat: POT
otherformats: PPSX POTM PPSM PPTM POWERPOINT POT PPS PPTX PPT POTX CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="A WORDML konvertálása POT-re Java segítségével" h2="WORDML konvertálása POT-be helyszíni Java API használatával bármely Java J2SE, J2EE, J2ME alkalmazáson belül Microsoft<sup>&reg;</sup> PowerPoint vagy Word használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
A fejlesztőknek gyakran programozottan kell konvertálniuk a WORDML fájlt POT-vé. A File Automation Java könyvtárak [Aspose.Total for Java](https://products.aspose.com/total/java/) használatával néhány egyszerű lépésben automatizálhatja a renderelési folyamatot. A WORDML-fájlt az [Aspose.Words for Java](https://products.aspose.com/words/java/) használatával töltheti be, és konvertálhatja HTML formátumba. Ezt követően a hatékony PowerPoint manipulációs Java API [Aspose.Slides for Java](https://products.aspose.com/slides/java/) segítségével új prezentációt hozhat létre, HTML-tartalmat írhat bele, és POT-ként mentheti. .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet WORDML-t POT-vé konvertálni Java-n keresztül" %}}
1. Nyissa meg a WORDML-fájlt a [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) osztály használatával
2. Alakítsa át a WORDML fájlt HTML formátumba a [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) segítségével)) módszer
3. Inicializáljon egy új [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) objektumot
5. Bontsa ki a tartalmat a HTML-fájlból a BufferedReader segítségével, és írja be a tartalmat a bemutatófájlba
6. Mentse a dokumentumot az POT-be a [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-) módszerrel
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
A WORDML-fájl POT-vé konvertálásához egyszerűen használhatja az Aspose.Total for Java-t közvetlenül a [Maven]-ből (https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose /aspose-total) alapú projektet, és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads] webhelyről (https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-wordml-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
Az API azt is lehetővé teszi, hogy jelszóval védett WORDML dokumentumokat konvertáljon POT-vé. Ha a bevitt WORDML-dokumentum jelszóval védett, nem konvertálhatja POT formátumba jelszó nélkül. A titkosított dokumentum megnyitásához beállíthatja a megfelelő jelszót a LoadOptions objektumban, és átadhatja a dokumentum konstruktorának.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-wordml-to-pptx-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-ppsm/" name="WORDML Nak nek PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-pot/" name="WORDML Nak nek POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-powerpoint/" name="WORDML Nak nek POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-pptx/" name="WORDML Nak nek PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-potx/" name="WORDML Nak nek POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-pptm/" name="WORDML Nak nek PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-potm/" name="WORDML Nak nek POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-pps/" name="WORDML Nak nek PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-ppsx/" name="WORDML Nak nek PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-ppt/" name="WORDML Nak nek PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-csv/" name="WORDML Nak nek CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-dif/" name="WORDML Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-fods/" name="WORDML Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-ods/" name="WORDML Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-sxc/" name="WORDML Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-tsv/" name="WORDML Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-xlam/" name="WORDML Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-xltm/" name="WORDML Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-excel/" name="WORDML Nak nek EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-xls/" name="WORDML Nak nek XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-xlsb/" name="WORDML Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-xlsm/" name="WORDML Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-xlsx/" name="WORDML Nak nek XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-xlt/" name="WORDML Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-xltm/" name="WORDML Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/wordml-to-xltx/" name="WORDML Nak nek XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}