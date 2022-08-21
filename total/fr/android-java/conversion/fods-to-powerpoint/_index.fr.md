---
title: Exporter FODS vers POWERPOINT dans Android
description: API Android pour convertir FODS en POWERPOINT sans utiliser Microsoft Word
url: /fr/android-java/conversion/fods-to-powerpoint/
family: total
platformtag: cpp
feature: conversion
informat: FODS
outformat: PPTX
otherformats: WORD DOCX DOC PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendu FODS en POWERPOINT sur Android via Java" h2="Transformez FODS en POWERPOINT dans vos applications Android sans utiliser Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) est un package de puissantes API d'automatisation de fichiers. En utilisant deux de ses API, vous pouvez intégrer la fonction de conversion FODS en POWERPOINT dans vos applications Android. Dans la première étape, vous pouvez exporter FODS au format PDF en utilisant [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). Après cela, en utilisant [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/), vous pouvez convertir un PDF en POWERPOINT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android pour exporter FODS vers POWERPOINT" %}}
1. Ouvrez le fichier FODS à l'aide de la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Convertissez FODS en PDF et définissez SaveFormat sur AUTO
3. Chargez le fichier PDF converti à l'aide de la classe [Powerpointument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument)
4. Enregistrez le powerpointument au format POWERPOINT en utilisant [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument#save-java.lang.String-com.aspose.pdf.SaveOptions -) méthode
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total for Android via Java directement depuis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et installez [Aspose.PDF for Android via Java](https://powerpoints.aspose.com/pdf/androidjava/installation/) et [Aspose.Cells for Android via Java](https://powerpoints.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) dans vos applications.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the FODS file using Workbook class
Workbook book = new Workbook("input.fods");
// save FODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Powerpointument class
Powerpointument powerpointument = new Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Supprimer les propriétés personnalisées du fichier FODS dans Android via Java" %}}
Outre la conversion de powerpointuments, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) fournit également des tonnes d'autres fonctionnalités. Avant le processus de conversion, vous pouvez supprimer les propriétés personnalisées du powerpointument FODS. Pour supprimer des propriétés personnalisées, appelez la méthode [PowerpointumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/powerpointumentpropertycollection#remove(java.lang.String)) et transmettez le nom de la propriété de powerpointument à supprimer.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the FODS file using Workbook class
Workbook book = new Workbook("input.fods");
// retrieve a list of all custom powerpointument properties of the Excel file
PowerpointumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPowerpointumentProperties();
// remove a custom powerpointument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/fods-to-word/" name="FODS À WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/fods-to-powerpointx/" name="FODS À POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/fods-to-powerpoint/" name="FODS À POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/fods-to-pptx/" name="FODS À PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}