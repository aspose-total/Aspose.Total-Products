---
title: Обновление файлов Excel с помощью .NET 

description: Редактируйте документы Microsoft Excel XLSX, XLS, CSV без установки Microsoft Office с приложениями на основе C# .NET.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Обновление документов Excel через .NET" h2="Изменяйте файлы Microsoft Excel XLSX, XLS в приложениях на основе .NET без установки Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Организации часто обновляют свои данные, хранящиеся в файлах Excel, таких как данные студентов, записи пациентов, список складских товаров и т. Д., С помощью программного обеспечения компании. API [Aspose.Total for .NET](https://products.aspose.com/total/net/) предоставляет возможность изменения электронных таблиц с помощью программного обеспечения. Программисты могут улучшить программное обеспечение с помощью возможностей модификации, просто написав несколько строк кода API. API [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), являющийся частью пакета [Aspose.Total for .NET](https://products.aspose.com/total/net/), упрощает процесс модификации. Ниже показан процесс обновления документа Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Обновление документов Excel с помощью .NET" %}}

API [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) предоставляет класс Workbook, который обрабатывает загрузку электронных таблиц Excel. Процесс прост. Создайте объект [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook/), указав исходный файл в качестве параметра. Получите доступ к соответствующему рабочему листу, указав его индекс, используя метод [Worksheets[0].Cells[column]](https://reference.aspose.com/cells/net/aspose.cells/worksheet/cells/). Используйте метод [PutValue(data)](https://reference.aspose.com/cells/net/aspose.cells/cell/putvalue/) для изменения содержимого в доступной ячейке и, наконец, вызовите метод save() для сохранения документа.

{{% blocks/products/pf/feature-page-code h3=".NET Code — Обновление документов Excel" %}}

{{< gist "aspose-com-gists" "800f8b626c3129d4682bc58338b93ecc" "update-excel-file-using-net.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Обновлять">}}