---
title: Преобразование PDF в WMF через Java
description: Экспорт файла PDF в WMF в ваших приложениях Java без использования каких-либо сторонних приложений.
url_ignore: /ru/java/conversion/pdf-to-wmf/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: WMF
otherformats: SVGZ PSD EMZ DXF IMAGE TGA JPEG2000 WMZ WMF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование PDF в WMF через Java" h2="Экспорт файла PDF в WMF в любом приложении Java J2SE, J2EE, J2ME без использования Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Вы можете преобразовать файл pdf в изображение WMF на Java в два простых шага. Во-первых, используя [Aspose.PDF для Java](https://products.aspose.com/pdf/java/), вы можете экспортировать PDF в JPEG. После этого, используя [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) API обработки изображений, вы можете отображать JPEG в WMF. Оба API входят в пакет [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Экспорт PDF в WMF через Java" %}}
1. Откройте файл PDF, используя класс [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Инициализируйте объект класса и визуализируйте PDF в JPEG с помощью [Process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com. метод aspose.pdf.Page-java.io.OutputStream-)
3. Загрузите файл JPEG с помощью класса [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image).
4. Сохраните документ в формате WMF, используя [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) метод
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total). и включите библиотеки в свой pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование PDF в WMF в одном файле через Java" %}}
API также позволяет экспортировать файл PDF в WMF в один файл. Чтобы преобразовать все страницы, вы можете сначала преобразовать документ PDF в один файл TIFF, а затем экспортировать файл TIFF в WMF. Вы можете открыть входной файл с помощью класса [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) и создать объекты устройства Resolution, TiffSettings и TIFF. Вы можете получить одно изображение TIFF, используя [процесс](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) класса [TiffDevice](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Наконец, вы можете загрузить файл TIFF с помощью класса [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) и сохранить его в формате WMF с помощью [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование PDF в WMF с водяным знаком через Java" %}}
Используя API, вы также можете экспортировать файл PDF в WMF с водяным знаком в вашем документе WMF. Чтобы добавить водяной знак, вы можете сначала преобразовать PDF в JPEG и добавить в него водяной знак. Чтобы добавить водяной знак, загрузите файл изображения с помощью класса [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image), создайте объект класса [Graphics](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) и инициализируйте его с помощью объекта Image, создайте новую [Matrix](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Matrix) и задайте перевод и трансформацию под желаемым углом и добавьте водяной знак с помощью [Graphics.drawString](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics# Метод drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). После добавления водяного знака на изображение вы можете сохранить JPEG в формате WMF. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование и поворот PDF в файл WMF через Java" %}}
Используя API, вы также можете поворачивать выходное изображение WMF в соответствии с вашими потребностями. Метод Image.rotateFlip можно использовать для поворота изображения на 90/180/270 градусов и отражения изображения по горизонтали или вертикали. Библиотека предоставляет простые методы для выполнения сложных операций, инкапсулируя все некрасивые детали. Вы можете указать тип поворота и отражения для применения к изображению. Чтобы повернуть и перевернуть изображение, вы можете загрузить преобразованное изображение JPEG с помощью класса [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) и вызвать метод Image. rotateFlip при указании соответствующего [RotateFlipType](https://apireference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pdf-to-emz/" name="PDF К EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pdf-to-tga/" name="PDF К TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pdf-to-jpeg2000/" name="PDF К JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pdf-to-image/" name="PDF К IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pdf-to-psd/" name="PDF К PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pdf-to-wmz/" name="PDF К WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pdf-to-svgz/" name="PDF К SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pdf-to/" name="PDF К" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pdf-to-wmf/" name="PDF К WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pdf-to-dxf/" name="PDF К DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pdf-to-dicom/" name="PDF К DICOM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}