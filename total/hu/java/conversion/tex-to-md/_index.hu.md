---
title: Java API a TEX MD formátumban való megjelenítéséhez
description: TEX exportálása MD formátumba Java API-n keresztül Microsoft Excel vagy Adobe Reader használata nélkül
url_ignore: /hu/java/conversion/tex-to-md/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: MD
otherformats: MD XLT ODS XLAM XLSM FODS TSV XLSB TXT EXCEL DIF XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="TEX exportálása MD-be Java-n keresztül" h2="TEX-fájl konvertálása MD-vé a helyszíni Java API használatával bármely Java J2SE, J2EE, J2ME alkalmazáson belül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for Java](https://products.aspose.com/total/java/) használatával kétlépéses folyamatban integrálhatja a TEX-ből MD-vé konvertáló funkciót Java-alkalmazásaiba. Először is, az [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) használatával a TEX XLSX formátumba renderelhető. A második lépésben az XLSX-et MD-vé konvertálhatja a Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) segítségével.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertálja a TEX fájlt MD-vé Java segítségével" %}}
1. Nyissa meg a TEX-fájlt a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával
2. Konvertálja a TEX-et XLSX-re a [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) módszerrel
3. Töltse be az XLSX dokumentumot a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
4. Mentse a dokumentumot MD formátumba a [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) segítségével. SaveOptions)) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://releases.aspose.com/total/java/) alapú projektből és tartalmazza az [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) és az [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) a pom.xml-ben.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
Ha a TEX-dokumentuma jelszóval védett, nem konvertálhatja MD-vé jelszó nélkül. Az API használatával először megnyithatja a védett dokumentumot érvényes jelszóval, és utána konvertálhatja. A titkosított fájl megnyitásához inicializálhatja a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) osztály, és adja meg a fájlnevet és a jelszót argumentumként.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertálja a védett TEX-et MD-vé Java segítségével" %}}
A TEX-fájl MD-vé konvertálásakor vízjelet is hozzáadhat a kimeneti MD-fájlformátumhoz. Vízjel hozzáadásához hozzon létre egy új munkafüzetet a konvertált XLSX fájl megnyitásához. Válassza ki a Munkalapot az indexén keresztül, hozzon létre egy alakzatot, és használja az addTextEffect funkciót, állítsa be a színeket, az átlátszóságot és így tovább. Ezt követően elmentheti az XLSX-dokumentumot MD-ként vízjellel. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



A TEX fájl átalakítása **MD formátumra (Markdown fájl)** egy standard Markdown fájlt hoz létre LaTeX-ből, megőrizve a szövegstruktúrát, táblázatokat és alapvető formázást a többplatformos olvashatóság érdekében.



{{% blocks/products/pf/agp/feature-section-col title="Kulcsfontosságú felhasználási esetek" %}}



* LaTeX kutatási jegyzetek előkészítése Git-alapú együttműködéshez.

* Könnyű dokumentáció matematikai és táblázat támogatással.

* LaTeX előadási jegyzetek megosztása nyílt forráskódú Markdown formátumban.

* Műszaki jelentések átalakítása statikus webhelyek számára.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Automatizálási forgatókönyvek" %}}



* Automatizált batch TEX-MD konverzió kutatócsoportok számára.

* Integráció verziókezelt webes tartalomcsövekbe.

* Kiváltott frissítések Markdown fájlokból LaTeX tárolókból.

* Folyamatos MD fájlok generálása oktatási vagy műszaki blogokhoz.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}