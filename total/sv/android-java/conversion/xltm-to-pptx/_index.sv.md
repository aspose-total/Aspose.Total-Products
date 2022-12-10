---
title: Exportera XLTM till PPTX i Android
description: Android API för att konvertera XLTM till PPTX utan att använda Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: XLTM
outformat: PPTX
otherformats: DOCX DOC WORD POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendera XLTM till PPTX på Android via Java" h2="Förvandla XLTM till PPTX i dina Android-applikationer utan att använda Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) är ett paket med kraftfulla API:er för filautomatisering. Genom att använda två av dess API:er kan du integrera XLTM till PPTX-konverteringsfunktionen i dina Android-applikationer. I det första steget kan du exportera XLTM till PDF genom att använda [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). Efter det, genom att använda [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/), kan du konvertera PDF till PPTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API för att exportera XLTM till PPTX" %}}
1. Öppna XLTM-filen med klassen [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Konvertera XLTM till PDF och ställ in SaveFormat till AUTO
3. Ladda den konverterade PDF-filen med klassen [Pptxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument)
4. Spara dokumentet i PPTX-format med [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument#save-java.lang.String-com.aspose.pdf.SaveOptions -) metod
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total for Android via Java direkt från [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) och installera [Aspose.PDF for Android via Java](https://pptxs.aspose.com/pdf/androidjava/installation/) och [Aspose.Cells for Android via Java](https://pptxs.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) i dina applikationer.

Alternativt kan du få en ZIP-fil från [downloads](https://releases.aspose.comtotal/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLTM file using Workbook class
Workbook book = new Workbook("input.xltm");
// save XLTM as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Pptxument class
Pptxument pptxument = new Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ta bort anpassade egenskaper från XLTM-fil i Android via Java" %}}
Förutom dokumentkonvertering ger [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) massor av andra funktioner också. Innan konverteringsprocessen kan du ta bort anpassade egenskaper för XLTM-dokument. För att ta bort anpassade egenskaper, anropar du metoden [PptxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/pptxumentpropertycollection#remove(java.lang.String)) och skickar namnet på dokumentegenskapen som ska tas bort.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLTM file using Workbook class
Workbook book = new Workbook("input.xltm");
// retrieve a list of all custom pptxument properties of the Excel file
PptxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPptxumentProperties();
// remove a custom pptxument property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xltm-to-pptxx/" name="XLTM Till PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xltm-to-pptx/" name="XLTM Till PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xltm-to-word/" name="XLTM Till WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xltm-to-powerpoint/" name="XLTM Till POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}