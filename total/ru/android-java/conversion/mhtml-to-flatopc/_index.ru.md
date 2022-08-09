---
title: Android API для рендеринга MHTML в FLATOPC
description: Преобразование MHTML в FLATOPC через Android через Java API
url: /ru/android-java/conversion/mhtml-to-flatopc/
family: total
platformtag: cpp
feature: conversion
informat: MHTML
outformat: FLAT_OPC
otherformats: RTF OTT XAMLFLOW DOTM WORDML MARKDOWN ODT PCL DOTX PS DOCM DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Рендеринг MHTML в FLATOPC на Android через Java" h2="Преобразование MHTML в FLATOPC в мобильных приложениях без установки какого-либо программного обеспечения" >}}

{{% blocks/products/pf/feature-page-summary %}}
Вы можете интегрировать функцию преобразования MHTML в FLATOPC в свои мобильные приложения, используя два API пакета [Aspose.Total для Android Java](https://products.aspose.com/total/android-java/). Сначала вам нужно преобразовать файл MHTML в DOC, используя [Aspose.PDF для Android через Java](https://products.aspose.com/pdf/android-java/). Во-вторых, с помощью API обработки текста [Aspose.Words для Android Java](https://products.aspose.com/words/android-java/) вы можете преобразовать DOC в FLATOPC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование MHTML в FLATOPC на Android через Java" %}}
1. Откройте файл MHTML, используя класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте MHTML в DOC, используя [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) метод
3. Загрузите файл DOC с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words.
4. Сохраните документ в формате FLATOPC, используя метод [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) и установите FLATOPC как СохранитьФормат
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Android через Java непосредственно из [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) и установите [Aspose.PDF для Android через Java](https://docs.aspose.com/pdf/androidjava/installation/) и [Aspose.Words для Android через Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-через-java/#install-asposewords-for-android-через-java-из-maven-репозитория) в ваших приложениях.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MHTML file with an instance of Document class
Document document = new Document("template.mhtml");
// save MHTML as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.FLAT_OPC
outputDocument.save("output.flat_opc", SaveFormat.FLAT_OPC);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Получить информацию о файле MHTML на Android через Java" %}}
Перед преобразованием MHTML в FLATOPC вам может потребоваться информация о документе, включая автора, дату создания, ключевые слова, дату изменения, тему и название. Эта информация полезна для принятия решения о процессе преобразования. Используя мощный API [Aspose.PDF для Android через Java](https://docs.aspose.com/pdf/androidjava/), вы можете получить все это. Чтобы получить специфичную для файла информацию о файле MHTML, сначала получите объект [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) с помощью [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--). После извлечения объекта DocumentInfo вы можете получить значения отдельных свойств.
{{% blocks/products/pf/feature-page-code %}}

```java
// load MHTML document
Document doc = new Document("template.mhtml");
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

{{% blocks/products/pf/feature-page-section  h2="Вставка концевых сносок в документ FLATOPC на Android через Java" %}}
Помимо преобразования документов, вы также можете добавить множество других функций в свои приложения для Android, используя API [Aspose.Words для Android через Java](https://products.aspose.com/words/androidjava/). Одной из таких функций является вставка концевых сносок и нумерация в документ FLATOPC. Если вы хотите вставить сноску или концевую сноску в документ FLATOPC, используйте метод DocumentBuilder.InsertFootnote. Этот метод вставляет сноску или концевую сноску в документ. Классы EndnoteOptions и FootnoteOptions представляют параметры нумерации сносок и концевых сносок.
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
doc.save("output.flat_opc", SaveFormat.FLAT_OPC);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/mhtml-to-rtf/" name="MHTML К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/mhtml-to-ott/" name="MHTML К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/mhtml-to-xamlflow/" name="MHTML К XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/mhtml-to-dotm/" name="MHTML К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/mhtml-to-wordml/" name="MHTML К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/mhtml-to-markdown/" name="MHTML К MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/mhtml-to-odt/" name="MHTML К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/mhtml-to-pcl/" name="MHTML К PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/mhtml-to-dotx/" name="MHTML К DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/mhtml-to-ps/" name="MHTML К PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/mhtml-to-flatopc/" name="MHTML К FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/mhtml-to-dot/" name="MHTML К DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}