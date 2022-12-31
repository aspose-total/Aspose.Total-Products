---
title: Преобразование TSV в PPTX с помощью Python
description: Преобразование TSV в PPTX в ваших приложениях Python без использования Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: TSV
outformat: PPTX
otherformats: PowerPoint PPT PPTX PPS POT PPSX PPTM PPSM POTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование TSV в PPTX через Python" h2="Преобразование TSV в PPTX в приложениях Python без установки Microsoft Excel<sup>&reg;</sup> или PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Для разработчика Python, который пытается добавить в приложение функцию преобразования TSV в PPTX., [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API может помочь автоматизировать процесс конвертации. Это полный пакет различных API, работающих с различными форматами, включая файлы TSV и PPTX..

Это в основном в два этапа. Сначала используйте API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) для преобразования файла TSV в PDF.. После этого с помощью PowerPoint Python API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) сохраните созданный PDF-файл в желаемом формате Microsoft PowerPoint.. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Как конвертировать TSV в PPTX в Python" %}}
- **Шаг 1** Используйте экземпляр класса Workbook, чтобы открыть исходный файл TSV. 
- Сохраните файл TSV в PDF, используя метод save, указав имя файла и желаемый путь к каталогу.
-  **Шаг 2** Загрузите файл PDF, используя класс [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)
-  Вызовите метод [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/), указав путь к выходному файлу PPTX.. Таким образом, ваш файл TSV преобразуется в PPTX по указанному пути.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}

- Для преобразования TSV в PPTX требуется Python 3.5 или более поздней версии.
- Справочные API внутри проекта непосредственно из PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) и [Aspose.Slides](https://pypi.org/project/Aspose.Slides/))
-  Или используйте следующие команды pip ```pip install aspose-cells-python``` и ```pip install aspose.slides```
-  Кроме того, ОС на базе Microsoft Windows или Linux (подробнее см. [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) и [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Сохранение TSV в PDF на Python — шаг 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "convert-microsoft-excel-file-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Сохранить PDF в PPTX в Python — шаг 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "pdf-documents-to-powerpoint-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}