---
title: Convierta ODS a PPTX usando Java
description: API de Java para exportar ODS a PPTX con Excel o Word
url_ignore: /es/java/conversion/ods-to-pptx/
family: total
platformtag: net
feature: conversion
informat: ODS
outformat: PPTX
otherformats: PPTX POWERPOINT WORD PPTXX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API de Java para exportar ODS a PPTX" h2="API de Java local para exportar ODS a PPTX sin depender de Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Renderizar ODS a PPTX es un proceso de dos pasos. Primero usará [Aspose.Cells for Java](https://products.aspose.com/cells/java) API para convertir el documento ODS dado a PDF, y luego usará [Aspose.Pdf for Java](https://products.aspose.com/pdf/java), puede convertir fácilmente su documento PDF a PPTX. Ambas API pertenecen a la colección de bibliotecas de automatización de formato de archivo [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cómo convertir ODS a PPTX a través de la API de Java" %}}
1. Abra el archivo ODS usando la clase [Libro de trabajo](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Convierta ODS a PDF y configure SaveFormat en AUTO
3. Cargue el archivo PDF convertido usando la clase [Documento](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Guarde el documento en formato PPTX usando [guardar](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) método y establecer Pptx como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Debe usar Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e incluya bibliotecas en su pom.xml.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the ODS file using Workbook class
Workbook book = new Workbook("input.ods");
// save ODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in PPTX format
document.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de conversión" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/ods-to-pptxx/" name="ODS Para PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/ods-to-pptx/" name="ODS Para PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/ods-to-powerpoint/" name="ODS Para POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/ods-to-word/" name="ODS Para WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}