---
title: A WORD konvertálása JSON formátumba Java segítségével
description: A WORD konvertálása JSON formátumba Java segítségével Microsoft Word vagy Microsoft Excel használata nélkül
url: /hu/java/conversion/word-to-json/
family: total
platformtag: net
feature: conversion
informat: WORD
outformat: JSON
otherformats: SXC XLSX XLS DIF XLSB XLT XLAM TSV XLTM XLSM EXCEL XLTX FODS CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="A WORD konvertálása JSON formátumba Java segítségével" h2="On Premise Java API a WORD konvertálásához JSON formátumba Microsoft<sup>&reg;</sup> Word vagy Microsoft<sup>&reg;</sup> Excel használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
A WORD konvertálása JSON formátumba az [Aspose.Total for Java] segítségével (https://products.aspose.com/total/java/) egy egyszerű kétlépéses folyamat. A funkciókban gazdag, dokumentumkezelési és -konverziós API [Aspose.Words for Java](https://products.aspose.com/words/java/) használatával WORD-t HTML-be exportálhat. Ezt követően az [Aspose.Cells for Java](https://products.aspose.com/cells/java/) használatával konvertálhatja a HTML-t JSON-ba.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="A WORD konvertálása JSON formátumba Java segítségével" %}}
1. Nyissa meg a WORD-fájlt a [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) osztály használatával
2. A [Mentés](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) segítségével konvertálja a WORD-t HTML-vé. ) módszerrel
3. Töltsön be HTML-dokumentumot a [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
4. Mentse a dokumentumot JSON formátumba a [Mentés](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells) segítségével. SaveOptions)) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) alapú projektből és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads] webhelyről (https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
Az API segítségével a jelszóval védett dokumentumot is megnyithatja. Ha a bevitt WORD-dokumentum jelszóval védett, nem konvertálhatja azt JSON-formátumba a jelszó használata nélkül. Az API lehetővé teszi a titkosított dokumentum megnyitását a megfelelő jelszó átadásával egy LoadOptions objektumban. A következő kódpélda bemutatja, hogyan próbáljon meg jelszóval megnyitni egy titkosított dokumentumot:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="A védett WORD konvertálása JSON formátumba Java segítségével" %}}
Miközben a WORD-t JSON-ba konvertálja, beállíthatja a kimeneti JSON-formátum tartományát is. A tartomány beállításához megnyithatja a konvertált HTML-t a Workbook osztály segítségével, létrehozhat egy tartományt exportálandó adatokból a Cells.createRange metódussal, meghívhatja a JsonUtility.exportRangeToJson metódust Range & ExportRangeToJsonOptions hivatkozásokkal, és karakterlánc JSON adatokat írhat a fájlba a következőn keresztül. BufferedWriter.write metódus. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-xlam/" name="WORD Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-xlt/" name="WORD Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-csv/" name="WORD Nak nek CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-xlsx/" name="WORD Nak nek XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-fods/" name="WORD Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-xltm/" name="WORD Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-xlsm/" name="WORD Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-xltx/" name="WORD Nak nek XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-ods/" name="WORD Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-xlsb/" name="WORD Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-excel/" name="WORD Nak nek EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-sxc/" name="WORD Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-tsv/" name="WORD Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/word-to-dif/" name="WORD Nak nek DIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}