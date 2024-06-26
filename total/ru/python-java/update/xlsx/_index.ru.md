---
title: Обновите файл XLSX с помощью Python
description: Измените документ XLSX в приложениях Python без использования Microsoft Excel. 

family: total
platformtag: Python
feature: update
informat: XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Обновите файл XLSX через Python" h2="Изменяйте электронные таблицы XLSX с помощью приложений Python, не устанавливая Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Для разработчика, который пытается обновить файлы XLSX через приложение Python? [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API может помочь автоматизировать процесс обновления. Это полный пакет различных API, работающих с разными форматами, включая файлы Microsoft Excel. ASPOSE.CELL API, который является частью пакета [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/), упрощает этот процесс модификации. Ниже показан процесс обновления документа XLSX.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Как обновить файл XLSX в Python" %}}

- Создайте новый объект класса [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) с исходным файлом XLSX в качестве параметра.
- Доступ к соответствующему рабочему листу с использованием метода [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets)
- Вставьте новые данные в доступную ячейку, используя метод [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)
- Сохраните файл как файл .xlsx, используя метод save(), передав файл с путем в качестве параметра.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к модификации" %}}

- Для модификации XLSX ссылайтесь на API в проекте непосредственно из PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/)).
- Или используйте следующую команду pip ```pip install aspose.cells``` 
- Кроме того, загрузите пакет API из раздела [Загрузки](https://releases.aspose.comcells/python-java).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Код — обновить файл XLSX в Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}