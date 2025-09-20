---
title: Java API для экспорта EPUB в OTT
description: Преобразование EPUB в OTT с использованием локального Java API
url_ignore: /ru/java/conversion/epub-to-ott/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: OTT
otherformats: MARKDOWN XAMLFLOW RTF OTT PCL DOTX DOT WORDML FLATOPC MHTML DOTM PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование EPUB в OTT с помощью Java" h2="Локальный Java API для рендеринга EPUB в OTT без использования каких-либо сторонних приложений" >}}
{{% blocks/products/pf/feature-page-summary %}}
Вы можете преобразовать EPUB в OTT, выполнив два простых шага. Сначала вам нужно преобразовать файл EPUB в DOC, используя [Aspose.PDF для Java](https://products.aspose.com/pdf/java/). После этого, используя мощный API обработки документов [Aspose.Words for Java](https://products.aspose.com/words/java/), вы можете преобразовать DOC в OTT. Оба API входят в пакет [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API для преобразования EPUB в OTT" %}}
1. Откройте файл EPUB, используя класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте EPUB в DOC, используя [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) метод
3. Загрузите файл DOC с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words.
4. Сохраните документ в формате OTT, используя метод [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) и установите OTT как СохранитьФормат
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://releases.aspose.com/total/java/). и включите [Aspose.PDF для Java](https://docs.aspose.com/pdf/java/installation/) и [Aspose.Words для Java](https://docs.aspose.com/words/java/installation/) в вашем файле pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-ott.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
При преобразовании EPUB в OTT, даже если ваш документ защищен паролем, вы все равно можете открыть его с помощью API управления PDF [Aspose.PDF для Java](https://docs.aspose.com/pdf/java/installation/). Чтобы открыть зашифрованный файл, вам необходимо создать объект [Документ](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) и открыть EPUB, используя пароль владельца.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-password-proteted-epub-file.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Открыть защищенный паролем документ EPUB через Java" %}}
При сохранении входного документа в формате файла OTT вы также можете сохранить документ в базе данных, а не в файловой системе. Вам может потребоваться реализовать хранение и извлечение объектов Document в базу данных и из нее. Это было бы необходимо, если бы вы внедряли систему управления контентом любого типа. Чтобы сохранить ваш OTT в базу данных, часто необходимо сериализовать документ, чтобы получить массив байтов. Это можно сделать с помощью API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Получив массив байтов, вы можете сохранить его в базе данных с помощью оператора SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.OTT);
    // get the byte array from output steam
    // the byte array now contains the document
    byte[] buffer = aout.toByteArray();
    // get the filename from the document.
    String fileName = doc.getOriginalFileName();
    String filePath = fileName.replace("\\", "\\\\");
    // create the SQL command.
    String commandString = "INSERT INTO Documents (FileName, FileContent) VALUES('" + filePath + "', '" + buffer + "')";
    Statement statement = mConnection.createStatement();
    statement.executeUpdate(commandString);
}  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Преобразование **EPUB в OTT (OpenDocument Text Template)** является важным для создания **стандартизированных шаблонов текстовых документов** из цифровых изданий. Файлы OTT обеспечивают многократное использование стандартных текстовых документов, гарантируя согласованность, эффективность и совместимость на различных платформах. Преобразуя EPUB в OTT, педагоги, издатели, бизнес и предприятия могут оптимизировать рабочие процессы по написанию, поддерживать стандарты контента и эффективно масштабировать создание документов.

{{% blocks/products/pf/agp/feature-section-col title="Основные сценарии использования" %}}
- **Шаблоны академического письма** – Стандартизация научных статей, заданий и учебных документов.
- **Шаблоны рабочего процесса издательства** – Поддержание согласованных редакционных и производственных форматов.
- **Шаблоны для бизнес-отчетов** – Обеспечение единообразия в корпоративной отчетности и документообороте.
- **Шаблоны образовательных ресурсов** – Создание многоразовых шаблонов для учебных материалов.
- **Стандартизация контента корпоративного уровня** – Применение согласованности шаблонов в крупномасштабных организационных документах.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Сценарии автоматизации" %}}
- **Конвейеры EPUB в OTT** – Автоматизация преобразования цифровых изданий в текстовые шаблоны.
- **Автоматизированное распространение шаблонов** – Распространение стандартизированных файлов OTT среди команд и отделов.
- **Преобразование метаданных в шаблоны** – Интеграция структурированных данных электронных книг в многоразовые шаблоны.
- **Автоматизация издательского процесса предприятия** – Масштабирование стандартизации документов и эффективности рабочего процесса в организациях.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}