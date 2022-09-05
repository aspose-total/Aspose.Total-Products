---
title: Преобразование документов через C++ 
url: /ru/cpp/conversion/
description: Преобразование различных форматов документов, таких как Word, Excel, PowerPoint, PDF, JSON, изображения и другие, с помощью C++ API. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование документов с использованием C++" h2="Преобразование Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, изображений и других форматов с помощью библиотеки C++." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Библиотека Total C++](https://products.aspose.com/total/cpp/) решает проблему преобразования документов, и разработчики могут легко автоматизировать решение для управления документами и манипулирования ими, интегрируя API в новые разработанные приложения или в существующие приложения. Программисты на C++ могут добавлять в свое решение такие функции, как создание, редактирование или преобразование документов различных форматов, не полагаясь на какое-либо программное обеспечение. Несколько общих случаев, таких как txt в PDF, SVG в PNG, XLSX в CSV, JSON в CSV, Word в PDF, HTML в PDF, можно легко преобразовать. Кроме того, несколько случаев, когда API имеет дело, перечислены ниже, и несколько ссылок приведены для соответствующих случаев преобразования. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование Microsoft Word в Excel" %}}
Total C++ API поддерживает преобразование Microsoft Word DOC/DOCX в Excel.  Процесс таков: загрузите файл Word DOC/DOCX с помощью ссылки на класс [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) и вызовите [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) для преобразования в HTML в первую очередь. Затем загрузите документ HTML с помощью ссылки на класс [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) и вызовите [Сохранить](https://reference.aspose.com/ Cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) для сохранения документа в формате Excel. 

{{% blocks/products/pf/feature-page-code h3="C++ — Преобразование Word в Excel" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование PDF в Word" %}}
Библиотека преобразования C++ также поддерживает преобразование PDF в Word DOC, DOCX и другие форматы. Учитывая случай рендеринга PDF в RTF, это двухэтапный процесс: сначала конвертируйте PDF в формат Word DOC/DOCX, а затем преобразуйте его в RTF. Шаги, включенные для этого, загрузка файла PDF с использованием ссылки на класс [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) и вызов [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) функция-член для преобразования PDF в Word. Теперь снова загрузите файл Word DOC / DOCX с помощью [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) ссылки на класс Aspose.Words API и сохраните его в формате RTF, используя [Сохранить](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) функция-член.

{{% blocks/products/pf/feature-page-code h3="C++ - Преобразование PDF в Word" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="Конвертировать JSON в Word" %}}
Для преобразования JSON C++ API поддерживает различные комбинации, такие как JSON в Word, Json в PowerPoint, Word в JSON и т. д. В случае преобразования Word процесс заключается в чтении действительных данных JSON из файла с помощью нового объекта [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) и последующем вызове [Сохранить](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) для сохранения JSON в виде файла PDF. Итак, теперь загрузите сохраненный файл с помощью класса [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) и сохраните его в формате документа Word с помощью [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat).
{{% blocks/products/pf/feature-page-code h3="C++ — преобразование JSON в Word" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}