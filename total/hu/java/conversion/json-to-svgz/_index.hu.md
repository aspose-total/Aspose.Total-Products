---
title: Konvertálja a JSON formátumot SVGZ-re Java segítségével
description: Elemezze a JSON-t SVGZ-be Java-ban Microsoft PowerPoint használata nélkül
url_ignore: /hu/java/conversion/json-to-svgz/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: SVGZ
otherformats: IMAGE DICOM TGA WMF WMZ EMZ PSD SVGZ JPEG2000 DXF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertálja a JSON formátumot SVGZ-re Java segítségével" h2="Java API a JSON formátum SVGZ-re történő elemzéséhez bármely Java J2SE, J2EE, J2ME alkalmazáson belül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for Java](https://products.aspose.com/total/java/) használatával bármely Java-alkalmazáson belül két egyszerű lépésben konvertálhatja a JSON-formátumot SVGZ-vé. Először is, az [Aspose.Cells for Java](https://products.aspose.com/cells/java/) használatával a JSON-t JPEG formátumba elemezheti. Ezt követően az [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) használatával konvertálhatja a JPEG-et SVGZ formátumba.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertálja a JSON formátumot SVGZ-re Java segítségével" %}}
1. Hozzon létre egy új [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) objektumot, és nyissa meg a JSON-fájlt
2. Mentse el a JSON fájlt JPEG formátumban a [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) segítségével. ) módszerrel
3. Töltse be a JPEG dokumentumot az [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) osztály használatával
4. Mentse a dokumentumot SVGZ formátumba a [mentés](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase) segítségével-) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://releases.aspose.com/total/java/) alapú projektből és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
Ezenkívül az API lehetővé teszi a JSON elemzését SVGZ-be meghatározott elrendezési beállításokkal. Az elrendezési beállítások megadásához használhatja a [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayutoptions) osztályt. Lehetővé teszi egy tömb táblaként történő feldolgozását, a nullák figyelmen kívül hagyását, a tömb címének figyelmen kívül hagyását, az objektum címének figyelmen kívül hagyását, a karakterlánc számmá vagy dátummá alakítását, a dátum és a számformátum beállítását, valamint a címstílus beállítását. Mindezek a lehetőségek lehetővé teszik, hogy adatait az igényeinek megfelelően mutassa be. A következő kódrészlet bemutatja, hogyan állíthatja be az elrendezési beállításokat.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Állítsa be az elrendezést, és konvertálja a JSON-formátumot SVGZ-re Java segítségével" %}}
Az API használatával a JSON-t SVGZ-vé alakíthatja vízjellel az SVGZ-dokumentumban. Ha vízjelet szeretne hozzáadni, először konvertálja a JSON-t JPEG formátumba, és adjon hozzá egy vízjelet. Vízjel hozzáadásához töltsön be egy képfájlt az [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) osztály használatával, és hozzon létre egy objektumot a [Graphics](https) ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) osztályt, és inicializálja azt Image objektummal, hozzon létre egy új [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) objektumot, és állítsa be a fordítást és az átalakítást a kívánt szögbe, és adjon hozzá vízjelet a [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) módszerrel. Miután hozzáadta a vízjelet a képhez, elmentheti a JPEG fájlt SVGZ formátumban. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Az **JSON to SVGZ** konvertálása alapvető fontosságú a **tömörített skálázható vektorgrafikák** közvetlenül strukturált adatokból történő létrehozásához. Az SVGZ, az SVG GZIP-tömörített verziója, kisebb fájlméreteket biztosít, miközben megőrzi a felbontás függetlenségét, így ideális webes, mobil és vállalati megjelenítési igényekhez. Az JSON adatkészletek átalakításával SVGZ formátumba, a szervezetek könnyű, interaktív és skálázható vizuális elemeket szállíthatnak platformokon át.

{{% blocks/products/pf/agp/feature-section-col title="Kulcsfontosságú felhasználási esetek" %}}

- **Skálázható diagramok** – Hozzon létre tömörített diagramokat, amelyek tisztaságukat bármilyen felbontásnál megőrzik.
- **Interaktív vezérlőpultok** – Támogassa adatalapú vezérlőpultjait könnyű SVGZ grafikákkal.
- **JSON-alapú vektorábrázolások** – Alakítsa át a strukturált adatokat minimális tárolási túlfeszültséggel diagrammá.
- **Mobiloptimalizált grafikák** – Szállítson gyorsabban betöltő vizuális elemeket az érzékeny alkalmazásokhoz és webhelyekhez.
- **Vállalati megjelenítési rendszerek** – Szabványosítsa a skálázható grafikákat a vállalati munkafolyamatokban.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Automatizálási forgatókönyvek" %}}

- **JSON-to-SVGZ csővezetékek** – Automatizálja az adatok átalakítását tömörített vektorfájlokká.
- **Automatizált diagramtömörítés** – Csökkentse a nagy megjelenítések méretét minőségvesztés nélkül.
- **JSON-alapú vektori rajzolás** – Hozzon létre dinamikus vizuális elemeket strukturált adatkészletekből.
- **Platformfüggetlen grafikai munkafolyamatok** – Biztosítsa a konzisztens, skálázható vizuális elemeket az asztali, mobil és felhőplatformokon.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}