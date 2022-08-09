---
title: Exportera XLSM till DOC i Android
description: Android API för att konvertera XLSM till DOC utan att använda Microsoft Word
url: /sv/android-java/conversion/xlsm-to-doc/
family: total
platformtag: cpp
feature: conversion
informat: XLSM
outformat: DOC
otherformats: POWERPOINT WORD PPTX DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendera XLSM till DOC på Android via Java" h2="Förvandla XLSM till DOC i dina Android-applikationer utan att använda Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total för Android via Java](https://products.aspose.com/total/android-java/) är ett paket med kraftfulla API:er för filautomatisering. Genom att använda två av dess API:er kan du integrera XLSM till DOC-konverteringsfunktionen i dina Android-applikationer. I det första steget kan du exportera XLSM till PDF genom att använda [Aspose.Cells för Android via Java](https://products.aspose.com/cells/android-java/). Efter det, genom att använda [Aspose.PDF för Android via Java](https://products.aspose.com/pdf/android-java/), kan du konvertera PDF till DOC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API för att exportera XLSM till DOC" %}}
1. Öppna XLSM-filen med klassen [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Konvertera XLSM till PDF och ställ in SaveFormat till AUTO
3. Ladda den konverterade PDF-filen med klassen [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Spara dokumentet i DOC-format med [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metod
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Android via Java direkt från [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) och installera [Aspose.PDF för Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) och [Aspose.Cells för Android via Java](https://docs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) i dina applikationer.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSM file using Workbook class
Workbook book = new Workbook("input.xlsm");
// save XLSM as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in DOC format
document.save("output.doc", com.aspose.pdf.SaveFormat.Doc);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ta bort anpassade egenskaper från XLSM-fil i Android via Java" %}}
Förutom dokumentkonvertering ger [Aspose.Cells för Android via Java](https://products.aspose.com/cells/android-java/) massor av andra funktioner också. Innan konverteringsprocessen kan du ta bort anpassade egenskaper för XLSM-dokument. För att ta bort anpassade egenskaper, anropar du metoden [DocumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/documentpropertycollection#remove(java.lang.String)) och skickar namnet på dokumentegenskapen som ska tas bort.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSM file using Workbook class
Workbook book = new Workbook("input.xlsm");
// retrieve a list of all custom document properties of the Excel file
DocumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocumentProperties();
// remove a custom document property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xlsm-to-powerpoint/" name="XLSM Till POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xlsm-to-word/" name="XLSM Till WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xlsm-to-pptx/" name="XLSM Till PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/xlsm-to-docx/" name="XLSM Till DOCX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}