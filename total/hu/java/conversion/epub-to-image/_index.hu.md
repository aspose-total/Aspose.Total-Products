---
title: Konvertálja a EPUB-et IMAGE-re Java segítségével
description: Exportáljon EPUB-fájlt IMAGE-be Java-alkalmazásaiban harmadik féltől származó alkalmazások használata nélkül
url_ignore: /hu/java/conversion/epub-to-image/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: JPEG2000
otherformats: JPEG2000 DXF WMF SVGZ TGA  WMZ EMZ PSD IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertálja a EPUB-et IMAGE-re Java segítségével" h2="EPUB-fájl exportálása IMAGE-be bármely Java J2SE, J2EE, J2ME alkalmazáson belül az Adobe<sup>&reg;</sup> Acrobat Reader használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Két egyszerű lépésben konvertálhatja a epub fájlt IMAGE képpé Java nyelven. Először is, az [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) használatával exportálhatja a EPUB-et JPEG formátumba. Ezt követően az [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API használatával a JPEG IMAGE formátumba renderelhető. Mindkét API az [Aspose.Total for Java](https://products.aspose.com/total/java/) csomag alá tartozik.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EPUB exportálása IMAGE-be Java-n keresztül" %}}
1. Nyissa meg a EPUB-fájlt a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával
2. Inicializálja a osztályobjektumot, és a [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com) segítségével jelenítse meg a EPUB-et JPEG formátumba. aspose.pdf.Page-java.io.OutputStream-) metódus
3. Töltse be a JPEG fájlt az [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) osztály használatával
4. Mentse a dokumentumot IMAGE formátumba a [mentés](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase) segítségével-) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://releases.aspose.com/total/java/) alapú projektből és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertálja a EPUB-et IMAGE-vé egyetlen fájlban Java segítségével" %}}
Az API azt is lehetővé teszi, hogy egyetlen fájlba exportálja a EPUB-fájlt IMAGE-be. Az összes oldal konvertálásához először a EPUB-dokumentumot egy TIFF-fájlba renderelheti, majd exportálhatja a TIFF-fájlt IMAGE-be. Megnyithatja a bemeneti fájlt a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával, és létrehozhat Resolution, TiffSettings és TIFF eszközobjektumokat. Egyetlen TIFF-képet kaphat a [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-) használatával. java.io.OutputStream-) metódus a [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) osztályban. Végül betöltheti a TIFF-fájlt az [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) osztály használatával, és a [mentés](https://) segítségével IMAGE formátumba mentheti. apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) módszerrel.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertálja a EPUB-et IMAGE-vé vízjellel Java segítségével" %}}
Az API használatával EPUB-fájlt is exportálhat IMAGE-be vízjellel az IMAGE-dokumentumban. Vízjel hozzáadásához először konvertálja a EPUB-et JPEG formátumba, és adjon hozzá egy vízjelet. Vízjel hozzáadásához töltsön be egy képfájlt az [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) osztály használatával, és hozzon létre egy objektumot a [Graphics](https) ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) osztályt, és inicializálja azt Image objektummal, hozzon létre egy új [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) objektumot, és állítsa be a fordítást és az átalakítást a kívánt szögbe, és adjon hozzá vízjelet a [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) módszerrel. Miután hozzáadta a vízjelet a képhez, elmentheti a JPEG fájlt IMAGE formátumban. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertálja és forgassa el a EPUB-et IMAGE-fájllá Java-n keresztül" %}}
Az API használatával igény szerint elforgathatja a kimeneti IMAGE-képet is. Az Image.rotateFlip módszerrel a kép 90/180/270 fokkal elforgatható, és vízszintesen vagy függőlegesen elforgatható. A könyvtár egyszerű módszereket kínál összetett műveletek végrehajtására, miközben minden csúnya részletet magába foglal. Megadhatja a képre alkalmazandó elforgatás és tükrözés típusát. A kép elforgatásához és megfordításához betöltheti az átalakított JPEG képet az [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) osztály használatával, és meghívhatja a képet. rotateFlip metódust, miközben megadja a megfelelő [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Az **EPUB átalakítása KÉPPE** elengedhetetlen a digitális kiadványok **vizuális pillanatképek** létrehozásához. A KÉP fájlok egy univerzális, platformfüggetlen módot biztosítanak az e-könyv tartalmának vizuális megjelenítésére, lehetővé téve az egyszerű előnézeteket, promóciós grafikákat és archív felvételeket. Az EPUB átalakításával képekbe a kiadók, oktatók és vállalatok javíthatják az elérhetőséget, egyszerűsíthetik a tartalommarketinget és támogathatják a keresztplatformos kiadási munkafolyamatokat.

{{% blocks/products/pf/agp/feature-section-col title="Kulcsfontosságú felhasználási esetek" %}}
- **eKönyv oldal-előnézetek** – Vizuális pillanatképek generálása online katalógusokhoz és előnézetekhez.
- **Oktatási infografikák** – Tartalom átalakítása könnyen emészthető vizuális tanítási segédletekké.
- **Marketing anyagok generálása** – Promóciós vizuálisok létrehozása az e-könyv oldalairól.
- **Archív pillanatképek** – Statikus digitális kiadványok hosszú távú tárolására.
- **Keresztplatformos kiadási munkafolyamatok** – Biztosítsa a konzisztens vizuális tartalmat a webes, mobil- és nyomtatott platformokon.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Automatizálási forgatókönyvek" %}}
- **EPUB-KÉP csövek** – Az e-könyvek automatikus átalakítása vizuális pillanatképekbe az hatékonyság érdekében.
- **Automatizált oldal-kép konvertálás** – Gyorsan előállíthatók magas minőségű oldalképek EPUB fájlokból.
- **Tömeges előnézet generálása kiadási platformokhoz** – Több ezer előnézetkép generálása egy adott folyamatban.
- **Vállalati méretű vizuális archiválás** – Nagy mennyiségű e-könyv képének karbantartása szervezeti igényekhez.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}