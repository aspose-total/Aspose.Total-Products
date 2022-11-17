---
title: Преобразование формата файла через C# 

description: Конвертируйте Microsoft Word, Excel, PowerPoint, Outlook, PDF, HTML, 3D-изображения, диаграммы, форматы видео и многие другие популярные файлы всего несколькими строками кода C#.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование формата файла через C# .NET" h2="Преобразование файлов Microsoft<sup>&reg;</sup> Office, PDF, изображений, HTML и других форматов без использования какого-либо другого программного обеспечения." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Общая библиотека .NET](https://products.aspose.com/total/net/) ускоряет разработку решений для управления документами с нуля или усовершенствование существующих приложений для облегчения работы с документами. API не только управляет документами Microsoft Office, но также обрабатывает PDF, HTML, изображения TIFF, JPG, PNG, BMP и SVG, файлы электронной почты, форматы видео, форматы данных ГИС и многое другое. Это полный набор API-интерфейсов решения для управления и обработки документов без каких-либо программных зависимостей. Программисты могут легко создавать, обновлять, визуализировать, печатать и преобразовывать между наиболее популярными форматами в любых приложениях на основе .NET.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование Word в PDF" %}}
Total API поддерживает не только взаимное преобразование форматов Microsoft Word, но и преобразование Word в PDF, HTML, изображения, EPUB, Markdown и XPS. Процесс конвертации прост. Загрузите документ через класс Document и просто вызовите метод Save с целевым форматом. Это так просто. Разработчики могут проверить [результат преобразования](https://products.aspose.com/words/net/conversion/word-to-pdf/) перед интеграцией кода **Word в PDF**.


{{% blocks/products/pf/feature-page-code h3="C# — Преобразование Word в PDF" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-word-to-pdf.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-excel word-to-json word-to-ods" >}}


{{% blocks/products/pf/feature-page-section  h2="Конвертировать PDF в изображения" %}}
API поддерживает преобразование PDF в изображения, Powerpoint, Excel и другие форматы. Для преобразования PDF в изображение давайте рассмотрим изображение JPG в качестве целевого файла. Процесс заключается в загрузке PDF-файла с использованием класса Document и инициализации объекта [JpegDevice class](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) и преобразовании PDF в JPEG с помощью [Process](https ://apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) метод
Загрузите файл JPEG с помощью класса [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) и, наконец, вызовите метод Save.

{{% blocks/products/pf/feature-page-code h3="С# — преобразование PDF в изображение" %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt" >}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование Excel в Word и PowerPoint" %}}

Для преобразования форматов Microsoft Excel в различные файлы, включая Word и PowerPoint, используются соответствующие вспомогательные API-интерфейсы основного API Aspose.Total для .NET. Процесс преобразования файлов Excel в документ Word, загрузите файл EXCEL с помощью класса [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) и сначала преобразуйте EXCEL в PDF и установите для SaveFormat значение Auto. Затем загрузите преобразованный PDF-файл с помощью класса Document, вызовите метод Save и установите Doc, Docx как SaveFormat. Также указан код для преобразования Microsoft **Excel в Powerpoint**.

{{% blocks/products/pf/feature-page-code h3="С# — преобразование JSON в Excel" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-word.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="С# — Преобразование Excel в JSON" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="excel-to-doc excel-to-docx excel-to-pptx" >}}