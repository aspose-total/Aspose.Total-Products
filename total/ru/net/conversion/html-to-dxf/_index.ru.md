---
title: Преобразование HTML в DXF через C# API
description: Экспорт HTML в DXF в ваших приложениях .NET без использования каких-либо сторонних приложений.
url_ignore: /ru/net/conversion/html-to-dxf/
family: total
platformtag: net
feature: conversion
informat: HTML
outformat: DXF
otherformats: DXF TGA IMAGE SVGZ EMZ WMF JPEG2000 PSD WMZ  DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразовать файл HTML в DXF через C#" h2="Экспорт HTML в DXF в приложениях .NET без использования Adobe<sup>&reg;</sup> Acrobat Reader или любых других сторонних приложений." >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total для .NET](https://products.aspose.com/total/net/), вы можете легко экспортировать изображение HTML в DXF в любых приложениях .NET за два простых шага. Прежде всего, используя [Aspose.PDF для .NET](https://products.aspose.com/pdf/net/), вы можете экспортировать HTML в JPEG. После этого, используя [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) API обработки изображений, вы можете конвертировать JPEG в DXF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование файла HTML в DXF через .NET" %}}
1. Откройте файл HTML, используя класс [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Инициализируйте объект класса [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) и визуализируйте HTML в JPEG с помощью [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) метод
3. Загрузите файл JPEG с помощью класса [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image).
4. Сохраните документ в формате DXF, используя метод [Сохранить](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование файла HTML в DXF в один файл с помощью С#" %}}
Используя API, вы также можете преобразовать файл HTML в DXF в один файл изображения. Чтобы преобразовать все страницы, вы можете сначала преобразовать документ HTML в один файл TIFF, а затем экспортировать файл TIFF в DXF. Вы можете открыть входной файл с помощью класса [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) и создать объекты устройства Resolution, TiffSettings и TIFF. Вы можете получить одно изображение TIFF, используя метод [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Наконец, вы можете загрузить файл TIFF, используя класс [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image).
и сохраните его в формате DXF, используя метод [Сохранить](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование и поворот файла HTML в DXF с помощью C#" %}}
Используя API, вы также можете поворачивать выходное изображение DXF в соответствии с вашими потребностями. Метод Image.RotateFlip можно использовать для поворота изображения на 90/180/270 градусов и отражения изображения по горизонтали или вертикали. Вы можете указать тип поворота и отражения для применения к изображению. Чтобы повернуть и отразить изображение, вы можете загрузить преобразованное изображение JPEG, используя фабричный метод, предоставляемый классом [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image), и вызвать Image .RotateFlip при указании соответствующего [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/html-to-emz/" name="HTML в EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/html-to-tga/" name="HTML в TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/html-to-jpeg2000/" name="HTML в JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/html-to-image/" name="HTML в IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/html-to-psd/" name="HTML в PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/html-to-wmz/" name="HTML в WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/html-to-svgz/" name="HTML в SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/html-to/" name="HTML в" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/html-to-wmf/" name="HTML в WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/html-to-dxf/" name="HTML в DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/html-to-dicom/" name="HTML в DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}