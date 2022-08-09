---
title: XLSB exporteren naar POWERPOINT in Android
description: Android API om XLSB naar POWERPOINT te converteren zonder Microsoft Word te gebruiken
url: /nl/android-java/conversion/xlsb-to-powerpoint/
family: total
platformtag: cpp
feature: conversion
informat: XLSB
outformat: PPTX
otherformats: PPTX WORD DOC DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render XLSB naar POWERPOINT op Android via Java" h2="Transformeer XLSB naar POWERPOINT binnen uw Android-applicaties zonder Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total voor Android via Java](https://products.aspose.com/total/android-java/) is een pakket krachtige API's voor bestandsautomatisering. Door twee van zijn API's te gebruiken, kunt u de conversiefunctie van XLSB naar POWERPOINT in uw Android-applicaties integreren. In de eerste stap kunt u XLSB naar PDF exporteren met [Aspose.Cells voor Android via Java](https://products.aspose.com/cells/android-java/). Daarna kunt u met [Aspose.PDF voor Android via Java](https://products.aspose.com/pdf/android-java/) PDF naar POWERPOINT converteren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API om XLSB naar POWERPOINT te exporteren" %}}
1. Open het XLSB-bestand met de klasse [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Converteer XLSB naar PDF en stel SaveFormat in op AUTO
3. Laad het geconverteerde PDF-bestand met de klasse [Powerpointument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument)
4. Sla het powerpointument op in POWERPOINT-formaat met [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument#save-java.lang.String-com.aspose.pdf.SaveOptions -) methode
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total voor Android eenvoudig via Java rechtstreeks vanuit [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) en installeer [Aspose.PDF voor Android via Java](https://powerpoints.aspose.com/pdf/androidjava/installation/) en [Aspose.Cells voor Android via Java](https://powerpoints.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) in uw toepassingen.

U kunt ook een ZIP-bestand krijgen van [downloads](https://downloads.aspose.com/total/androidjava).
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

{{% blocks/products/pf/feature-page-section  h2="Verwijder aangepaste eigenschappen uit XLSB-bestand in Android via Java" %}}
Naast powerpointumentconversie biedt [Aspose.Cells voor Android via Java](https://products.aspose.com/cells/android-java/) ook tal van andere functies. Vóór het conversieproces kunt u aangepaste eigenschappen van het XLSB-powerpointument verwijderen. Om aangepaste eigenschappen te verwijderen, roept u de methode [PowerpointumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/powerpointumentpropertycollection#remove(java.lang.String)) aan en geeft u de naam van de powerpointumenteigenschap die moet worden verwijderd.
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
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/xlsb-to-pptx/" name="XLSB Tot PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/xlsb-to-word/" name="XLSB Tot WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/xlsb-to-powerpoint/" name="XLSB Tot POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/xlsb-to-powerpointx/" name="XLSB Tot POWERPOINTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}