---
title: Преобразование формата JSON в CHM через Java
description: Разобрать JSON в CHM на Java без использования Microsoft Word
url_ignore: /ru/java/conversion/json-to-chm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: CHM
otherformats: FLATOPC DOCM WORD WORDML ODT RTF DOC MOBI OTT DOTX PCL DOT EPUB PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование формата JSON в CHM через Java" h2="Локальный Java API для преобразования JSON в CHM без использования Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total для Java](https://products.aspose.com/total/java/), вы можете конвертировать JSON в CHM в своих Java-приложениях в два этапа. Во-первых, с помощью [Aspose.Cells for Java](https://products.aspose.com/cells/java/) вы можете преобразовать JSON в PDF. На втором этапе вы можете конвертировать PDF в CHM с помощью API обработки текстов [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование формата JSON в CHM через Java" %}}
1. Создайте новый объект [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) и прочитайте действительные данные JSON из файла.
2. Импортируйте файл JSON на лист, используя класс [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) и [Save](https://reference.aspose.com/ ячейки/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) в формате PDF
3. Загрузите документ PDF с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
4. Сохраните документ в формате CHM, используя [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions).)) метод
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
Кроме того, API позволяет вам устанавливать параметры макета для вашего JSON при анализе JSON в CHM с помощью [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Он позволяет обрабатывать массив как таблицу, игнорировать нули, игнорировать заголовок массива, игнорировать заголовок объекта, преобразовывать строку в число или дату, устанавливать формат даты и числа и устанавливать стиль заголовка. Все эти параметры позволяют вам представить ваши данные в соответствии с вашими потребностями. В следующем фрагменте кода показано, как установить параметры макета.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Установить макет и преобразовать формат JSON в CHM через Java" %}}
Используя API, вы также можете преобразовать JSON в CHM с водяным знаком. Чтобы добавить водяной знак в документ CHM, вы можете сначала преобразовать файл JSON в PDF и добавить к нему водяной знак. Чтобы добавить водяной знак, загрузите только что созданный файл PDF с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), создайте экземпляр TextWatermarkOptions и установите его свойства, вызвать метод Watermark.setText и передать текст водяного знака и объект TextWatermarkOptions. После добавления водяного знака вы можете сохранить документ в CHM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Преобразование **JSON в CHM (Compiled HTML Help)** необходимо для создания **скомпилированных справочных руководств** непосредственно из структурированной документации. Файлы CHM объединяют несколько тем справки в один, доступный для поиска и оффлайн-ресурс, что делает их идеальными для поддержки программного обеспечения и управления знаниями предприятия. Преобразуя JSON в CHM, организации могут оптимизировать доставку документации, улучшить удобство использования и обеспечить доступность даже без подключения к Интернету.

{{% blocks/products/pf/agp/feature-section-col title="Основные сценарии использования" %}}

- **Документация по программному обеспечению** – Упаковка технических руководств в скомпилированный, удобный для пользователя формат.
- **Системы оффлайн-справки** – Предоставление документации без необходимости доступа к Интернету.
- **Базы знаний предприятия** – Централизация организационных знаний в структурированном файле справки.
- **Учебные пособия** – Распространение скомпилированных учебных ресурсов для сотрудников или студентов.
- **Ссылки на API разработчика** – Преобразование структурированных определений JSON в доступные для поиска оффлайн-ссылки.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Сценарии автоматизации" %}}

- **Конвейеры JSON-to-CHM** – Автоматизация преобразования структурированных данных в скомпилированные справочные руководства.
- **Автоматизированное создание файлов справки** – Генерация файлов CHM непосредственно из развивающегося контента на основе JSON.
- **Компиляция данных в документацию** – Преобразование структурированной документации JSON в доступные системы справки.
- **Распространение оффлайн-знаний** – Стандартизация справочных руководств CHM для обучения и поддержки на предприятии.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}