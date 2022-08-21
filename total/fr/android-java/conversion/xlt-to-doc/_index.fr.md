---
title: Exporter XLT vers DOC dans Android
description: API Android pour convertir XLT en DOC sans utiliser Microsoft Word
url: /fr/android-java/conversion/xlt-to-doc/
family: total
platformtag: cpp
feature: conversion
informat: XLT
outformat: DOC
otherformats: PPTX WORD POWERPOINT DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendu XLT en DOC sur Android via Java" h2="Transformez XLT en DOC dans vos applications Android sans utiliser Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) est un package de puissantes API d'automatisation de fichiers. En utilisant deux de ses API, vous pouvez intégrer la fonction de conversion XLT en DOC dans vos applications Android. Dans la première étape, vous pouvez exporter XLT au format PDF en utilisant [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). Après cela, en utilisant [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/), vous pouvez convertir un PDF en DOC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android pour exporter XLT vers DOC" %}}
1. Ouvrez le fichier XLT à l'aide de la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Convertissez XLT en PDF et définissez SaveFormat sur AUTO
3. Chargez le fichier PDF converti à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Enregistrez le document au format DOC en utilisant [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) méthode
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total for Android via Java directement depuis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et installez [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) et [Aspose.Cells for Android via Java](https://docs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) dans vos applications.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLT file using Workbook class
Workbook book = new Workbook("input.xlt");
// save XLT as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in DOC format
document.save("output.doc", com.aspose.pdf.SaveFormat.Doc);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Supprimer les propriétés personnalisées du fichier XLT dans Android via Java" %}}
Outre la conversion de documents, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) fournit également des tonnes d'autres fonctionnalités. Avant le processus de conversion, vous pouvez supprimer les propriétés personnalisées du document XLT. Pour supprimer des propriétés personnalisées, appelez la méthode [DocumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/documentpropertycollection#remove(java.lang.String)) et transmettez le nom de la propriété de document à supprimer.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLT file using Workbook class
Workbook book = new Workbook("input.xlt");
// retrieve a list of all custom document properties of the Excel file
DocumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocumentProperties();
// remove a custom document property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xlt-to-pptx/" name="XLT À PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xlt-to-word/" name="XLT À WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xlt-to-powerpoint/" name="XLT À POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xlt-to-docx/" name="XLT À DOCX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}