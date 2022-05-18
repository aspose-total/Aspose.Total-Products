---
title: Преобразование формата файла через Java 
url: /ru/java/conversion/
description: Преобразование Microsoft Office Word, Excel, PowerPoint, Outlook, PDF, HTML, 3D-изображений, диаграмм, форматов видео и других форматов с помощью всего нескольких строк кода Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование формата файла через Java" h2="Преобразование документов Microsoft<sup>&reg;</sup> Office, PDF, изображений, HTML и многих других файлов без использования какого-либо другого программного обеспечения." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Общая библиотека Java](https://products.aspose.com/total/java/) ускоряет разработку решений для работы с документами с нуля или усовершенствование существующих приложений для упрощения управления документами. API не только создает, редактирует и конвертирует документы Microsoft Office, но также обрабатывает PDF, HTML, изображения TIFF, JPG, PNG, BMP и SVG, файлы электронной почты, форматы видео, 3D, CAD и многое другое. Это набор API-интерфейсов решений для управления и обработки документов без каких-либо программных зависимостей в любых приложениях Java J2SE, J2EE, J2ME. Программисты могут легко создавать, обновлять, визуализировать, печатать и преобразовывать между наиболее популярными форматами в любых приложениях на основе Java.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование Word в Excel" %}}
Total API поддерживает не только взаимное преобразование форматов Microsoft Word, но и преобразование Word в Excel, PDF, HTML, изображения, EPUB, Markdown и XPS. Процесс конвертации прост. Давайте рассмотрим случай преобразования **Word в Excel**. Загрузите файл Microsoft Word с помощью класса [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) и преобразуйте **WORD в HTML** с помощью [метода сохранения](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)). Затем откройте преобразованный HTML-документ с помощью класса [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) и сохраните документ в формате XLSX с помощью [Save](https:/ /apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) метод.
 Разработчики также могут конвертировать [Word в PDF](https://products.aspose.com/words/java/conversion/word-to-pdf/).


{{% blocks/products/pf/feature-page-code h3="Java Преобразование Word в Excel" %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-json word-to-powerpoint" >}}


{{% blocks/products/pf/feature-page-section  h2="Конвертировать PDF в изображения" %}}
API поддерживает преобразование PDF в изображения, такие как JPEG2000, EMZ, WMZ, TGA, PSD, DXF, WMF, SVGZ, APNG, DICOM, Powerpoint, Excel и другие форматы. Для преобразования PDF в изображение давайте рассмотрим изображение JPG в качестве целевого файла. Процесс заключается в загрузке PDF-файла с использованием класса Document и инициализации объекта [JpegDevice class](https://apireference.aspose.com/pdf/java/aspose.pdf.devices/jpegdevice) и преобразовании PDF в JPEG с помощью [Process](https ://apireference.aspose.com/pdf/java/aspose.pdf.devices.pagedevice/process/methods/1) метод
Загрузите файл JPEG с помощью класса [Image](https://apireference.aspose.com/imaging/java/aspose.imaging/image) и, наконец, вызовите метод Save.

{{% blocks/products/pf/feature-page-code h3="Java PDF to Image Conversion" %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-csv pdf-to-txt pdf-to-markdown" >}}

{{% blocks/products/pf/feature-page-section  h2="Конвертировать PowerPoint в файлы Excel" %}}

Для преобразования файлов Microsoft PowerPoint в другие файлы, включая Excel Word, MHTML, соответствующие вспомогательные API, связанные с основным API Aspose.Total для Java. Процесс преобразования файлов PowerPoint в документ Excel. Загрузка файла PowerPoint с помощью класса [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) и преобразование **PowerPoint в HTML** с помощью используя метод [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-). Затем загрузите преобразованный HTML-документ с помощью класса [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) и сохраните документ в формате EXCEL, используя [save](https:/ /apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) метод. Также указан код для преобразования **PowerPoint в Word**.

{{% blocks/products/pf/feature-page-code h3="Преобразование Java PowerPoint в Excel" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Преобразование PowerPoint в Word" %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="powerpoint-to-doc powerpoint-to-docx powerpoint-to-xlsx" >}}