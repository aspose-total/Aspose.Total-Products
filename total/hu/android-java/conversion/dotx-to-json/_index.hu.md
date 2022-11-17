---
title: Konvertálja a DOTX-t JSON formátumba Androidon Java segítségével
description: Elemezze a DOTX-t JSON formátumba Androidon Java segítségével Microsoft Word vagy Excel használata nélkül

family: total
platformtag: cpp
feature: conversion
informat: DOTX
outformat: JSON
otherformats: SXC XLSM XLSB TSV XLAM XLT DIF EXCEL XLTX CSV XLTM FODS ODS XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertálja a DOTX-t JSON formátumba Androidon Java segítségével" h2="Tervezzen Android-alkalmazásokat a DOTX JSON-ba exportálásához Microsoft<sup>&reg;</sup> Word vagy Excel használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
A DOTX-t JSON-formátumba konvertálhatja Android-alkalmazásaiban az [Aspose.Total for Android via Java] segítségével (https://products.aspose.com/total/android-java/). A dokumentumkezelési és -konverziós API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) használatával DOTX-t HTML-be exportálhat. Ezt követően az [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) használatával konvertálhatja a HTML-t JSON-ba. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertálja a DOTX-t JSON formátumba az Androidon" %}}
1. Nyissa meg a DOTX-fájlt a [Dotxument](https://reference.aspose.com/words/java/com.aspose.words/Dotxument) osztály használatával
2. A [Mentés](https://reference.aspose.com/words/java/com.aspose.words/Dotxument#save(java.lang.String,com.aspose.words.SaveOptions) segítségével konvertálja a DOTX-t HTML-vé. ) módszerrel
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

{{% blocks/products/pf/feature-page-section  h2="A védett DOTX konvertálása JSON formátumba Androidon Java segítségével" %}}
Az API segítségével a jelszóval védett dokumentumot is megnyithatja. Ha a bemeneti DOTX-dokumentum jelszóval védett, nem konvertálhatja azt JSON-formátumba jelszó nélkül. Az API lehetővé teszi a titkosított dokumentum megnyitását a megfelelő jelszó átadásával egy LoadOptions objektumban. A következő kódpélda bemutatja, hogyan lehet megnyitni egy titkosított dokumentumot jelszóval.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a DOTX-t JSON-ba az Android tartományban Java-n keresztül" %}}
Miközben a DOTX-t JSON-ba konvertálja, beállíthatja a kimeneti JSON-formátum tartományát is. A tartomány beállításához megnyithatja a konvertált HTML-t a Workbook osztály segítségével, létrehozhat egy adattartományt exportálandó adatokból a Cells.createRange metódussal, meghívhatja a JsonUtility.exportRangeToJson metódust Range & ExportRangeToJsonOptions hivatkozásokkal, és karakterlánc JSON-adatokat írhat a fájlba a következőn keresztül. BufferedWriter.write metódus.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/dotx-to-sxc/" name="DOTX Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/dotx-to-xlsm/" name="DOTX Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/dotx-to-xlsb/" name="DOTX Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/dotx-to-tsv/" name="DOTX Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/dotx-to-xlam/" name="DOTX Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/dotx-to-xlt/" name="DOTX Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/dotx-to-dif/" name="DOTX Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/dotx-to-excel/" name="DOTX Nak nek EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/dotx-to-xltx/" name="DOTX Nak nek XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/dotx-to-csv/" name="DOTX Nak nek CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/dotx-to-xltm/" name="DOTX Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/dotx-to-fods/" name="DOTX Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/dotx-to-ods/" name="DOTX Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/dotx-to-xlsx/" name="DOTX Nak nek XLSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}