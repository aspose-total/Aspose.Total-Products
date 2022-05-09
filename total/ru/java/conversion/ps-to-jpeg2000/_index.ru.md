---
title: Преобразование PS в JPEG2000 через Java
description: Экспорт файла PS в JPEG2000 в ваших приложениях Java без использования каких-либо сторонних приложений.
url_ignore: /ru/java/conversion/ps-to-jpeg2000/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: JPEG2000
otherformats: TGA WMZ SVGZ WMF PSD IMAGE DXF  EMZ JPEG2000 DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование PS в JPEG2000 через Java" h2="Экспорт файла PS в JPEG2000 в любом приложении Java J2SE, J2EE, J2ME без использования Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Вы можете преобразовать файл ps в изображение JPEG2000 на Java в два простых шага. Во-первых, используя [Aspose.PDF для Java](https://products.aspose.com/pdf/java/), вы можете экспортировать PS в JPEG. После этого, используя [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) API обработки изображений, вы можете отображать JPEG в JPEG2000. Оба API входят в пакет [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Экспорт PS в JPEG2000 через Java" %}}
1. Откройте файл PS, используя класс [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Инициализируйте объект класса и визуализируйте PS в JPEG с помощью [Process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com. метод aspose.pdf.Page-java.io.OutputStream-)
3. Загрузите файл JPEG с помощью класса [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image).
4. Сохраните документ в формате JPEG2000, используя [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) метод
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total). и включите библиотеки в свой pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование PS в JPEG2000 в одном файле через Java" %}}
API также позволяет экспортировать файл PS в JPEG2000 в один файл. Чтобы преобразовать все страницы, вы можете сначала преобразовать документ PS в один файл TIFF, а затем экспортировать файл TIFF в JPEG2000. Вы можете открыть входной файл с помощью класса [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) и создать объекты устройства Resolution, TiffSettings и TIFF. Вы можете получить одно изображение TIFF, используя [процесс](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) класса [TiffDevice](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Наконец, вы можете загрузить файл TIFF с помощью класса [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) и сохранить его в формате JPEG2000 с помощью [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование PS в JPEG2000 с водяным знаком через Java" %}}
Используя API, вы также можете экспортировать файл PS в JPEG2000 с водяным знаком в вашем документе JPEG2000. Чтобы добавить водяной знак, вы можете сначала преобразовать PS в JPEG и добавить в него водяной знак. Чтобы добавить водяной знак, загрузите файл изображения с помощью класса [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image), создайте объект класса [Graphics](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) и инициализируйте его с помощью объекта Image, создайте новую [Matrix](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Matrix) и задайте перевод и трансформацию под желаемым углом и добавьте водяной знак с помощью [Graphics.drawString](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics# Метод drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). После добавления водяного знака на изображение вы можете сохранить JPEG в формате JPEG2000. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование и поворот PS в файл JPEG2000 через Java" %}}
Используя API, вы также можете поворачивать выходное изображение JPEG2000 в соответствии с вашими потребностями. Метод Image.rotateFlip можно использовать для поворота изображения на 90/180/270 градусов и отражения изображения по горизонтали или вертикали. Библиотека предоставляет простые методы для выполнения сложных операций, инкапсулируя все некрасивые детали. Вы можете указать тип поворота и отражения для применения к изображению. Чтобы повернуть и перевернуть изображение, вы можете загрузить преобразованное изображение JPEG с помощью класса [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) и вызвать метод Image. rotateFlip при указании соответствующего [RotateFlipType](https://apireference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ps-to-emz/" name="PS К EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ps-to-tga/" name="PS К TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ps-to-jpeg2000/" name="PS К JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ps-to-image/" name="PS К IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ps-to-psd/" name="PS К PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ps-to-wmz/" name="PS К WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ps-to-svgz/" name="PS К SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ps-to/" name="PS К" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ps-to-wmf/" name="PS К WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ps-to-dxf/" name="PS К DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ps-to-dicom/" name="PS К DICOM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}