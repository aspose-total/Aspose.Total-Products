---
title: TSV exporteren naar DOCX in Android
description: Android API om TSV naar DOCX te converteren zonder Microsoft Word te gebruiken
url: /nl/android-java/conversion/tsv-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: TSV
outformat: DOCX
otherformats: WORD DOC POWERPOINT PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render TSV naar DOCX op Android via Java" h2="Transformeer TSV naar DOCX binnen uw Android-applicaties zonder Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total voor Android via Java](https://products.aspose.com/total/android-java/) is een pakket krachtige API's voor bestandsautomatisering. Door twee van zijn API's te gebruiken, kunt u de conversiefunctie van TSV naar DOCX in uw Android-applicaties integreren. In de eerste stap kunt u TSV naar PDF exporteren met [Aspose.Cells voor Android via Java](https://products.aspose.com/cells/android-java/). Daarna kunt u met [Aspose.PDF voor Android via Java](https://products.aspose.com/pdf/android-java/) PDF naar DOCX converteren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API om TSV naar DOCX te exporteren" %}}
1. Open het TSV-bestand met de klasse [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Converteer TSV naar PDF en stel SaveFormat in op AUTO
3. Laad het geconverteerde PDF-bestand met de klasse [Docxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument)
4. Sla het docxument op in DOCX-formaat met [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument#save-java.lang.String-com.aspose.pdf.SaveOptions -) methode
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total voor Android eenvoudig via Java rechtstreeks vanuit [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) en installeer [Aspose.PDF voor Android via Java](https://docxs.aspose.com/pdf/androidjava/installation/) en [Aspose.Cells voor Android via Java](https://docxs.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) in uw toepassingen.

U kunt ook een ZIP-bestand krijgen van [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the TSV file using Workbook class
Workbook book = new Workbook("input.tsv");
// save TSV as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Docxument class
Docxument docxument = new Docxument("pdfOutput.pdf");
// save docxument in DOCX format
docxument.save("output.docx", com.aspose.pdf.SaveFormat.DocxX);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Verwijder aangepaste eigenschappen uit TSV-bestand in Android via Java" %}}
Naast docxumentconversie biedt [Aspose.Cells voor Android via Java](https://products.aspose.com/cells/android-java/) ook tal van andere functies. Vóór het conversieproces kunt u aangepaste eigenschappen van het TSV-docxument verwijderen. Om aangepaste eigenschappen te verwijderen, roept u de methode [DocxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/docxumentpropertycollection#remove(java.lang.String)) aan en geeft u de naam van de docxumenteigenschap die moet worden verwijderd.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the TSV file using Workbook class
Workbook book = new Workbook("input.tsv");
// retrieve a list of all custom docxument properties of the Excel file
DocxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocxumentProperties();
// remove a custom docxument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/tsv-to-word/" name="TSV Tot WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/tsv-to-docx/" name="TSV Tot DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/tsv-to-powerpoint/" name="TSV Tot POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/tsv-to-pptx/" name="TSV Tot PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}