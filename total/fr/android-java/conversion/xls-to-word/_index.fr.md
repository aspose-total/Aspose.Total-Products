---
title: Exporter XLS vers WORD dans Android
description: API Android pour convertir XLS en WORD sans utiliser Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: XLS
outformat: DOC
otherformats: PPTX DOC POWERPOINT DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendu XLS en WORD sur Android via Java" h2="Transformez XLS en WORD dans vos applications Android sans utiliser Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) est un package de puissantes API d'automatisation de fichiers. En utilisant deux de ses API, vous pouvez intégrer la fonction de conversion XLS en WORD dans vos applications Android. Dans la première étape, vous pouvez exporter XLS au format PDF en utilisant [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). Après cela, en utilisant [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/), vous pouvez convertir un PDF en WORD. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android pour exporter XLS vers WORD" %}}
1. Ouvrez le fichier XLS à l'aide de la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Convertissez XLS en PDF et définissez SaveFormat sur AUTO
3. Chargez le fichier PDF converti à l'aide de la classe [Wordument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument)
4. Enregistrez le wordument au format WORD en utilisant [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument#save-java.lang.String-com.aspose.pdf.SaveOptions -) méthode
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total for Android via Java directement depuis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et installez [Aspose.PDF for Android via Java](https://words.aspose.com/pdf/androidjava/installation/) et [Aspose.Cells for Android via Java](https://words.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) dans vos applications.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLS file using Workbook class
Workbook book = new Workbook("input.xls");
// save XLS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Wordument class
Wordument wordument = new Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.save("output.word", com.aspose.pdf.SaveFormat.Word);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Supprimer les propriétés personnalisées du fichier XLS dans Android via Java" %}}
Outre la conversion de worduments, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) fournit également des tonnes d'autres fonctionnalités. Avant le processus de conversion, vous pouvez supprimer les propriétés personnalisées du wordument XLS. Pour supprimer des propriétés personnalisées, appelez la méthode [WordumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/wordumentpropertycollection#remove(java.lang.String)) et transmettez le nom de la propriété de wordument à supprimer.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLS file using Workbook class
Workbook book = new Workbook("input.xls");
// retrieve a list of all custom wordument properties of the Excel file
WordumentPropertyCollection customProperties = workbook.getWorksheets().getCustomWordumentProperties();
// remove a custom wordument property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xls-to-pptx/" name="XLS À PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xls-to-word/" name="XLS À WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xls-to-powerpoint/" name="XLS À POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xls-to-wordx/" name="XLS À WORDX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}