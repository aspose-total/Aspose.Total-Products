---
title: Java API a CGM FODS formátumban való megjelenítéséhez
description: CGM exportálása FODS formátumba Java API-n keresztül Microsoft Excel vagy Adobe Reader használata nélkül
url_ignore: /hu/java/conversion/cgm-to-fods/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: FODS
otherformats: ODS TSV XLTX EXCEL XLSB TXT SXC XLSM XLTM MD XLT DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="CGM exportálása FODS-be Java-n keresztül" h2="CGM-fájl konvertálása FODS-vé a helyszíni Java API használatával bármely Java J2SE, J2EE, J2ME alkalmazáson belül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for Java](https://products.aspose.com/total/java/) használatával kétlépéses folyamatban integrálhatja a CGM-ből FODS-vé konvertáló funkciót Java-alkalmazásaiba. Először is, az [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) használatával a CGM XLSX formátumba renderelhető. A második lépésben az XLSX-et FODS-vé konvertálhatja a Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) segítségével.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertálja a CGM fájlt FODS-vé Java segítségével" %}}
1. Nyissa meg a CGM-fájlt a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával
2. Konvertálja a CGM-et XLSX-re a [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) módszerrel
3. Töltse be az XLSX dokumentumot a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
4. Mentse a dokumentumot FODS formátumba a [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) segítségével. SaveOptions)) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java könnyen használható közvetlenül [Maven](https://releases.aspose.com/total/java/) alapú projektből és tartalmazza az [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) és az [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) a pom.xml-ben.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverziós követelmények" %}}
Ha a CGM-dokumentuma jelszóval védett, nem konvertálhatja FODS-vé jelszó nélkül. Az API használatával először megnyithatja a védett dokumentumot érvényes jelszóval, és utána konvertálhatja. A titkosított fájl megnyitásához inicializálhatja a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) osztály, és adja meg a fájlnevet és a jelszót argumentumként.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertálja a védett CGM-et FODS-vé Java segítségével" %}}
A CGM-fájl FODS-vé konvertálásakor vízjelet is hozzáadhat a kimeneti FODS-fájlformátumhoz. Vízjel hozzáadásához hozzon létre egy új munkafüzetet a konvertált XLSX fájl megnyitásához. Válassza ki a Munkalapot az indexén keresztül, hozzon létre egy alakzatot, és használja az addTextEffect funkciót, állítsa be a színeket, az átlátszóságot és így tovább. Ezt követően elmentheti az XLSX-dokumentumot FODS-ként vízjellel. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Az **Computer Graphics Metafile (CGM)** fájlok átalakítása **FODS (Flat OpenDocument Spreadsheet)** formátumba hatékony módszer a grafikus technikai adatok strukturált, nyílt szabványú táblázatokká történő átalakítására. **Java alapú nyílt forráskódú alkalmazásokban** ez az átalakítás lehetővé teszi a mérési értékek, specifikációk és vektorgrafikus részletek kinyerését a CGM diagramokból szerkeszthető FODS táblázatokba. Mint egy ODF-kompatibilis XML formátum, a FODS kompatibilis az OpenOffice hasonló eszközeivel, így könnyen megosztható és együttműködhető anélkül, hogy korlátozások lennének.

## ✅ Fő felhasználási esetek

- **Grafikus technikai adatok átalakítása táblázatokká**  
  Vektorgrafikus adatok kinyerése a CGM fájlokból strukturált sorokba és oszlopokba történő elemzéshez.

- **Mérési értékek dokumentálása**  
  Mérnöki méréseket vagy kísérleti eredményeket tárolni és kezelni hordozható táblázatformátumban.

- **Megosztás ODF eszközökön keresztül**  
  A CGM-ből származó táblázatadatok terjesztése ODF-kompatibilis alkalmazásokon keresztül.

## ⚙️ Automatizálási forgatókönyvek

- **Java könyvtárak, mint a JOpenDocument**  
  Automatizálja a CGM-FODS átalakítást Java munkafolyamatokban nyílt forráskódú táblázatkezelő könyvtárak segítségével.

- **Fej nélküli LibreOffice integráció**  
  Futtassa a LibreOffice-ot fej nélküli módban Java alkalmazásokból, hogy tömegesen átalakítsa a CGM grafikákat FODS táblázatokká.

- **Tömeges FODS generálás**  
  Építse be a CGM feldolgozást és FODS létrehozást Java alapú ETL csővezetékekbe nagy adatmennyiségű adatok kinyeréséhez.

- **Nyílt forráskódú adatfeldolgozási rendszerek**  
  Használja a FODS-t Java-alapú tudományos vagy mérnöki platformok részeként átlátható, szabványokon alapuló adatkezeléshez.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}