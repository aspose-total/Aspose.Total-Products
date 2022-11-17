---
title: Преобразование документов через Python 

description: Преобразование форматов Microsoft Word DOC, DOCX в PDF, изображения и многое другое, а также слайды презентаций, сообщения электронной почты и 3D-изображения всего в несколько строк кода Python.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование документов с использованием API Python" h2="Преобразование Microsoft<sup>&reg;</sup> Office Word, PDF, изображений и различных других форматов с помощью Aspose.Words for Python for .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Python API](https://products.aspose.com/total/python-net/) ускоряет разработку решений для автоматизации документов с нуля или усовершенствование существующих приложений для создания, редактирования или преобразования документов, презентаций, электронных писем и 3D-файлов. Python API не только обрабатывает слайды Microsoft Office Word и презентации, но также обрабатывает PDF, HTML, изображения и файлы электронной почты и многое другое. API не зависит от какого-либо программного обеспечения и представляет собой полный набор решений для управления и обработки документов.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование Microsoft Word в PDF" %}}
Total Python API поддерживает многократное преобразование форматов, таких как Microsoft Word, в PDF, изображения, Markdown и HTML. API упрощает процесс преобразования документа Word в PDF с качеством вывода, максимально приближенным к документу, как у файлов DOC, DOCX. Процесс загружает файл DOC или DOCX в объект [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) и просто вызывает [save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) с целевым форматом PDF вместе с путем к его каталогу. Это так просто. В случае необходимости указать стандарты PDF, такие как PDF 1.7 или 1.5, API предоставляет перечисление [PdfComplaince](https://reference.aspose.com/words/python-net/aspose.words.saving/pdfcompliance/) для настройки [PdfSaveOptions()](https://reference.aspose.com/words/python-net/aspose.words.saving/pdfsaveoptions/). 

{{% blocks/products/pf/feature-page-code h3="Python — Преобразование Word в PDF" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-word-document-to-pdf-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование Microsoft Word в изображения" %}}
Преобразование слов в изображения — основная функция Python API. Помимо простого преобразования, можно легко установить различные параметры сохранения, такие как яркость, контрастность, разрешение по горизонтали и вертикали и т. д. Процесс заключается в том, чтобы загрузить документ через объект Document, а затем вызвать метод сохранения с желаемым расширением файла изображения, указав путь. Чтобы указать различные параметры сохранения, API предоставляет [ImageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/imagesaveoptions/), [FixedPageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/fixedpagesaveoptions/) или [SaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/saveoptions/) могут быть используется по требуемому сценарию. Ниже пример кода демонстрирует создание предварительного просмотра первой страницы документа с применением некоторых дополнительных настроек.

{{% blocks/products/pf/feature-page-code h3="Python — преобразование слова в изображение" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-word-to-images-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование Microsoft PowerPoint в Word" %}}
API Python поддерживает преобразование файлов Microsoft PowerPoint PPT/PPTX в файлы Word DOC/DOCX. Два API [Aspose.Slides for Python for .NET](https://products.aspose.com/slides/python-net/) и [Aspose.Words for Python for .NET](https://products.aspose.com/words/python-net/), используемый для выполнения этого преобразования. Загрузите файл PPT/PPTX, используя [Презентацию](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/). Получите объект класса Words Document. Итерация по каждому слайду, создание и вставка изображения слайда, а затем вставка текста слайда путем итерации по формам слайдов.

{{% blocks/products/pf/feature-page-code h3="Python - Преобразование слайдов PowerPoint в Word" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-powerpoint-presentation-to-word-via-python.py" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}


{{< blocks/products/pf/feature-page-options pairs="powerpoint-to-word ppsx-to-doc pptx-to-docx ppt-to-docm pot-to-dotx potx-to-dotm potm-to-rtf pptm-to-word pps-to-docx odp-to-doc word-to-powerpoint doc-to-odp dot-to-pps docx-to-ppsm docm-to-pptm dotx-to-potm dotm-to-potx rtf-to-pot wordml-to-pptx odt-to-ppsx ott-to-pps txt-to-powerpoint md-to-ppsm" >}}