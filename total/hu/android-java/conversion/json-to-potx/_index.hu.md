---
title: Konvertálja a JSON formátumot POTX-re az Androidon Java segítségével
description: Elemezze a JSON-t POTX-re az Android alkalmazásokban Microsoft PowerPoint használata nélkül

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: POTX
otherformats: PPSX PPTM POWERPOINT POT POTM ODP PPSM OTP PPS PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertálja a JSON formátumot POTX-re Androidon" h2="JSON formátum elemzése POTX-re az Android alkalmazásokban a Microsoft<sup>&reg;</sup> PowerPoint használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
A JSON formátumot POTX-re konvertálhatja Android-alkalmazásaiban egy kétlépéses folyamatban. Először is, az [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) használatával elemezheti a JSON-t PPTX-re. Ezt követően az [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) használatával konvertálhatja a PPTX-t POTX-vé. Mindkét API az [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) csomagba tartozik. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertálja a JSON formátumot POTX-re Androidon" %}}
1. Hozzon létre egy új [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) objektumot, és nyissa meg a JSON-fájlt
2. Mentse el a JSON-fájlt PPTX-ként a [mentés](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) segítségével. ) módszerrel
3. Töltse be a PPTX dokumentumot a [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) osztály használatával
4. Mentse a dokumentumot POTX formátumba a [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) módszerrel
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Könnyedén használhatja az Aspose.Total for Android rendszert Java-n keresztül közvetlenül a [Maven](https://releases.aspose.com/total/java/) webhelyről és könyvtárakat telepíteni az alkalmazásba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/androidjava) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "convert-json-to-powerpoint.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Állítsa be az elrendezést, és alakítsa át a JSON-formátumot POTX-re az Android-alkalmazásokban" %}}
Ezenkívül az API lehetővé teszi a JSON POTX-re történő elemzését meghatározott elrendezési beállításokkal. Az elrendezési beállítások megadásához használhatja a [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayotoptions) osztályt. Lehetővé teszi egy tömb táblázatként történő feldolgozását, a nullák figyelmen kívül hagyását, a tömb címének figyelmen kívül hagyását, az objektum címének figyelmen kívül hagyását, a karakterlánc számmá vagy dátummá alakítását, a dátum és a számformátum beállítását, valamint a címstílus beállítását. Mindezek a lehetőségek lehetővé teszik, hogy adatait az igényeinek megfelelően jelenítse meg. A következő kódrészlet bemutatja, hogyan állíthatja be az elrendezési beállításokat.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a JSON formátumot POTX-vé vízjellel az Androidon Java segítségével" %}}
Az API használatával a JSON-t vízjellel POTX-vé is konvertálhatja. Ha vízjelet szeretne hozzáadni az POTX-dokumentumhoz, először elemezheti a JSON-t PPTX-be, és vízjelet adhat hozzá. Vízjel hozzáadásához töltse be az újonnan létrehozott PPTX fájlt a [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) osztály segítségével, görgessen végig az összes dián, és adjon hozzá szöveget az addTextFrame segítségével állítsa be az összes releváns beállítást, például a színt, a fillType-ot és egyebeket, és mentheti a dokumentumot az POTX-be.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}