---
title: Java API для экспорта CGM в DOTM
description: Преобразование CGM в DOTM с использованием локального Java API
url: /ru/java/conversion/cgm-to-dotm/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DOTM
otherformats: OTT MHTML MARKDOWN PCL WORDML DOTM XAMLFLOW ODT DOTX DOT RTF FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование CGM в DOTM с помощью Java" h2="Локальный Java API для рендеринга CGM в DOTM без использования каких-либо сторонних приложений" >}}
{{% blocks/products/pf/feature-page-summary %}}
Вы можете преобразовать CGM в DOTM, выполнив два простых шага. Сначала вам нужно преобразовать файл CGM в DOC, используя [Aspose.PDF для Java](https://products.aspose.com/pdf/java/). После этого, используя мощный API обработки документов [Aspose.Words for Java](https://products.aspose.com/words/java/), вы можете преобразовать DOC в DOTM. Оба API входят в пакет [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API для преобразования CGM в DOTM" %}}
1. Откройте файл CGM, используя класс [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте CGM в DOC, используя [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) метод
3. Загрузите файл DOC с помощью класса [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words.
4. Сохраните документ в формате DOTM, используя метод [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) и установите DOTM как СохранитьФормат
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total). и включите [Aspose.PDF для Java](https://docs.aspose.com/pdf/java/installation/) и [Aspose.Words для Java](https://docs.aspose.com/words/java/ установка/) в вашем файле pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load CGM file with an instance of Document class
Document document = new Document("template.cgm");
// save CGM as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOTM
outputDocument.save("output.dotm", SaveFormat.DOTM);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
При преобразовании CGM в DOTM, даже если ваш документ защищен паролем, вы все равно можете открыть его с помощью API управления PDF [Aspose.PDF для Java](https://docs.aspose.com/pdf/java/installation/). Чтобы открыть зашифрованный файл, вам необходимо создать объект [Документ](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) и открыть CGM, используя пароль владельца.  
{{% blocks/products/pf/feature-page-code %}}
```cs```cs
// open encrypted document
Document document = new Document("input.cgm", "password");
// save CGM as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Открыть защищенный паролем документ CGM через Java" %}}
При сохранении входного документа в формате файла DOTM вы также можете сохранить документ в базе данных, а не в файловой системе. Вам может потребоваться реализовать хранение и извлечение объектов Document в базу данных и из нее. Это было бы необходимо, если бы вы внедряли систему управления контентом любого типа. Чтобы сохранить ваш DOTM в базу данных, часто необходимо сериализовать документ, чтобы получить массив байтов. Это можно сделать с помощью API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Получив массив байтов, вы можете сохранить его в базе данных с помощью оператора SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.DOTM);
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/cgm-to-rtf/" name="CGM К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/cgm-to-wordml/" name="CGM К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/cgm-to-odt/" name="CGM К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/cgm-to-flatopc/" name="CGM К FLAКPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/cgm-to-ps/" name="CGM К PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/cgm-to-pcl/" name="CGM К PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/cgm-to-mhtml/" name="CGM К MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/cgm-to-dotm/" name="CGM К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/cgm-to-ott/" name="CGM К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/cgm-to-dotx/" name="CGM К DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/cgm-to-xamlflow/" name="CGM К XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/cgm-to-markdown/" name="CGM К MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}