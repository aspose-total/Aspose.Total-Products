---
title: Преобразование TEX в IMAGE через Java
description: Экспорт файла TEX в IMAGE в ваших приложениях Java без использования каких-либо сторонних приложений.
url_ignore: /ru/java/conversion/tex-to-image/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: JPEG2000
otherformats: DXF WMZ WMF TGA EMZ JPEG2000 SVGZ PSD  IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование TEX в IMAGE через Java" h2="Экспорт файла TEX в IMAGE в любом приложении Java J2SE, J2EE, J2ME без использования Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Вы можете преобразовать файл tex в изображение IMAGE на Java в два простых шага. Во-первых, используя [Aspose.PDF для Java](https://products.aspose.com/pdf/java/), вы можете экспортировать TEX в JPEG. После этого, используя [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) API обработки изображений, вы можете отображать JPEG в IMAGE. Оба API входят в пакет [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Экспорт TEX в IMAGE через Java" %}}
1. Откройте файл TEX, используя класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Инициализируйте объект класса и визуализируйте TEX в JPEG с помощью [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com. метод aspose.pdf.Page-java.io.OutputStream-)
3. Загрузите файл JPEG с помощью класса [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image).
4. Сохраните документ в формате IMAGE, используя [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) метод
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total). и включите библиотеки в свой pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование TEX в IMAGE в одном файле через Java" %}}
API также позволяет экспортировать файл TEX в IMAGE в один файл. Чтобы преобразовать все страницы, вы можете сначала преобразовать документ TEX в один файл TIFF, а затем экспортировать файл TIFF в IMAGE. Вы можете открыть входной файл с помощью класса [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) и создать объекты устройства Resolution, TiffSettings и TIFF. Вы можете получить одно изображение TIFF, используя [процесс](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) класса [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Наконец, вы можете загрузить файл TIFF с помощью класса [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) и сохранить его в формате IMAGE с помощью [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование TEX в IMAGE с водяным знаком через Java" %}}
Используя API, вы также можете экспортировать файл TEX в IMAGE с водяным знаком в вашем документе IMAGE. Чтобы добавить водяной знак, вы можете сначала преобразовать TEX в JPEG и добавить в него водяной знак. Чтобы добавить водяной знак, загрузите файл изображения с помощью класса [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), создайте объект класса [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) и инициализируйте его с помощью объекта Image, создайте новую [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) и задайте перевод и трансформацию под желаемым углом и добавьте водяной знак с помощью [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics# Метод drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). После добавления водяного знака на изображение вы можете сохранить JPEG в формате IMAGE. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование и поворот TEX в файл IMAGE через Java" %}}
Используя API, вы также можете поворачивать выходное изображение IMAGE в соответствии с вашими потребностями. Метод Image.rotateFlip можно использовать для поворота изображения на 90/180/270 градусов и отражения изображения по горизонтали или вертикали. Библиотека предоставляет простые методы для выполнения сложных операций, инкапсулируя все некрасивые детали. Вы можете указать тип поворота и отражения для применения к изображению. Чтобы повернуть и перевернуть изображение, вы можете загрузить преобразованное изображение JPEG с помощью класса [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) и вызвать метод Image. rotateFlip при указании соответствующего [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/tex-to-emz/" name="TEX К EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/tex-to-tga/" name="TEX К TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/tex-to-jpeg2000/" name="TEX К JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/tex-to-image/" name="TEX К IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/tex-to-psd/" name="TEX К PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/tex-to-wmz/" name="TEX К WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/tex-to-svgz/" name="TEX К SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/tex-to/" name="TEX К" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/tex-to-wmf/" name="TEX К WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/tex-to-dxf/" name="TEX К DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/tex-to-dicom/" name="TEX К DICOM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}