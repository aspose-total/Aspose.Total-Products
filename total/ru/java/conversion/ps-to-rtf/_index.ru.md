---
title: Java API для экспорта PS в RTF
description: Преобразование PS в RTF с использованием локального Java API
url_ignore: /ru/java/conversion/ps-to-rtf/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: RTF
otherformats: XAMLFLOW FLATOPC ODT DOTM WORDML DOT MARKDOWN MHTML RTF DOTX PCL OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование PS в RTF с помощью Java" h2="Локальный Java API для рендеринга PS в RTF без использования каких-либо сторонних приложений" >}}
{{% blocks/products/pf/feature-page-summary %}}
Вы можете преобразовать PS в RTF, выполнив два простых шага. Сначала вам нужно преобразовать файл PS в DOC, используя [Aspose.PDF для Java](https://products.aspose.com/pdf/java/). После этого, используя мощный API обработки документов [Aspose.Words for Java](https://products.aspose.com/words/java/), вы можете преобразовать DOC в RTF. Оба API входят в пакет [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API для преобразования PS в RTF" %}}
1. Откройте файл PS, используя класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте PS в DOC, используя [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) метод
3. Загрузите файл DOC с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words.
4. Сохраните документ в формате RTF, используя метод [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) и установите RTF как СохранитьФормат
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://releases.aspose.com/total/java/). и включите [Aspose.PDF для Java](https://docs.aspose.com/pdf/java/installation/) и [Aspose.Words для Java](https://docs.aspose.com/words/java/installation/) в вашем файле pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "f5707d58ebee8d2889c8dbe5aa739d87" "convert-ps-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
При преобразовании PS в RTF, даже если ваш документ защищен паролем, вы все равно можете открыть его с помощью API управления PDF [Aspose.PDF для Java](https://docs.aspose.com/pdf/java/installation/). Чтобы открыть зашифрованный файл, вам необходимо создать объект [Документ](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) и открыть PS, используя пароль владельца.  
{{% blocks/products/pf/feature-page-code %}}
```cs
// open encrypted document
Document document = new Document("input.ps", "password");
// save PS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Открыть защищенный паролем документ PS через Java" %}}
При сохранении входного документа в формате файла RTF вы также можете сохранить документ в базе данных, а не в файловой системе. Вам может потребоваться реализовать хранение и извлечение объектов Document в базу данных и из нее. Это было бы необходимо, если бы вы внедряли систему управления контентом любого типа. Чтобы сохранить ваш RTF в базу данных, часто необходимо сериализовать документ, чтобы получить массив байтов. Это можно сделать с помощью API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Получив массив байтов, вы можете сохранить его в базе данных с помощью оператора SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.RTF);
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

Преобразование PS (PostScript) в RTF (Rich Text Format) позволяет использовать документы на различных платформах и текстовых процессорах, сохраняя основное форматирование, шрифты и векторную графику. Преобразование в RTF идеально подходит для обмена отчетами без проблем совместимости.

{{% blocks/products/pf/agp/feature-section-col title="Основные сценарии использования" %}}

* Преобразование отчетов на основе PostScript в универсально читаемые файлы RTF.
* Обмен диаграммами и графиками PS с командами на различных платформах.
* Сохранение форматирования для официальных документов, писем и внутренних отчетов.
* Подготовка документов для систем, которые не поддерживают PS или DOCX изначально.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Сценарии автоматизации" %}}

* Автоматизированное преобразование PS в RTF для интеграции с устаревшими системами.
* Пакетная обработка для распространения документов в многоплатформенных средах.
* Рабочие процессы на основе ETL для преобразования PS-архивов в редактируемые форматы.
* Извлечение и сохранение форматирования из документов PS с помощью искусственного интеллекта.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}