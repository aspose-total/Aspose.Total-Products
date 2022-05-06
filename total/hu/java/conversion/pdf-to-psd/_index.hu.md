---
title: Konvertálja a PDF-et PSD-re Java segítségével
description: Exportáljon PDF-fájlt PSD-be Java-alkalmazásaiban harmadik féltől származó alkalmazások használata nélkül
url_ignore: /hu/java/conversion/pdf-to-psd/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: PSD
otherformats: WMZ PSD TGA JPEG2000 EMZ SVGZ IMAGE  WMF DXF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertálja a PDF-et PSD-re Java segítségével" h2="PDF-fájl exportálása PSD-be bármely Java J2SE, J2EE, J2ME alkalmazáson belül az Adobe<sup>&reg;</sup> Acrobat Reader használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Két egyszerű lépésben konvertálhatja a pdf fájlt PSD képpé Java nyelven. Először is, az [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) használatával exportálhatja a PDF-et JPEG formátumba. Ezt követően az [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API használatával a JPEG PSD formátumba renderelhető. Mindkét API az [Aspose.Total for Java](https://products.aspose.com/total/java/) csomag alá tartozik.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PDF exportálása PSD-be Java-n keresztül" %}}
1. Nyissa meg a PDF-fájlt a [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával
2. Inicializálja a osztályobjektumot, és a [Process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com) segítségével jelenítse meg a PDF-et JPEG formátumba. aspose.pdf.Page-java.io.OutputStream-) metódus
3. Töltse be a JPEG fájlt az [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) osztály használatával
4. Mentse a dokumentumot PSD formátumba a [mentés](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase) segítségével-) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) alapú projektből és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertálja a PDF-et PSD-vé egyetlen fájlban Java segítségével" %}}
Az API azt is lehetővé teszi, hogy egyetlen fájlba exportálja a PDF-fájlt PSD-be. Az összes oldal konvertálásához először a PDF-dokumentumot egy TIFF-fájlba renderelheti, majd exportálhatja a TIFF-fájlt PSD-be. Megnyithatja a bemeneti fájlt a [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával, és létrehozhat Resolution, TiffSettings és TIFF eszközobjektumokat. Egyetlen TIFF-képet kaphat a [process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-) használatával. java.io.OutputStream-) metódus a [TiffDevice](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) osztályban. Végül betöltheti a TIFF-fájlt az [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) osztály használatával, és a [mentés](https://) segítségével PSD formátumba mentheti. apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) módszerrel.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertálja a PDF-et PSD-vé vízjellel Java segítségével" %}}
Az API használatával PDF-fájlt is exportálhat PSD-be vízjellel az PSD-dokumentumban. Vízjel hozzáadásához először konvertálja a PDF-et JPEG formátumba, és adjon hozzá egy vízjelet. Vízjel hozzáadásához töltsön be egy képfájlt az [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) osztály használatával, és hozzon létre egy objektumot a [Graphics](https) ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) osztályt, és inicializálja azt Image objektummal, hozzon létre egy új [Matrix](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Matrix) objektumot, és állítsa be a fordítást és az átalakítást a kívánt szögbe, és adjon hozzá vízjelet a [Graphics.drawString](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics# drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) módszerrel. Miután hozzáadta a vízjelet a képhez, elmentheti a JPEG fájlt PSD formátumban. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertálja és forgassa el a PDF-et PSD-fájllá Java-n keresztül" %}}
Az API használatával igény szerint elforgathatja a kimeneti PSD-képet is. Az Image.rotateFlip módszerrel a kép 90/180/270 fokkal elforgatható, és vízszintesen vagy függőlegesen elforgatható. A könyvtár egyszerű módszereket kínál összetett műveletek végrehajtására, miközben minden csúnya részletet magába foglal. Megadhatja a képre alkalmazandó elforgatás és tükrözés típusát. A kép elforgatásához és megfordításához betöltheti az átalakított JPEG képet az [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) osztály használatával, és meghívhatja a képet. rotateFlip metódust, miközben megadja a megfelelő [RotateFlipType](https://apireference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-emz/" name="PDF Nak nek EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-tga/" name="PDF Nak nek TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-jpeg2000/" name="PDF Nak nek JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-image/" name="PDF Nak nek IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-psd/" name="PDF Nak nek PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-wmz/" name="PDF Nak nek WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-svgz/" name="PDF Nak nek SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to/" name="PDF Nak nek" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-wmf/" name="PDF Nak nek WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-dxf/" name="PDF Nak nek DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-dicom/" name="PDF Nak nek DICOM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}