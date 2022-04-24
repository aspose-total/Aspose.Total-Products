---
title: Java API для экспорта MD в FLATOPC
description: Преобразование MD в FLATOPC с использованием локального Java API
url: /ru/java/conversion/md-to-flatopc/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: FLAT_OPC
otherformats: ODT DOT MARKDOWN DOTM PCL XAMLFLOW PS DOTX WORDML FLATOPC OTT RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование MD в FLATOPC с помощью Java" h2="Локальный Java API для рендеринга MD в FLATOPC без использования каких-либо сторонних приложений" >}}
{{% blocks/products/pf/feature-page-summary %}}
Вы можете преобразовать MD в FLATOPC, выполнив два простых шага. Сначала вам нужно преобразовать файл MD в DOC, используя [Aspose.PDF для Java] (https://products.aspose.com/pdf/java/). После этого, используя мощный API обработки документов [Aspose.Words for Java](https://products.aspose.com/words/java/), вы можете преобразовать DOC в FLATOPC. Оба API входят в пакет [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API для преобразования MD в FLATOPC" %}}
1. Откройте файл MD, используя класс [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте MD в DOC, используя [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) метод
3. Загрузите файл DOC с помощью класса [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words.
4. Сохраните документ в формате FLATOPC, используя метод [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) и установите FLATOPC как СохранитьФормат
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total). и включите [Aspose.PDF для Java](https://docs.aspose.com/pdf/java/installation/) и [Aspose.Words для Java](https://docs.aspose.com/words/java/ установка/) в вашем файле pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки] (https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MD file with an instance of Document class
Document document = new Document("template.md");
// save MD as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.FLAT_OPC
outputDocument.save("output.flat_opc", SaveFormat.FLAT_OPC);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
При преобразовании MD в FLATOPC, даже если ваш документ защищен паролем, вы все равно можете открыть его с помощью API управления PDF [Aspose.PDF для Java] (https://docs.aspose.com/pdf/java/installation/). Чтобы открыть зашифрованный файл, вам необходимо создать объект [Документ](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) и открыть MD, используя пароль владельца.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.md", "password");
// save MD as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Открыть защищенный паролем документ MD через Java" %}}
При сохранении входного документа в формате файла FLATOPC вы также можете сохранить документ в базе данных, а не в файловой системе. Вам может потребоваться реализовать хранение и извлечение объектов Document в базу данных и из нее. Это было бы необходимо, если бы вы внедряли систему управления контентом любого типа. Чтобы сохранить ваш FLATOPC в базу данных, часто необходимо сериализовать документ, чтобы получить массив байтов. Это можно сделать с помощью API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Получив массив байтов, вы можете сохранить его в базе данных с помощью оператора SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.FLAT_OPC);
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-rtf/" name="MD К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-wordml/" name="MD К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-odt/" name="MD К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-flatopc/" name="MD К FLAКPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-ps/" name="MD К PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-pcl/" name="MD К PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-mhtml/" name="MD К MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-dotm/" name="MD К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-ott/" name="MD К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-dotx/" name="MD К DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-xamlflow/" name="MD К XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-markdown/" name="MD К MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}