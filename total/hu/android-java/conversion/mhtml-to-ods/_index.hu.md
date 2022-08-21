---
title: Konvertálja a MHTML-et ODS-vé Androidon Java segítségével
description: Rendelje meg a MHTML-et ODS formátumban Androidon a Java API-n keresztül Microsoft Excel vagy Adobe Reader használata nélkül
url: /hu/android-java/conversion/mhtml-to-ods/
family: total
platformtag: cpp
feature: conversion
informat: MHTML
outformat: ODS
otherformats: TSV XLSM DIF MD EXCEL XLTM TXT FODS XLT SXC XLSB XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderelje le a MHTML-et ODS formátumba Androidon Java segítségével" h2="A MHTML átalakítása ODS-vé az Android-alkalmazásokon belül Microsoft<sup>&reg;</sup> Excel vagy Adobe<sup>&reg;</sup> Acrobat Reader alkalmazása nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Két lépésben integrálhatja a MHTML-ODS konverziós funkciót az Android-alkalmazásaiba. Először is, az [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) használatával rejtett MHTML-et XLSX-re alakíthat. Másodszor, az XLSX-t ODS-vé alakíthatja a Powerful Spreadsheet Processing API [Aspose.Cells for Android via Java] használatával (https://products.aspose.com/cells/android-java/). Mindkét API az [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) termékcsaládba tartozik. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API a MHTML ODS formátumban való megjelenítéséhez" %}}
1. Nyissa meg a MHTML-fájlt a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával
2. Konvertálja a MHTML-et XLSX-re a [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) módszerrel
3. Töltse be az XLSX dokumentumot a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
4. Mentse a dokumentumot ODS formátumba a [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) segítségével. SaveOptions)) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Könnyedén használhatja az Aspose.Total for Android rendszert Java-n keresztül közvetlenül a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) webhelyről és telepítse az [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) és az [Aspose.Cells for Android via Java](https://docs.aspose.com/cells) /java/aspose-cells-for-android-via-java-installation/) az alkalmazásaiban.

Másik megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://downloads.aspose.com/total/androidjava) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Szerezze be a MHTML-fájl XMP-metaadatait Androidon Java-n keresztül" %}}
Az [Aspose.PDF for Android Java viadal](https://products.aspose.com/pdf/android-java/) lehetővé teszi a MHTML-fájlok XMP-metaadatainak elérését. A metaadatok beszerzéséhez hozzon létre egy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) objektumot, nyissa meg a bemeneti MHTML-fájlt, és használja a [getMetadata()](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getMetadata--) tulajdonságot a metaadatok lekéréséhez.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "get-pdf-xmp-metadata.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Védje a ODS-dokumentumot Androidon Java segítségével" %}}
Az [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) támogatja a ODS-fájl védelmét az Ön igényeitől függően. A dokumentum védelme érdekében használhatja a [protectSharedWorkbook](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#protectSharedWorkbook(java.lang.String)) módszert a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "protect-ods.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/mhtml-to-tsv/" name="MHTML Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/mhtml-to-xlsm/" name="MHTML Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/mhtml-to-dif/" name="MHTML Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/mhtml-to-md/" name="MHTML Nak nek MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/mhtml-to-excel/" name="MHTML Nak nek EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/mhtml-to-xltm/" name="MHTML Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/mhtml-to-txt/" name="MHTML Nak nek TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/mhtml-to-fods/" name="MHTML Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/mhtml-to-xlt/" name="MHTML Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/mhtml-to-sxc/" name="MHTML Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/mhtml-to-xlsb/" name="MHTML Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/mhtml-to-xltx/" name="MHTML Nak nek XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}