---
title: Java API a MHTML XLT formátumban való megjelenítéséhez
description: MHTML exportálása XLT formátumba Java API-n keresztül Microsoft Excel vagy Adobe Reader használata nélkül
url_ignore: /hu/java/conversion/mhtml-to-xlt/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: XLT
otherformats: DIF MD EXCEL ODS XLT FODS XLAM XLSB SXC XLTM TXT TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="MHTML exportálása XLT-be Java-n keresztül" h2="MHTML-fájl konvertálása XLT-vé a helyszíni Java API használatával bármely Java J2SE, J2EE, J2ME alkalmazáson belül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for Java](https://products.aspose.com/total/java/) használatával kétlépéses folyamatban integrálhatja a MHTML-ből XLT-vé konvertáló funkciót Java-alkalmazásaiba. Először is, az [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) használatával a MHTML XLSX formátumba renderelhető. A második lépésben az XLSX-et XLT-vé konvertálhatja a Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) segítségével.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertálja a MHTML fájlt XLT-vé Java segítségével" %}}
1. Nyissa meg a MHTML-fájlt a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával
2. Konvertálja a MHTML-et XLSX-re a [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) módszerrel
3. Töltse be az XLSX dokumentumot a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
4. Mentse a dokumentumot XLT formátumba a [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) segítségével. SaveOptions)) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) alapú projektből és tartalmazza az [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) és az [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) a pom.xml-ben.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
Ha a MHTML-dokumentuma jelszóval védett, nem konvertálhatja XLT-vé jelszó nélkül. Az API használatával először megnyithatja a védett dokumentumot érvényes jelszóval, és utána konvertálhatja. A titkosított fájl megnyitásához inicializálhatja a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) osztály, és adja meg a fájlnevet és a jelszót argumentumként.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertálja a védett MHTML-et XLT-vé Java segítségével" %}}
A MHTML-fájl XLT-vé konvertálásakor vízjelet is hozzáadhat a kimeneti XLT-fájlformátumhoz. Vízjel hozzáadásához hozzon létre egy új munkafüzetet a konvertált XLSX fájl megnyitásához. Válassza ki a Munkalapot az indexén keresztül, hozzon létre egy alakzatot, és használja az addTextEffect funkciót, állítsa be a színeket, az átlátszóságot és így tovább. Ezt követően elmentheti az XLSX-dokumentumot XLT-ként vízjellel. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/mhtml-to-dif/" name="MHTML Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/mhtml-to-xltx/" name="MHTML Nak nek XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/mhtml-to-md/" name="MHTML Nak nek MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/mhtml-to-fods/" name="MHTML Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/mhtml-to-xltm/" name="MHTML Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/mhtml-to-excel/" name="MHTML Nak nek EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/mhtml-to-xlsm/" name="MHTML Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/mhtml-to-xlam/" name="MHTML Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/mhtml-to-xlt/" name="MHTML Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/mhtml-to-xlsb/" name="MHTML Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/mhtml-to-ods/" name="MHTML Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/mhtml-to-sxc/" name="MHTML Nak nek SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}