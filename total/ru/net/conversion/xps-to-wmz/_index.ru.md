---
title: Преобразование XPS в WMZ через C# API
description: Экспорт XPS в WMZ в ваших приложениях .NET без использования каких-либо сторонних приложений.
url: /ru/net/conversion/xps-to-wmz/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: WMZ
otherformats: WMZ IMAGE WMF SVGZ EMZ DXF JPEG2000  TGA PSD DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразовать файл XPS в WMZ через C#" h2="Экспорт XPS в WMZ в приложениях .NET без использования Adobe<sup>&reg;</sup> Acrobat Reader или любых других сторонних приложений." >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total для .NET](https://products.aspose.com/total/net/), вы можете легко экспортировать изображение XPS в WMZ в любых приложениях .NET за два простых шага. Прежде всего, используя [Aspose.PDF для .NET](https://products.aspose.com/pdf/net/), вы можете экспортировать XPS в JPEG. После этого, используя [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) API обработки изображений, вы можете конвертировать JPEG в WMZ.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование файла XPS в WMZ через .NET" %}}
1. Откройте файл XPS, используя класс [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document).
2. Инициализируйте объект класса [JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) и визуализируйте XPS в JPEG с помощью [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) метод
3. Загрузите файл JPEG с помощью класса [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image).
4. Сохраните документ в формате WMZ, используя метод [Сохранить](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование файла XPS в WMZ в один файл с помощью С#" %}}
Используя API, вы также можете преобразовать файл XPS в WMZ в один файл изображения. Чтобы преобразовать все страницы, вы можете сначала преобразовать документ XPS в один файл TIFF, а затем экспортировать файл TIFF в WMZ. Вы можете открыть входной файл с помощью класса [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) и создать объекты устройства Resolution, TiffSettings и TIFF. Вы можете получить одно изображение TIFF, используя метод [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) [TiffDevice](https:// apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Наконец, вы можете загрузить файл TIFF, используя класс [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image).
и сохраните его в формате WMZ, используя метод [Сохранить](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование и поворот файла XPS в WMZ с помощью C#" %}}
Используя API, вы также можете поворачивать выходное изображение WMZ в соответствии с вашими потребностями. Метод Image.RotateFlip можно использовать для поворота изображения на 90/180/270 градусов и отражения изображения по горизонтали или вертикали. Вы можете указать тип поворота и отражения для применения к изображению. Чтобы повернуть и отразить изображение, вы можете загрузить преобразованное изображение JPEG, используя фабричный метод, предоставляемый классом [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image), и вызвать Image .RotateFlip при указании соответствующего [RotateFlipType](https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xps-to-emz/" name="XPS в EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xps-to-tga/" name="XPS в TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xps-to-jpeg2000/" name="XPS в JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xps-to-image/" name="XPS в IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xps-to-psd/" name="XPS в PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xps-to-wmz/" name="XPS в WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xps-to-svgz/" name="XPS в SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xps-to/" name="XPS в" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xps-to-wmf/" name="XPS в WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xps-to-dxf/" name="XPS в DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xps-to-dicom/" name="XPS в DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}