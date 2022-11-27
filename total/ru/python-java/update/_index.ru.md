---
title: Обновите файлы Excel с помощью Python 

description: Редактируйте документы Microsoft Excel XLSX, XLS, CSV без установки Microsoft Office в приложениях Python.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Обновление документов Excel через Python" h2="Изменяйте файлы Microsoft Excel XLSX, XLS в приложениях Python без установки Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Организации часто обновляют свои данные, хранящиеся в файлах Excel, таких как данные студентов, записи пациентов, список складских товаров и т. Д., С помощью программного обеспечения компании. API [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) предоставляет возможность изменять электронные таблицы с помощью программного обеспечения. Программисты могут улучшить программное обеспечение с помощью возможностей модификации, интегрировав API и написав несколько строк кода. [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API, который является частью пакета [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/), упрощает этот процесс модификации. Ниже показан процесс обновления документа Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Обновление документов Excel с помощью Python" %}}

API [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) предоставляет класс Workbook, который обрабатывает загрузку электронных таблиц Excel. Процесс прост. Создайте объект класса [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook), указав исходный файл в качестве параметра. Используйте метод [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets) для доступа к соответствующему рабочему листу, указав его индекс. вызовите метод [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells), чтобы изменить содержимое в доступной ячейке, и, наконец, вызовите метод save() для сохранения документа.

{{% blocks/products/pf/feature-page-code h3="Python — обновление документов Excel" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Обновлять">}}