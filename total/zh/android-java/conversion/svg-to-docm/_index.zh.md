---
title: 将 SVG 渲染到 DOCM 的 Android API
description: 通过 Android 通过 Java API 将 SVG 转换为 DOCM

family: total
platformtag: cpp
feature: conversion
informat: SVG
outformat: DOCM
otherformats: FLATOPC DOTX PCL MARKDOWN ODT RTF PS MHTML XAMLFLOW DOT DOTM WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 Java 在 Android 上将 SVG 渲染到 DOCM" h2="在移动应用程序中将 SVG 转换为 DOCM，无需安装任何软件" >}}

{{% blocks/products/pf/feature-page-summary %}}
您可以使用 [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/) 包的两个 API 在您的移动应用程序中集成 SVG 到 DOCM 的转换功能。首先，您需要使用 [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) 将 SVG 文件转换为 DOC。其次，通过使用文字处理 API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)，您可以将 DOC 渲染为 DOCM。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 Java 在 Android 上将 SVG 转换为 DOCM" %}}
1.使用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开SVG文件
2. 使用 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) 将 SVG 转换为 DOC ) 方法
3. 使用 Aspose.Words 的 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类加载 DOC 文件
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) 方法将文档保存为 DOCM 格式并设置 DOCM保存格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您可以直接从 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)通过 Java 轻松使用 Aspose.Total for Android 和安装 [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) 和 [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) 在您的应用程序中。

或者，您可以从 [下载](https://releases.aspose.com/total/androidjava) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load SVG file with an instance of Document class
Document document = new Document("template.svg");
// save SVG as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOCM
outputDocument.save("output.docm", SaveFormat.DOCM);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 Java 在 Android 上获取 SVG 文件信息" %}}
在将 SVG 转换为 DOCM 之前，您可能需要有关文档的信息，包括作者、创建日期、关键字、修改日期、主题和标题。此信息有助于转换过程的决策。使用强大的 [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API，您可以获得所有内容。要获取有关 SVG 文件的文件特定信息，首先使用 [getInfo](https://参考.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) 方法。一旦检索到 DocumentInfo 对象，您就可以获取各个属性的值。
{{% blocks/products/pf/feature-page-code %}}

```java
// load SVG document
Document doc = new Document("template.svg");
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

{{% blocks/products/pf/feature-page-section  h2="通过 Java 在 Android 中的 DOCM 文档中插入尾注" %}}
除了文档转换，您还可以使用 [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API 在您的 Android 应用程序中添加许多其他功能。该功能之一是在 DOCM 文档中插入尾注和编号。如果要在 DOCM 文档中插入脚注或尾注，请使用 DocumentBuilder.InsertFootnote 方法。此方法在文档中插入脚注或尾注。 EndnoteOptions 和 FootnoteOptions 类表示脚注和尾注的编号选项。
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
doc.save("output.docm", SaveFormat.DOCM);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/svg-to-flatopc/" name="SVG 至 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/svg-to-dotx/" name="SVG 至 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/svg-to-pcl/" name="SVG 至 PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/svg-to-markdown/" name="SVG 至 MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/svg-to-odt/" name="SVG 至 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/svg-to-rtf/" name="SVG 至 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/svg-to-ps/" name="SVG 至 PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/svg-to-mhtml/" name="SVG 至 MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/svg-to-xamlflow/" name="SVG 至 XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/svg-to-dot/" name="SVG 至 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/svg-to-dotm/" name="SVG 至 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/svg-to-wordml/" name="SVG 至 WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}