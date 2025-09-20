---
title: Преобразование формата JSON в DOCM через Java
description: Разобрать JSON в DOCM на Java без использования Microsoft Word
url_ignore: /ru/java/conversion/json-to-docm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DOCM
otherformats: EPUB RTF DOTX WORDML DOCM OTT ODT PCL DOC FLATOPC PS MOBI DOT WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование формата JSON в DOCM через Java" h2="Локальный Java API для преобразования JSON в DOCM без использования Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total для Java](https://products.aspose.com/total/java/), вы можете конвертировать JSON в DOCM в своих Java-приложениях в два этапа. Во-первых, с помощью [Aspose.Cells for Java](https://products.aspose.com/cells/java/) вы можете преобразовать JSON в PDF. На втором этапе вы можете конвертировать PDF в DOCM с помощью API обработки текстов [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование формата JSON в DOCM через Java" %}}
1. Создайте новый объект [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) и прочитайте действительные данные JSON из файла.
2. Импортируйте файл JSON на лист, используя класс [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) и [Save](https://reference.aspose.com/ ячейки/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) в формате PDF
3. Загрузите документ PDF с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
4. Сохраните документ в формате DOCM, используя [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions).)) метод
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
Кроме того, API позволяет вам устанавливать параметры макета для вашего JSON при анализе JSON в DOCM с помощью [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Он позволяет обрабатывать массив как таблицу, игнорировать нули, игнорировать заголовок массива, игнорировать заголовок объекта, преобразовывать строку в число или дату, устанавливать формат даты и числа и устанавливать стиль заголовка. Все эти параметры позволяют вам представить ваши данные в соответствии с вашими потребностями. В следующем фрагменте кода показано, как установить параметры макета.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Установить макет и преобразовать формат JSON в DOCM через Java" %}}
Используя API, вы также можете преобразовать JSON в DOCM с водяным знаком. Чтобы добавить водяной знак в документ DOCM, вы можете сначала преобразовать файл JSON в PDF и добавить к нему водяной знак. Чтобы добавить водяной знак, загрузите только что созданный файл PDF с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), создайте экземпляр TextWatermarkOptions и установите его свойства, вызвать метод Watermark.setText и передать текст водяного знака и объект TextWatermarkOptions. После добавления водяного знака вы можете сохранить документ в DOCM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Преобразование **JSON в DOCM** важно для встраивания **макросов в документы Word**, созданные на основе структурированных данных. Этот процесс позволяет организациям объединить исходные наборы данных с мощными функциями автоматизации внутри Word, что позволяет генерировать динамическое содержимое, выполнять бизнес-правила и обеспечивать интерактивную функциональность документа. Преобразуя JSON в файлы DOCM, предприятия могут оптимизировать рабочие процессы, улучшить отчетность и создавать шаблоны с включенными макросами, которые адаптируются к изменяющимся потребностям в данных.  

{{% blocks/products/pf/agp/feature-section-col title="Основные сценарии использования" %}}

- **Автоматизированные рабочие процессы с документами** – Обеспечьте повторяемое создание документов с встроенными макросами.  
- **Сценарии анализа данных** – Интегрируйте макросы, управляемые JSON, для расчетов и обработки в реальном времени.  
- **Шаблоны с включенными макросами** – Создавайте многоразовые интеллектуальные шаблоны для корпоративной документации.  
- **Системы корпоративной отчетности** – Генерируйте отчеты с автоматизированным форматированием и анализом.  
- **Интерактивные формы соответствия** – Предоставляйте формы с валидацией и обработкой с включенными макросами.  

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Сценарии автоматизации" %}}

- **Конвейеры JSON в DOCM** – Автоматизируйте преобразование структурированных наборов данных в файлы Word с включенными макросами.  
- **Автоматическое выполнение макросов Word** – Выполняйте макросы динамически во время или после создания документа.  
- **Динамическая обработка бизнес-правил** – Применяйте политики предприятия и правила обработки данных непосредственно в документах.  
- **Автоматизация отчетности с включенными макросами** – Стандартизируйте и ускорьте сложные рабочие процессы по отчетности в масштабе.  

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}