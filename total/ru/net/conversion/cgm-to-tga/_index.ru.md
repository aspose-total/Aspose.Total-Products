---
title: Преобразование CGM в TGA через C# API
description: Экспорт CGM в TGA в ваших приложениях .NET без использования каких-либо сторонних приложений.
url_ignore: /ru/net/conversion/cgm-to-tga/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TGA
otherformats: EMZ TGA SVGZ IMAGE WMF  JPEG2000 WMZ DXF PSD DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразовать файл CGM в TGA через C#" h2="Экспорт CGM в TGA в приложениях .NET без использования Adobe<sup>&reg;</sup> Acrobat Reader или любых других сторонних приложений." >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total for .NET](https://products.aspose.com/total/net/), вы можете легко экспортировать изображение CGM в TGA в любых приложениях .NET за два простых шага. Прежде всего, используя [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), вы можете экспортировать CGM в JPEG. После этого, используя [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) API обработки изображений, вы можете конвертировать JPEG в TGA.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование файла CGM в TGA через .NET" %}}
1. Откройте файл CGM, используя класс [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Инициализируйте объект класса [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) и визуализируйте CGM в JPEG с помощью [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) метод
3. Загрузите файл JPEG с помощью класса [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image).
4. Сохраните документ в формате TGA, используя метод [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование файла CGM в TGA в один файл с помощью С#" %}}
Используя API, вы также можете преобразовать файл CGM в TGA в один файл изображения. Чтобы преобразовать все страницы, вы можете сначала преобразовать документ CGM в один файл TIFF, а затем экспортировать файл TIFF в TGA. Вы можете открыть входной файл с помощью класса [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) и создать объекты устройства Resolution, TiffSettings и TIFF. Вы можете получить одно изображение TIFF, используя метод [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Наконец, вы можете загрузить файл TIFF, используя класс [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image).
и сохраните его в формате TGA, используя метод [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование и поворот файла CGM в TGA с помощью C#" %}}
Используя API, вы также можете поворачивать выходное изображение TGA в соответствии с вашими потребностями. Метод Image.RotateFlip можно использовать для поворота изображения на 90/180/270 градусов и отражения изображения по горизонтали или вертикали. Вы можете указать тип поворота и отражения для применения к изображению. Чтобы повернуть и отразить изображение, вы можете загрузить преобразованное изображение JPEG, используя фабричный метод, предоставляемый классом [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image), и вызвать Image .RotateFlip при указании соответствующего [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла CGM в TGA: примеры использования" %}}
Переведение файлов CGM (Computer Graphics Metafile) в форматы TGA (Truevision TGA Image File) открывает мир креативных возможностей, делая их идеальными для различных приложений. Однако при работе с динамической контентцией редакторы изображений, такие как GIMP, становятся необходимостью для редактирования и манипуляции.

Переход файлов CGM в форматы TGA позволяет раскрыть полную функциональность вашего редакторского потенциала. Это преобразование позволяет:

**Примеры применения:**

*   **Редактирование изображений**: Переводить файлы CGM для редактирования изображений, корректировки яркости, контрастности и насыщенности.
*   **Графическое дизайн**: Использовать TGA для создания и манипуляции графикой, логотипами, иконками и другими визуальными элементами.
*   **Цифровое живопись**: Переводить файлы CGM для цифрового живописия, создавая яркие работы с широким спектром цветов и эффектов.
*   **Визуализация архитектуры**: Использовать TGA для визуализации 3D моделей, создавая фотореалистичные изображения для архитекторов, дизайнеров и строителей.
*   **Анализ медицинской имагинacji**: Переводить файлы CGM для анализа медицинской имагинации, исследуя детализированные изображения органов, тканей и клеток.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}