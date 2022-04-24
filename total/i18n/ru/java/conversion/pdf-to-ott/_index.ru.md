---
title: Java API для экспорта PDF в OTT
description: Преобразование PDF в OTT с использованием локального Java API
url: /ru/java/conversion/pdf-to-ott/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: OTT
otherformats: RTF WORDML ODT OTT FLATOPC DOTM XAMLFLOW DOTX MARKDOWN DOT MHTML PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование PDF в OTT с помощью Java" h2="Локальный Java API для рендеринга PDF в OTT без использования каких-либо сторонних приложений" >}}
{{% blocks/products/pf/feature-page-summary %}}
Вы можете преобразовать PDF в OTT, выполнив два простых шага. Сначала вам нужно преобразовать файл PDF в DOC, используя [Aspose.PDF для Java] (https://products.aspose.com/pdf/java/). После этого, используя мощный API обработки документов [Aspose.Words for Java](https://products.aspose.com/words/java/), вы можете преобразовать DOC в OTT. Оба API входят в пакет [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API для преобразования PDF в OTT" %}}
1. Откройте файл PDF, используя класс [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте PDF в DOC, используя [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) метод
3. Загрузите файл DOC с помощью класса [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words.
4. Сохраните документ в формате OTT, используя метод [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) и установите OTT как СохранитьФормат
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total). и включите [Aspose.PDF для Java](https://docs.aspose.com/pdf/java/installation/) и [Aspose.Words для Java](https://docs.aspose.com/words/java/ установка/) в вашем файле pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки] (https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PDF file with an instance of Document class
Document document = new Document("template.pdf");
// save PDF as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.OTT
outputDocument.save("output.ott", SaveFormat.OTT);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
При преобразовании PDF в OTT, даже если ваш документ защищен паролем, вы все равно можете открыть его с помощью API управления PDF [Aspose.PDF для Java] (https://docs.aspose.com/pdf/java/installation/). Чтобы открыть зашифрованный файл, вам необходимо создать объект [Документ](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) и открыть PDF, используя пароль владельца.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.pdf", "password");
// save PDF as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Открыть защищенный паролем документ PDF через Java" %}}
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
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pdf-to-rtf/" name="PDF К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pdf-to-wordml/" name="PDF К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pdf-to-odt/" name="PDF К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pdf-to-flatopc/" name="PDF К FLAКPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pdf-to-ps/" name="PDF К PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pdf-to-pcl/" name="PDF К PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pdf-to-mhtml/" name="PDF К MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pdf-to-dotm/" name="PDF К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pdf-to-ott/" name="PDF К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pdf-to-dotx/" name="PDF К DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pdf-to-xamlflow/" name="PDF К XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pdf-to-markdown/" name="PDF К MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}