---
title: XLTM exporteren naar DOCX in Android
description: Android API om XLTM naar DOCX te converteren zonder Microsoft Word te gebruiken

family: total
platformtag: cpp
feature: conversion
informat: XLTM
outformat: DOCX
otherformats: PPTX WORD DOC POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render XLTM naar DOCX op Android via Java" h2="Transformeer XLTM naar DOCX binnen uw Android-applicaties zonder Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) is een pakket krachtige API's voor bestandsautomatisering. Door twee van zijn API's te gebruiken, kunt u de conversiefunctie van XLTM naar DOCX in uw Android-applicaties integreren. In de eerste stap kunt u XLTM naar PDF exporteren met [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). Daarna kunt u met [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) PDF naar DOCX converteren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API om XLTM naar DOCX te exporteren" %}}
1. Open het XLTM-bestand met de klasse [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Converteer XLTM naar PDF en stel SaveFormat in op AUTO
3. Laad het geconverteerde PDF-bestand met de klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Sla het document op in DOCX-formaat met [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions -) methode
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total for Android eenvoudig via Java rechtstreeks vanuit [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) en installeer [Aspose.PDF for Android via Java](https://docxs.aspose.com/pdf/androidjava/installation/) en [Aspose.Cells for Android via Java](https://docxs.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) in uw toepassingen.

U kunt ook een ZIP-bestand krijgen van [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLTM file using Workbook class
Workbook book = new Workbook("input.xltm");
// save XLTM as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in DOCX format
document.save("output.docx", com.aspose.pdf.SaveFormat.DocxX);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Verwijder aangepaste eigenschappen uit XLTM-bestand in Android via Java" %}}Document
Naast documentconversie biedt [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) ook tal van andere functies. Vóór het conversieproces kunt u aangepaste eigenschappen van het XLTM-document verwijderen. Om aangepaste eigenschappen te verwijderen, roept u de methode [DocxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/documentpropertycollection#remove(java.lang.String)) aan en geeft u de naam van de documenteigenschap die moet worden verwijderd.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLTM file using Workbook class
Workbook book = new Workbook("input.xltm");
Documentve a list of all custom document properties of the Excel fileDocument
DocxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocxumentProperties();
// remove a custom document property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/xltm-to-pptx/" name="XLTM Tot PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/xltm-to-word/" name="XLTM Tot WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/xltm-to-docx/" name="XLTM Tot DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/xltm-to-powerpoint/" name="XLTM Tot POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}