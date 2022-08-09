---
title: Exportera XLSB till POWERPOINT i Android
description: Android API för att konvertera XLSB till POWERPOINT utan att använda Microsoft Word
url: /sv/android-java/conversion/xlsb-to-powerpoint/
family: total
platformtag: cpp
feature: conversion
informat: XLSB
outformat: PPTX
otherformats: PPTX WORD DOC DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendera XLSB till POWERPOINT på Android via Java" h2="Förvandla XLSB till POWERPOINT i dina Android-applikationer utan att använda Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total för Android via Java](https://products.aspose.com/total/android-java/) är ett paket med kraftfulla API:er för filautomatisering. Genom att använda två av dess API:er kan du integrera XLSB till POWERPOINT-konverteringsfunktionen i dina Android-applikationer. I det första steget kan du exportera XLSB till PDF genom att använda [Aspose.Cells för Android via Java](https://products.aspose.com/cells/android-java/). Efter det, genom att använda [Aspose.PDF för Android via Java](https://products.aspose.com/pdf/android-java/), kan du konvertera PDF till POWERPOINT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API för att exportera XLSB till POWERPOINT" %}}
1. Öppna XLSB-filen med klassen [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Konvertera XLSB till PDF och ställ in SaveFormat till AUTO
3. Ladda den konverterade PDF-filen med klassen [Powerpointument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument)
4. Spara dokumentet i POWERPOINT-format med [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument#save-java.lang.String-com.aspose.pdf.SaveOptions -) metod
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Android via Java direkt från [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) och installera [Aspose.PDF för Android via Java](https://powerpoints.aspose.com/pdf/androidjava/installation/) och [Aspose.Cells för Android via Java](https://powerpoints.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) i dina applikationer.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSB file using Workbook class
Workbook book = new Workbook("input.xlsb");
// save XLSB as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Powerpointument class
Powerpointument powerpointument = new Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ta bort anpassade egenskaper från XLSB-fil i Android via Java" %}}
Förutom dokumentkonvertering ger [Aspose.Cells för Android via Java](https://products.aspose.com/cells/android-java/) massor av andra funktioner också. Innan konverteringsprocessen kan du ta bort anpassade egenskaper för XLSB-dokument. För att ta bort anpassade egenskaper, anropar du metoden [PowerpointumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/powerpointumentpropertycollection#remove(java.lang.String)) och skickar namnet på dokumentegenskapen som ska tas bort.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSB file using Workbook class
Workbook book = new Workbook("input.xlsb");
// retrieve a list of all custom powerpointument properties of the Excel file
PowerpointumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPowerpointumentProperties();
// remove a custom powerpointument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xlsb-to-pptx/" name="XLSB Till PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xlsb-to-word/" name="XLSB Till WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xlsb-to-powerpoint/" name="XLSB Till POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xlsb-to-powerpointx/" name="XLSB Till POWERPOINTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}