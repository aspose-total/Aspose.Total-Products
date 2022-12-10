---
title: Konvertálja a PS-et APNG-re Java segítségével
description: Exportáljon PS-fájlt APNG-be Java-alkalmazásaiban harmadik féltől származó alkalmazások használata nélkül
url_ignore: /hu/java/conversion/ps-to-apng/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: APNG
otherformats: SVGZ DXF PSD IMAGE EMZ TGA JPEG2000 WMZ  WMF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertálja a PS-et APNG-re Java segítségével" h2="PS-fájl exportálása APNG-be bármely Java J2SE, J2EE, J2ME alkalmazáson belül az Adobe<sup>&reg;</sup> Acrobat Reader használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Két egyszerű lépésben konvertálhatja a ps fájlt APNG képpé Java nyelven. Először is, az [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) használatával exportálhatja a PS-et JPEG formátumba. Ezt követően az [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API használatával a JPEG APNG formátumba renderelhető. Mindkét API az [Aspose.Total for Java](https://products.aspose.com/total/java/) csomag alá tartozik.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PS exportálása APNG-be Java-n keresztül" %}}
1. Nyissa meg a PS-fájlt a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával
2. Inicializálja a osztályobjektumot, és a [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com) segítségével jelenítse meg a PS-et JPEG formátumba. aspose.pdf.Page-java.io.OutputStream-) metódus
3. Töltse be a JPEG fájlt az [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) osztály használatával
4. Mentse a dokumentumot APNG formátumba a [mentés](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase) segítségével-) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) alapú projektből és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertálja a PS-et APNG-vé egyetlen fájlban Java segítségével" %}}
Az API azt is lehetővé teszi, hogy egyetlen fájlba exportálja a PS-fájlt APNG-be. Az összes oldal konvertálásához először a PS-dokumentumot egy TIFF-fájlba renderelheti, majd exportálhatja a TIFF-fájlt APNG-be. Megnyithatja a bemeneti fájlt a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával, és létrehozhat Resolution, TiffSettings és TIFF eszközobjektumokat. Egyetlen TIFF-képet kaphat a [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-) használatával. java.io.OutputStream-) metódus a [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) osztályban. Végül betöltheti a TIFF-fájlt az [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) osztály használatával, és a [mentés](https://) segítségével APNG formátumba mentheti. apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) módszerrel.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertálja a PS-et APNG-vé vízjellel Java segítségével" %}}
Az API használatával PS-fájlt is exportálhat APNG-be vízjellel az APNG-dokumentumban. Vízjel hozzáadásához először konvertálja a PS-et JPEG formátumba, és adjon hozzá egy vízjelet. Vízjel hozzáadásához töltsön be egy képfájlt az [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) osztály használatával, és hozzon létre egy objektumot a [Graphics](https) ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) osztályt, és inicializálja azt Image objektummal, hozzon létre egy új [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) objektumot, és állítsa be a fordítást és az átalakítást a kívánt szögbe, és adjon hozzá vízjelet a [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) módszerrel. Miután hozzáadta a vízjelet a képhez, elmentheti a JPEG fájlt APNG formátumban. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertálja és forgassa el a PS-et APNG-fájllá Java-n keresztül" %}}
Az API használatával igény szerint elforgathatja a kimeneti APNG-képet is. Az Image.rotateFlip módszerrel a kép 90/180/270 fokkal elforgatható, és vízszintesen vagy függőlegesen elforgatható. A könyvtár egyszerű módszereket kínál összetett műveletek végrehajtására, miközben minden csúnya részletet magába foglal. Megadhatja a képre alkalmazandó elforgatás és tükrözés típusát. A kép elforgatásához és megfordításához betöltheti az átalakított JPEG képet az [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) osztály használatával, és meghívhatja a képet. rotateFlip metódust, miközben megadja a megfelelő [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ps-to-emz/" name="PS Nak nek EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ps-to-tga/" name="PS Nak nek TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ps-to-jpeg2000/" name="PS Nak nek JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ps-to-image/" name="PS Nak nek IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ps-to-psd/" name="PS Nak nek PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ps-to-wmz/" name="PS Nak nek WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ps-to-svgz/" name="PS Nak nek SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ps-to/" name="PS Nak nek" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ps-to-wmf/" name="PS Nak nek WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ps-to-dxf/" name="PS Nak nek DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ps-to-dicom/" name="PS Nak nek DICOM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}