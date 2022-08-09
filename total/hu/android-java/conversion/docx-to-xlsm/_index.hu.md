---
title: Android API a DOCX konvertálásához XLSM-vé
description: Konvertálja a DOCX-t XLSM-vé Androidon Java segítségével Microsoft Word vagy Microsoft Excel használata nélkül
url: /hu/android-java/conversion/docx-to-xlsm/
family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: XLSM
otherformats: CSV XLTM SXC FODS XLSX EXCEL XLS XLAM DIF ODS XLSB XLTX TSV XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="A DOCX konvertálása XLSM formátumba az Android alkalmazásokban" h2="DOCX exportálása XLSM formátumba Androidon Java segítségével Microsoft<sup>&reg;</sup> Word vagy Microsoft<sup>&reg;</sup> Excel használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) használatával integrálhatja a DOCX-XLSM-konverziós funkciót androidos alkalmazásaiba. Először is konvertálhatja a DOCX-t HTML-vé a funkciókban gazdag dokumentumkezelési és -konverziós API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) használatával. Ezt követően az [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/) használatával konvertálhatja a HTML-t XLSM-vé. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API a DOCX konvertálásához XLSM-vé" %}}
1. Nyissa meg a DOCX-fájlt a [Docxument](https://reference.aspose.com/words/java/com.aspose.words/Docxument) osztály használatával
2. A [Mentés](https://reference.aspose.com/words/java/com.aspose.words/Docxument#save(java.lang.String,com.aspose.words.SaveOptions) segítségével konvertálja a DOCX-t HTML-vé. ) módszerrel
3. Töltsön be HTML-dokumentumot a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
4. Mentse a dokumentumot XLSM formátumba a [Mentés](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) segítségével. SaveOptions)) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Könnyedén használhatja az Aspose.Total for Android rendszert Java-n keresztül közvetlenül a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) webhelyről és telepítse [Aspose.Cells for Android via Java](https://docxs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) és [Aspose.Words for Android via Java](https://docxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository) alkalmazásaiban.

Másik megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://downloads.aspose.com/total/androidjava) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Távolítsa el a fel nem használt információkat egy DOCX-dokumentumból Androidon Java segítségével" %}}
Mielőtt a DOCX-t XLSM-vé alakítaná, eltávolíthatja a fel nem használt információkat a DOCX-dokumentumból az [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) segítségével. Néha előfordulhat, hogy el kell távolítania a fel nem használt vagy ismétlődő információkat, hogy csökkentse a kimeneti dokumentum méretét és a feldolgozási időt. A [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) osztály lehetővé teszi a dokumentumok tisztítására vonatkozó beállítások megadását. Az ismétlődő stílusok vagy csak a nem használt stílusok vagy listák dokumentumból való eltávolításához használja a [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Docxument#cleanup()) metódust. Használhatja a [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) és az [UnusedBuiltinStyles](https://reference.aspose.com/words/java) /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) tulajdonságai a „nem használtként” megjelölt stílusok észleléséhez és eltávolításához.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-docxument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Mentse el a XLSM-fájlt a streameléshez Androidon Java segítségével" %}}
A DOCX XLSM-vé konvertálása után az [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) lehetővé teszi a dokumentum adatfolyamba mentését. Ha a fájlokat adatfolyamba kell mentenie, akkor hozzon létre egy FileOutputStream objektumot, majd [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) a fájlt a Stream objektumhoz a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) mentési metódusának meghívásával. tárgy.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docx-to-xlsm/" name="DOCX Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docx-to-xltm/" name="DOCX Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docx-to-sxc/" name="DOCX Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docx-to-fods/" name="DOCX Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docx-to-xlsx/" name="DOCX Nak nek XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docx-to-excel/" name="DOCX Nak nek EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docx-to-xls/" name="DOCX Nak nek XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docx-to-xlam/" name="DOCX Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docx-to-dif/" name="DOCX Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docx-to-ods/" name="DOCX Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docx-to-xlsb/" name="DOCX Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docx-to-xltx/" name="DOCX Nak nek XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docx-to-tsv/" name="DOCX Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/docx-to-xlt/" name="DOCX Nak nek XLT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}