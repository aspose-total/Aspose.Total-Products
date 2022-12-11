---
title: Преобразование XLTM в DOTM с помощью Python
description: Преобразование XLTM в DOTM в ваших приложениях Python без использования Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: XLTM
outformat: DOTM
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование XLTM в DOTM через Python" h2="Преобразование XLTM в DOTM в приложениях Python без установки Microsoft Excel<sup>&reg;</sup> или Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

Для разработчика Python, который пытается добавить в приложение функцию преобразования XLTM в DOTM. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API может помочь автоматизировать процесс конвертации. Это полный пакет различных API, работающих с различными форматами, включая файлы XLTM и DOTM.

Это в основном в два этапа. Сначала используйте API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) для преобразования файла XLTM в HTML. После этого с помощью Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) сохраните созданный HTML в желаемом формате Microsoft Word. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Как конвертировать XLTM в DOTM в Python" %}}
- **Шаг 1** Откройте исходный файл XLTM, используя класс Workbook.
- Сохраните файл XLTM в HTML, используя метод save(file, SaveFormat.HTML), указав имя файла и желаемый путь к каталогу.
-  **Шаг 2** Загрузить файл HTML с экземпляром класса [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
-  Вызовите метод `save`, указав путь к выходному файлу DOTM. Таким образом, ваш файл XLTM преобразуется в DOTM по указанному пути.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}

- Для преобразования XLTM в DOTM требуется Python 3.5 или более поздней версии.
- Справочные API внутри проекта непосредственно из PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) и [Aspose.Words](https://pypi.org/project/aspose-words/))
-  Или используйте следующие команды pip ```pip install aspose-cells-python``` и ```pip install aspose.words```
-  Кроме того, для ОС на базе Microsoft Windows или Linux (дополнительную информацию см. в [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) и [Words](https://docs.aspose.com/words/python-net/system-requirements/)) и для Linux проверьте дополнительные требования для gcc и libpython и выполните [пошаговые инструкции](https://docs.aspose.com/words/python-net/installation/).
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Сохранение XLTM в HTML в Python — шаг 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Сохранение HTML в DOTM в Python — шаг 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}