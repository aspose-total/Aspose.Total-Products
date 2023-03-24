---
title: Обновите файл XLSB с помощью C++
description: Изменение документа XLSB в приложениях C++ без использования Microsoft Excel.
family: total
platformtag: C++
feature: update
informat: XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Обновите файл XLSB через C++" h2="Изменяйте электронные таблицы XLSB с помощью приложений на основе C++, не устанавливая Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Для программиста, который пытается обновить файлы XLSB в приложении C++, [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API может помочь автоматизировать процесс обновления. Это полный пакет различных библиотек C++, работающих с несколькими форматами, включая документы Microsoft Excel. [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API, который является частью пакета [Aspose.Total for C++](https://products.aspose.com/total/cpp/), упрощает этот процесс модификации. Процесс обновления документа XLSB прост: сначала нужно получить доступ к листу, а затем обновить значение ячейки в Excel с помощью C++.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Как обновить файл XLSB в C++" %}}

- Загрузите файл XLSB, используя [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8)
- Доступ к соответствующему [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) с использованием GetIWorksheets()->GetObjectByIndex(0) и соответствующей ячейке с использованием GetICells()->GetObjectByIndex
- Вставьте новые данные в доступную ячейку, используя метод PutValue.
- Сохраните файл как файл .xlsb, используя метод «Сохранить», передав файл с путем в качестве параметра.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к модификации" %}}

- Для модификации XLSB следуйте [Системные Требования](https://docs.aspose.com/cells/cpp/system-requirements/) для систем Windows и Linux. 
- Установите из командной строки как ```nuget install Aspose.Total.Cpp```
- Или через консоль диспетчера пакетов Visual Studio с ```Install-Package Aspose.Total.Cpp```
- Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [Загрузки](https://releases.aspose.comcells/cpp).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Код — обновить файл XLSB в C++" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}