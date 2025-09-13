---
title: Java API для экспорта CGM в DOCM
description: Преобразование CGM в DOCM с использованием локального Java API
url_ignore: /ru/java/conversion/cgm-to-docm/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DOCM
otherformats: RTF WORDML ODT FLATOPC PS PCL MHTML DOTM OTT DOTX XAMLFLOW MARKDOWN
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование CGM в DOCM с помощью Java" h2="Локальный Java API для рендеринга CGM в DOCM без использования каких-либо сторонних приложений" >}}
{{% blocks/products/pf/feature-page-summary %}}
Вы можете преобразовать CGM в DOCM, выполнив два простых шага. Сначала вам нужно преобразовать файл CGM в DOC, используя [Aspose.PDF для Java](https://products.aspose.com/pdf/java/). После этого, используя мощный API обработки документов [Aspose.Words for Java](https://products.aspose.com/words/java/), вы можете преобразовать DOC в DOCM. Оба API входят в пакет [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API для преобразования CGM в DOCM" %}}
1. Откройте файл CGM, используя класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте CGM в DOC, используя [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) метод
3. Загрузите файл DOC с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words.
4. Сохраните документ в формате DOCM, используя метод [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) и установите DOCM как СохранитьФормат
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://releases.aspose.com/total/java/). и включите [Aspose.PDF для Java](https://docs.aspose.com/pdf/java/installation/) и [Aspose.Words для Java](https://docs.aspose.com/words/java/installation/) в вашем файле pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "cgm-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
При преобразовании CGM в DOCM, даже если ваш документ защищен паролем, вы все равно можете открыть его с помощью API управления PDF [Aspose.PDF для Java](https://docs.aspose.com/pdf/java/installation/). Чтобы открыть зашифрованный файл, вам необходимо создать объект [Документ](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) и открыть CGM, используя пароль владельца.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "open-password-protected-cgm.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Открыть защищенный паролем документ CGM через Java" %}}
При сохранении входного документа в формате файла DOCM вы также можете сохранить документ в базе данных, а не в файловой системе. Вам может потребоваться реализовать хранение и извлечение объектов Document в базу данных и из нее. Это было бы необходимо, если бы вы внедряли систему управления контентом любого типа. Чтобы сохранить ваш DOCM в базу данных, часто необходимо сериализовать документ, чтобы получить массив байтов. Это можно сделать с помощью API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Получив массив байтов, вы можете сохранить его в базе данных с помощью оператора SQL. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "save-cgm-to-database.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/agp/feature-section >}}
```
Преобразование файлов **Computer Graphics Metafile (CGM)** в **DOCM (Macro-Enabled Word Document)** имеет высокую ценность для организаций, которым необходимы интерактивные, автоматизированные и динамичные рабочие процессы с документами. В **системах автоматизации документов на основе Java** это преобразование позволяет встраивать технические диаграммы, инженерные схемы и визуализации процессов из CGM в макрос-включенные отчеты. Формат DOCM поддерживает макросы VBA, обеспечивая автоматизированные вычисления, обновление данных и интерактивную отчетность — идеально подходит для потребностей в инженерной, промышленной и корпоративной документации.


{{% blocks/products/pf/agp/feature-section-col title="Основные сценарии использования" %}}

- **Динамичное техническое отчетирование**  
  Встраивание иллюстраций на основе CGM в шаблоны DOCM, которые автоматически обновляют графики, таблицы и аналитический контент.

- **Генерация макрос-включенных документов для журналов инженера**  
  Создание журналов инженера, где макросы обрабатывают и представляют данные диаграмм CGM с вычисленными результатами.

- **Документация рабочих процессов**  
  Создание интерактивных руководств или операционных инструкций с встроенными визуализациями CGM и навигацией, управляемой макросами.


{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Сценарии автоматизации" %}}

- **Библиотеки Java для создания DOCM**  
  Используйте API, такие как **Apache POI**, **docx4j** или **Aspose.Words for Java**, для автоматизации преобразования CGM в DOCM с поддержкой макросов.

- **Сборка корпоративных документов**  
  Интегрируйте процесс преобразования в системы управления корпоративным контентом на Java для мгновенного создания файлов с включенными макросами.

- **Обработка данных, управляемая макросами**  
  Автоматизируйте технический анализ путем встраивания макросов, которые считывают, интерпретируют и обновляют данные, связанные с визуализациями CGM.

- **Пакетная обработка рабочих процессов**  
  Преобразуйте и компилируйте несколько файлов CGM в макрос-включенные отчеты DOCM с помощью инструментов пакетной автоматизации на основе Java.
```
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}