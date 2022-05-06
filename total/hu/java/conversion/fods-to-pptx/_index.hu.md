---
title: A FODS konvertálása PPTX formátumba Java segítségével
description: Java API a FODS exportálásához PPTX-ba Excel vagy Word használatával
url_ignore: /hu/java/conversion/fods-to-pptx/
family: total
platformtag: net
feature: conversion
informat: FODS
outformat: PPTX
otherformats: PPTX POWERPOINT PPTXX WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API a FODS exportálásához PPTX-ba" h2="On Premise Java API a FODS exportálásához PPTX-ba anélkül, hogy a Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
A FODS megjelenítése PPTX-ba kétlépéses folyamat. Először az [Aspose.Cells for Java](https://products.aspose.com/cells/java) API segítségével konvertálja az adott FODS-dokumentumot PDF-be, majd az [Aspose.Pdf for Java](https ://products.aspose.com/pdf/java) API segítségével könnyedén konvertálhatja PDF dokumentumát PPTX formátumba. Mindkét API az [Aspose.Total for Java](https://products.aspose.com/total/java/) fájlformátumú automatizálási könyvtárak gyűjteményébe tartozik.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet FODS-t PPTX-ba konvertálni Java API-n keresztül" %}}
1. Nyissa meg a FODS-fájlt a [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
2. Alakítsa át a FODS-t PDF-be, és állítsa a SaveFormat beállítást AUTO-ra
3. Töltse be a konvertált PDF-fájlt a [Pptxument](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Pptxument) osztály használatával
4. Mentse a dokumentumot PPTX formátumba a [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Pptxument#save-java.lang.String-com.aspose.pdf.SaveOptions) segítségével-) metódust, és állítsa be a Pptx-ot SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java programot közvetlenül egy [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) alapú projektből kell használnia és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the FODS file using Workbook class
Workbook book = new Workbook("input.fods");
// save FODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Pptxument class
Pptxument pptxument = new Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/fods-to-pptxx/" name="FODS Nak nek PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/fods-to-pptx/" name="FODS Nak nek PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/fods-to-powerpoint/" name="FODS Nak nek POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/fods-to-word/" name="FODS Nak nek WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}