---
title: Преобразование CGM в JPEG2000 через C# API
description: Экспорт CGM в JPEG2000 в ваших приложениях .NET без использования каких-либо сторонних приложений.
url_ignore: /ru/net/conversion/cgm-to-jpeg2000/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: JPEG2000
otherformats: WMF  TGA DXF IMAGE WMZ JPEG2000 PSD SVGZ EMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразовать файл CGM в JPEG2000 через C#" h2="Экспорт CGM в JPEG2000 в приложениях .NET без использования Adobe<sup>&reg;</sup> Acrobat Reader или любых других сторонних приложений." >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total for .NET](https://products.aspose.com/total/net/), вы можете легко экспортировать изображение CGM в JPEG2000 в любых приложениях .NET за два простых шага. Прежде всего, используя [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), вы можете экспортировать CGM в JPEG. После этого, используя [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) API обработки изображений, вы можете конвертировать JPEG в JPEG2000.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование файла CGM в JPEG2000 через .NET" %}}
1. Откройте файл CGM, используя класс [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Инициализируйте объект класса [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) и визуализируйте CGM в JPEG с помощью [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) метод
3. Загрузите файл JPEG с помощью класса [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image).
4. Сохраните документ в формате JPEG2000, используя метод [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование файла CGM в JPEG2000 в один файл с помощью С#" %}}
Используя API, вы также можете преобразовать файл CGM в JPEG2000 в один файл изображения. Чтобы преобразовать все страницы, вы можете сначала преобразовать документ CGM в один файл TIFF, а затем экспортировать файл TIFF в JPEG2000. Вы можете открыть входной файл с помощью класса [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) и создать объекты устройства Resolution, TiffSettings и TIFF. Вы можете получить одно изображение TIFF, используя метод [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Наконец, вы можете загрузить файл TIFF, используя класс [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image).
и сохраните его в формате JPEG2000, используя метод [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование и поворот файла CGM в JPEG2000 с помощью C#" %}}
Используя API, вы также можете поворачивать выходное изображение JPEG2000 в соответствии с вашими потребностями. Метод Image.RotateFlip можно использовать для поворота изображения на 90/180/270 градусов и отражения изображения по горизонтали или вертикали. Вы можете указать тип поворота и отражения для применения к изображению. Чтобы повернуть и отразить изображение, вы можете загрузить преобразованное изображение JPEG, используя фабричный метод, предоставляемый классом [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image), и вызвать Image .RotateFlip при указании соответствующего [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла CGM в JPEG2000: примеры использования" %}}
Файлы CGM (Computer Graphics Metafile) используются для хранения информации по векторным графическим данным, что делает их идеальным выбором для создания статических изображений и иллюстраций. Однако при работе с динамическими данными, такие как JPEG 2000, становятся необходимыми для оптимального сжатия и обеспечения качества.

Приведение файлов CGM в форматы JPEG 2000 позволяет:

**Использования:**  

*   **Высококачественное редактирование изображений**: Преобразование файлов CGM в высококачественные изображения, оптимизация графических данных для веб-использования и обеспечение одинакового брендинга во всех маркетинговых материалах.  

*   **Архивные и сохранение данных**: Использование JPEG 2000 для сжатия и хранения больших наборов изображений, обеспечивая долгосрочное хранение и доступность ценных визуальных данных.  

*   **Медицинское обследование и диагностика**: Преобразование файлов CGM в детализированные, высококачественные медицинские изображения для целей диагностики, снижение ошибок и улучшение результатов лечения.  

*   **Научное исследование и публикации**: Использование JPEG 2000 для сжатия и публикации больших наборов научных изображений, способствующее международной spolupráci и обменом знаниями.  

*   **Цифровые библиотеки и архивы**: Преобразование файлов CGM в масштабируемые, высококачественные цифровые библиотеки, сохранение культурного наследия и исторических артефактов для будущих поколений.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}