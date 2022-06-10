---
title: A DOTX konvertálása PPTX-re Java segítségével
description: Java API a DOTX exportálásához PPTX-be Microsoft Word vagy PowerPoint használata nélkül
url_ignore: /hu/java/conversion/dotx-to-pptx/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: PPTX
otherformats: POTX POTM POT PPSX PPS POWERPOINT PPTM PPT PPSM PPTX CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="A DOTX konvertálása PPTX-re Java segítségével" h2="DOTX konvertálása PPTX-be helyszíni Java API használatával bármely Java J2SE, J2EE, J2ME alkalmazáson belül Microsoft<sup>&reg;</sup> PowerPoint vagy Word használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
A fejlesztőknek gyakran programozottan kell konvertálniuk a DOTX fájlt PPTX-vé. A File Automation Java könyvtárak [Aspose.Total for Java](https://products.aspose.com/total/java/) használatával néhány egyszerű lépésben automatizálhatja a renderelési folyamatot. A DOTX-fájlt az [Aspose.Words for Java](https://products.aspose.com/words/java/) használatával töltheti be, és konvertálhatja HTML formátumba. Ezt követően a hatékony PowerPoint manipulációs Java API [Aspose.Slides for Java](https://products.aspose.com/slides/java/) segítségével új prezentációt hozhat létre, HTML-tartalmat írhat bele, és PPTX-ként mentheti. .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet DOTX-t PPTX-vé konvertálni Java-n keresztül" %}}
1. Nyissa meg a DOTX-fájlt a [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) osztály használatával
2. Alakítsa át a DOTX fájlt HTML formátumba a [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) segítségével)) módszer
3. Inicializáljon egy új [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) objektumot
5. Bontsa ki a tartalmat a HTML-fájlból a BufferedReader segítségével, és írja be a tartalmat a bemutatófájlba
6. Mentse a dokumentumot az PPTX-be a [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-) módszerrel
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
A DOTX-fájl PPTX-vé konvertálásához egyszerűen használhatja az Aspose.Total for Java-t közvetlenül a [Maven]-ből (https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) alapú projektet, és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-dotx-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
Az API azt is lehetővé teszi, hogy jelszóval védett DOTX dokumentumokat konvertáljon PPTX-vé. Ha a bevitt DOTX-dokumentum jelszóval védett, nem konvertálhatja PPTX formátumba jelszó nélkül. A titkosított dokumentum megnyitásához beállíthatja a megfelelő jelszót a LoadOptions objektumban, és átadhatja a dokumentum konstruktorának.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-protected-dotx-to-pptx.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-ppsm/" name="DOTX Nak nek PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-pot/" name="DOTX Nak nek POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-powerpoint/" name="DOTX Nak nek POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-pptx/" name="DOTX Nak nek PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-potx/" name="DOTX Nak nek POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-pptm/" name="DOTX Nak nek PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-potm/" name="DOTX Nak nek POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-pps/" name="DOTX Nak nek PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-ppsx/" name="DOTX Nak nek PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-ppt/" name="DOTX Nak nek PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-csv/" name="DOTX Nak nek CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-dif/" name="DOTX Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-fods/" name="DOTX Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-ods/" name="DOTX Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-sxc/" name="DOTX Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-tsv/" name="DOTX Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-xlam/" name="DOTX Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-xltm/" name="DOTX Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-excel/" name="DOTX Nak nek EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-xls/" name="DOTX Nak nek XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-xlsb/" name="DOTX Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-xlsm/" name="DOTX Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-xlsx/" name="DOTX Nak nek XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-xlt/" name="DOTX Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-xltm/" name="DOTX Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-xltx/" name="DOTX Nak nek XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}