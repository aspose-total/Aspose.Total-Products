---
title: Convertir XLSB en DOCX en utilisant Java
description: API Java pour exporter XLSB vers DOCX en utilisant Excel ou Word
url_ignore: /fr/java/conversion/xlsb-to-docx/
family: total
platformtag: net
feature: conversion
informat: XLSB
outformat: DOCXX
otherformats: PPTX WORD DOCX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java pour exporter XLSB vers DOCX" h2="API Java sur site pour exporter XLSB vers DOCX sans dépendre de Microsoft Excel®" >}}
{{% blocks/products/pf/feature-page-summary %}}
Le rendu XLSB en DOCX est un processus en deux étapes. Vous utiliserez d'abord l'API [Aspose.Cells for Java](https://products.aspose.com/cells/java) pour convertir le Document XLSB donné en PDF, puis en utilisant [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API, vous pouvez facilement convertir votre Document PDF en DOCX. Les deux API font partie de la collection de bibliothèques d'automatisation de format de fichier [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Comment convertir XLSB en DOCX via l'API Java" %}}
1. Ouvrez le fichier XLSB à l'aide de la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Convertissez XLSB en PDF et définissez SaveFormat sur AUTO
3. Chargez le fichier PDF converti à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Enregistrez le Document au format DOCX en utilisant [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) méthode et définissez Docx comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous devez utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et incluez des bibliothèques dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSB file using Workbook class
Workbook book = new Workbook("input.xlsb");
// save XLSB as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document Document = new Document("pdfOutput.pdf");
// save Document in DOCXX format
Document.save("output.docxx", com.aspose.pdf.SaveFormat.DocxX);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres options de conversion" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xlsb-to-docxx/" name="XLSB Pour DOCXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xlsb-to-pptx/" name="XLSB Pour PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xlsb-to-powerpoint/" name="XLSB Pour POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xlsb-to-word/" name="XLSB Pour WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}