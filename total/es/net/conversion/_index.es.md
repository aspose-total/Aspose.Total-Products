---
title: Conversión de formato de archivo a través de C# 
url: /es/net/conversion/
description: Convierta Microsoft Word, Excel, PowerPoint, Outlook, PDF, HTML, imágenes 3D, diagramas, formatos de video y muchos otros archivos populares con solo unas pocas líneas de código C#.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Conversión de formato de archivo a través de C# .NET" h2="Convierta archivos de Microsoft<sup>&reg;</sup> Office, PDF, imágenes, HTML y otros formatos diferentes sin usar ningún otro software." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Biblioteca total de .NET](https://products.aspose.com/total/net/) acelera el desarrollo de soluciones de gestión de documentos desde cero o mejora las aplicaciones existentes para manejar la manipulación de documentos con facilidad. La API no solo administra documentos de Microsoft Office, sino que también maneja PDF, HTML, imágenes TIFF, JPG, PNG, BMP y SVG, archivos de correo electrónico, formatos de video, formatos de datos GIS y mucho más. Es un conjunto completo de API de solución de gestión y manipulación de documentos sin dependencias de software. Los programadores pueden crear, actualizar, renderizar, imprimir y convertir fácilmente entre los formatos más populares dentro de cualquier aplicación basada en .NET.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir Word a PDF" %}}
Total API admite no solo la interconversión de formatos de Microsoft Word, sino también la conversión de Word a PDF, HTML, imágenes, EPUB, Markdown y XPS. El proceso de conversión es simple. Cargue el documento a través de la clase Documento y simplemente llame al método Guardar con el formato de destino. Es tan simple. Los desarrolladores pueden verificar el [resultado de la conversión](https://products.aspose.com/words/net/conversion/word-to-pdf/) antes de la integración del código de **Word to PDF**


{{% blocks/products/pf/feature-page-code h3="C# - Conversión de Word a PDF" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-word-to-pdf.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-excel word-to-json word-to-ods" >}}


{{% blocks/products/pf/feature-page-section  h2="Convertir PDF a Imágenes" %}}
La API admite la conversión de PDF a imágenes, PowerPoint, Excel y otros formatos. Para la conversión de PDF a imagen, consideremos la imagen JPG como archivo de destino. El proceso es cargar el archivo PDF usando la clase Document e inicializar el objeto [Clase JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) y renderizar PDF a JPEG mediante [Proceso](https ://apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) método
Cargue el archivo JPEG usando la clase [Imagen](https://apireference.aspose.com/imaging/net/aspose.imaging/image) y finalmente llame al método Guardar.

{{% blocks/products/pf/feature-page-code h3="C# - Conversión de PDF a imagen" %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt" >}}

{{% blocks/products/pf/feature-page-section  h2="Convertir Excel a Word y PowerPoint" %}}

Para convertir formatos de Microsoft Excel a diferentes archivos, incluidos Word y PowerPoint, sub API relevantes involucradas de Aspose.Total principal para .NET API. Proceso de conversión de archivos de Excel a documentos de Word, cargue el archivo EXCEL usando la clase [Libro de trabajo](https://apireference.aspose.com/cells/net/aspose.cells/workbook) y convierta EXCEL a PDF en primer lugar y configure Guardar formato en Automático. Luego cargue el archivo PDF convertido usando la clase Document y llame al método Save y configure Doc, Docx como SaveFormat. También aparece el código para la conversión de Microsoft **Excel a Powerpoint**.

{{% blocks/products/pf/feature-page-code h3="C# - Conversión de JSON a Excel" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-word.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# - Conversión de Excel a JSON" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="excel-to-doc excel-to-docx excel-to-pptx" >}}