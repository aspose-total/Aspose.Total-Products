---
title: Conversión de formato de archivo a través de Java 
url: /es/java/conversion/
description: Convierta Microsoft Office Word, Excel, PowerPoint, Outlook, PDF, HTML, imágenes 3D, diagramas, formatos de video y otros formatos diferentes con solo unas pocas líneas de código Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Conversión de formato de archivo a través de Java" h2="Convierta documentos de Microsoft<sup>&reg;</sup> Office, PDF, imágenes, HTML y muchos otros archivos sin usar ningún otro software." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Java Total Library](https://products.aspose.com/total/java/) acelera el desarrollo de soluciones de manipulación de documentos desde cero o mejora las aplicaciones existentes para manejar la gestión de documentos con facilidad. La API no solo crea, edita y convierte documentos de Microsoft Office, sino que también maneja PDF, HTML, imágenes TIFF, JPG, PNG, BMP y SVG, archivos de correo electrónico, formatos de video, 3D, CAD y mucho más. Es una colección de API de soluciones de gestión y manipulación de documentos sin dependencias de software dentro de ninguna aplicación Java J2SE, J2EE, J2ME. Los programadores pueden crear, actualizar, renderizar, imprimir y convertir fácilmente entre los formatos más populares dentro de cualquier aplicación basada en Java.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Conversión de Word a Excel" %}}
Total API admite no solo la interconversión de formatos de Microsoft Word, sino también la conversión de Word a Excel, PDF, HTML, imágenes, EPUB, Markdown y XPS. El proceso de conversión es simple. Consideremos el caso de la conversión de **Word to Excel**. Cargue el archivo de Microsoft Word usando la clase [Documento](https://reference.aspose.com/words/java/com.aspose.words/Document) y convierta **WORD a HTML** usando [Guardar método](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)). A continuación, abra el documento HTML convertido usando la clase [Libro de trabajo](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) y guarde el documento en formato XLSX usando [Guardar](https:/ /apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) método.
 Los desarrolladores también pueden convertir [Word a PDF](https://products.aspose.com/words/java/conversion/word-to-pdf/).


{{% blocks/products/pf/feature-page-code h3="Java Conversión de Word a Excel" %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-json word-to-powerpoint" >}}


{{% blocks/products/pf/feature-page-section  h2="Convertir PDF a Imágenes" %}}
La API admite la conversión de PDF a imágenes como JPEG2000, EMZ, WMZ, TGA, PSD, DXF, WMF, SVGZ, APNG, DICOM, Powerpoint, Excel y otros formatos. Para la conversión de PDF a imagen, consideremos la imagen JPG como archivo de destino. El proceso es cargar el archivo PDF usando la clase Document e inicializar el objeto [Clase JpegDevice](https://reference.aspose.com/pdf/java/aspose.pdf.devices/jpegdevice) y renderizar PDF a JPEG a través de [Proceso](https ://apireference.aspose.com/pdf/java/aspose.pdf.devices.pagedevice/process/methods/1) método
Cargue el archivo JPEG usando la clase [Imagen](https://reference.aspose.com/imaging/java/aspose.imaging/image) y finalmente llame al método Guardar.

{{% blocks/products/pf/feature-page-code h3="Java PDF to Image Conversion" %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-csv pdf-to-txt pdf-to-markdown" >}}

{{% blocks/products/pf/feature-page-section  h2="Convertir archivos de PowerPoint a Excel" %}}

Para convertir archivos de Microsoft PowerPoint a diferentes archivos, incluidos Excel Word, MHTML, sub API relevantes involucradas en la API principal de Aspose.Total para Java. Proceso de conversión de archivos de PowerPoint a documentos de Excel, cargue el archivo de PowerPoint usando la clase [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) y convierta **PowerPoint a HTML** por usando el método [guardar](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-). A continuación, cargue el documento HTML convertido usando la clase [Libro de trabajo](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) y guarde el documento en formato EXCEL usando [guardar](https:/ /apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) método. También se incluye el código para la conversión de **PowerPoint a Word**.

{{% blocks/products/pf/feature-page-code h3="Conversión de Java PowerPoint a Excel" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Conversión de Java PowerPoint a Word" %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="powerpoint-to-doc powerpoint-to-docx powerpoint-to-xlsx" >}}