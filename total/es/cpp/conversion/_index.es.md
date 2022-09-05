---
title: Conversión de documentos a través de C++ 
url: /es/cpp/conversion/
description: Convierta varios formatos de documentos como Word, Excel, PowerPoint, PDF, JSON, imágenes y más utilizando la API de C++. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Conversión de documentos usando C++" h2="Convierta Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, imágenes y varios otros formatos utilizando la biblioteca C++." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Biblioteca Total C++](https://products.aspose.com/total/cpp/) resuelve el problema de la conversión de documentos y los desarrolladores pueden automatizar la solución de gestión y manipulación de documentos fácilmente mediante la integración de API dentro de nuevas aplicaciones desarrolladas o en aplicaciones existentes. Los programadores de C ++ pueden agregar funcionalidades como crear, editar o convertir documentos de varios formatos dentro de su solución sin depender de ningún software. Pocos casos genéricos como txt a PDF, SVG a PNG, XLSX a CSV, JSON a CSV, Word a PDF, HTML a PDF, se pueden convertir fácilmente. Además, se enumeran a continuación algunos casos que trata la API y se proporcionan pocos enlaces para los casos de conversión relevantes. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir Microsoft Word a Excel" %}}
Total C++ API es compatible con la conversión de Microsoft Word DOC/DOCX a Excel.  El proceso es cargar el archivo DOC/DOCX de Word usando la referencia de clase [Documento](https://reference.aspose.com/words/cpp/class/aspose.words.document) e invocar [Guardar](https://reference. aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) función miembro para convertir en HTML en primer lugar. A continuación, cargue el documento HTML utilizando la referencia de clase [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) e invoque [Guardar](https://reference.aspose.com/ cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) función miembro para guardar el documento en formato Excel. 

{{% blocks/products/pf/feature-page-code h3="C++ - Conversión de Word a Excel" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc  doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="Conversión de PDF a Word" %}}
La biblioteca de conversión de C++ también es compatible con la conversión de PDF a Word DOC, DOCX y otros formatos. Teniendo en cuenta el caso de renderizar PDF a RTF, es un proceso de dos pasos, primero convertir PDF a formato Word DOC/DOCX y luego renderizarlo a RTF. Pasos incluidos para esto, cargando el archivo PDF usando [Documento] (https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) referencia de clase e invocando [Guardar] (https://reference.aspose .com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) función miembro para convertir PDF a Word. Ahora cargue nuevamente el archivo Word DOC / DOCX usando [Documento] (https://reference.aspose.com/words/cpp/class/aspose.words.document) referencia de clase de Aspose.Words API y guárdelo en formato RTF usando [Guardar](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) función miembro.

{{% blocks/products/pf/feature-page-code h3="C++ - Conversión de PDF a Word" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="Convertir JSON a Word" %}}
Para la conversión de JSON, la API de C++ admite varias combinaciones, como JSON a Word, Json a PowerPoint, Word a JSON, etc. Teniendo en cuenta el caso de la conversión de Word, Process es leer datos JSON válidos del archivo utilizando un nuevo objeto [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) y luego invocar [Guardar](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) método para guardar JSON como archivo PDF. Así que ahora cargue el archivo guardado usando la clase [Documento] (https://reference.aspose.com/words/cpp/class/aspose.words.document) y guárdelo en formato de documento de Word usando [Guardar] (https://referencia .aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat).
{{% blocks/products/pf/feature-page-code h3="C++ - Conversión de JSON a Word" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}