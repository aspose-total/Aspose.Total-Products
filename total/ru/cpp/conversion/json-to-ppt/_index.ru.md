---
title: Преобразование формата JSON в PPT через C++
description: Разбор JSON в PPT на C++ без использования Microsoft PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: PPT
otherformats: OTP PPSM PPSX POTM PPTM POT ODP PPS POWERPOINT POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование формата JSON в PPT через C++" h2="C++ API для преобразования JSON в PPT без использования Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Вы можете преобразовать JSON в PPT в любом приложении C++, выполнив два простых шага. Во-первых, с помощью [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) вы можете преобразовать JSON в PPTX. После этого, используя [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), вы можете конвертировать PPTX в PPT. Оба API входят в пакет [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование формата JSON в PPT через C++" %}}
1. Создайте новый объект [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) и прочитайте действительные данные JSON из файла.
2. Сохраните JSON как PPTX, используя метод [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997).
3. Загрузите документ PPTX с помощью класса [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation).
4. Сохраните документ в формате PPT, используя метод [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Установите через консоль диспетчера пакетов Visual Studio с помощью Install-Package Aspose.Total.Cpp.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://releases.aspose.comtotal/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Установить макет и преобразовать формат JSON в PPT через C++" %}}
При синтаксическом анализе JSON в PPT вы также можете установить размер строк и столбцов, загрузив JSON с классом [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Если вам нужно установить одинаковую высоту строки для всех строк на листе, вы можете сделать это с помощью [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) метод коллекции [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). Точно так же, чтобы установить одинаковую ширину столбца для всех столбцов на листе, используйте метод [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) коллекции ICells.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование формата JSON в PPT с водяным знаком на C++" %}}
Используя API, вы также можете конвертировать JSON в PPT с водяным знаком. Чтобы добавить водяной знак в документ PPT, вы можете сначала преобразовать JSON в PPTX и добавить к нему водяной знак. Чтобы добавить водяной знак, загрузите только что созданный файл PPTX с помощью класса [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation), получите первый слайд, добавьте AutoShape типа Rectangle, добавьте TextFrame в Rectangle, создайте объект Paragraph для текстового фрейма, создайте объект Partion для абзаца, добавьте водяной знак с помощью set_Text() и можете сохранить документ в PPT.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}