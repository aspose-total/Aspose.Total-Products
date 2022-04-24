---
title: Konvertálja a JSON formátumot ODP-re Java segítségével
description: Elemezze a JSON-t ODP-vé Java-ban Microsoft PowerPoint használata nélkül
url: /hu/java/conversion/json-to-odp/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: ODP
otherformats: PPS PPT PPTM PPSM POWERPOINT POT POTM OTP PPSX POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertálja a JSON formátumot ODP-re Java segítségével" h2="Java API a JSON formátum ODP-re történő elemzéséhez a Microsoft<sup>&reg;</sup> PowerPoint használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for Java](https://products.aspose.com/total/java/) használatával két egyszerű lépésben konvertálhat JSON-formátumot ODP-vé bármely Java-alkalmazáson belül. Először is, az [Aspose.Cells for Java](https://products.aspose.com/cells/java/) használatával elemezheti a JSON-t PPTX-re. Ezt követően az [Aspose.Slides for Java](https://products.aspose.com/slides/java/) használatával konvertálhatja a PPTX-t ODP-vé.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertálja a JSON formátumot ODP-re Java segítségével" %}}
1. Hozzon létre egy új [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) objektumot, és nyissa meg a JSON-fájlt
2. Mentse el a JSON-t PPTX-ként a [mentés](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) segítségével. ) módszerrel
3. Töltse be a PPTX dokumentumot a [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) osztály használatával
4. Mentse a dokumentumot ODP formátumba a [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) módszerrel
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) alapú projektből és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads] webhelyről (https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "convert-json-to-powerpoint.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
Ezenkívül az API lehetővé teszi a JSON elemzését ODP-re meghatározott elrendezési beállításokkal. Az elrendezési beállítások megadásához használhatja a [JsonLayoutOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonlayutoptions) osztályt. Lehetővé teszi egy tömb táblaként történő feldolgozását, a nullák figyelmen kívül hagyását, a tömb címének figyelmen kívül hagyását, az objektum címének figyelmen kívül hagyását, a karakterlánc számmá vagy dátummá alakítását, a dátum és a számformátum beállítását, valamint a címstílus beállítását. Mindezek a lehetőségek lehetővé teszik, hogy adatait az igényeinek megfelelően mutassa be. A következő kódrészlet bemutatja, hogyan állíthatja be az elrendezési beállításokat.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Állítsa be az elrendezést, és konvertálja a JSON-formátumot ODP-re Java segítségével" %}}
Az API használatával a JSON-t vízjellel ODP-vé is konvertálhatja. Ha vízjelet szeretne hozzáadni az ODP-dokumentumhoz, először elemezze a JSON-t PPTX-be, és adjon hozzá egy vízjelet. Vízjel hozzáadásához töltse be az újonnan létrehozott PPTX fájlt a [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) osztály segítségével, görgessen végig az összes dián, és adjon hozzá szöveget az addTextFrame segítségével állítsa be az összes releváns beállítást, például a színt, a fillType-ot és egyebeket, és mentheti a dokumentumot az ODP-be. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-pps/" name="JSON Nak nek PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-ppt/" name="JSON Nak nek PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-pptm/" name="JSON Nak nek PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-ppsm/" name="JSON Nak nek PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-powerpoint/" name="JSON Nak nek POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-pot/" name="JSON Nak nek POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-potm/" name="JSON Nak nek POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-otp/" name="JSON Nak nek OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-ppsx/" name="JSON Nak nek PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-potx/" name="JSON Nak nek POTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}