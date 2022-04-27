---
title: Преобразование формата JSON в PPT через .NET
description: Разбор JSON в PPT на C# без использования Microsoft PowerPoint
url: /ru/net/conversion/json-to-ppt/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPT
otherformats: PPSM POT POTM PPS OTP POWERPOINT PPTM PPT PPSX POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование формата JSON в PPT через C#" h2="C# API для преобразования JSON в PPT без использования Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Вы можете преобразовать JSON в PPT в любом приложении .NET, C#, ASP.NET и VB.NET, выполнив два простых шага. Во-первых, с помощью [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) вы можете преобразовать JSON в PPTX. После этого, используя [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), вы можете конвертировать PPTX в PPT. Оба API входят в пакет [Aspose.Total for .NET](https://products.aspose.com/total/net/).
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование формата JSON в PPT через C#" %}}
1. Создайте новый объект [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) и прочитайте действительные данные JSON из файла.
2. Импортируйте файл JSON на лист, используя класс [JsonUtility](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonutility) и [Сохранить](https://apireference.aspose.com/ ячейки/net/aspose.cells.workbook/save/methods/4) это как PPTX
3. Загрузите документ PPTX с помощью класса [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation).
4. Сохраните документ в формате PPT, используя метод [Сохранить](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Установить макет и преобразовать формат JSON в PPT через С#" %}}
При синтаксическом анализе JSON в PPT вы также можете установить параметры макета для вашего формата JSON, используя [JsonLayoutOptions](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Он позволяет обрабатывать массив как таблицу, игнорировать нули, игнорировать заголовок массива, игнорировать заголовок объекта, преобразовывать строку в число или дату, устанавливать формат даты и числа и устанавливать стиль заголовка. Все эти параметры позволяют вам представить ваши данные в соответствии с вашими потребностями. В следующем фрагменте кода показано, как установить параметры макета.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "set-layout-and-parse-json-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование формата JSON в PPT с водяным знаком" %}}
Используя API, вы также можете конвертировать JSON в PPT с водяным знаком. Чтобы добавить водяной знак в документ PPT, вы можете сначала преобразовать JSON в PPTX и добавить к нему водяной знак. Чтобы добавить водяной знак, загрузите вновь созданный файл PPTX с помощью класса [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation), выберите основную презентацию, добавьте тип формы с помощью AddAutoShape и добавьте текст водяного знака с помощью AddTextFrame. После добавления водяного знака вы можете сохранить документ в PPT. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-ppt/" name="JSON в PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-otp/" name="JSON в OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-ppsx/" name="JSON в PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-powerpoint/" name="JSON в POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-potm/" name="JSON в POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-pot/" name="JSON в POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-ppsm/" name="JSON в PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-potx/" name="JSON в POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-pptm/" name="JSON в PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-pps/" name="JSON в PPS" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}