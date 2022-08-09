---
title: Exporter XLSX vers DOCX dans Android
description: API Android pour convertir XLSX en DOCX sans utiliser Microsoft Word
url: /fr/android-java/conversion/xlsx-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: XLSX
outformat: DOCX
otherformats: POWERPOINT PPTX DOC WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendu XLSX en DOCX sur Android via Java" h2="Transformez XLSX en DOCX dans vos applications Android sans utiliser Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total pour Android via Java](https://products.aspose.com/total/android-java/) est un package de puissantes API d'automatisation de fichiers. En utilisant deux de ses API, vous pouvez intégrer la fonction de conversion XLSX en DOCX dans vos applications Android. Dans la première étape, vous pouvez exporter XLSX au format PDF en utilisant [Aspose.Cells pour Android via Java](https://products.aspose.com/cells/android-java/). Après cela, en utilisant [Aspose.PDF pour Android via Java](https://products.aspose.com/pdf/android-java/), vous pouvez convertir un PDF en DOCX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android pour exporter XLSX vers DOCX" %}}
1. Ouvrez le fichier XLSX à l'aide de la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Convertissez XLSX en PDF et définissez SaveFormat sur AUTO
3. Chargez le fichier PDF converti à l'aide de la classe [Docxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument)
4. Enregistrez le docxument au format DOCX en utilisant [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument#save-java.lang.String-com.aspose.pdf.SaveOptions -) méthode
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Android via Java directement depuis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et installez [Aspose.PDF pour Android via Java](https://docxs.aspose.com/pdf/androidjava/installation/) et [Aspose.Cells pour Android via Java](https://docxs.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) dans vos applications.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSX file using Workbook class
Workbook book = new Workbook("input.xlsx");
// save XLSX as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Docxument class
Docxument docxument = new Docxument("pdfOutput.pdf");
// save docxument in DOCX format
docxument.save("output.docx", com.aspose.pdf.SaveFormat.DocxX);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Supprimer les propriétés personnalisées du fichier XLSX dans Android via Java" %}}
Outre la conversion de docxuments, [Aspose.Cells pour Android via Java](https://products.aspose.com/cells/android-java/) fournit également des tonnes d'autres fonctionnalités. Avant le processus de conversion, vous pouvez supprimer les propriétés personnalisées du docxument XLSX. Pour supprimer des propriétés personnalisées, appelez la méthode [DocxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/docxumentpropertycollection#remove(java.lang.String)) et transmettez le nom de la propriété de docxument à supprimer.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSX file using Workbook class
Workbook book = new Workbook("input.xlsx");
// retrieve a list of all custom docxument properties of the Excel file
DocxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocxumentProperties();
// remove a custom docxument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xlsx-to-powerpoint/" name="XLSX À POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xlsx-to-pptx/" name="XLSX À PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xlsx-to-docx/" name="XLSX À DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xlsx-to-word/" name="XLSX À WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}