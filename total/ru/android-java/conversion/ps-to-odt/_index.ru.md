---
title: Android API для рендеринга PS в ODT
description: Преобразование PS в ODT через Android через Java API

family: total
platformtag: cpp
feature: conversion
informat: PS
outformat: ODT
otherformats: DOCM DOTM MARKDOWN RTF DOT DOTX MHTML OTT WORDML PCL FLATOPC XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Рендеринг PS в ODT на Android через Java" h2="Преобразование PS в ODT в мобильных приложениях без установки какого-либо программного обеспечения" >}}

{{% blocks/products/pf/feature-page-summary %}}
Вы можете интегрировать функцию преобразования PS в ODT в свои мобильные приложения, используя два API пакета [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). Сначала вам нужно преобразовать файл PS в DOC, используя [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Во-вторых, с помощью API обработки текста [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) вы можете преобразовать DOC в ODT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование PS в ODT на Android через Java" %}}
1. Откройте файл PS, используя класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте PS в DOC, используя [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) метод
3. Загрузите файл DOC с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words.
4. Сохраните документ в формате ODT, используя метод [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) и установите ODT как СохранитьФормат
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total for Android via Java непосредственно из [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) и установите [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) и [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-через-java/#install-asposewords-for-android-через-java-из-maven-репозитория) в ваших приложениях.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PS file with an instance of Document class
Document document = new Document("template.ps");
// save PS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.ODT
outputDocument.save("output.odt", SaveFormat.ODT);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Получить информацию о файле PS на Android через Java" %}}
Перед преобразованием PS в ODT вам может потребоваться информация о документе, включая автора, дату создания, ключевые слова, дату изменения, тему и название. Эта информация полезна для принятия решения о процессе преобразования. Используя мощный API [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/), вы можете получить все это. Чтобы получить специфичную для файла информацию о файле PS, сначала получите объект [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) с помощью [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--). После извлечения объекта DocumentInfo вы можете получить значения отдельных свойств.
{{% blocks/products/pf/feature-page-code %}}

```java
// load PS document
Document doc = new Document("template.ps");
// get document information
DocumentInfo docInfo = doc.getInfo();
// show document information
System.out.println("Author: " + docInfo.getAuthor());
System.out.println("Creation Date: " + docInfo.getCreationDate());
System.out.println("Keywords: " + docInfo.getKeywords());
System.out.println("Modify Date: " + docInfo.getModDate());
System.out.println("Subject: " + docInfo.getSubject());
System.out.println("Title: " + docInfo.getTitle());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Вставка концевых сносок в документ ODT на Android через Java" %}}
Помимо преобразования документов, вы также можете добавить множество других функций в свои приложения для Android, используя API [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/). Одной из таких функций является вставка концевых сносок и нумерация в документ ODT. Если вы хотите вставить сноску или концевую сноску в документ ODT, используйте метод DocumentBuilder.InsertFootnote. Этот метод вставляет сноску или концевую сноску в документ. Классы EndnoteOptions и FootnoteOptions представляют параметры нумерации сносок и концевых сносок.
{{% blocks/products/pf/feature-page-code %}}

```java
// load document
Document doc = new Document("input.DOC");
// initialize document builder
DocumentBuilder builder = new DocumentBuilder(doc);
// add text in it
builder.write("Some text");
// insert footnote
builder.insertFootnote(FootnoteType.ENDNOTE, "Endnote text.");
// initialize endnote options
EndnoteOptions option = doc.getEndnoteOptions();
// set restart rule
option.setRestartRule(FootnoteNumberingRule.RESTART_PAGE);
// set position
option.setPosition(EndnotePosition.END_OF_SECTION);
// save the document to disk.
doc.save("output.odt", SaveFormat.ODT);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ps-to-odt/" name="PS К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ps-to-dotm/" name="PS К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ps-to-markdown/" name="PS К MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ps-to-rtf/" name="PS К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ps-to-dot/" name="PS К DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ps-to-dotx/" name="PS К DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ps-to-mhtml/" name="PS К MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ps-to-ott/" name="PS К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ps-to-wordml/" name="PS К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ps-to-pcl/" name="PS К PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ps-to-flatopc/" name="PS К FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ps-to-xamlflow/" name="PS К XAMLFLOW" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}