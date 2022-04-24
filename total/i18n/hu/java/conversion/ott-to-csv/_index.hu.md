---
title: Java API a OTT konvertálásához CSV-vé
description: A OTT konvertálása CSV-vé Java segítségével Microsoft Word vagy Microsoft Excel használata nélkül
url: /hu/java/conversion/ott-to-csv/
family: total
platformtag: net
feature: conversion
informat: OTT
outformat: CSV
otherformats: SXC TSV XLSM XLTX DIF EXCEL XLTM XLAM XLSX XLSB XLT ODS FODS XLS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="A OTT konvertálása CSV-vé Java segítségével" h2="On Premise Java API a OTT konvertálásához CSV-vé Microsoft<sup>&reg;</sup> Word vagy Microsoft<sup>&reg;</sup> Excel használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
A OTT konvertálása CSV-vé az [Aspose.Total for Java] segítségével (https://products.aspose.com/total/java/) egy egyszerű kétlépéses folyamat. A funkciókban gazdag, dokumentumkezelési és -konverziós API [Aspose.Words for Java] (https://products.aspose.com/words/java/) használatával OTT-t HTML-be exportálhat. Ezt követően az [Aspose.Cells for Java] (https://products.aspose.com/cells/java/) használatával konvertálhatja a HTML-t CSV-vé.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API a OTT konvertálásához CSV-vé" %}}
1. Nyissa meg a OTT-fájlt a [Ottument](https://apireference.aspose.com/words/java/com.aspose.words/Ottument) osztály használatával
2. A [Mentés](https://apireference.aspose.com/words/java/com.aspose.words/Ottument#save(java.lang.String,com.aspose.words.SaveOptions) segítségével konvertálja a OTT-t HTML-vé. ) módszerrel
3. Töltsön be HTML-dokumentumot a [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
4. Mentse a dokumentumot CSV formátumba a [Mentés](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells) segítségével. SaveOptions)) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) alapú projektből és tartalmazza az [Aspose.Words for Java](https://otts.aspose.com/words/java/installation/) és az [Aspose.Cells for Java](https://otts.aspose.com/cells/java/) install/) a pom.xml-ben.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads] webhelyről (https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
Mielőtt a OTT-t CSV-vé alakítaná, eltávolíthatja a fel nem használt információkat a OTT-dokumentumból az [Aspose.Words for Java] (https://products.aspose.com/words/java/) segítségével. Néha előfordulhat, hogy el kell távolítania a fel nem használt vagy ismétlődő információkat a kimeneti dokumentum méretének és a feldolgozási idő csökkentése érdekében. A [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) osztály lehetővé teszi a dokumentumok tisztítására vonatkozó beállítások megadását. Az ismétlődő stílusok vagy csak a nem használt stílusok vagy listák dokumentumból való eltávolításához használja a [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Ottument#cleanup()) metódust. Használhatja a [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) és az [UnusedBuiltinStyles](https://apireference.aspose.com/words/java) /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) tulajdonságok a „nem használtként” megjelölt stílusok észleléséhez és eltávolításához.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-ottument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Távolítsa el a fel nem használt információkat a OTT-dokumentumból Java segítségével" %}}
A OTT CSV-vé konvertálása után az [Aspose.Cells for Java](https://products.aspose.com/cells/java/) lehetővé teszi a dokumentum adatfolyamba való mentését. Ha a fájlokat adatfolyamba kell menteni, akkor hozzon létre egy FileOutputStream objektumot, majd [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io. OutputStream,%20com.aspose.cells.SaveOptions)) a fájlt a Stream objektumhoz a [Workbook] (https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) mentési metódusának meghívásával. tárgy. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ott-to-xlsm/" name="OTT Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ott-to-xlt/" name="OTT Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ott-to-ods/" name="OTT Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ott-to-tsv/" name="OTT Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ott-to-xls/" name="OTT Nak nek XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ott-to-xlsb/" name="OTT Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ott-to-fods/" name="OTT Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ott-to-dif/" name="OTT Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ott-to-xltx/" name="OTT Nak nek XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ott-to-xlam/" name="OTT Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ott-to-xlsx/" name="OTT Nak nek XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ott-to-xltm/" name="OTT Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ott-to-sxc/" name="OTT Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/ott-to-excel/" name="OTT Nak nek EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}