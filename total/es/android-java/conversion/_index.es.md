---
title: Conversión de documentos a través de la API de Android 
url: /es/android-java/conversion/
description: Convierta formatos de Word, Excel, PowerPoint, HTML, PDF e imagen utilizando la API de conversión de Android. Android convierte Office docx, xlsx, pptx a PDF. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Conversión de documentos usando la API de Android" h2="Convierta Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, imágenes y varios otros formatos usando Aspose.Total for Android via Java." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Android API](https://products.aspose.com/total/android-java/) proporciona la solución de gestión y conversión de documentos para aplicaciones de Android sin depender de ningún otro software. Los programadores pueden automatizar fácilmente la solución de gestión y manipulación de documentos mediante la integración de API dentro de nuevas aplicaciones desarrolladas o en aplicaciones existentes. Al integrar la API, el programador puede agregar fácilmente funciones para crear, editar o convertir varios documentos de formato dentro de la aplicación. PDF Converter API en Android maneja casos de conversión como Office DOCX, XLSX, PPTX a PDF o viceversa. Además, se enumeran a continuación algunos casos que trata la API y se proporcionan pocos enlaces para los casos de conversión relevantes. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir PDF a CSV" %}}
La API total de Android admite la conversión de PDF a Excel XLSX y CSV. Es un proceso de dos pasos. Dos API totales [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) y (Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) involucradas. El proceso es que puede convertir PDF a formato Excel XLSX primero y luego XLSX a CSV. Más detalladamente, cargue el archivo PDF a través de la clase [Documento](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) y renderícelo en XLSX a través de [guardar](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-). A continuación, cargue el documento XLSX renderizado utilizando la clase [Libro de trabajo](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) e invoque [guardar](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).

{{% blocks/products/pf/feature-page-code h3="Android - Conversión de PDF a Excel" %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint potm-to-rtf powerpoint-to-docx ppt-to-docx pptx-to-odt potm-to-docx email-to-docx email-to-word eml-to-pdf emlx-to-bmp emlx-to-image msg-to-pdf oft-to-word" >}}


{{% blocks/products/pf/feature-page-section  h2="Conversión de Excel a Word" %}}
La API de Android también maneja la conversión de Excel. El proceso es, cargue el archivo EXCEL XLSX usando la clase [Libro de trabajo](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) y convierta EXCEL a PDF configurando SaveFormat en AUTO en primer lugar. A continuación, cargue el archivo PDF guardado usando la clase [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) e invoque [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) para guardar el documento en formato Word DOC/DOCX.

{{% blocks/products/pf/feature-page-code h3="Android - Conversión de Excel a Word" %}}

{{< gist "aspose-com-gists" "10fdb88fb4d39618cdc2dfd0d0bd86c1" "excel-to-word-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mhtml-to-docm pdf-to-rtf svg-to-docm xps-to-dotx pdf-to-powerpoint tex-to-ppsx xps-to-potx csv-to-doc excel-to-word xls-to-word xlsx-to-powerpoint xltx-to-word word-to-excel" >}}

{{% blocks/products/pf/feature-page-section  h2="Convertir POWERPOINT a HTML y MHTML" %}}
Android Total API se ocupa de varios formatos, incluidos los archivos de PowerPoint, por lo que puede convertir presentaciones a HTML y MHTML. El proceso es cargar el archivo POWERPOINT PPT/ PPTX usando la clase [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) e invocar [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) para convertir POWERPOINT a HTML. Además, ahora cargue el documento HTML convertido usando la clase [Libro de trabajo](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) y llame a [guardar](https://reference.aspose.com/cells/java/com.aspose.cells/) para la conversión de MHTML. 
{{% blocks/products/pf/feature-page-code h3="Android - Conversión de diapositivas de PowerPoint a HTML y MHTML" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="rtf-to-excel docx-to-csv json-to-word json-to-powerpoint word-to-json powerpoint-to-json potm-to-excel pptx-to-excel ppsx-to-mhtml" >}}