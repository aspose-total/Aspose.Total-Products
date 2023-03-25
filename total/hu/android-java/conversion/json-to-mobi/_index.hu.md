---
title: Konvertálja a JSON formátumot MOBI-re az Androidon Java segítségével
description: Elemezze a JSON-t MOBI-be Java-ban Microsoft Word használata nélkül

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: MOBI
otherformats: RTF ODT FLATOPC OTT WORD DOT EPUB DOTX PCL DOCM DOC CHM PS WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertálja a JSON formátumot MOBI-re az Android alkalmazásokban" h2="Elemezze a JSON-t MOBI-be az Android-alkalmazásokon belül a Microsoft<sup>&reg;</sup> Word használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Kétlépéses folyamatban konvertálhatja a JSON-t MOBI-re az Android-alkalmazásokban. Először is, a Powerful Spreadsheet Processing API [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) használatával a JSON-t PDF-be elemezheti. A második lépésben a PDF-et MOBI-re konvertálhatja a Word Processing API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) használatával. Mindkét API az [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) termékcsaládba tartozik. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertálja a JSON formátumot MOBI-re az Androidon Java segítségével" %}}
1. Hozzon létre egy új [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) objektumot, és olvassa be az érvényes JSON-adatokat a fájlból
2. Importálja a JSON-fájlt a munkalapra a [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) osztály és a [Mentés](https://reference.aspose.com/) használatával PDF formátumban
3. Töltse be a PDF-dokumentumot a [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) osztály használatával
4. Mentse a dokumentumot MOBI formátumba a [Mentés](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Könnyedén használhatja az Aspose.Total for Android rendszert Java-n keresztül közvetlenül a [Maven](https://releases.aspose.com/total/java/) webhelyről és könyvtárakat telepíteni az alkalmazásba.

Másik megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/androidjava) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Állítsa be az elrendezést és konvertálja a JSON-formátumot MOBI-re az Androidon Java segítségével" %}}
Ezenkívül az API lehetővé teszi, hogy elrendezési beállításokat állítson be a JSON-formátumhoz, miközben a JSON-t MOBI-be elemezi a [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayotoptions) használatával. Lehetővé teszi a tömb táblaként történő feldolgozását, a nullák figyelmen kívül hagyását, a tömb címének figyelmen kívül hagyását, az objektum címének figyelmen kívül hagyását, a karakterlánc számmá vagy dátummá alakítását, a dátum és számformátum beállítását, valamint a címstílus beállítását. Mindezek a lehetőségek lehetővé teszik, hogy adatait az igényeinek megfelelően jelenítse meg. A következő kódrészlet bemutatja, hogyan állíthatja be az elrendezési beállításokat.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a JSON formátumot MOBI-re vízjellel az Androidon Java segítségével" %}}
Az API használatával a JSON-t vízjellel MOBI-re is konvertálhatja. Ha vízjelet szeretne hozzáadni a MOBI-dokumentumhoz, először elemezheti a JSON-fájlt PDF-be, és vízjelet adhat hozzá. Vízjel hozzáadásához töltse be az újonnan létrehozott PDF-fájlt a [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) osztály használatával, hozzon létre egy TextWatermarkOptions példányt, és állítsa be tulajdonságait, hívja meg a Watermark.setText metódust, és adja át a vízjel szövegét és a TextWatermarkOptions objektumát. A vízjel hozzáadása után a dokumentumot elmentheti a MOBI-be.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}