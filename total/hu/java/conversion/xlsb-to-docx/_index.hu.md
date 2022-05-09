---
title: A XLSB konvertálása DOCX formátumba Java segítségével
description: Java API a XLSB exportálásához DOCX-ba Excel vagy Word használatával
url_ignore: /hu/java/conversion/xlsb-to-docx/
family: total
platformtag: net
feature: conversion
informat: XLSB
outformat: DOCXX
otherformats: PPTX WORD DOCX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API a XLSB exportálásához DOCX-ba" h2="On Premise Java API a XLSB exportálásához DOCX-ba anélkül, hogy a Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
A XLSB megjelenítése DOCX-ba kétlépéses folyamat. Először az [Aspose.Cells for Java](https://products.aspose.com/cells/java) API segítségével konvertálja az adott XLSB-dokumentumot PDF-be, majd az [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API segítségével könnyedén konvertálhatja PDF dokumentumát DOCX formátumba. Mindkét API az [Aspose.Total for Java](https://products.aspose.com/total/java/) fájlformátumú automatizálási könyvtárak gyűjteményébe tartozik.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet XLSB-t DOCX-ba konvertálni Java API-n keresztül" %}}
1. Nyissa meg a XLSB-fájlt a [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
2. Alakítsa át a XLSB-t PDF-be, és állítsa a SaveFormat beállítást AUTO-ra
3. Töltse be a konvertált PDF-fájlt a [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával
4. Mentse a dokumentumot DOCX formátumba a [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions) segítségével-) metódust, és állítsa be a Docx-ot SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java programot közvetlenül egy [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) alapú projektből kell használnia és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSB file using Workbook class
Workbook book = new Workbook("input.xlsb");
// save XLSB as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document Document = new Document("pdfOutput.pdf");
// save Document in DOCXX format
Document.save("output.docxx", com.aspose.pdf.SaveFormat.DocxX);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xlsb-to-docxx/" name="XLSB Nak nek DOCXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xlsb-to-pptx/" name="XLSB Nak nek PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xlsb-to-powerpoint/" name="XLSB Nak nek POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xlsb-to-word/" name="XLSB Nak nek WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}