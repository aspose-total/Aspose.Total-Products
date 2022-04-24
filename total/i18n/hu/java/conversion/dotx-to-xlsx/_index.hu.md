---
title: Java API a DOTX konvertálásához XLSX-vé
description: A DOTX konvertálása XLSX-vé Java segítségével Microsoft Word vagy Microsoft Excel használata nélkül
url: /hu/java/conversion/dotx-to-xlsx/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: XLSX
otherformats: XLAM ODS TSV XLT FODS XLSX DIF XLTM XLS SXC XLSM XLSB EXCEL XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="A DOTX konvertálása XLSX-vé Java segítségével" h2="On Premise Java API a DOTX konvertálásához XLSX-vé Microsoft<sup>&reg;</sup> Word vagy Microsoft<sup>&reg;</sup> Excel használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
A DOTX konvertálása XLSX-vé az [Aspose.Total for Java] segítségével (https://products.aspose.com/total/java/) egy egyszerű kétlépéses folyamat. A funkciókban gazdag, dokumentumkezelési és -konverziós API [Aspose.Words for Java](https://products.aspose.com/words/java/) használatával DOTX-t HTML-be exportálhat. Ezt követően az [Aspose.Cells for Java](https://products.aspose.com/cells/java/) használatával konvertálhatja a HTML-t XLSX-vé.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API a DOTX konvertálásához XLSX-vé" %}}
1. Nyissa meg a DOTX-fájlt a [Dotxument](https://apireference.aspose.com/words/java/com.aspose.words/Dotxument) osztály használatával
2. A [Mentés](https://apireference.aspose.com/words/java/com.aspose.words/Dotxument#save(java.lang.String,com.aspose.words.SaveOptions) segítségével konvertálja a DOTX-t HTML-vé. ) módszerrel
3. Töltsön be HTML-dokumentumot a [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
4. Mentse a dokumentumot XLSX formátumba a [Mentés](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells) segítségével. SaveOptions)) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) alapú projektből és tartalmazza az [Aspose.Words for Java](https://dotxs.aspose.com/words/java/installation/) és az [Aspose.Cells for Java](https://dotxs.aspose.com/cells/java/) install/) a pom.xml-ben.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads] webhelyről (https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}](
Mielőtt a DOTX-t XLSX-vé alakítaná, eltávolíthatja a fel nem használt információkat a DOTX-dokumentumból az [Aspose.Words for Java](https://products.aspose.com/words/java/) segítségével. Néha előfordulhat, hogy el kell távolítania a fel nem használt vagy ismétlődő információkat a kimeneti dokumentum méretének és a feldolgozási idő csökkentése érdekében. A [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) osztály lehetővé teszi a dokumentumok tisztítására vonatkozó beállítások megadását. Az ismétlődő stílusok vagy csak a nem használt stílusok vagy listák dokumentumból való eltávolításához használja a [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Dotxument#cleanup()) metódust. Használhatja a [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) és az [UnusedBuiltinStyles](https://apireference.aspose.com/words/java) /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) tulajdonságok a „nem használtként” megjelölt stílusok észleléséhez és eltávolításához.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-protected-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}](
{{% blocks/products/pf/feature-page-section  h2="Távolítsa el a fel nem használt információkat a DOTX-dokumentumból Java segítségével" %}}
A DOTX XLSX-vé konvertálása után az [Aspose.Cells for Java](https://products.aspose.com/cells/java/) lehetővé teszi a dokumentum adatfolyamba való mentését. Ha a fájlokat adatfolyamba kell menteni, akkor hozzon létre egy FileOutputStream objektumot, majd [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io. OutputStream,%20com.aspose.cells.SaveOptions)) a fájlt a Stream objektumhoz a [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) mentési metódusának meghívásával. tárgy. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-protected-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-xlsm/" name="DOTX Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-xlt/" name="DOTX Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-ods/" name="DOTX Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-tsv/" name="DOTX Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-xls/" name="DOTX Nak nek XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-xlsb/" name="DOTX Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-fods/" name="DOTX Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-dif/" name="DOTX Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-xltx/" name="DOTX Nak nek XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-xlam/" name="DOTX Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-xlsx/" name="DOTX Nak nek XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-xltm/" name="DOTX Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-sxc/" name="DOTX Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dotx-to-excel/" name="DOTX Nak nek EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}