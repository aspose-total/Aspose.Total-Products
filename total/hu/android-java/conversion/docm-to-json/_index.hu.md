---
title: Konvertálja a DOCM-t JSON formátumba Androidon Java segítségével
description: Elemezze a DOCM-t JSON formátumba Androidon Java segítségével Microsoft Word vagy Excel használata nélkül
url: /hu/android-java/conversion/docm-to-json/
family: total
platformtag: cpp
feature: conversion
informat: DOCM
outformat: JSON
otherformats: XLT XLTM FODS SXC XLAM XLS EXCEL ODS XLSM DIF XLSB XLTX TSV CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertálja a DOCM-t JSON formátumba Androidon Java segítségével" h2="Tervezzen Android-alkalmazásokat a DOCM JSON-ba exportálásához Microsoft<sup>&reg;</sup> Word vagy Excel használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
A DOCM-t JSON-formátumba konvertálhatja Android-alkalmazásaiban az [Aspose.Total for Android via Java] segítségével (https://products.aspose.com/total/android-java/). A dokumentumkezelési és -konverziós API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) használatával DOCM-t HTML-be exportálhat. Ezt követően az [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) használatával konvertálhatja a HTML-t JSON-ba. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertálja a DOCM-t JSON formátumba az Androidon" %}}
1. Nyissa meg a DOCM-fájlt a [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) osztály használatával
2. A [Mentés](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) segítségével konvertálja a DOCM-t HTML-vé. ) módszerrel
3. Töltsön be HTML-dokumentumot a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
4. Mentse a dokumentumot JSON formátumba a [Mentés](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) segítségével. SaveOptions)) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Könnyedén használhatja az Aspose.Total for Android rendszert Java-n keresztül közvetlenül a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) webhelyről és könyvtárakat telepíteni az alkalmazásba.

Másik megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://downloads.aspose.com/total/androidjava) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="A védett DOCM konvertálása JSON formátumba Androidon Java segítségével" %}}
Az API segítségével a jelszóval védett dokumentumot is megnyithatja. Ha a bemeneti DOCM-dokumentum jelszóval védett, nem konvertálhatja azt JSON-formátumba jelszó nélkül. Az API lehetővé teszi a titkosított dokumentum megnyitását a megfelelő jelszó átadásával egy LoadOptions objektumban. A következő kódpélda bemutatja, hogyan lehet megnyitni egy titkosított dokumentumot jelszóval.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a DOCM-t JSON-ba az Android tartományban Java-n keresztül" %}}
Miközben a DOCM-t JSON-ba konvertálja, beállíthatja a kimeneti JSON-formátum tartományát is. A tartomány beállításához megnyithatja a konvertált HTML-t a Workbook osztály segítségével, létrehozhat egy adattartományt exportálandó adatokból a Cells.createRange metódussal, meghívhatja a JsonUtility.exportRangeToJson metódust Range & ExportRangeToJsonOptions hivatkozásokkal, és karakterlánc JSON-adatokat írhat a fájlba a következőn keresztül. BufferedWriter.write metódus.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-xlt/" name="DOCM Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-xltm/" name="DOCM Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-fods/" name="DOCM Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-sxc/" name="DOCM Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-xlam/" name="DOCM Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-xls/" name="DOCM Nak nek XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-excel/" name="DOCM Nak nek EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-ods/" name="DOCM Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-xlsm/" name="DOCM Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-dif/" name="DOCM Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-xlsb/" name="DOCM Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-xltx/" name="DOCM Nak nek XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-tsv/" name="DOCM Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-csv/" name="DOCM Nak nek CSV" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}