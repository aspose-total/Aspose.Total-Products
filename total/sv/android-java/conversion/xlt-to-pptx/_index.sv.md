---
title: Exportera XLT till PPTX i Android
description: Android API för att konvertera XLT till PPTX utan att använda Microsoft Word
url: /sv/android-java/conversion/xlt-to-pptx/
family: total
platformtag: cpp
feature: conversion
informat: XLT
outformat: PPTX
otherformats: DOC DOCX WORD POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendera XLT till PPTX på Android via Java" h2="Förvandla XLT till PPTX i dina Android-applikationer utan att använda Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) är ett paket med kraftfulla API:er för filautomatisering. Genom att använda två av dess API:er kan du integrera XLT till PPTX-konverteringsfunktionen i dina Android-applikationer. I det första steget kan du exportera XLT till PDF genom att använda [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). Efter det, genom att använda [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/), kan du konvertera PDF till PPTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API för att exportera XLT till PPTX" %}}
1. Öppna XLT-filen med klassen [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Konvertera XLT till PDF och ställ in SaveFormat till AUTO
3. Ladda den konverterade PDF-filen med klassen [Pptxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument)
4. Spara dokumentet i PPTX-format med [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument#save-java.lang.String-com.aspose.pdf.SaveOptions -) metod
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total for Android via Java direkt från [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) och installera [Aspose.PDF for Android via Java](https://pptxs.aspose.com/pdf/androidjava/installation/) och [Aspose.Cells for Android via Java](https://pptxs.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) i dina applikationer.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLT file using Workbook class
Workbook book = new Workbook("input.xlt");
// save XLT as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Pptxument class
Pptxument pptxument = new Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ta bort anpassade egenskaper från XLT-fil i Android via Java" %}}
Förutom dokumentkonvertering ger [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) massor av andra funktioner också. Innan konverteringsprocessen kan du ta bort anpassade egenskaper för XLT-dokument. För att ta bort anpassade egenskaper, anropar du metoden [PptxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/pptxumentpropertycollection#remove(java.lang.String)) och skickar namnet på dokumentegenskapen som ska tas bort.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLT file using Workbook class
Workbook book = new Workbook("input.xlt");
// retrieve a list of all custom pptxument properties of the Excel file
PptxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPptxumentProperties();
// remove a custom pptxument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xlt-to-pptx/" name="XLT Till PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xlt-to-pptxx/" name="XLT Till PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xlt-to-word/" name="XLT Till WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xlt-to-powerpoint/" name="XLT Till POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}