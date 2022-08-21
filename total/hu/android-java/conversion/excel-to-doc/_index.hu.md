---
title: EXCEL exportálása DOC formátumba Androidon
description: Android API a EXCEL konvertálásához DOC formátumba Microsoft Word használata nélkül
url: /hu/android-java/conversion/excel-to-doc/
family: total
platformtag: cpp
feature: conversion
informat: CSV
outformat: DOC
otherformats: PPTX WORD DOCX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderelje le a EXCEL-t DOC-fájlba Androidon Java segítségével" h2="A Microsoft<sup>&reg;</sup> Excel használata nélkül alakítsa át a EXCEL-t DOC formátumba Android-alkalmazásaiban" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) egy hatékony fájlautomatizálási API-k csomagja. Két API használatával integrálhatja a EXCEL-ből DOC-ba konvertáló funkciót Android-alkalmazásaiba. Az első lépésben exportálhatja a EXCEL-t PDF formátumba az [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) használatával. Ezt követően az [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) használatával konvertálhatja a PDF-et DOC formátumba. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API a EXCEL exportálásához DOC-ba" %}}
1. Nyissa meg a EXCEL-fájlt a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
2. Alakítsa át a EXCEL-t PDF-be, és állítsa a SaveFormat beállítást AUTO-ra
3. Töltse be a konvertált PDF-fájlt a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával
4. Mentse a dokumentumot DOC formátumba a [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) segítségével  módszer
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Könnyedén használhatja az Aspose.Total for Android rendszert Java-n keresztül közvetlenül a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) webhelyről és telepítse az [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) és az [Aspose.Cells for Android via Java](https://docs.aspose.com/cells) /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) alkalmazásaiban.

Másik megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://downloads.aspose.com/total/androidjava) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the EXCEL file using Workbook class
Workbook book = new Workbook("input.excel");
// save EXCEL as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in DOC format
document.save("output.doc", com.aspose.pdf.SaveFormat.Doc);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Távolítsa el az egyéni tulajdonságokat a EXCEL-fájlból az Androidon Java segítségével" %}}
A dokumentumok konvertálásán kívül az [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) rengeteg egyéb funkciót is biztosít. Az átalakítási folyamat előtt eltávolíthatja a EXCEL-dokumentum egyéni tulajdonságait. Az egyéni tulajdonságok eltávolításához hívja meg a [DocumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/documentpropertycollection#remove(java.lang.String)) metódust, és adja meg a az eltávolítandó dokumentumtulajdonság.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the EXCEL file using Workbook class
Workbook book = new Workbook("input.excel");
// retrieve a list of all custom document properties of the Excel file
DocumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocumentProperties();
// remove a custom document property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/excel-to-pptx/" name="EXCEL Nak nek PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/excel-to-word/" name="EXCEL Nak nek WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/excel-to-docx/" name="EXCEL Nak nek DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/excel-to-powerpoint/" name="EXCEL Nak nek POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}