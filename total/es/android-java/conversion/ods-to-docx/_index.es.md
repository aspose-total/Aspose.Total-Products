---
title: Exportar ODS a DOCX en Android
description: API de Android para convertir ODS a DOCX sin usar Microsoft Word
url: /es/android-java/conversion/ods-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: ODS
outformat: DOCX
otherformats: DOC POWERPOINT PPTX WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderizar ODS a DOCX en Android a través de Java" h2="Transforme ODS a DOCX dentro de sus aplicaciones de Android sin usar Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total para Android a través de Java](https://products.aspose.com/total/android-java/) es un paquete de potentes API de automatización de archivos. Al usar dos de sus API, puede integrar la función de conversión de ODS a DOCX dentro de sus aplicaciones de Android. En el primer paso, puede exportar ODS a PDF utilizando [Aspose.Cells para Android a través de Java](https://products.aspose.com/cells/android-java/). Después de eso, usando [Aspose.PDF para Android a través de Java](https://products.aspose.com/pdf/android-java/), puede convertir PDF a DOCX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de Android para exportar ODS a DOCX" %}}
1. Abra el archivo ODS usando la clase [Libro de trabajo](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Convierta ODS a PDF y configure SaveFormat en AUTO
3. Cargue el archivo PDF convertido usando la clase [Docxumento](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument)
4. Guarde el docxumento en formato DOCX usando [guardar](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument#save-java.lang.String-com.aspose.pdf.SaveOptions -) método
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Android a través de Java directamente desde [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) y instale [Aspose.PDF para Android a través de Java](https://docxs.aspose.com/pdf/androidjava/installation/) y [Aspose.Cells para Android a través de Java](https://docxs.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) en sus aplicaciones.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the ODS file using Workbook class
Workbook book = new Workbook("input.ods");
// save ODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Docxument class
Docxument docxument = new Docxument("pdfOutput.pdf");
// save docxument in DOCX format
docxument.save("output.docx", com.aspose.pdf.SaveFormat.DocxX);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Eliminar propiedades personalizadas del archivo ODS en Android a través de Java" %}}
Además de la conversión de docxumentos, [Aspose.Cells para Android a través de Java](https://products.aspose.com/cells/android-java/) también ofrece muchas otras funciones. Antes del proceso de conversión, puede eliminar las propiedades personalizadas del docxumento ODS. Para eliminar propiedades personalizadas, llame al método [DocxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/docxumentpropertycollection#remove(java.lang.String)) y pase el nombre de la propiedad del docxumento que se eliminará.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the ODS file using Workbook class
Workbook book = new Workbook("input.ods");
// retrieve a list of all custom docxument properties of the Excel file
DocxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocxumentProperties();
// remove a custom docxument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ods-to-docx/" name="ODS A DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ods-to-powerpoint/" name="ODS A POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ods-to-pptx/" name="ODS A PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ods-to-word/" name="ODS A WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}