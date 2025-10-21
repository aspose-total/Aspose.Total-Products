---
title: Преобразование PS в DICOM через Java
description: Экспорт файла PS в DICOM в ваших приложениях Java без использования каких-либо сторонних приложений.
url_ignore: /ru/java/conversion/ps-to-dicom/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: DICOM
otherformats: TGA DICOM JPEG2000 IMAGE WMF PSD WMZ DXF EMZ SVGZ
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование PS в DICOM через Java" h2="Экспорт файла PS в DICOM в любом приложении Java J2SE, J2EE, J2ME без использования Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Вы можете преобразовать файл ps в изображение DICOM на Java в два простых шага. Во-первых, используя [Aspose.PDF для Java](https://products.aspose.com/pdf/java/), вы можете экспортировать PS в JPEG. После этого, используя [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) API обработки изображений, вы можете отображать JPEG в DICOM. Оба API входят в пакет [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Экспорт PS в DICOM через Java" %}}
1. Откройте файл PS, используя класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Инициализируйте объект класса и визуализируйте PS в JPEG с помощью [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com. метод aspose.pdf.Page-java.io.OutputStream-)
3. Загрузите файл JPEG с помощью класса [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image).
4. Сохраните документ в формате DICOM, используя [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) метод
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://releases.aspose.com/total/java/). и включите библиотеки в свой pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование PS в DICOM в одном файле через Java" %}}
API также позволяет экспортировать файл PS в DICOM в один файл. Чтобы преобразовать все страницы, вы можете сначала преобразовать документ PS в один файл TIFF, а затем экспортировать файл TIFF в DICOM. Вы можете открыть входной файл с помощью класса [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) и создать объекты устройства Resolution, TiffSettings и TIFF. Вы можете получить одно изображение TIFF, используя [процесс](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) класса [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Наконец, вы можете загрузить файл TIFF с помощью класса [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) и сохранить его в формате DICOM с помощью [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование PS в DICOM с водяным знаком через Java" %}}
Используя API, вы также можете экспортировать файл PS в DICOM с водяным знаком в вашем документе DICOM. Чтобы добавить водяной знак, вы можете сначала преобразовать PS в JPEG и добавить в него водяной знак. Чтобы добавить водяной знак, загрузите файл изображения с помощью класса [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), создайте объект класса [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) и инициализируйте его с помощью объекта Image, создайте новую [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) и задайте перевод и трансформацию под желаемым углом и добавьте водяной знак с помощью [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics# Метод drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). После добавления водяного знака на изображение вы можете сохранить JPEG в формате DICOM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование и поворот PS в файл DICOM через Java" %}}
Используя API, вы также можете поворачивать выходное изображение DICOM в соответствии с вашими потребностями. Метод Image.rotateFlip можно использовать для поворота изображения на 90/180/270 градусов и отражения изображения по горизонтали или вертикали. Библиотека предоставляет простые методы для выполнения сложных операций, инкапсулируя все некрасивые детали. Вы можете указать тип поворота и отражения для применения к изображению. Чтобы повернуть и перевернуть изображение, вы можете загрузить преобразованное изображение JPEG с помощью класса [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) и вызвать метод Image. rotateFlip при указании соответствующего [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}

Преобразование файлов PS (PostScript) в формат DICOM (цифровое изображение и связь в медицине) обеспечивает беспрепятственную интеграцию векторных отчетов, диагностических диаграмм и радиографических аннотаций в стандартизированные медицинские рабочие процессы. Совместимость с DICOM гарантирует, что эти визуальные отчеты могут быть безопасно просмотрены и проанализированы на платформах PACS (система архивирования и передачи изображений), используемых в больницах и клиниках.

{{% blocks/products/pf/agp/feature-section-col title="Основные сценарии использования" %}}

* Встраивание векторных диагностических диаграмм в архивы изображений пациентов.
* Преобразование кардиологических или онкологических диаграмм PS в серии изображений, совместимых с DICOM.
* Интеграция визуального планирования хирургических вмешательств в системы изображений больниц.
* Создание диагностических сводок в качестве наложений DICOM для радиологических отчетов.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Сценарии автоматизации" %}}

* Автоматизированное преобразование PS в DICOM в рамках рабочих процессов ЭМК (электронная медицинская карта).
* Интеграция данных ETL в аналитические конвейеры здравоохранения для отчетности на основе изображений.
* Пакетное преобразование с помощью искусственного интеллекта для диагностической визуализации в медицинских системах искусственного интеллекта.
* Автоматический экспорт DICOM для автоматически созданных клинических документов об изображениях.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}