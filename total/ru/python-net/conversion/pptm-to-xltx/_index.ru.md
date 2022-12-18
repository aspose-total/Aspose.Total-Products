---
title: Преобразование PPTM в XLTX с помощью Python
description: Преобразование PPTM в XLTX в ваших приложениях Python без использования Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: PPTM
outformat: XLTX
otherformats: Excel XLS XLSX XLSB XLTX XLTM XLSM CSV TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование PPTM в XLTX через Python" h2="Преобразование PPTM в XLTX в приложениях Python без установки Microsoft PowerPoint<sup>&reg;</sup> или Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

Для разработчика Python, который пытается добавить в приложение функцию преобразования PPTM в XLTX. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API может помочь автоматизировать процесс конвертации. Это полный пакет различных API, работающих с различными форматами, включая файлы PPTM и XLTX.

Это в основном в два этапа. Сначала используйте API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) для преобразования файла PPTM в HTML. После этого, используя Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), сохраните созданный HTML в желаемом формате Microsoft Excel. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Как конвертировать PPTM в XLTX в Python" %}}
- **Шаг 1** Используйте экземпляр класса [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/), чтобы открыть исходный файл PPTM. 
- Сохраните файл PPTM в HTML, используя метод [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/), указав имя файла и желаемый путь к каталогу.
-  **Шаг 2** Загрузить файл HTML с экземпляром класса Workbook
-  Вызовите метод `save`, указав путь к выходному файлу XLTX. Таким образом, ваш файл PPTM преобразуется в XLTX по указанному пути.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}

- Для преобразования PPTM в XLTX требуется Python 3.5 или более поздней версии.
- Справочные API внутри проекта непосредственно из PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) и [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Или используйте следующие команды pip ```pip install aspose.slides``` и ```pip install aspose-cells-python```
-  Кроме того, ОС на базе Microsoft Windows или Linux (подробнее см. [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) и [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Сохранение PPTM в HTML в Python — шаг 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "convert-microsoft-powerpoint-presentations-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Сохранение HTML в XLTX в Python — шаг 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "html-documents-to-excel-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}