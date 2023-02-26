---
title: XLSM exportálása WORD formátumba Androidon vagy ingyenes online konverterrel
description: Android API a XLSM konvertálásához WORD formátumba Microsoft Word használata nélkül vagy online. A kód integrálása előtt gyorsan tesztelje az ingyenes CSV-DOC online konvertert.

family: total
platformtag: cpp
feature: conversion
informat: XLSM
outformat: DOC
otherformats: PPTX DOCX DOC POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderelje le a XLSM-t WORD-fájlba Androidon Java segítségével vagy online" h2="A Microsoft<sup>&reg;</sup> Excel használata nélkül alakítsa át a XLSM-t WORD formátumba Android-alkalmazásaiban" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) egy hatékony fájlautomatizálási API-k csomagja. Két API használatával integrálhatja a XLSM-ből WORD-ba konvertáló funkciót Android-alkalmazásaiba. Az első lépésben exportálhatja a XLSM-t PDF formátumba az [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) használatával. Ezt követően az [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) használatával konvertálhatja a PDF-et WORD formátumba. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API a XLSM exportálásához WORD-ba" %}}
1. Nyissa meg a XLSM-fájlt a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
2. Alakítsa át a XLSM-t PDF-be, és állítsa a SaveFormat beállítást AUTO-ra
3. Töltse be a konvertált PDF-fájlt a [Wordument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument) osztály használatával
4. Mentse a dokumentumot WORD formátumba a [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument#save-java.lang.String-com.aspose.pdf.SaveOptions segítségével -) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Könnyedén használhatja az Aspose.Total for Android rendszert Java-n keresztül közvetlenül a [Maven](https://releases.aspose.com/total/java/) webhelyről és telepítse az [Aspose.PDF for Android via Java](https://words.aspose.com/pdf/androidjava/installation/) és az [Aspose.Cells for Android via Java](https://words.aspose.com/cells) /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) alkalmazásaiban.

Másik megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/androidjava) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSM file using Workbook class
Workbook book = new Workbook("input.xlsm");
// save XLSM as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Wordument class
Wordument wordument = new Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.save("output.word", com.aspose.pdf.SaveFormat.Word);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Ingyenes online konverter XLSM-hez WORD-be</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=xlsm" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Távolítsa el az egyéni tulajdonságokat a XLSM-fájlból az Androidon Java segítségével" %}}
A dokumentumok konvertálásán kívül az [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) rengeteg egyéb funkciót is biztosít. Az átalakítási folyamat előtt eltávolíthatja a XLSM-dokumentum egyéni tulajdonságait. Az egyéni tulajdonságok eltávolításához hívja meg a [WordumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/wordumentpropertycollection#remove(java.lang.String)) metódust, és adja meg a az eltávolítandó dokumentumtulajdonság.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSM file using Workbook class
Workbook book = new Workbook("input.xlsm");
// retrieve a list of all custom wordument properties of the Excel file
WordumentPropertyCollection customProperties = workbook.getWorksheets().getCustomWordumentProperties();
// remove a custom wordument property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/xlsm-to-pptx/" name="XLSM Nak nek PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/xlsm-to-wordx/" name="XLSM Nak nek WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/xlsm-to-word/" name="XLSM Nak nek WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/xlsm-to-powerpoint/" name="XLSM Nak nek POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}