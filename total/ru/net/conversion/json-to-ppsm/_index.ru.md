---
title: Преобразование формата JSON в PPSM через .NET
description: Разбор JSON в PPSM на C# без использования Microsoft PowerPoint
url_ignore: /ru/net/conversion/json-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPSM
otherformats: POTM PPS PPSM POWERPOINT POT OTP PPT POTX PPTM PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование формата JSON в PPSM через C#" h2="C# API для преобразования JSON в PPSM без использования Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Вы можете преобразовать JSON в PPSM в любом приложении .NET, C#, ASP.NET и VB.NET, выполнив два простых шага. Во-первых, с помощью [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) вы можете преобразовать JSON в PPTX. После этого, используя [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), вы можете конвертировать PPTX в PPSM. Оба API входят в пакет [Aspose.Total for .NET](https://products.aspose.com/total/net/).
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование формата JSON в PPSM через C#" %}}
1. Создайте новый объект [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) и прочитайте действительные данные JSON из файла.
2. Импортируйте файл JSON на лист, используя класс [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) и [Save](https://reference.aspose.com/ ячейки/net/aspose.cells.workbook/save/methods/4) это как PPTX
3. Загрузите документ PPTX с помощью класса [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation).
4. Сохраните документ в формате PPSM, используя метод [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Установить макет и преобразовать формат JSON в PPSM через С#" %}}
При синтаксическом анализе JSON в PPSM вы также можете установить параметры макета для вашего формата JSON, используя [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Он позволяет обрабатывать массив как таблицу, игнорировать нули, игнорировать заголовок массива, игнорировать заголовок объекта, преобразовывать строку в число или дату, устанавливать формат даты и числа и устанавливать стиль заголовка. Все эти параметры позволяют вам представить ваши данные в соответствии с вашими потребностями. В следующем фрагменте кода показано, как установить параметры макета.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "set-layout-and-parse-json-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование формата JSON в PPSM с водяным знаком" %}}
Используя API, вы также можете конвертировать JSON в PPSM с водяным знаком. Чтобы добавить водяной знак в документ PPSM, вы можете сначала преобразовать JSON в PPTX и добавить к нему водяной знак. Чтобы добавить водяной знак, загрузите вновь созданный файл PPTX с помощью класса [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation), выберите основную презентацию, добавьте тип формы с помощью AddAutoShape и добавьте текст водяного знака с помощью AddTextFrame. После добавления водяного знака вы можете сохранить документ в PPSM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}