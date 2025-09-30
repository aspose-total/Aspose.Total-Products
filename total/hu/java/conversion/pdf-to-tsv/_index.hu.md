---
title: Java API a PDF TSV formátumban való megjelenítéséhez
description: PDF exportálása TSV formátumba Java API-n keresztül Microsoft Excel vagy Adobe Reader használata nélkül
url_ignore: /hu/java/conversion/pdf-to-tsv/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: TSV
otherformats: XLSM XLTM DIF SXC FODS MD TSV TXT XLAM XLT EXCEL XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="PDF exportálása TSV-be Java-n keresztül" h2="PDF-fájl konvertálása TSV-vé a helyszíni Java API használatával bármely Java J2SE, J2EE, J2ME alkalmazáson belül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for Java](https://products.aspose.com/total/java/) használatával kétlépéses folyamatban integrálhatja a PDF-ből TSV-vé konvertáló funkciót Java-alkalmazásaiba. Először is, az [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) használatával a PDF XLSX formátumba renderelhető. A második lépésben az XLSX-et TSV-vé konvertálhatja a Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) segítségével.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertálja a PDF fájlt TSV-vé Java segítségével" %}}
1. Nyissa meg a PDF-fájlt a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával
2. Konvertálja a PDF-et XLSX-re a [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) módszerrel
3. Töltse be az XLSX dokumentumot a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
4. Mentse a dokumentumot TSV formátumba a [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) segítségével. SaveOptions)) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://releases.aspose.com/total/java/) alapú projektből és tartalmazza az [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) és az [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) a pom.xml-ben.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
Ha a PDF-dokumentuma jelszóval védett, nem konvertálhatja TSV-vé jelszó nélkül. Az API használatával először megnyithatja a védett dokumentumot érvényes jelszóval, és utána konvertálhatja. A titkosított fájl megnyitásához inicializálhatja a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) osztály, és adja meg a fájlnevet és a jelszót argumentumként.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertálja a védett PDF-et TSV-vé Java segítségével" %}}
A PDF-fájl TSV-vé konvertálásakor vízjelet is hozzáadhat a kimeneti TSV-fájlformátumhoz. Vízjel hozzáadásához hozzon létre egy új munkafüzetet a konvertált XLSX fájl megnyitásához. Válassza ki a Munkalapot az indexén keresztül, hozzon létre egy alakzatot, és használja az addTextEffect funkciót, állítsa be a színeket, az átlátszóságot és így tovább. Ezt követően elmentheti az XLSX-dokumentumot TSV-ként vízjellel. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Az **PDF átalakítása TSV formátumba** értékes a tiszta, oszlopalapú adatkészletek létrehozásához. A PDF-ből TSV formátumba történő átalakítókkal és automatizálással a szervezetek biztosítják az adatbázisokkal, táblázatkezelőkkel és kutatási eszközökkel való kompatibilitást.
{{% blocks/products/pf/agp/feature-section-col title="Kulcsfontosságú felhasználási esetek" %}}
- Akadémiai kutatási adatkészletek
- Bioinformatikai és tudományos adattáblák
- Piaci kutatási felmérési eredmények
- Kormányzati statisztikai archívumok
- Keresztrendszerű strukturált adatcsere
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Automatizálási forgatókönyvek" %}}
- Automatizált PDF-TSV munkafolyamatok kutató laboratóriumok számára
- TSV generálás tételben strukturált jelentéskészítéshez
- Integráció adatbázis beolvasási csatornákkal
- Adatok előkészítése analitikai platformokhoz
- Nagy mennyiségű táblázatos adat automatizálása
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}