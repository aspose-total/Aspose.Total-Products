---
title: Exportar TSV a WORD en Android
description: API de Android para convertir TSV a WORD sin usar Microsoft Word
url: /es/android-java/conversion/tsv-to-word/
family: total
platformtag: cpp
feature: conversion
informat: TSV
outformat: DOC
otherformats: PPTX POWERPOINT DOCX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderizar TSV a WORD en Android a través de Java" h2="Transforme TSV a WORD dentro de sus aplicaciones de Android sin usar Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total para Android a través de Java](https://products.aspose.com/total/android-java/) es un paquete de potentes API de automatización de archivos. Al usar dos de sus API, puede integrar la función de conversión de TSV a WORD dentro de sus aplicaciones de Android. En el primer paso, puede exportar TSV a PDF utilizando [Aspose.Cells para Android a través de Java](https://products.aspose.com/cells/android-java/). Después de eso, usando [Aspose.PDF para Android a través de Java](https://products.aspose.com/pdf/android-java/), puede convertir PDF a WORD. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de Android para exportar TSV a WORD" %}}
1. Abra el archivo TSV usando la clase [Libro de trabajo](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Convierta TSV a PDF y configure SaveFormat en AUTO
3. Cargue el archivo PDF convertido usando la clase [Wordumento](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument)
4. Guarde el wordumento en formato WORD usando [guardar](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument#save-java.lang.String-com.aspose.pdf.SaveOptions -) método
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Android a través de Java directamente desde [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) y instale [Aspose.PDF para Android a través de Java](https://words.aspose.com/pdf/androidjava/installation/) y [Aspose.Cells para Android a través de Java](https://words.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) en sus aplicaciones.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the TSV file using Workbook class
Workbook book = new Workbook("input.tsv");
// save TSV as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Wordument class
Wordument wordument = new Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.save("output.word", com.aspose.pdf.SaveFormat.Word);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Eliminar propiedades personalizadas del archivo TSV en Android a través de Java" %}}
Además de la conversión de wordumentos, [Aspose.Cells para Android a través de Java](https://products.aspose.com/cells/android-java/) también ofrece muchas otras funciones. Antes del proceso de conversión, puede eliminar las propiedades personalizadas del wordumento TSV. Para eliminar propiedades personalizadas, llame al método [WordumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/wordumentpropertycollection#remove(java.lang.String)) y pase el nombre de la propiedad del wordumento que se eliminará.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the TSV file using Workbook class
Workbook book = new Workbook("input.tsv");
// retrieve a list of all custom wordument properties of the Excel file
WordumentPropertyCollection customProperties = workbook.getWorksheets().getCustomWordumentProperties();
// remove a custom wordument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/tsv-to-pptx/" name="TSV A PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/tsv-to-powerpoint/" name="TSV A POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/tsv-to-wordx/" name="TSV A WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/tsv-to-word/" name="TSV A WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}