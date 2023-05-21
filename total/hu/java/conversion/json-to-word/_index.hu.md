---
title: Konvertálja a JSON formátumot WORD-re Java segítségével
description: Elemezze a JSON-t WORD-be Java-ban Microsoft Word használata nélkül
url_ignore: /hu/java/conversion/json-to-word/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: WORD
otherformats: EPUB PCL WORDML WORD RTF MOBI DOT ODT PS FLATOPC DOTX OTT DOCM DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertálja a JSON formátumot WORD-re Java segítségével" h2="A helyszíni Java API a JSON elemzéséhez WORD-be a Microsoft<sup>&reg;</sup> Word használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for Java](https://products.aspose.com/total/java/) használatával kétlépéses folyamatban konvertálhatja a JSON-t WORD-re a Java-alkalmazásokban. Először is, az [Aspose.Cells for Java](https://products.aspose.com/cells/java/) használatával elemezheti a JSON-t PDF-be. A második lépésben a PDF-et WORD-re konvertálhatja a Word Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/) használatával.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertálja a JSON formátumot WORD-re Java segítségével" %}}
1. Hozzon létre egy új [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) objektumot, és olvassa be az érvényes JSON-adatokat a fájlból
2. Importálja a JSON-fájlt a munkalapra a [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) osztály és a [Save](https://reference.aspose.com/) használatával cell/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) PDF formátumban
3. Töltse be a PDF-dokumentumot a [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) osztály használatával
4. Mentse a dokumentumot WORD formátumba a [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) segítségével)) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://releases.aspose.com/total/java/) alapú projektből és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
Ezenkívül az API lehetővé teszi, hogy elrendezési beállításokat állítson be a JSON-hoz, miközben a JSON-t WORD-be elemezi a [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayotoptions) használatával. Lehetővé teszi a tömb táblaként történő feldolgozását, a nullák figyelmen kívül hagyását, a tömb címének figyelmen kívül hagyását, az objektum címének figyelmen kívül hagyását, a karakterlánc számmá vagy dátummá alakítását, a dátum és számformátum beállítását, valamint a címstílus beállítását. Mindezek a lehetőségek lehetővé teszik, hogy adatait az igényeinek megfelelően mutassa be. A következő kódrészlet bemutatja, hogyan állíthatja be az elrendezési beállításokat.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Állítsa be az elrendezést és konvertálja a JSON-formátumot WORD-re Java-n keresztül" %}}
Az API használatával a JSON-t WORD-be is elemezheti vízjellel. Ha vízjelet szeretne hozzáadni a WORD-dokumentumhoz, először konvertálja a JSON-fájlt PDF-be, és vízjelet adjon hozzá. Vízjel hozzáadásához töltse be az újonnan létrehozott PDF-fájlt a [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) osztály használatával, hozzon létre egy példányt a TextWatermarkOptions alkalmazásból, és állítsa be. tulajdonságai, Hívja meg a Watermark.setText metódust, és adja át a vízjel szövegét és a TextWatermarkOptions objektumát. A vízjel hozzáadása után a dokumentumot elmentheti a WORD-be. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}