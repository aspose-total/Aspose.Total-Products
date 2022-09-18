---
title: Преобразование PPTX в DOCM в Python
description: Преобразование PPTX в DOCM в ваших приложениях Python без использования Microsoft Word или PowerPoint 
url: /ru/python-net/conversion/pptx-to-docm/
family: total
platformtag: Python
feature: conversion
informat: PPTX
outformat: DOCM
otherformats: Word DOC DOT DOCX DOCM DOTX DOTM RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование PPTX в DOCM с помощью Python" h2="Преобразование PPTX в DOCM в приложениях Python без установки Microsoft Word<sup>&reg;</sup> или PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Для разработчика Python, который пытается добавить функцию преобразования PPTX в DOCM в приложение? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API может помочь автоматизировать процесс конвертации. Это полный пакет различных API, работающих с разными форматами. Так **Как преобразовать PPTX в DOCM в Python?**

Это в основном в два этапа. Сначала используйте API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) для преобразования файла PPTX в PDF. После этого с помощью Microsoft Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) сохраните созданный PDF-файл в Microsoft Word в формате DOCM. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование PPTX в DOCM в Python" %}}
-  **Шаг 1** Загрузите файл PDF с экземпляром класса [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/).
-  Вызовите метод `save`, указав путь к выходному файлу и SaveFormat.PDF в качестве параметров. Таким образом, ваш файл PPTX преобразуется в PDF по указанному пути.
- **Шаг 2** Откройте файл PDF с помощью класса [Document](https://reference.aspose.com/words/python-net/aspose.words/document/).
- Сохраните файл PDF в файл DOCM, используя метод [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/), указав имя файла и желаемый путь к каталогу.
- Вот еще один фрагмент кода для преобразования презентации PowerPoint в Word (Microsoft Powerpoint to Word)[https://products.aspose.com/total/python-net/conversion/].

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}

- Для преобразования PPTX в DOCM требуется Python 3.5 или более поздней версии.
- Ссылочные API внутри проекта непосредственно из PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) и [Aspose.Words](https://pypi.org/project/aspose-words/)) или
- Используйте следующие команды pip ```pip install aspose.slides``` и ```pip install aspose.words```. Более того,
- ОС на базе Microsoft Windows или Linux (дополнительную информацию см. в [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) и [Words](https://docs.aspose.com/words/python-net/system-requirements/)) и для Linux проверьте дополнительные требования для gcc и libpython и следуйте пошаговым инструкциям [INSTALL](https://docs.aspose.com/words/python-net/installation/).
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Сохранение PPTX в PDF на Python — шаг 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-powerpoint-slides-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Сохранить PDF в DOCM в Python — шаг 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-files-to-microsoft-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}