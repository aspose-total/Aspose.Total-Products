---
title: 将 PDF 渲染到 OTT 的 Android API
description: 通过 Android 通过 Java API 将 PDF 转换为 OTT

family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: OTT
otherformats: MHTML RTF MARKDOWN DOT PS DOCM FLATOPC ODT DOTX PCL WORDML XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 Java 在 Android 上将 PDF 渲染到 OTT" h2="在移动应用程序中将 PDF 转换为 OTT，无需安装任何软件" >}}

{{% blocks/products/pf/feature-page-summary %}}
您可以使用 [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/) 包的两个 API 在您的移动应用程序中集成 PDF 到 OTT 的转换功能。首先，您需要使用 [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) 将 PDF 文件转换为 DOC。其次，通过使用文字处理 API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)，您可以将 DOC 渲染为 OTT。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 Java 在 Android 上将 PDF 转换为 OTT" %}}
1. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开PDF文件
2. 使用 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) 将 PDF 转换为 DOC ) 方法
3. 使用 Aspose.Words 的 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类加载 DOC 文件
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) 方法将文档保存为 OTT 格式并设置 OTT保存格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您可以直接从 [Maven](https://releases.aspose.com/total/java/)通过 Java 轻松使用 Aspose.Total for Android 和安装 [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) 和 [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) 在您的应用程序中。

或者，您可以从 [下载](https://releases.aspose.com/total/androidjava) 获取 ZIP 文件。
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

{{% blocks/products/pf/feature-page-section  h2="通过 Java 在 Android 上获取 PDF 文件信息" %}}
在将 PDF 转换为 OTT 之前，您可能需要有关文档的信息，包括作者、创建日期、关键字、修改日期、主题和标题。此信息有助于转换过程的决策。使用强大的 [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API，您可以获得所有内容。要获取有关 PDF 文件的文件特定信息，首先使用 [getInfo](https://参考.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) 方法。一旦检索到 DocumentInfo 对象，您就可以获取各个属性的值。
{{% blocks/products/pf/feature-page-code %}}

```java
// load PDF document
Document doc = new Document("template.pdf");
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

{{% blocks/products/pf/feature-page-section  h2="通过 Java 在 Android 中的 OTT 文档中插入尾注" %}}
除了文档转换，您还可以使用 [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API 在您的 Android 应用程序中添加许多其他功能。该功能之一是在 OTT 文档中插入尾注和编号。如果要在 OTT 文档中插入脚注或尾注，请使用 DocumentBuilder.InsertFootnote 方法。此方法在文档中插入脚注或尾注。 EndnoteOptions 和 FootnoteOptions 类表示脚注和尾注的编号选项。
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
doc.save("output.ott", SaveFormat.OTT);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}