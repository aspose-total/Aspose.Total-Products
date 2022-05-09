---
title: A DOT konvertálása ODP-re Java segítségével
description: Java API a DOT exportálásához ODP-be Microsoft Word vagy PowerPoint használata nélkül
url_ignore: /hu/java/conversion/dot-to-odp/
family: total
platformtag: net
feature: conversion
informat: DOT
outformat: ODP
otherformats: PPTX POT PPS PPTM POTX POTM PPSX POWERPOINT PPSM PPT CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="A DOT konvertálása ODP-re Java segítségével" h2="DOT konvertálása ODP-be helyszíni Java API használatával bármely Java J2SE, J2EE, J2ME alkalmazáson belül Microsoft<sup>&reg;</sup> PowerPoint vagy Word használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
A fejlesztőknek gyakran programozottan kell konvertálniuk a DOT fájlt ODP-vé. A File Automation Java könyvtárak [Aspose.Total for Java](https://products.aspose.com/total/java/) használatával néhány egyszerű lépésben automatizálhatja a renderelési folyamatot. A DOT-fájlt az [Aspose.Words for Java](https://products.aspose.com/words/java/) használatával töltheti be, és konvertálhatja HTML formátumba. Ezt követően a hatékony PowerPoint manipulációs Java API [Aspose.Slides for Java](https://products.aspose.com/slides/java/) segítségével új prezentációt hozhat létre, HTML-tartalmat írhat bele, és ODP-ként mentheti. .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet DOT-t ODP-vé konvertálni Java-n keresztül" %}}
1. Nyissa meg a DOT-fájlt a [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) osztály használatával
2. Alakítsa át a DOT fájlt HTML formátumba a [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) segítségével)) módszer
3. Inicializáljon egy új [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) objektumot
5. Bontsa ki a tartalmat a HTML-fájlból a BufferedReader segítségével, és írja be a tartalmat a bemutatófájlba
6. Mentse a dokumentumot az ODP-be a [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-) módszerrel
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
A DOT-fájl ODP-vé konvertálásához egyszerűen használhatja az Aspose.Total for Java-t közvetlenül a [Maven]-ből (https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) alapú projektet, és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-dot-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
Az API azt is lehetővé teszi, hogy jelszóval védett DOT dokumentumokat konvertáljon ODP-vé. Ha a bevitt DOT-dokumentum jelszóval védett, nem konvertálhatja ODP formátumba jelszó nélkül. A titkosított dokumentum megnyitásához beállíthatja a megfelelő jelszót a LoadOptions objektumban, és átadhatja a dokumentum konstruktorának.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-protected-dot-to-pptx.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-ppsm/" name="DOT Nak nek PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-pot/" name="DOT Nak nek POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-powerpoint/" name="DOT Nak nek POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-pptx/" name="DOT Nak nek PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-potx/" name="DOT Nak nek POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-pptm/" name="DOT Nak nek PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-potm/" name="DOT Nak nek POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-pps/" name="DOT Nak nek PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-ppsx/" name="DOT Nak nek PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-ppt/" name="DOT Nak nek PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-csv/" name="DOT Nak nek CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-dif/" name="DOT Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-fods/" name="DOT Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-ods/" name="DOT Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-sxc/" name="DOT Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-tsv/" name="DOT Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xlam/" name="DOT Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xltm/" name="DOT Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-excel/" name="DOT Nak nek EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xls/" name="DOT Nak nek XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xlsb/" name="DOT Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xlsm/" name="DOT Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xlsx/" name="DOT Nak nek XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xlt/" name="DOT Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xltm/" name="DOT Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xltx/" name="DOT Nak nek XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}