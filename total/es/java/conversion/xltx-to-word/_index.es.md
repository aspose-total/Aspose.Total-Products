---
title: Convierta XLTX a WORD usando Java
description: API de Java para exportar XLTX a WORD con Excel o Word
url_ignore: /es/java/conversion/xltx-to-word/
family: total
platformtag: net
feature: conversion
informat: XLTX
outformat: WORD
otherformats: WORD WORDX PPTX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API de Java para exportar XLTX a WORD" h2="API de Java local para exportar XLTX a WORD sin depender de Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Renderizar XLTX a WORD es un proceso de dos pasos. Primero usará [Aspose.Cells for Java](https://products.aspose.com/cells/java) API para convertir el documento XLTX dado a PDF, y luego usará [Aspose.Pdf for Java](https://products.aspose.com/pdf/java), puede convertir fácilmente su documento PDF a WORD. Ambas API pertenecen a la colección de bibliotecas de automatización de formato de archivo [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cómo convertir XLTX a WORD a través de la API de Java" %}}
1. Abra el archivo XLTX usando la clase [Libro de trabajo](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Convierta XLTX a PDF y configure SaveFormat en AUTO
3. Cargue el archivo PDF convertido usando la clase [Documento](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Guarde el documento en formato WORD usando [guardar](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) método y establecer Word como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Debe usar Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e incluya bibliotecas en su pom.xml.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLTX file using Workbook class
Workbook book = new Workbook("input.xltx");
// save XLTX as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in WORD format
document.save("output.word", com.aspose.pdf.SaveFormat.Word);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de conversión" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xltx-to-wordx/" name="XLTX Para WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xltx-to-pptx/" name="XLTX Para PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xltx-to-powerpoint/" name="XLTX Para POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xltx-to-word/" name="XLTX Para WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}