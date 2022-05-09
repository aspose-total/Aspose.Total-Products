---
title: Convierta EXCEL a WORD usando Java
description: API de Java para exportar EXCEL a WORD con Excel o Word
url_ignore: /es/java/conversion/excel-to-word/
family: total
platformtag: net
feature: conversion
informat: EXCEL
outformat: WORD
otherformats: POWERPOINT PPTX WORD WORDX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API de Java para exportar EXCEL a WORD" h2="API de Java local para exportar EXCEL a WORD sin depender de Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Renderizar EXCEL a WORD es un proceso de dos pasos. Primero usará [Aspose.Cells for Java](https://products.aspose.com/cells/java) API para convertir el documento EXCEL dado a PDF, y luego usará [Aspose.Pdf for Java](https://products.aspose.com/pdf/java), puede convertir fácilmente su documento PDF a WORD. Ambas API pertenecen a la colección de bibliotecas de automatización de formato de archivo [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cómo convertir EXCEL a WORD a través de la API de Java" %}}
1. Abra el archivo EXCEL usando la clase [Libro de trabajo](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Convierta EXCEL a PDF y configure SaveFormat en AUTO
3. Cargue el archivo PDF convertido usando la clase [Documento](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Guarde el documento en formato WORD usando [guardar](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) método y establecer Word como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Debe usar Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e incluya bibliotecas en su pom.xml.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EXCEL file using Workbook class
Workbook book = new Workbook("input.excel");
// save EXCEL as PDF
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/excel-to-wordx/" name="EXCEL Para WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/excel-to-pptx/" name="EXCEL Para PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/excel-to-powerpoint/" name="EXCEL Para POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/excel-to-word/" name="EXCEL Para WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}