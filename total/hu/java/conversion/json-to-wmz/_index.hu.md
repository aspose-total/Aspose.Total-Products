---
title: Konvertálja a JSON formátumot WMZ-re Java segítségével
description: Elemezze a JSON-t WMZ-be Java-ban Microsoft PowerPoint használata nélkül
url_ignore: /hu/java/conversion/json-to-wmz/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: WMZ
otherformats: SVGZ WMZ JPEG2000 TGA DICOM IMAGE EMZ DXF PSD WMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertálja a JSON formátumot WMZ-re Java segítségével" h2="Java API a JSON formátum WMZ-re történő elemzéséhez bármely Java J2SE, J2EE, J2ME alkalmazáson belül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for Java](https://products.aspose.com/total/java/) használatával bármely Java-alkalmazáson belül két egyszerű lépésben konvertálhatja a JSON-formátumot WMZ-vé. Először is, az [Aspose.Cells for Java](https://products.aspose.com/cells/java/) használatával a JSON-t JPEG formátumba elemezheti. Ezt követően az [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) használatával konvertálhatja a JPEG-et WMZ formátumba.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertálja a JSON formátumot WMZ-re Java segítségével" %}}
1. Hozzon létre egy új [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) objektumot, és nyissa meg a JSON-fájlt
2. Mentse el a JSON fájlt JPEG formátumban a [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) segítségével. ) módszerrel
3. Töltse be a JPEG dokumentumot az [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) osztály használatával
4. Mentse a dokumentumot WMZ formátumba a [mentés](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase) segítségével-) módszer
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
Ezenkívül az API lehetővé teszi a JSON elemzését WMZ-be meghatározott elrendezési beállításokkal. Az elrendezési beállítások megadásához használhatja a [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayutoptions) osztályt. Lehetővé teszi egy tömb táblaként történő feldolgozását, a nullák figyelmen kívül hagyását, a tömb címének figyelmen kívül hagyását, az objektum címének figyelmen kívül hagyását, a karakterlánc számmá vagy dátummá alakítását, a dátum és a számformátum beállítását, valamint a címstílus beállítását. Mindezek a lehetőségek lehetővé teszik, hogy adatait az igényeinek megfelelően mutassa be. A következő kódrészlet bemutatja, hogyan állíthatja be az elrendezési beállításokat.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Állítsa be az elrendezést, és konvertálja a JSON-formátumot WMZ-re Java segítségével" %}}
Az API használatával a JSON-t WMZ-vé alakíthatja vízjellel az WMZ-dokumentumban. Ha vízjelet szeretne hozzáadni, először konvertálja a JSON-t JPEG formátumba, és adjon hozzá egy vízjelet. Vízjel hozzáadásához töltsön be egy képfájlt az [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) osztály használatával, és hozzon létre egy objektumot a [Graphics](https) ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) osztályt, és inicializálja azt Image objektummal, hozzon létre egy új [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) objektumot, és állítsa be a fordítást és az átalakítást a kívánt szögbe, és adjon hozzá vízjelet a [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) módszerrel. Miután hozzáadta a vízjelet a képhez, elmentheti a JPEG fájlt WMZ formátumban. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Az **JSON átalakítása WMZ formátumba** alapvető fontosságú a **strukturált adatokból történő tömörített Windows Metafile grafikák generálásához**. A WMZ fájlok kompakt, skálázható vektorgrafikát biztosítanak, amelyek ideálisak dokumentumokba, jelentésekbe és vállalati rendszerekbe való beágyazáshoz. A JSON átalakításával WMZ formátumba az szervezetek optimalizálhatják a tárolást, javíthatják a platformok közötti kompatibilitást, és automatizálhatják a könnyű, magas minőségű grafikák előállítását.

{{% blocks/products/pf/agp/feature-section-col title="Kulcsfontosságú felhasználási esetek" %}}

- **Könnyű grafikai tárolás** – Tömörítse a vektorgrafikákat hatékony tárolás és átvitel érdekében.
- **Dokumentumba való beágyazás** – Illessze be a WMZ grafikákat zökkenőmentesen a Word, PowerPoint és Excel fájlokba.
- **Platformok közötti kompatibilitás** – Tartsa fenn a skálázható grafikákat Windows és más környezetek között.
- **Vállalati jelentési vizuális elemek** – Automatizálja a táblázatok és diagramok generálását vállalati jelentésekhez.
- **Optimalizált vállalati diagramok** – Állítson elő szabványosított, tömörített vizuális elemeket vállalati dokumentációhoz.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Automatizálási forgatókönyvek" %}}

- **JSON-WMZ csővezetékek** – Automatizálja a strukturált adatok átalakítását tömörített WMZ grafikákká.
- **Automatizált tömörített grafikus generálás** – Csökkentse a fájlméretet, miközben megőrzi a vektor minőségét.
- **JSON vezérelt vizuális optimalizálás** – Hatékonyan generáljon magas minőségű, adatalapú vizuális elemeket.
- **Vállalati kész könnyű illusztrációs munkafolyamatok** – Skálázza fel a WMZ generálást az osztályok és rendszerek között.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}