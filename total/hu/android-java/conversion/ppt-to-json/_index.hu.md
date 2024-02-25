---
title: Konvertálja a PPT-ot JSON-vé Androidon Java segítségével
description: Konvertálja a PPT-ot JSON-vé Androidon Java segítségével Microsoft Excel vagy PowerPoint használata nélkül

family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertálja a PPT-ot JSON-vé Androidon Java segítségével" h2="PPT-fájl exportálása JSON-fájlba Android-alkalmazásokban Microsoft<sup>&reg;</sup> Excel vagy PowerPoint használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) segítségével kétlépéses folyamatban egyszerűen konvertálhat PPT-fájlt JSON-vé Android-alkalmazásaiban. Az első lépésben a PPT-fájlt exportálhatja HTML-be az [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) használatával. Másodszor, az [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) használatával konvertálhatja a HTML-t JSON-vé. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet a PPT-ot JSON-vé konvertálni Androidon" %}}
1. Nyissa meg a PPT-fájlt a [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) osztály használatával
2. A [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) segítségével konvertálja a PPT-ot HTML-be.ISaveOptions-) metódus
3. Töltsön be HTML-dokumentumot a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
4. Mentse a dokumentumot JSON-formátumba a [mentés](https://reference.aspose.com/cells/java/com.aspose.cells/) segítségével.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
A PPT JSON formátumba konvertálásához egyszerűen használhatja az Aspose.Total for Android alkalmazást Java-n keresztül közvetlenül a [Maven](https://releases.aspose.com/total/java/) webhelyről, és telepítse a könyvtárakat az alkalmazásba.

Másik megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/androidjava) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a Protected PPT-ot JSON-vé Androidon Java segítségével" %}}
Az API segítségével a jelszóval védett dokumentumot is megnyithatja. Ha a bevitt PPT-dokumentum jelszóval védett, nem konvertálhatja JSON-vé a jelszó használata nélkül. Az API lehetővé teszi a titkosított dokumentum megnyitását a megfelelő jelszó átadásával egy LoadOptions objektumban. A következő kódpélda bemutatja, hogyan lehet megpróbálni jelszóval megnyitni egy titkosított dokumentumot:
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a PPT fájlt JSON-vé vízjellel az Androidon" %}}
A PPT fájl JSON formátumba konvertálásakor vízjelet is hozzáadhat a kimeneti JSON fájlformátumhoz. Vízjel hozzáadásához hozzon létre egy új munkafüzetet a konvertált HTML-fájl megnyitásához. Válassza ki a Munkalappt az indexén keresztül, hozzon létre egy alakzatot, és használja az addTextEffect funkciót, állítsa be a színeket, az átlátszóságot és így tovább. Ezt követően elmentheti a HTML-dokumentumot JSON-ként vízjellel.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}