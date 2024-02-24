---
title: Преобразование формата JSON в EMZ через .NET
description: Разбирать JSON в EMZ на C# без использования сторонних зависимостей
url_ignore: /ru/net/conversion/json-to-emz/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: EMZ
otherformats: IMAGE TGA SVGZ JPEG2000 EMZ DXF WMZ WMF DICOM PSD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование формата JSON в EMZ через C#" h2="C# API для анализа JSON в EMZ без использования сторонних зависимостей" >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total for .NET](https://products.aspose.com/total/net/), вы можете преобразовать JSON в EMZ в любом приложении .NET, C#, ASP.NET и VB.NET двумя простыми способами. шаги. Во-первых, с помощью [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) вы можете экспортировать JSON в JPEG. После этого, используя [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/), вы можете конвертировать JPEG в EMZ.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование формата JSON в EMZ через C#" %}}
1. Создайте новый объект [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) и прочитайте данные JSON из файла
2. Преобразуйте JSON в JPEG, используя метод [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4).
3. Загрузите документ JPEG с помощью класса [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image).
4. Сохраните документ в формате EMZ, используя метод [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "parse-json-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Установить макет и преобразовать формат JSON в EMZ через С#" %}}
При синтаксическом анализе JSON в EMZ вы также можете установить параметры макета для вашего JSON с помощью [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Он позволяет обрабатывать массив как таблицу, игнорировать нули, игнорировать заголовок массива, игнорировать заголовок объекта, преобразовывать строку в число или дату, устанавливать формат даты и числа и устанавливать стиль заголовка. Все эти параметры позволяют вам представить ваши данные в соответствии с вашими потребностями. В следующем фрагменте кода показано, как установить параметры макета.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "set-layout-and-parse-json-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Разобрать формат JSON в EMZ с водяным знаком" %}}
Используя API, вы также можете конвертировать JSON в EMZ с водяным знаком в документе EMZ. Чтобы добавить водяной знак, вы можете сначала преобразовать документ JSON в JPEG и добавить в него водяной знак. Чтобы продемонстрировать операцию, вы можете загрузить преобразованное изображение JPEG, добавить преобразования с помощью объекта класса Matrix и нарисовать строку в качестве водяного знака на поверхности изображения с помощью [Graphics](https://reference.aspose.com/imaging/ net/aspose.imaging/graphics) класс» метод [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring). После добавления к нему водяного знака вы можете сохранить JPEG в формате EMZ. Ниже приведен пример кода, демонстрирующий, как добавить в документ диагональный водяной знак. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "convert-json-to-image-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}