---
title: Создание и обновление файлов Microsoft Excel с помощью Python 
url: /ru/python-java/create/
description: Создавайте отчеты на листах Microsoft Excel без установки Microsoft Office 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Создание отчетов Excel с использованием Python" h2="Создавайте и обновляйте электронные таблицы Microsoft Excel, документы XLS, XLSX в приложениях Python без установки Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) — это API Python для создания, чтения и записи документов в форматах Microsoft Excel, включая XLS и XLSX. Этот API является частью пакета [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/). Кроме того, Develpors может легко написать код для вставки данных, изображений, диаграмм, сводных таблиц в рабочие листы и многих других функций. Python API также поддерживает такие функции, как установка различных [Формулы](https://docs.aspose.com/cells/python-java/supported-formula-functions/), преобразование текста в столбцы, смарт-маркер и параметры динамической формулы. Ниже приведены несколько примеров кода для создания и изменения электронных таблиц.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Как создавать файлы Excel с помощью Python" %}}

API [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) предоставляет класс Workbook, который обрабатывает создание файлов. Процесс прост. Создайте объект класса Workbook и получите доступ к соответствующему рабочему листу, указав его индекс. Используйте метод putValue, чтобы добавить содержимое в доступную ячейку, и, наконец, вызовите метод save(), чтобы сохранить документ с определенным именем.

{{% blocks/products/pf/feature-page-code h3="Код 1 — создать простой файл Excel" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="Код 2 — вставка изображений в документы Microsoft Excel" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Как обновить файлы Microsoft Excel с помощью Python" %}}

Процесс создания и обновления файла Excel почти такой же, за исключением единственной разницы. Разница в том, что в процессе создания создается объект «Пустая рабочая книга», а в процессе обновления требуется существующий файл Excel. Поэтому передайте существующий файл в качестве параметра классу Workbook. В остальном процедура такая же

{{% blocks/products/pf/feature-page-code h3="Код 3 — Обновление документов Microsoft Excel" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}