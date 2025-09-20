---
title: Преобразование формата JSON в PS через Java
description: Разобрать JSON в PS на Java без использования Microsoft Word
url_ignore: /ru/java/conversion/json-to-ps/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PS
otherformats: WORD DOTX PS OTT EPUB RTF PCL DOC DOCM FLATOPC ODT WORDML DOT MOBI
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование формата JSON в PS через Java" h2="Локальный Java API для преобразования JSON в PS без использования Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total для Java](https://products.aspose.com/total/java/), вы можете конвертировать JSON в PS в своих Java-приложениях в два этапа. Во-первых, с помощью [Aspose.Cells for Java](https://products.aspose.com/cells/java/) вы можете преобразовать JSON в PDF. На втором этапе вы можете конвертировать PDF в PS с помощью API обработки текстов [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование формата JSON в PS через Java" %}}
1. Создайте новый объект [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) и прочитайте действительные данные JSON из файла.
2. Импортируйте файл JSON на лист, используя класс [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) и [Save](https://reference.aspose.com/ ячейки/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) в формате PDF
3. Загрузите документ PDF с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
4. Сохраните документ в формате PS, используя [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions).)) метод
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://releases.aspose.com/total/java/). и включите библиотеки в свой pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
Кроме того, API позволяет вам устанавливать параметры макета для вашего JSON при анализе JSON в PS с помощью [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Он позволяет обрабатывать массив как таблицу, игнорировать нули, игнорировать заголовок массива, игнорировать заголовок объекта, преобразовывать строку в число или дату, устанавливать формат даты и числа и устанавливать стиль заголовка. Все эти параметры позволяют вам представить ваши данные в соответствии с вашими потребностями. В следующем фрагменте кода показано, как установить параметры макета.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Установить макет и преобразовать формат JSON в PS через Java" %}}
Используя API, вы также можете преобразовать JSON в PS с водяным знаком. Чтобы добавить водяной знак в документ PS, вы можете сначала преобразовать файл JSON в PDF и добавить к нему водяной знак. Чтобы добавить водяной знак, загрузите только что созданный файл PDF с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), создайте экземпляр TextWatermarkOptions и установите его свойства, вызвать метод Watermark.setText и передать текст водяного знака и объект TextWatermarkOptions. После добавления водяного знака вы можете сохранить документ в PS. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Преобразование **JSON в PS** необходимо для преобразования **структурированных данных в файлы PostScript** для печати и публикации высокого качества. Файлы PS обеспечивают устройствонезависимый, масштабируемый вывод, подходящий для профессиональной печати, документации предприятия и архивных целей. Преобразуя JSON в PS, организации могут автоматизировать рабочие процессы печати, поддерживать согласованность выводов и эффективно производить публикации стандартов отрасли.

{{% blocks/products/pf/agp/feature-section-col title="Основные сценарии использования" %}}

- **Публикация печати высокого качества** – Создание профессиональных, масштабируемых файлов PostScript для производства печати.
- **Отчеты с графическими элементами** – Создание визуально детализированных отчетов с точным форматированием из структурированных данных.
- **Печатные рабочие процессы предприятия** – Стандартизация процессов массовой печати в отделах и офисах.
- **Архивирование документов** – Создание файлов, готовых к печати, для долгосрочного хранения и соблюдения нормативных требований.
- **Промышленный вывод** – Обеспечение высокого разрешения, совместимых с принтером файлов для производства или технической документации.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Сценарии автоматизации" %}}

- **Конвейеры JSON-to-PS** – Автоматизация преобразования структурированных данных в файлы PostScript.
- **Автоматизированное создание PostScript** – Упрощение создания документов, готовых к печати.
- **Печатные рабочие процессы** – Сокращение ручного форматирования и подготовки к печати.
- **Автоматизация публикации на основе JSON** – Эффективное интегрирование структурированных данных в профессиональные рабочие процессы печати и публикации.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}