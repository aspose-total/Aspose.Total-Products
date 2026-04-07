---
title: Преобразование XPS в EML в Python
description: Сохраняйте XPS в EML в приложениях Python без использования Microsoft Word или Outlook.

family: total
platformtag: Python
feature: conversion
informat: XPS
outformat: EML
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование XPS в EML с помощью Python" h2="Преобразование XPS в EML в приложениях Python без установки Microsoft Word<sup>&reg;</sup> или Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}

Для разработчика Python, который пытается добавить функцию преобразования XPS в EML в приложение? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API может помочь автоматизировать процесс конвертации. Это полный пакет различных API, работающих с различными форматами, включая электронную почту, изображения и форматы Microsoft Word. API-интерфейсы [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) и [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/), которые являются частью пакета [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/), упрощают это преобразование с помощью Python. Это двухэтапный процесс: сначала загрузите файл XPS и преобразуйте его в HTML через [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/). Во-вторых, загрузите преобразованный HTML с помощью [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) и сохраните его в формате EML.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Как конвертировать XPS в EML в Python" %}}

- Откройте исходный файл XPS, используя класс [Document](https://reference.aspose.com/words/python-net/aspose.words/document/).
- Вызовите метод `save`, указав путь к выходному файлу HTML и соответствующие параметры сохранения HTML в качестве параметра. Таким образом, ваш файл XPS преобразуется в HTML по указанному пути.
- Теперь загрузите сохраненный файл HTML с помощью MailMessage.load.
- Вызовите метод сохранения с соответствующим путем к файлу. Итак, наконец, XPS конвертируется

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}

- Для преобразования XPS в EML требуется Python 3.5 или более поздней версии.
- Справочные API внутри проекта непосредственно из PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) и [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Или используйте следующую команду pip ```pip install aspose.words``` и ```pip install Aspose.Email-for-Python-через-NET``` 
- Кроме того, для ОС на базе Microsoft Windows или Linux (дополнительную информацию см. в [Words](https://docs.aspose.com/words/python-net/system-requirements/) и [Email](https://docs.aspose.com/email/python-net/system-requirements/)) и для Linux проверьте дополнительные требования для gcc и libpython и следуйте пошаговым инструкциям [INSTALL](https://docs.aspose.com/words/python-net/installation/).
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Сохранить XPS в EML в Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Преобразование XPS в EML с помощью Python API позволяет фиксированным документам преобразовываться в стандартные файлы электронных сообщений, которые широко используются для хранения, обмена и архивирования сообщений. Это особенно полезно, когда содержимое документа должно быть сохранено в переносимом формате электронной почты для последующей коммуникации, обзора или соблюдения нормативных требований.

С точки зрения автоматизации, рабочие процессы преобразования XPS в EML повышают согласованность сообщений, основанных на документах, снижают затраты на ручную подготовку и поддерживают масштабируемую интеграцию между системами документооборота, инструментами обработки почты и архивными средами.

{{% blocks/products/pf/agp/feature-section-col title="Ключевые сценарии использования" %}}

* **Создание переносимых сообщений электронной почты**  
  Преобразует документы XPS в файлы EML для стандартизированного хранения и передачи между совместимыми системами.

* **Архивирование документов в почтовом формате**  
  Помогает сохранять содержимое документов в виде сообщений электронной почты для регулируемого удержания и будущего доступа.

* **Взаимодействие при обмене сообщениями**  
  Обеспечивает более простое перемещение преобразованных сообщений между платформами, поддерживающими стандартные файлы электронной почты.

* **Процессы обзора и утверждения**  
  Поддерживает рабочие потоки, в которых содержимое документа должно быть передано в виде файлов сообщений для проверки или подписания.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Сценарии автоматизации" %}}

* **Пакетное преобразование документов в сообщения**  
  Автоматизированные задания могут преобразовывать большие объёмы файлов XPS в EML для последовательной последующей обработки.

* **Упаковка записей, генерируемых системой**  
  Приложения могут преобразовывать сгенерированные выходные данные XPS в файлы EML в рамках процессов управления записями.

* **Загрузка в почтовый архив**  
  Преобразованные файлы EML могут программно направляться в архивные или индексирующие системы для удержания.

* **Экспорт сообщений на основе рабочего процесса**  
  Динамические конвейеры могут создавать выводы EML, когда документы достигают определённого этапа обработки.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}