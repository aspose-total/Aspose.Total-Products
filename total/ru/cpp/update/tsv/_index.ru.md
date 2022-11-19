---
title: Обновите файл TSV с помощью C++
description: Изменение документа TSV в приложениях C++ без использования Microsoft Excel.
family: total
platformtag: C++
feature: update
informat: TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Обновите файл TSV через C++" h2="Изменяйте электронные таблицы TSV с помощью приложений на основе C++, не устанавливая Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Для программиста, который пытается обновить файлы TSV в приложении C++, [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API может помочь автоматизировать процесс обновления. Это полный пакет различных библиотек C++, работающих с несколькими форматами, включая документы Microsoft Excel. [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API, который является частью пакета [Aspose.Total for C++](https://products.aspose.com/total/cpp/), упрощает этот процесс модификации. Процесс обновления документа TSV прост: сначала нужно получить доступ к листу, а затем обновить значение ячейки в Excel с помощью C++.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Как обновить файл TSV в C++" %}}

- Загрузите файл TSV, используя [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8)
- Доступ к соответствующему [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) с использованием GetIWorksheets()->GetObjectByIndex(0) и соответствующей ячейке с использованием GetICells()->GetObjectByIndex
- Вставьте новые данные в доступную ячейку, используя метод PutValue.
- Сохраните файл как файл .tsv, используя метод «Сохранить», передав файл с путем в качестве параметра.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к модификации" %}}

- Для модификации TSV следуйте [Системные Требования](https://docs.aspose.com/cells/cpp/system-requirements/) для систем Windows и Linux. 
- Установите из командной строки как ```nuget install Aspose.Total.Cpp```
- Или через консоль диспетчера пакетов Visual Studio с ```Install-Package Aspose.Total.Cpp```
- Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [Загрузки](https://downloads.aspose.com/cells/cpp).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Код — обновить файл TSV в C++" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты модификации" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/update/xls/" name="Обновлять XLS Файл" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/update/xlsx/" name="Обновлять XLSX Файл" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/update/csv/" name="Обновлять CSV Файл" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/update/xlsb/" name="Обновлять XLSB Файл" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/update/xlsm/" name="Изменить XLSM Файл" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/update/xlt/" name="Обновлять XLT Файл" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/update/xltx/" name="Обновлять XLTX Файл" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/update/xltm/" name="Обновлять XLTM Файл" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/update/tsv/" name="Обновлять TSV Файл" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}