---
title: Java API для экспорта CGM в MHTML
description: Преобразование CGM в MHTML с использованием локального Java API
url_ignore: /ru/java/conversion/cgm-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: MHTML
otherformats: XAMLFLOW DOTX WORDML OTT FLATOPC DOTM PCL ODT PS MHTML MARKDOWN DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование CGM в MHTML с помощью Java" h2="Локальный Java API для рендеринга CGM в MHTML без использования каких-либо сторонних приложений" >}}
{{% blocks/products/pf/feature-page-summary %}}
Вы можете преобразовать CGM в MHTML, выполнив два простых шага. Сначала вам нужно преобразовать файл CGM в DOC, используя [Aspose.PDF для Java](https://products.aspose.com/pdf/java/). После этого, используя мощный API обработки документов [Aspose.Words for Java](https://products.aspose.com/words/java/), вы можете преобразовать DOC в MHTML. Оба API входят в пакет [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API для преобразования CGM в MHTML" %}}
1. Откройте файл CGM, используя класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте CGM в DOC, используя [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) метод
3. Загрузите файл DOC с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words.
4. Сохраните документ в формате MHTML, используя метод [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) и установите MHTML как СохранитьФормат
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://releases.aspose.com/total/java/). и включите [Aspose.PDF для Java](https://docs.aspose.com/pdf/java/installation/) и [Aspose.Words для Java](https://docs.aspose.com/words/java/installation/) в вашем файле pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-mhtml.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
При преобразовании CGM в MHTML, даже если ваш документ защищен паролем, вы все равно можете открыть его с помощью API управления PDF [Aspose.PDF для Java](https://docs.aspose.com/pdf/java/installation/). Чтобы открыть зашифрованный файл, вам необходимо создать объект [Документ](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) и открыть CGM, используя пароль владельца.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "open-password-protected-cgm.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Открыть защищенный паролем документ CGM через Java" %}}
При сохранении входного документа в формате файла MHTML вы также можете сохранить документ в базе данных, а не в файловой системе. Вам может потребоваться реализовать хранение и извлечение объектов Document в базу данных и из нее. Это было бы необходимо, если бы вы внедряли систему управления контентом любого типа. Чтобы сохранить ваш MHTML в базу данных, часто необходимо сериализовать документ, чтобы получить массив байтов. Это можно сделать с помощью API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Получив массив байтов, вы можете сохранить его в базе данных с помощью оператора SQL. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "save-cgm-to-database.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Преобразование файлов **Computer Graphics Metafile (CGM)** в формат **MHTML (MIME HTML)** является необходимым для сохранения сложных инженерных и технических документов с встроенной графикой в одном самодостаточном файле. В **системах архивирования веб-страниц на основе Java** это преобразование позволяет организациям сохранять полные документы, включая визуальные элементы CGM, стили и ресурсы, в портативном архиве, подходящем для офлайн-просмотра и развертывания в интранете. MHTML гарантирует сохранность спецификаций дизайна, отчетов и чертежей для долгосрочного доступа и распространения.

---

## ✅ Основные сценарии использования

- **Упаковка инженерных документов с встроенной графикой**  
  Упаковка диаграмм CGM и связанного контента в MHTML для создания последовательных самодостаточных технических записей.

- **Офлайн-просмотр в интранет-порталах**  
  Предоставление документов, улучшенных с помощью CGM, в формате MHTML для беспрепятственного офлайн-доступа по корпоративным сетям.

- **Архивирование спецификаций дизайна**  
  Хранение версий MHTML спецификаций на основе CGM для соблюдения требований, ссылок и документации проекта.

---

## ⚙️ Сценарии автоматизации

- **Java-библиотеки с поддержкой MHTML**  
  Используйте API, такие как **Aspose.Words для Java**, или настраиваемые Java-экспортеры для создания файлов MHTML из документов на основе CGM.

- **Инструменты экспорта на основе веб-технологий**  
  Интегрируйте преобразование CGM в MHTML в веб-приложения, работающие на Java, для мгновенной упаковки файлов.

- **Рабочие процессы преобразования на основе сервлетов**  
  Развертывайте Java-сервлеты, которые обрабатывают входные данные CGM и создают архивы MHTML для безопасного распространения.

- **Автоматизированные конвейеры архивирования**  
  Включите шаги преобразования CGM в MHTML в системы управления документами или ETL на основе Java для запланированного архивирования.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}