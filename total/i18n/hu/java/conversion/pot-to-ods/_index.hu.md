---
title: Konvertálja a POT-ot ODS formátumba Java segítségével
description: Konvertálja a POT-ot ODS formátumba Java segítségével Microsoft Excel vagy PowerPoint használata nélkül
url: /hu/java/conversion/pot-to-ods/
family: total
platformtag: net
feature: conversion
informat: POT
outformat: ODS
otherformats: XLS ODS DIF FODS XLSB XLSM MARKDOWN SXC XLSX XLT TSV XLTX EXCEL XLAM MHTML XLTM DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="POT konvertálása ODS-vé Java segítségével" h2="On Premise Java API a POT exportálásához ODS formátumba Microsoft<sup>&reg;</sup> Excel vagy PowerPoint használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
A POT-fájlt ODS-vé konvertálhatja az [Aspose.Total for Java](https://products.aspose.com/total/java/) segítségével, két lépésben. Az első lépésben exportálhatja a POT-ot HTML-be az [Aspose.Slides for Java](https://products.aspose.com/slides/java/) használatával. Másodszor, az [Aspose.Cells for Java](https://products.aspose.com/cells/java/) használatával konvertálhatja a HTML-t ODS-vé.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet a POT-ot ODS-vé konvertálni Java segítségével" %}}
1. Nyissa meg a POT-fájlt a [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) osztály használatával
2. A [mentés](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) segítségével konvertálja a POT-ot HTML-be. ISaveOptions-) metódus
3. Töltsön be HTML-dokumentumot a [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
4. Mentse a dokumentumot ODS formátumba a [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells) segítségével. SaveOptions)) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
A POT ODS-vé konvertálásához egyszerűen használhatja az Aspose.Total for Java alkalmazást közvetlenül a [Maven]-ből (https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/ aspose/aspose-total) alapú projekt, és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads] webhelyről (https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
Az API segítségével a jelszóval védett dokumentumot is megnyithatja. Ha a bevitt POT-dokumentum jelszóval védett, nem konvertálhatja ODS-vé a jelszó használata nélkül. Az API lehetővé teszi a titkosított dokumentum megnyitását a megfelelő jelszó átadásával egy LoadOptions objektumban.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-protected-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="A Protected POT konvertálása ODS-re Java segítségével" %}}
A POT fájl ODS formátumba konvertálásakor vízjelet is hozzáadhat a kimeneti ODS fájlformátumhoz. Vízjel hozzáadásához hozzon létre egy új munkafüzetet a konvertált HTML-fájl megnyitásához. Válassza ki a Munkalapot az indexén keresztül, hozzon létre egy alakzatot, és használja az addTextEffect funkciót, állítsa be a színeket, az átlátszóságot és így tovább. Ezt követően elmentheti a HTML-dokumentumot ODS-ként vízjellel. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-fods/" name="POT Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-xltm/" name="POT Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-xlt/" name="POT Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-xlam/" name="POT Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-markdown/" name="POT Nak nek MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-excel/" name="POT Nak nek EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-mhtml/" name="POT Nak nek MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-xlsb/" name="POT Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-ods/" name="POT Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-sxc/" name="POT Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-xls/" name="POT Nak nek XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-xltx/" name="POT Nak nek XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-xlsx/" name="POT Nak nek XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-tsv/" name="POT Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-dif/" name="POT Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-xlsm/" name="POT Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-doc/" name="POT Nak nek DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-docx/" name="POT Nak nek DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-docm/" name="POT Nak nek DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-dot/" name="POT Nak nek DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-dotm/" name="POT Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-dotx/" name="POT Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-odt/" name="POT Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-ott/" name="POT Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-rtf/" name="POT Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-word/" name="POT Nak nek WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-wordml/" name="POT Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-text/" name="POT Nak nek TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pot-to-flatopx/" name="POT Nak nek FLANak nekPX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}