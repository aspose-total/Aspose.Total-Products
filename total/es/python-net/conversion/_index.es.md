---
title: Conversión de documentos a través de Python 

description: Convierta formatos de Microsoft Word DOC, DOCX a PDF, imágenes y más, así como diapositivas de presentación, mensajes de correo electrónico e imágenes en 3D con solo unas pocas líneas de código Python.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Conversión de documentos usando las API de Python" h2="Convierta Microsoft<sup>&reg;</sup> Office Word, PDF, imágenes y varios otros formatos usando Aspose.Words para Python a través de .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Python API](https://products.aspose.com/total/python-net/) acelera el desarrollo de soluciones de automatización de documentos desde cero o mejora las aplicaciones existentes para crear, editar o convertir documentos, presentaciones, correos electrónicos y archivos 3D. La API de Python no solo maneja diapositivas de presentación y Word de Microsoft Office, sino que también maneja archivos PDF, HTML, imágenes y correo electrónico y mucho más. La API no depende de ningún software y es un conjunto completo de soluciones de gestión y manipulación de documentos.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir Microsoft Word a PDF" %}}
Total Python API admite la conversión múltiple de formatos como Microsoft Word a PDF, imágenes, Markdown y HTML. La API simplifica el proceso de conversión de documentos de Word a PDF con una salida de calidad tan cercana al documento como a un archivo DOC, DOCX. El proceso es cargar el archivo DOC o DOCX en el objeto [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) y simplemente llamar al [save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) con el formato PDF de destino junto con su ruta de directorio. Es tan simple. En caso de que sea necesario especificar estándares de PDF como PDF 1.7 o 1.5, la API proporciona enumeración [PdfComplaince](https://reference.aspose.com/words/python-net/aspose.words.saving/pdfcompliance/), para configurar [PdfSaveOptions()](https://reference.aspose.com/words/python-net/aspose.words.saving/pdfsaveoptions/). 

{{% blocks/products/pf/feature-page-code h3="Python - Conversión de Word a PDF" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-word-document-to-pdf-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Conversión de Microsoft Word a Imágenes" %}}
La conversión de palabras a imágenes es una característica adicional de la API de Python. Además de solo la conversión, se pueden configurar fácilmente varias opciones de guardado, como brillo, contraste, resolución horizontal y vertical, etc. Para especificar varias opciones de guardado, la API proporciona [ImageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/imagesaveoptions/), [FixedPageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/fixedpagesaveoptions/) o [SaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/saveoptions/) las clases pueden ser utilizado a partir del escenario requerido. El ejemplo de código siguiente muestra la creación de una vista previa de la primera página del documento con la aplicación de algunas configuraciones adicionales.

{{% blocks/products/pf/feature-page-code h3="Python - Conversión de palabra a imagen" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-word-to-images-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir Microsoft PowerPoint a Word" %}}
La API de Python admite la conversión de archivos PPT / PPTX de Microsoft PowerPoint a archivos DOC / DOCX de Word. Dos API [Aspose.Slides para Python a través de .NET](https://products.aspose.com/slides/python-net/) y [Aspose.Words para Python a través de .NET](https://products.aspose.com/words/python-net/) utilizado para realizar esta conversión. Cargue el archivo PPT/PPTX usando [Presentación](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/). Obtenga el objeto de la clase Documento de Word. Recorre cada diapositiva, genera e inserta la imagen de la diapositiva y luego inserta el texto de la diapositiva iterando a través de las formas de las diapositivas.

{{% blocks/products/pf/feature-page-code h3="Python - Conversión de diapositivas de PowerPoint a Word" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-powerpoint-presentation-to-word-via-python.py" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}


{{< blocks/products/pf/feature-page-options pairs="powerpoint-to-word ppsx-to-doc pptx-to-docx ppt-to-docm pot-to-dotx potx-to-dotm potm-to-rtf pptm-to-word pps-to-docx odp-to-doc word-to-powerpoint doc-to-odp dot-to-pps docx-to-ppsm docm-to-pptm dotx-to-potm dotm-to-potx rtf-to-pot wordml-to-pptx odt-to-ppsx ott-to-pps txt-to-powerpoint md-to-ppsm" >}}

{{% blocks/products/pf/feature-page-section  h2="Conversión de correo electrónico a Word, PDF, HTML e imágenes" %}}
Para la conversión de archivos de correo electrónico a PDF, Word, imágenes y HTML, Email Python API [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) realiza la conversión. La API carga el archivo fuente en su modelo de objetos e invoca el método Guardar con los parámetros relevantes. 

{{% blocks/products/pf/feature-page-code h3="Python - Conversión de archivos de correo electrónico a Word" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-email-to-word-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="email-to-doc ics-to-docx mbox-to-pdf ost-to-image msg-to-tiff pst-to-jpeg oft-to-gif vcf-to-docm emlx-to-png eml-to-text" >}}