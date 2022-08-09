---
title: Exportar XLTX a POWERPOINT en Android
description: API de Android para convertir XLTX a POWERPOINT sin usar Microsoft Word
url: /es/android-java/conversion/xltx-to-powerpoint/
family: total
platformtag: cpp
feature: conversion
informat: XLTX
outformat: PPTX
otherformats: DOCX DOC PPTX WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderizar XLTX a POWERPOINT en Android a través de Java" h2="Transforme XLTX a POWERPOINT dentro de sus aplicaciones de Android sin usar Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total para Android a través de Java](https://products.aspose.com/total/android-java/) es un paquete de potentes API de automatización de archivos. Al usar dos de sus API, puede integrar la función de conversión de XLTX a POWERPOINT dentro de sus aplicaciones de Android. En el primer paso, puede exportar XLTX a PDF utilizando [Aspose.Cells para Android a través de Java](https://products.aspose.com/cells/android-java/). Después de eso, usando [Aspose.PDF para Android a través de Java](https://products.aspose.com/pdf/android-java/), puede convertir PDF a POWERPOINT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de Android para exportar XLTX a POWERPOINT" %}}
1. Abra el archivo XLTX usando la clase [Libro de trabajo](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Convierta XLTX a PDF y configure SaveFormat en AUTO
3. Cargue el archivo PDF convertido usando la clase [Powerpointumento](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument)
4. Guarde el powerpointumento en formato POWERPOINT usando [guardar](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument#save-java.lang.String-com.aspose.pdf.SaveOptions -) método
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Android a través de Java directamente desde [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) y instale [Aspose.PDF para Android a través de Java](https://powerpoints.aspose.com/pdf/androidjava/installation/) y [Aspose.Cells para Android a través de Java](https://powerpoints.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) en sus aplicaciones.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLTX file using Workbook class
Workbook book = new Workbook("input.xltx");
// save XLTX as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Powerpointument class
Powerpointument powerpointument = new Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Eliminar propiedades personalizadas del archivo XLTX en Android a través de Java" %}}
Además de la conversión de powerpointumentos, [Aspose.Cells para Android a través de Java](https://products.aspose.com/cells/android-java/) también ofrece muchas otras funciones. Antes del proceso de conversión, puede eliminar las propiedades personalizadas del powerpointumento XLTX. Para eliminar propiedades personalizadas, llame al método [PowerpointumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/powerpointumentpropertycollection#remove(java.lang.String)) y pase el nombre de la propiedad del powerpointumento que se eliminará.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLTX file using Workbook class
Workbook book = new Workbook("input.xltx");
// retrieve a list of all custom powerpointument properties of the Excel file
PowerpointumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPowerpointumentProperties();
// remove a custom powerpointument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xltx-to-powerpointx/" name="XLTX A POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xltx-to-powerpoint/" name="XLTX A POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xltx-to-pptx/" name="XLTX A PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xltx-to-word/" name="XLTX A WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}