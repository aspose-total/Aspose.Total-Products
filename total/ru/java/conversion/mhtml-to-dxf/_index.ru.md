---
title: Преобразование MHTML в DXF через Java
description: Экспорт файла MHTML в DXF в ваших приложениях Java без использования каких-либо сторонних приложений.
url_ignore: /ru/java/conversion/mhtml-to-dxf/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: DXF
otherformats: SVGZ EMZ  DXF WMF WMZ PSD IMAGE TGA JPEG2000 DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование MHTML в DXF через Java" h2="Экспорт файла MHTML в DXF в любом приложении Java J2SE, J2EE, J2ME без использования Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Вы можете преобразовать файл mhtml в изображение DXF на Java в два простых шага. Во-первых, используя [Aspose.PDF для Java](https://products.aspose.com/pdf/java/), вы можете экспортировать MHTML в JPEG. После этого, используя [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) API обработки изображений, вы можете отображать JPEG в DXF. Оба API входят в пакет [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Экспорт MHTML в DXF через Java" %}}
1. Откройте файл MHTML, используя класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Инициализируйте объект класса и визуализируйте MHTML в JPEG с помощью [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com. метод aspose.pdf.Page-java.io.OutputStream-)
3. Загрузите файл JPEG с помощью класса [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image).
4. Сохраните документ в формате DXF, используя [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) метод
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://releases.aspose.com/total/java/). и включите библиотеки в свой pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование MHTML в DXF в одном файле через Java" %}}
API также позволяет экспортировать файл MHTML в DXF в один файл. Чтобы преобразовать все страницы, вы можете сначала преобразовать документ MHTML в один файл TIFF, а затем экспортировать файл TIFF в DXF. Вы можете открыть входной файл с помощью класса [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) и создать объекты устройства Resolution, TiffSettings и TIFF. Вы можете получить одно изображение TIFF, используя [процесс](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) класса [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Наконец, вы можете загрузить файл TIFF с помощью класса [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) и сохранить его в формате DXF с помощью [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование MHTML в DXF с водяным знаком через Java" %}}
Используя API, вы также можете экспортировать файл MHTML в DXF с водяным знаком в вашем документе DXF. Чтобы добавить водяной знак, вы можете сначала преобразовать MHTML в JPEG и добавить в него водяной знак. Чтобы добавить водяной знак, загрузите файл изображения с помощью класса [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), создайте объект класса [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) и инициализируйте его с помощью объекта Image, создайте новую [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) и задайте перевод и трансформацию под желаемым углом и добавьте водяной знак с помощью [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics# Метод drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). После добавления водяного знака на изображение вы можете сохранить JPEG в формате DXF. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование и поворот MHTML в файл DXF через Java" %}}
Используя API, вы также можете поворачивать выходное изображение DXF в соответствии с вашими потребностями. Метод Image.rotateFlip можно использовать для поворота изображения на 90/180/270 градусов и отражения изображения по горизонтали или вертикали. Библиотека предоставляет простые методы для выполнения сложных операций, инкапсулируя все некрасивые детали. Вы можете указать тип поворота и отражения для применения к изображению. Чтобы повернуть и перевернуть изображение, вы можете загрузить преобразованное изображение JPEG с помощью класса [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) и вызвать метод Image. rotateFlip при указании соответствующего [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}