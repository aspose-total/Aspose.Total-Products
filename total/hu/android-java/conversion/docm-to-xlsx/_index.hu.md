---
title: Android API a DOCM konvertálásához XLSX-vé
description: Konvertálja a DOCM-t XLSX-vé Androidon Java segítségével Microsoft Word vagy Microsoft Excel használata nélkül
url: /hu/android-java/conversion/docm-to-xlsx/
family: total
platformtag: cpp
feature: conversion
informat: DOCM
outformat: XLSX
otherformats: XLTM XLS XLSM ODS DIF SXC XLAM EXCEL XLSB FODS XLT TSV XLTX CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="A DOCM konvertálása XLSX formátumba az Android alkalmazásokban" h2="DOCM exportálása XLSX formátumba Androidon Java segítségével Microsoft<sup>&reg;</sup> Word vagy Microsoft<sup>&reg;</sup> Excel használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) használatával integrálhatja a DOCM-XLSX-konverziós funkciót androidos alkalmazásaiba. Először is konvertálhatja a DOCM-t HTML-vé a funkciókban gazdag dokumentumkezelési és -konverziós API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) használatával. Ezt követően az [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/) használatával konvertálhatja a HTML-t XLSX-vé. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API a DOCM konvertálásához XLSX-vé" %}}
1. Nyissa meg a DOCM-fájlt a [Docmument](https://reference.aspose.com/words/java/com.aspose.words/Docmument) osztály használatával
2. A [Mentés](https://reference.aspose.com/words/java/com.aspose.words/Docmument#save(java.lang.String,com.aspose.words.SaveOptions)) segítségével konvertálja a DOCM-t HTML-vé. ) módszerrel
3. Töltsön be HTML-dokumentumot a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
4. Mentse a dokumentumot XLSX formátumba a [Mentés](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) segítségével. SaveOptions)) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Könnyedén használhatja az Aspose.Total for Android rendszert Java-n keresztül közvetlenül a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) webhelyről és telepítse [Aspose.Cells for Android via Java](https://docms.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) és [Aspose.Words for Android via Java](https://docms.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) alkalmazásaiban.

Másik megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://downloads.aspose.com/total/androidjava) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Távolítsa el a fel nem használt információkat egy DOCM-dokumentumból Androidon Java segítségével" %}}
Mielőtt a DOCM-t XLSX-vé alakítaná, eltávolíthatja a fel nem használt információkat a DOCM-dokumentumból az [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) segítségével. Néha előfordulhat, hogy el kell távolítania a fel nem használt vagy ismétlődő információkat, hogy csökkentse a kimeneti dokumentum méretét és a feldolgozási időt. A [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) osztály lehetővé teszi a dokumentumok tisztítására vonatkozó beállítások megadását. Az ismétlődő stílusok vagy csak a nem használt stílusok vagy listák dokumentumból való eltávolításához használja a [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Docmument#cleanup()) metódust. Használhatja a [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) és az [UnusedBuiltinStyles](https://reference.aspose.com/words/java) /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) tulajdonságai a „nem használtként” megjelölt stílusok észleléséhez és eltávolításához.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-docmument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Mentse el a XLSX-fájlt a streameléshez Androidon Java segítségével" %}}
A DOCM XLSX-vé konvertálása után az [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) lehetővé teszi a dokumentum adatfolyamba mentését. Ha a fájlokat adatfolyamba kell mentenie, akkor hozzon létre egy FileOutputStream objektumot, majd [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) a fájlt a Stream objektumhoz a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) mentési metódusának meghívásával. tárgy.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-xltm/" name="DOCM Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-xls/" name="DOCM Nak nek XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-xlsm/" name="DOCM Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-ods/" name="DOCM Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-dif/" name="DOCM Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-sxc/" name="DOCM Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-xlam/" name="DOCM Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-excel/" name="DOCM Nak nek EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-xlsb/" name="DOCM Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-fods/" name="DOCM Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-xlt/" name="DOCM Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-tsv/" name="DOCM Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-xltx/" name="DOCM Nak nek XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docm-to-xlsx/" name="DOCM Nak nek XLSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}