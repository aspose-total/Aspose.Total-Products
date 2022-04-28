---
title: Java API a DOT konvertálásához TSV-vé
description: A DOT konvertálása TSV-vé Java segítségével Microsoft Word vagy Microsoft Excel használata nélkül
url: /hu/java/conversion/dot-to-tsv/
family: total
platformtag: net
feature: conversion
informat: DOT
outformat: TSV
otherformats: XLTX XLS XLAM EXCEL TSV XLT XLSB ODS XLTM SXC XLSX XLSM FODS DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="A DOT konvertálása TSV-vé Java segítségével" h2="On Premise Java API a DOT konvertálásához TSV-vé Microsoft<sup>&reg;</sup> Word vagy Microsoft<sup>&reg;</sup> Excel használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
A DOT konvertálása TSV-vé az [Aspose.Total for Java] segítségével (https://products.aspose.com/total/java/) egy egyszerű kétlépéses folyamat. A funkciókban gazdag, dokumentumkezelési és -konverziós API [Aspose.Words for Java](https://products.aspose.com/words/java/) használatával DOT-t HTML-be exportálhat. Ezt követően az [Aspose.Cells for Java](https://products.aspose.com/cells/java/) használatával konvertálhatja a HTML-t TSV-vé.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API a DOT konvertálásához TSV-vé" %}}
1. Nyissa meg a DOT-fájlt a [Dotument](https://apireference.aspose.com/words/java/com.aspose.words/Dotument) osztály használatával
2. A [Mentés](https://apireference.aspose.com/words/java/com.aspose.words/Dotument#save(java.lang.String,com.aspose.words.SaveOptions) segítségével konvertálja a DOT-t HTML-vé. ) módszerrel
3. Töltsön be HTML-dokumentumot a [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
4. Mentse a dokumentumot TSV formátumba a [Mentés](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells) segítségével. SaveOptions)) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) alapú projektből és tartalmazza az [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) és az [Aspose.Cells for Java](https://docs.aspose.com/cells/java/) install/) a pom.xml-ben.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads] webhelyről (https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}](
Mielőtt a DOT-t TSV-vé alakítaná, eltávolíthatja a fel nem használt információkat a DOT-dokumentumból az [Aspose.Words for Java](https://products.aspose.com/words/java/) segítségével. Néha előfordulhat, hogy el kell távolítania a fel nem használt vagy ismétlődő információkat a kimeneti dokumentum méretének és a feldolgozási idő csökkentése érdekében. A [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) osztály lehetővé teszi a dokumentumok tisztítására vonatkozó beállítások megadását. Az ismétlődő stílusok vagy csak a nem használt stílusok vagy listák dokumentumból való eltávolításához használja a [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Dotument#cleanup()) metódust. Használhatja a [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) és az [UnusedBuiltinStyles](https://apireference.aspose.com/words/java) /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) tulajdonságok a „nem használtként” megjelölt stílusok észleléséhez és eltávolításához.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-dotument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}](
{{% blocks/products/pf/feature-page-section  h2="Távolítsa el a fel nem használt információkat a DOT-dokumentumból Java segítségével" %}}
A DOT TSV-vé konvertálása után az [Aspose.Cells for Java](https://products.aspose.com/cells/java/) lehetővé teszi a dokumentum adatfolyamba való mentését. Ha a fájlokat adatfolyamba kell menteni, akkor hozzon létre egy FileOutputStream objektumot, majd [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) a fájlt a Stream objektumhoz a [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) mentési metódusának meghívásával. tárgy. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xlsm/" name="DOT Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xlt/" name="DOT Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-ods/" name="DOT Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-tsv/" name="DOT Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xls/" name="DOT Nak nek XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xlsb/" name="DOT Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-fods/" name="DOT Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-dif/" name="DOT Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xltx/" name="DOT Nak nek XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xlam/" name="DOT Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xlsx/" name="DOT Nak nek XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-xltm/" name="DOT Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-sxc/" name="DOT Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/dot-to-excel/" name="DOT Nak nek EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}