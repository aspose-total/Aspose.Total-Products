---
title: Java API a DOCX konvertálásához XLS-vé vagy ingyenes online konverterrel
description: A DOCX konvertálása XLS-vé Java segítségével vagy Online App Microsoft Word vagy Microsoft Excel használata nélkül vagy online. A kód integrálása előtt gyorsan tesztelje az ingyenes DOCX-XLS online konvertert. 
url_ignore: /hu/java/conversion/docx-to-xls/
family: total
platformtag: net
feature: conversion
informat: DOCX
outformat: XLS
otherformats: XLS SXC XLT XLSM XLSB XLTX XLS EXCEL TSV ODS XLAM XLTM FODS DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="A DOCX konvertálása XLS-vé Java segítségével vagy Online App" h2="On Premise Java API a DOCX konvertálásához XLS-vé Microsoft<sup>&reg;</sup> Word vagy Microsoft<sup>&reg;</sup> Excel használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
A DOCX konvertálása XLS-vé az [Aspose.Total for Java](https://products.aspose.com/total/java/) egy egyszerű kétlépéses folyamat. A funkciókban gazdag, dokumentumkezelési és -konverziós API [Aspose.Words for Java](https://products.aspose.com/words/java/) használatával DOCX-t HTML-be exportálhat. Ezt követően az [Aspose.Cells for Java](https://products.aspose.com/cells/java/) használatával konvertálhatja a HTML-t XLS-vé.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API a DOCX konvertálásához XLS-vé" %}}
1. Nyissa meg a DOCX-fájlt a [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) osztály használatával
2. A [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) segítségével konvertálja a DOCX-t HTML-vé. ) módszerrel
3. Töltsön be HTML-dokumentumot a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
4. Mentse a dokumentumot XLS formátumba a [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) segítségével. SaveOptions)) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://releases.aspose.com/total/java/) alapú projektből és tartalmazza az [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) és az [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) a pom.xml-ben.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Ingyenes online konverter DOCX-hez XLS-be</h3>

<iframe title="docx-ból xls-be konvertáló online eszköz" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=xls&from=docx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
Mielőtt a DOCX-t XLS-vé alakítaná, eltávolíthatja a fel nem használt információkat a DOCX-dokumentumból az [Aspose.Words for Java](https://products.aspose.com/words/java/) segítségével. Néha előfordulhat, hogy el kell távolítania a fel nem használt vagy ismétlődő információkat a kimeneti dokumentum méretének és a feldolgozási idő csökkentése érdekében. A [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) osztály lehetővé teszi a dokumentumok tisztítására vonatkozó beállítások megadását. Az ismétlődő stílusok vagy csak a nem használt stílusok vagy listák dokumentumból való eltávolításához használja a [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Document#cleanup()) metódust. Használhatja a [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) és az [UnusedBuiltinStyles](https://reference.aspose.com/words/java) /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) tulajdonságok a „nem használtként” megjelölt stílusok észleléséhez és eltávolításához.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-protected-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Távolítsa el a fel nem használt információkat a DOCX-dokumentumból Java segítségével" %}}
A DOCX XLS-vé konvertálása után az [Aspose.Cells for Java](https://products.aspose.com/cells/java/) lehetővé teszi a dokumentum adatfolyamba való mentését. Ha a fájlokat adatfolyamba kell menteni, akkor hozzon létre egy FileOutputStream objektumot, majd [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) a fájlt a Stream objektumhoz a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) mentési metódusának meghívásával. tárgy. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-protected-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}