---
title: C++ API для преобразования SVG в XLSM
description: Преобразование SVG в XLSM через C++ API без использования Microsoft Excel или Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: SVG
outformat: XLSM
otherformats: XLTM CSV XLT ODS FODS XLAM MD DIF TSV XLTX XLSB EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Рендеринг SVG в XLSM в приложениях C++" h2="Преобразование SVG в XLSM в собственных приложениях C++ без использования Microsoft<sup>&reg;</sup> Excel или Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Преобразование SVG в XLSM в C++ с помощью библиотек автоматизации форматов файлов [Aspose.Total for C++](https://products.aspose.com/total/cpp/) представляет собой простой двухэтапный процесс. На первом этапе вы можете экспортировать SVG в XLSX с помощью [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), после этого с помощью [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API программирования электронных таблиц, вы можете конвертировать XLSX в XLSM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API для преобразования SVG в XLSM" %}}
1. Откройте файл SVG, используя ссылку на класс [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document).
2. Преобразуйте SVG в XLSX с помощью функции-члена [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db).
3. Загрузите документ XLSX, используя ссылку на класс [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
4. Сохраните документ в формате XLSM, используя функцию-член [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Установите из командной строки как ```nuget install Aspose.Total.Cpp``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total.Cpp```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://releases.aspose.comtotal/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Получить или установить информацию о файле SVG через C++" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) также позволяет вам получить информацию о вашем документе SVG и позволяет принимать обоснованные решения до процесса преобразования. Чтобы получить информацию о файле SVG, вам сначала нужно вызвать метод [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document). После извлечения объекта DocumentInfo вы можете получить значения отдельных свойств. Кроме того, вы также можете установить свойства, используя соответствующие методы класса DocumentInfo.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Сохранить формат файла XLSM для потоковой передачи через C++" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/) позволяет сохранять формат файла XLSM для потоковой передачи. Чтобы сохранить файлы в потоке, создайте объект MemoryStream или FileStream и сохраните файл в этом объекте потока, вызвав [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) объекта. Укажите нужный формат файла, используя перечисление [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) при вызове метода Save.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-xlsm-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}