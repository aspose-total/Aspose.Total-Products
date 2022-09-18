---
title: Преобразование MD в PPSX в Python
description: Преобразование MD в PPSX в ваших приложениях Python без использования Microsoft Word или PowerPoint 
url: /ru/python-net/conversion/md-to-ppsx/
family: total
platformtag: Python
feature: conversion
informat: MD
outformat: PPSX
otherformats: PowerPoint PPSX PPTX PPT POT POTX POTM PPTM PPSM PPS ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование MD в PPSX с помощью Python" h2="Преобразование MD в PPSX в приложениях Python без установки Microsoft Word<sup>&reg;</sup> или PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Для разработчика Python, который пытается добавить функцию преобразования MD в PPSX в приложение? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API может помочь автоматизировать процесс конвертации. Это полный пакет различных API, работающих с разными форматами. Так **Как преобразовать MD в PPSX в Python?**

Это в основном в два этапа. Сначала используйте API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) для преобразования файла MD в PDF. После этого с помощью PowerPoint API Python [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) сохраните созданный PDF-файл в презентацию в формате PPSX. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование MD в PPSX в Python" %}}
- **Шаг 1** Откройте исходный файл MD, используя класс [Document](https://reference.aspose.com/words/python-net/aspose.words/document/).
- Сохраните файл MD в PDF, используя метод [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/), указав имя файла и путь к нужному каталогу.
-  **Шаг 2** Загрузите файл PDF с экземпляром класса [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/).
-  Вызовите метод `save`, указав путь к выходному файлу и SaveFormat.PPSX в качестве параметров. Таким образом, ваш файл MD преобразуется в PPSX по указанному пути.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}

- Для преобразования MD в PPSX требуется Python 3.5 или более поздней версии.
- Ссылочные API внутри проекта непосредственно из PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) и [Aspose.Words](https://pypi.org/project/aspose-words/)) или
- Используйте следующие команды pip ```pip install aspose.slides``` и ```pip install aspose.words```. Более того,
- ОС на базе Microsoft Windows или Linux (дополнительную информацию см. в [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) и [Words](https://docs.aspose.com/words/python-net/system-requirements/)) и для Linux проверьте дополнительные требования для gcc и libpython и следуйте пошаговым инструкциям [INSTALL](https://docs.aspose.com/words/python-net/installation/).
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Сохранение MD в PDF на Python — шаг 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-microsoft-word-documents-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Сохранить PDF в PPSX в Python — шаг 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-pdf-files-to-powerpoint-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}