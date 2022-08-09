---
title: Konvertálja a PCL-et TXT-vé Androidon Java segítségével
description: Rendelje meg a PCL-et TXT formátumban Androidon a Java API-n keresztül Microsoft Excel vagy Adobe Reader használata nélkül
url: /hu/android-java/conversion/pcl-to-txt/
family: total
platformtag: cpp
feature: conversion
informat: PCL
outformat: TXT
otherformats: TSV XLT XLTX DIF XLAM SXC MD XLSB XLSM EXCEL FODS CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderelje le a PCL-et TXT formátumba Androidon Java segítségével" h2="A PCL átalakítása TXT-vé az Android-alkalmazásokon belül Microsoft<sup>&reg;</sup> Excel vagy Adobe<sup>&reg;</sup> Acrobat Reader alkalmazása nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Két lépésben integrálhatja a PCL-TXT konverziós funkciót az Android-alkalmazásaiba. Először is, az [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) használatával rejtett PCL-et XLSX-re alakíthat. Másodszor, az XLSX-t TXT-vé alakíthatja a Powerful Spreadsheet Processing API [Aspose.Cells for Android via Java] használatával (https://products.aspose.com/cells/android-java/). Mindkét API az [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) termékcsaládba tartozik. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API a PCL TXT formátumban való megjelenítéséhez" %}}
1. Nyissa meg a PCL-fájlt a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával
2. Konvertálja a PCL-et XLSX-re a [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) módszerrel
3. Töltse be az XLSX dokumentumot a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
4. Mentse a dokumentumot TXT formátumba a [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) segítségével. SaveOptions)) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Könnyedén használhatja az Aspose.Total for Android rendszert Java-n keresztül közvetlenül a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) webhelyről és telepítse az [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) és az [Aspose.Cells for Android via Java](https://docs.aspose.com/cells) /java/aspose-cells-for-android-via-java-installation/) az alkalmazásaiban.

Másik megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://downloads.aspose.com/total/androidjava) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Szerezze be a PCL-fájl XMP-metaadatait Androidon Java-n keresztül" %}}
Az [Aspose.PDF for Android Java viadal](https://products.aspose.com/pdf/android-java/) lehetővé teszi a PCL-fájlok XMP-metaadatainak elérését. A metaadatok beszerzéséhez hozzon létre egy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) objektumot, nyissa meg a bemeneti PCL-fájlt, és használja a [getMetadata()](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getMetadata--) tulajdonságot a metaadatok lekéréséhez.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "get-pdf-xmp-metadata.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Védje a TXT-dokumentumot Androidon Java segítségével" %}}
Az [Aspose.Cells for Android Java-n keresztül](https://products.aspose.com/cells/android-java/) támogatja a TXT-fájl védelmét az Ön igényeitől függően. A dokumentum védelme érdekében használhatja a [protectSharedWorkbook](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#protectSharedWorkbook(java.lang.String)) módszert a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "protect-txt.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pcl-to-tsv/" name="PCL Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pcl-to-xlt/" name="PCL Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pcl-to-xltx/" name="PCL Nak nek XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pcl-to-dif/" name="PCL Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pcl-to-xlam/" name="PCL Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pcl-to-sxc/" name="PCL Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pcl-to-md/" name="PCL Nak nek MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pcl-to-xlsb/" name="PCL Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pcl-to-xlsm/" name="PCL Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pcl-to-excel/" name="PCL Nak nek EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pcl-to-fods/" name="PCL Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/pcl-to-txt/" name="PCL Nak nek TXT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}