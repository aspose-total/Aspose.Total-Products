---
title: Преобразование PPTX в XLSX с помощью Python
description: Преобразование PPTX в XLSX в ваших приложениях Python без использования Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: PPTX
outformat: XLSX
otherformats: Excel XLS XLSX XLSB XLTX XLTM XLSM CSV TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование PPTX в XLSX через Python" h2="Преобразование PPTX в XLSX в приложениях Python без установки Microsoft PowerPoint<sup>&reg;</sup> или Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

Для разработчика Python, который пытается добавить в приложение функцию преобразования PPTX в XLSX. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API может помочь автоматизировать процесс конвертации. Это полный пакет различных API, работающих с различными форматами, включая файлы PPTX и XLSX.

Это в основном в два этапа. Сначала используйте API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) для преобразования файла PPTX в HTML. После этого, используя Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), сохраните созданный HTML в желаемом формате Microsoft Excel. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Как конвертировать PPTX в XLSX в Python" %}}
- **Шаг 1** Используйте экземпляр класса [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/), чтобы открыть исходный файл PPTX. 
- Сохраните файл PPTX в HTML, используя метод [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/), указав имя файла и желаемый путь к каталогу.
-  **Шаг 2** Загрузить файл HTML с экземпляром класса Workbook
-  Вызовите метод `save`, указав путь к выходному файлу XLSX. Таким образом, ваш файл PPTX преобразуется в XLSX по указанному пути.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}

- Для преобразования PPTX в XLSX требуется Python 3.5 или более поздней версии.
- Справочные API внутри проекта непосредственно из PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) и [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Или используйте следующие команды pip ```pip install aspose.slides``` и ```pip install aspose-cells-python```
-  Кроме того, ОС на базе Microsoft Windows или Linux (подробнее см. [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) и [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Сохранение PPTX в HTML в Python — шаг 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "convert-microsoft-powerpoint-presentations-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Сохранение HTML в XLSX в Python — шаг 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "html-documents-to-excel-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}