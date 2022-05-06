---
title: A XLSX konvertálása POWERPOINT formátumba Java segítségével
description: Java API a XLSX exportálásához POWERPOINT-ba Excel vagy Word használatával
url_ignore: /hu/java/conversion/xlsx-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: XLSX
outformat: PPTX
otherformats: POWERPOINTX POWERPOINT WORD PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API a XLSX exportálásához POWERPOINT-ba" h2="On Premise Java API a XLSX exportálásához POWERPOINT-ba anélkül, hogy a Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
A XLSX megjelenítése POWERPOINT-ba kétlépéses folyamat. Először az [Aspose.Cells for Java](https://products.aspose.com/cells/java) API segítségével konvertálja az adott XLSX-dokumentumot PDF-be, majd az [Aspose.Pdf for Java](https ://products.aspose.com/pdf/java) API segítségével könnyedén konvertálhatja PDF dokumentumát POWERPOINT formátumba. Mindkét API az [Aspose.Total for Java](https://products.aspose.com/total/java/) fájlformátumú automatizálási könyvtárak gyűjteményébe tartozik.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet XLSX-t POWERPOINT-ba konvertálni Java API-n keresztül" %}}
1. Nyissa meg a XLSX-fájlt a [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
2. Alakítsa át a XLSX-t PDF-be, és állítsa a SaveFormat beállítást AUTO-ra
3. Töltse be a konvertált PDF-fájlt a [Powerpointument](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument) osztály használatával
4. Mentse a dokumentumot POWERPOINT formátumba a [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument#save-java.lang.String-com.aspose.pdf.SaveOptions) segítségével-) metódust, és állítsa be a Powerpoint-ot SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java programot közvetlenül egy [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) alapú projektből kell használnia és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSX file using Workbook class
Workbook book = new Workbook("input.xlsx");
// save XLSX as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Powerpointument class
Powerpointument powerpointument = new Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xlsx-to-powerpointx/" name="XLSX Nak nek POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xlsx-to-pptx/" name="XLSX Nak nek PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xlsx-to-powerpoint/" name="XLSX Nak nek POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xlsx-to-word/" name="XLSX Nak nek WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}