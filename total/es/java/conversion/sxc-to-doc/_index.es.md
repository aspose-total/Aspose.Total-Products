---
title: Convierta SXC a DOC usando Java
description: API de Java para exportar SXC a DOC con Excel o Word
url_ignore: /es/java/conversion/sxc-to-doc/
family: total
platformtag: net
feature: conversion
informat: SXC
outformat: DOC
otherformats: DOCX WORD POWERPOINT PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API de Java para exportar SXC a DOC" h2="API de Java local para exportar SXC a DOC sin depender de Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Renderizar SXC a DOC es un proceso de dos pasos. Primero usará [Aspose.Cells for Java](https://products.aspose.com/cells/java) API para convertir el documento SXC dado a PDF, y luego usará [Aspose.Pdf for Java](https://products.aspose.com/pdf/java), puede convertir fácilmente su documento PDF a DOC. Ambas API pertenecen a la colección de bibliotecas de automatización de formato de archivo [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cómo convertir SXC a DOC a través de la API de Java" %}}
1. Abra el archivo SXC usando la clase [Libro de trabajo](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Convierta SXC a PDF y configure SaveFormat en AUTO
3. Cargue el archivo PDF convertido usando la clase [Documento](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Guarde el documento en formato DOC usando [guardar](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) método y establecer Doc como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Debe usar Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e incluya bibliotecas en su pom.xml.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the SXC file using Workbook class
Workbook book = new Workbook("input.sxc");
// save SXC as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in DOC format
document.save("output.doc", com.aspose.pdf.SaveFormat.Doc);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de conversión" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/sxc-to-docx/" name="SXC Para DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/sxc-to-pptx/" name="SXC Para PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/sxc-to-powerpoint/" name="SXC Para POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/sxc-to-word/" name="SXC Para WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}