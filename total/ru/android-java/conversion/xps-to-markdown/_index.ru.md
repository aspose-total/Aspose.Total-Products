---
title: Android API для рендеринга XPS в MARKDOWN
description: Преобразование XPS в MARKDOWN через Android через Java API

family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: MARKDOWN
otherformats: MHTML XAMLFLOW DOCM PS ODT OTT DOTM FLATOPC DOTX DOT WORDML RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Рендеринг XPS в MARKDOWN на Android через Java" h2="Преобразование XPS в MARKDOWN в мобильных приложениях без установки какого-либо программного обеспечения" >}}

{{% blocks/products/pf/feature-page-summary %}}
Вы можете интегрировать функцию преобразования XPS в MARKDOWN в свои мобильные приложения, используя два API пакета [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). Сначала вам нужно преобразовать файл XPS в DOC, используя [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Во-вторых, с помощью API обработки текста [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) вы можете преобразовать DOC в MARKDOWN. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование XPS в MARKDOWN на Android через Java" %}}
1. Откройте файл XPS, используя класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте XPS в DOC, используя [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) метод
3. Загрузите файл DOC с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words.
4. Сохраните документ в формате MARKDOWN, используя метод [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) и установите MARKDOWN как СохранитьФормат
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total for Android via Java непосредственно из [Maven](https://releases.aspose.com/total/java/) и установите [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) и [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-через-java/#install-asposewords-for-android-через-java-из-maven-репозитория) в ваших приложениях.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://releases.aspose.comtotal/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.MARKDOWN
outputDocument.save("output.markdown", SaveFormat.MARKDOWN);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Получить информацию о файле XPS на Android через Java" %}}
Перед преобразованием XPS в MARKDOWN вам может потребоваться информация о документе, включая автора, дату создания, ключевые слова, дату изменения, тему и название. Эта информация полезна для принятия решения о процессе преобразования. Используя мощный API [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/), вы можете получить все это. Чтобы получить специфичную для файла информацию о файле XPS, сначала получите объект [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) с помощью [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--). После извлечения объекта DocumentInfo вы можете получить значения отдельных свойств.
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS document
Document doc = new Document("template.xps");
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

{{% blocks/products/pf/feature-page-section  h2="Вставка концевых сносок в документ MARKDOWN на Android через Java" %}}
Помимо преобразования документов, вы также можете добавить множество других функций в свои приложения для Android, используя API [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/). Одной из таких функций является вставка концевых сносок и нумерация в документ MARKDOWN. Если вы хотите вставить сноску или концевую сноску в документ MARKDOWN, используйте метод DocumentBuilder.InsertFootnote. Этот метод вставляет сноску или концевую сноску в документ. Классы EndnoteOptions и FootnoteOptions представляют параметры нумерации сносок и концевых сносок.
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
doc.save("output.markdown", SaveFormat.MARKDOWN);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}