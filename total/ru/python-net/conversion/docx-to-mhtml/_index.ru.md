---
title: Преобразование DOCX в MHTML в Python
description: Формат веб-архива DOCX в mhtml и преобразование файлов HtmlFixed в ваших приложениях Python без использования Microsoft Word 

family: total
platformtag: Python
feature: conversion
informat: DOCX
outformat: MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование DOCX в MHTML с помощью Python" h2="Преобразование DOCX в MHTML, HtmlFixed и HTML в приложениях Python без установки Microsoft Word<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Для разработчика Python, который пытается добавить функцию преобразования DOCX в MHTML (формат веб-архива) или HtmlFixed, означает, что он хочет сохранить документ в формате HTML, используя абсолютно позиционированные элементы в приложении. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API может помочь автоматизировать процесс конвертации. Это полный пакет различных API, работающих с разными форматами. 

Мы используем API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/), который является частью пакета [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/), чтобы добавить функцию преобразования DOCX в MHTML. Если файл DOCX простой, то это всего две строки кода. Загрузите файл DOCX и вызовите метод сохранения с соответствующим путем к файлу вместе с перечислением SaveFormat как MHTML или HTML_FIXED. Но в случае, если есть необходимость восстановить модель документа максимально приближенную к исходной, необходимо сохранить некоторую дополнительную информацию в результирующем документе, называемую круговой информацией.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Как Преобразование DOCX в MHTML в Python" %}}
- Загрузите исходный DOCX-файл, используя класс [Document](https://reference.aspose.com/words/python-net/aspose.words/document/).
- Создайте экземпляр [HtmlSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/htmlsaveoptions/)
- Установите export_roundtrip_information как True
- Укажите [SaveFormat](https://reference.aspose.com/words/python-net/aspose.words/saveformat/) как MHTML.
- Вызовите метод `save`, указав путь к выходному файлу и SaveFormat в качестве параметров. Таким образом, ваш файл DOCX преобразуется в MHTML по указанному пути.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}

- Для преобразования формата DOCX в MHTML или HtmlFixed требуется Python 3.5 или более поздней версии.
- Справочные API внутри проекта непосредственно из PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/))
- Или используйте следующие команды pip ```pip install aspose.words```
- Кроме того, для ОС на базе Microsoft Windows или Linux (см. подробнее [Words](https://docs.aspose.com/words/python-net/system-requirements/)) и для Linux проверьте дополнительные требования для gcc и libpython и следуйте пошаговым инструкциям [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Сохранить DOCX в MHTML в Python — просто" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-simple-microsoft-word-documents-to-mhtml-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Преобразование DOCX в MHTML в Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "word-files-to-mhtml-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}