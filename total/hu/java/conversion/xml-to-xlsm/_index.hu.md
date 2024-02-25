---
title: Java API a XML XLSM formátumban való megjelenítéséhez
description: XML exportálása XLSM formátumba Java API-n keresztül Microsoft Excel vagy Adobe Reader használata nélkül
url_ignore: /hu/java/conversion/xml-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: XML
outformat: XLSM
otherformats: XLSM XLTM ODS MD FODS EXCEL DIF XLT TSV XLSB XLTX SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="XML exportálása XLSM-be Java-n keresztül" h2="XML-fájl konvertálása XLSM-vé a helyszíni Java API használatával bármely Java J2SE, J2EE, J2ME alkalmazáson belül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for Java](https://products.aspose.com/total/java/) használatával kétlépéses folyamatban integrálhatja a XML-ből XLSM-vé konvertáló funkciót Java-alkalmazásaiba. Először is, az [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) használatával a XML XLSX formátumba renderelhető. A második lépésben az XLSX-et XLSM-vé konvertálhatja a Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) segítségével.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertálja a XML fájlt XLSM-vé Java segítségével" %}}
1. Nyissa meg a XML-fájlt a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával
2. Konvertálja a XML-et XLSX-re a [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) módszerrel
3. Töltse be az XLSX dokumentumot a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
4. Mentse a dokumentumot XLSM formátumba a [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) segítségével. SaveOptions)) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://releases.aspose.com/total/java/) alapú projektből és tartalmazza az [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) és az [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) a pom.xml-ben.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
Ha a XML-dokumentuma jelszóval védett, nem konvertálhatja XLSM-vé jelszó nélkül. Az API használatával először megnyithatja a védett dokumentumot érvényes jelszóval, és utána konvertálhatja. A titkosított fájl megnyitásához inicializálhatja a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) osztály, és adja meg a fájlnevet és a jelszót argumentumként.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertálja a védett XML-et XLSM-vé Java segítségével" %}}
A XML-fájl XLSM-vé konvertálásakor vízjelet is hozzáadhat a kimeneti XLSM-fájlformátumhoz. Vízjel hozzáadásához hozzon létre egy új munkafüzetet a konvertált XLSX fájl megnyitásához. Válassza ki a Munkalapot az indexén keresztül, hozzon létre egy alakzatot, és használja az addTextEffect funkciót, állítsa be a színeket, az átlátszóságot és így tovább. Ezt követően elmentheti az XLSX-dokumentumot XLSM-ként vízjellel. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}