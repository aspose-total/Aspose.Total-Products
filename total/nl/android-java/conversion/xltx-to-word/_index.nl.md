---
title: XLTX exporteren naar WORD in Android
description: Android API om XLTX naar WORD te converteren zonder Microsoft Word te gebruiken

family: total
platformtag: cpp
feature: conversion
informat: XLTX
outformat: DOC
otherformats: PPTX POWERPOINT DOC DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render XLTX naar WORD op Android via Java" h2="Transformeer XLTX naar WORD binnen uw Android-applicaties zonder Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) is een pakket krachtige API's voor bestandsautomatisering. Door twee van zijn API's te gebruiken, kunt u de conversiefunctie van XLTX naar WORD in uw Android-applicaties integreren. In de eerste stap kunt u XLTX naar PDF exporteren met [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). Daarna kunt u met [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) PDF naar WORD converteren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API om XLTX naar WORD te exporteren" %}}
1. Open het XLTX-bestand met de klasse [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Converteer XLTX naar PDF en stel SaveFormat in op AUTO
3. Laad het geconverteerde PDF-bestand met de klasse [Wordument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument)
4. Sla het wordument op in WORD-formaat met [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument#save-java.lang.String-com.aspose.pdf.SaveOptions -) methode
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total for Android eenvoudig via Java rechtstreeks vanuit [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) en installeer [Aspose.PDF for Android via Java](https://words.aspose.com/pdf/androidjava/installation/) en [Aspose.Cells for Android via Java](https://words.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) in uw toepassingen.

U kunt ook een ZIP-bestand krijgen van [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLTX file using Workbook class
Workbook book = new Workbook("input.xltx");
// save XLTX as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Wordument class
Wordument wordument = new Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.save("output.word", com.aspose.pdf.SaveFormat.Word);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Verwijder aangepaste eigenschappen uit XLTX-bestand in Android via Java" %}}
Naast wordumentconversie biedt [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) ook tal van andere functies. Vóór het conversieproces kunt u aangepaste eigenschappen van het XLTX-wordument verwijderen. Om aangepaste eigenschappen te verwijderen, roept u de methode [WordumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/wordumentpropertycollection#remove(java.lang.String)) aan en geeft u de naam van de wordumenteigenschap die moet worden verwijderd.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLTX file using Workbook class
Workbook book = new Workbook("input.xltx");
// retrieve a list of all custom wordument properties of the Excel file
WordumentPropertyCollection customProperties = workbook.getWorksheets().getCustomWordumentProperties();
// remove a custom wordument property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/xltx-to-pptx/" name="XLTX Tot PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/xltx-to-powerpoint/" name="XLTX Tot POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/xltx-to-word/" name="XLTX Tot WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/xltx-to-wordx/" name="XLTX Tot WORDX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}