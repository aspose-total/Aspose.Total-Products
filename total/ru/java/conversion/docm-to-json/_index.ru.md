---
title: Преобразование DOCM в формат JSON через Java
description: Преобразование DOCM в формат JSON через Java без использования Microsoft Word или Microsoft Excel
url_ignore: /ru/java/conversion/docm-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: JSON
otherformats: XLT XLTM FODS SXC XLAM XLS EXCEL ODS XLSM DIF XLSB XLTX TSV CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование DOCM в формат JSON через Java" h2="Локальный Java API для преобразования DOCM в JSON без использования Microsoft<sup>&reg;</sup> Word или Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Преобразование DOCM в формат JSON с помощью [Aspose.Total для Java](https://products.aspose.com/total/java/) — это простой двухэтапный процесс. Используя многофункциональный API для обработки и преобразования документов [Aspose.Words for Java](https://products.aspose.com/words/java/), вы можете экспортировать DOCM в HTML. После этого с помощью [Aspose.Cells for Java](https://products.aspose.com/cells/java/) вы можете конвертировать HTML в JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование DOCM в формат JSON через Java" %}}
1. Откройте файл DOCM, используя класс [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
2. Преобразуйте DOCM в HTML, используя [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) метод
3. Загрузите HTML-документ с помощью класса [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Сохраните документ в формате JSON с помощью [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) метод
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://releases.aspose.com/total/java/). и включите библиотеки в свой pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
С помощью API вы также можете открыть защищенный паролем документ. Если ваш входной документ DOCM защищен паролем, вы не сможете преобразовать его в формат JSON без использования пароля. API позволяет открыть зашифрованный документ, указав правильный пароль в объекте LoadOptions. В следующем примере кода показано, как попытаться открыть зашифрованный документ с помощью пароля:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование защищенного DOCM в формат JSON через Java" %}}
Пока вы конвертируете DOCM в JSON, вы также можете установить диапазон выходного формата JSON. Чтобы установить диапазон, вы можете открыть преобразованный HTML с помощью класса Workbook, создать диапазон данных для экспорта с помощью метода Cells.createRange, вызвать метод JsonUtility.exportRangeToJson со ссылками Range и ExportRangeToJsonOptions и записать строковые данные JSON в файл через Метод BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
## ✅ Основные сценарии использования  

- **Публикация данных документа в REST/GraphQL API**  
  Предоставление извлеченного содержимого DOCM в формате JSON для прямого использования в веб- и мобильных приложениях.  

- **Подача данных в NoSQL-базы данных и хранилища данных**  
  Загрузка структурированных данных, полученных из DOCM, в MongoDB, Elasticsearch или облачные хранилища данных.  

- **Подача питания панелей управления данными в реальном времени с помощью JSON-потоков**  
  Подача ключевых показателей эффективности и метрик, основанных на документах, в бизнес-панели и инструменты мониторинга.  

- **Проверка ввода по схеме JSON**  
  Обеспечение согласованности и целостности путем сопоставления данных полей DOCM с правилами схемы JSON.  

- **Включение безголовых CMS или микросервисных архитектур**  
  Интеграция содержимого DOCM в распределенные системы, ориентированные на API, где JSON является лингва франка.  

## ⚙️ Сценарии автоматизации  

- **Извлечение из DOCM в JSON с сопоставлением полей**  
  Определение сопоставлений для преобразования таблиц, заголовков и полей в структурированные объекты JSON.  

- **Бессерверные функции, которые преобразуют и генерируют события JSON**  
  Запуск преобразований при загрузке файла, генерация JSON-пакетов для событийно-ориентированных систем.  

- **Задания ETL, нормализующие типы и ключи**  
  Стандартизация экспорта DOCM в согласованные структуры JSON для последующего анализа.  

- **Вебхуки, которые передают JSON в нижестоящие системы**  
  Автоматизация экспорта DOCM в JSON для питания CRM-систем, ERP-инструментов или сторонних приложений.  

- **Правила управления, которые удаляют макросы и ПИИ перед экспортом в JSON**  
  Применение проверок соответствия для обеспечения безопасного, санитарного вывода JSON из файлов с макросами.  
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}