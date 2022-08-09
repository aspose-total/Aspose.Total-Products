---
title: XLTM exportálása DOCX formátumba Androidon
description: Android API a XLTM konvertálásához DOCX formátumba Microsoft Word használata nélkül
url: /hu/android-java/conversion/xltm-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: XLTM
outformat: DOCX
otherformats: PPTX WORD DOC POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderelje le a XLTM-t DOCX-fájlba Androidon Java segítségével" h2="A Microsoft<sup>&reg;</sup> Excel használata nélkül alakítsa át a XLTM-t DOCX formátumba Android-alkalmazásaiban" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total Androidra Java-n keresztül](https://products.aspose.com/total/android-java/) egy hatékony fájlautomatizálási API-k csomagja. Két API használatával integrálhatja a XLTM-ből DOCX-ba konvertáló funkciót Android-alkalmazásaiba. Az első lépésben exportálhatja a XLTM-t PDF formátumba az [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) használatával. Ezt követően az [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) használatával konvertálhatja a PDF-et DOCX formátumba. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API a XLTM exportálásához DOCX-ba" %}}
1. Nyissa meg a XLTM-fájlt a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
2. Alakítsa át a XLTM-t PDF-be, és állítsa a SaveFormat beállítást AUTO-ra
3. Töltse be a konvertált PDF-fájlt a [Docxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument) osztály használatával
4. Mentse a dokumentumot DOCX formátumba a [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument#save-java.lang.String-com.aspose.pdf.SaveOptions segítségével -) módszer
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Könnyedén használhatja az Aspose.Total for Android rendszert Java-n keresztül közvetlenül a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) webhelyről és telepítse az [Aspose.PDF for Android via Java](https://docxs.aspose.com/pdf/androidjava/installation/) és az [Aspose.Cells for Android via Java](https://docxs.aspose.com/cells) /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) alkalmazásaiban.

Másik megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://downloads.aspose.com/total/androidjava) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLTM file using Workbook class
Workbook book = new Workbook("input.xltm");
// save XLTM as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Docxument class
Docxument docxument = new Docxument("pdfOutput.pdf");
// save docxument in DOCX format
docxument.save("output.docx", com.aspose.pdf.SaveFormat.DocxX);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Távolítsa el az egyéni tulajdonságokat a XLTM-fájlból az Androidon Java segítségével" %}}
A dokumentumok konvertálásán kívül az [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) rengeteg egyéb funkciót is biztosít. Az átalakítási folyamat előtt eltávolíthatja a XLTM-dokumentum egyéni tulajdonságait. Az egyéni tulajdonságok eltávolításához hívja meg a [DocxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/docxumentpropertycollection#remove(java.lang.String)) metódust, és adja meg a az eltávolítandó dokumentumtulajdonság.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLTM file using Workbook class
Workbook book = new Workbook("input.xltm");
// retrieve a list of all custom docxument properties of the Excel file
DocxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocxumentProperties();
// remove a custom docxument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/xltm-to-pptx/" name="XLTM Nak nek PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/xltm-to-word/" name="XLTM Nak nek WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/xltm-to-docx/" name="XLTM Nak nek DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/xltm-to-powerpoint/" name="XLTM Nak nek POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}