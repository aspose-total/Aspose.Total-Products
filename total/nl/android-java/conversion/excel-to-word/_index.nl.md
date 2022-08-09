---
title: EXCEL exporteren naar WORD in Android
description: Android API om EXCEL naar WORD te converteren zonder Microsoft Word te gebruiken
url: /nl/android-java/conversion/excel-to-word/
family: total
platformtag: cpp
feature: conversion
informat: CSV
outformat: DOC
otherformats: DOCX PPTX POWERPOINT DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render EXCEL naar WORD op Android via Java" h2="Transformeer EXCEL naar WORD binnen uw Android-applicaties zonder Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total voor Android via Java](https://products.aspose.com/total/android-java/) is een pakket krachtige API's voor bestandsautomatisering. Door twee van zijn API's te gebruiken, kunt u de conversiefunctie van EXCEL naar WORD in uw Android-applicaties integreren. In de eerste stap kunt u EXCEL naar PDF exporteren met [Aspose.Cells voor Android via Java](https://products.aspose.com/cells/android-java/). Daarna kunt u met [Aspose.PDF voor Android via Java](https://products.aspose.com/pdf/android-java/) PDF naar WORD converteren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API om EXCEL naar WORD te exporteren" %}}
1. Open het EXCEL-bestand met de klasse [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Converteer EXCEL naar PDF en stel SaveFormat in op AUTO
3. Laad het geconverteerde PDF-bestand met de klasse [Wordument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument)
4. Sla het wordument op in WORD-formaat met [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument#save-java.lang.String-com.aspose.pdf.SaveOptions -) methode
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total voor Android eenvoudig via Java rechtstreeks vanuit [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) en installeer [Aspose.PDF voor Android via Java](https://words.aspose.com/pdf/androidjava/installation/) en [Aspose.Cells voor Android via Java](https://words.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) in uw toepassingen.

U kunt ook een ZIP-bestand krijgen van [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the EXCEL file using Workbook class
Workbook book = new Workbook("input.excel");
// save EXCEL as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Wordument class
Wordument wordument = new Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.save("output.word", com.aspose.pdf.SaveFormat.Word);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Verwijder aangepaste eigenschappen uit EXCEL-bestand in Android via Java" %}}
Naast wordumentconversie biedt [Aspose.Cells voor Android via Java](https://products.aspose.com/cells/android-java/) ook tal van andere functies. Vóór het conversieproces kunt u aangepaste eigenschappen van het EXCEL-wordument verwijderen. Om aangepaste eigenschappen te verwijderen, roept u de methode [WordumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/wordumentpropertycollection#remove(java.lang.String)) aan en geeft u de naam van de wordumenteigenschap die moet worden verwijderd.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the EXCEL file using Workbook class
Workbook book = new Workbook("input.excel");
// retrieve a list of all custom wordument properties of the Excel file
WordumentPropertyCollection customProperties = workbook.getWorksheets().getCustomWordumentProperties();
// remove a custom wordument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/excel-to-wordx/" name="EXCEL Tot WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/excel-to-pptx/" name="EXCEL Tot PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/excel-to-powerpoint/" name="EXCEL Tot POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/excel-to-word/" name="EXCEL Tot WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}