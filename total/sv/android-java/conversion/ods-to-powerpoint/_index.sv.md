---
title: Exportera ODS till POWERPOINT i Android
description: Android API för att konvertera ODS till POWERPOINT utan att använda Microsoft Word
url: /sv/android-java/conversion/ods-to-powerpoint/
family: total
platformtag: cpp
feature: conversion
informat: ODS
outformat: PPTX
otherformats: DOCX DOC WORD PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendera ODS till POWERPOINT på Android via Java" h2="Förvandla ODS till POWERPOINT i dina Android-applikationer utan att använda Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total för Android via Java](https://products.aspose.com/total/android-java/) är ett paket med kraftfulla API:er för filautomatisering. Genom att använda två av dess API:er kan du integrera ODS till POWERPOINT-konverteringsfunktionen i dina Android-applikationer. I det första steget kan du exportera ODS till PDF genom att använda [Aspose.Cells för Android via Java](https://products.aspose.com/cells/android-java/). Efter det, genom att använda [Aspose.PDF för Android via Java](https://products.aspose.com/pdf/android-java/), kan du konvertera PDF till POWERPOINT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API för att exportera ODS till POWERPOINT" %}}
1. Öppna ODS-filen med klassen [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Konvertera ODS till PDF och ställ in SaveFormat till AUTO
3. Ladda den konverterade PDF-filen med klassen [Powerpointument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument)
4. Spara dokumentet i POWERPOINT-format med [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument#save-java.lang.String-com.aspose.pdf.SaveOptions -) metod
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Android via Java direkt från [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) och installera [Aspose.PDF för Android via Java](https://powerpoints.aspose.com/pdf/androidjava/installation/) och [Aspose.Cells för Android via Java](https://powerpoints.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) i dina applikationer.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the ODS file using Workbook class
Workbook book = new Workbook("input.ods");
// save ODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Powerpointument class
Powerpointument powerpointument = new Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ta bort anpassade egenskaper från ODS-fil i Android via Java" %}}
Förutom dokumentkonvertering ger [Aspose.Cells för Android via Java](https://products.aspose.com/cells/android-java/) massor av andra funktioner också. Innan konverteringsprocessen kan du ta bort anpassade egenskaper för ODS-dokument. För att ta bort anpassade egenskaper, anropar du metoden [PowerpointumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/powerpointumentpropertycollection#remove(java.lang.String)) och skickar namnet på dokumentegenskapen som ska tas bort.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the ODS file using Workbook class
Workbook book = new Workbook("input.ods");
// retrieve a list of all custom powerpointument properties of the Excel file
PowerpointumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPowerpointumentProperties();
// remove a custom powerpointument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ods-to-powerpointx/" name="ODS Till POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ods-to-powerpoint/" name="ODS Till POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ods-to-word/" name="ODS Till WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ods-to-pptx/" name="ODS Till PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}