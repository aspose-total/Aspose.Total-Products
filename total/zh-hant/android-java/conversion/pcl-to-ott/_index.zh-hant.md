---
title: 將 PCL 渲染到 OTT 的 Android API
description: 通過 Android 通過 Java API 將 PCL 轉換為 OTT

family: total
platformtag: cpp
feature: conversion
informat: PCL
outformat: OTT
otherformats: FLATOPC DOT DOTM RTF MHTML WORDML DOCM XAMLFLOW ODT MARKDOWN PS DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 Java 在 Android 上將 PCL 渲染到 OTT" h2="在移動應用程序中將 PCL 轉換為 OTT，無需安裝任何軟件" >}}

{{% blocks/products/pf/feature-page-summary %}}
您可以使用 [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/) 包的兩個 API 在您的移動應用程序中集成 PCL 到 OTT 的轉換功能。首先，您需要使用 [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) 將 PCL 文件轉換為 DOC。其次，通過使用文字處理 API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)，您可以將 DOC 渲染為 OTT。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通過 Java 在 Android 上將 PCL 轉換為 OTT" %}}
1. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)類打開PCL文件
2. 使用 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) 將 PCL 轉換為 DOC ) 方法
3. 使用 Aspose.Words 的 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 類加載 DOC 文件
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) 方法將文檔保存為 OTT 格式並設置 OTT保存格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
您可以直接從 [Maven](https://releases.aspose.com/total/java/)通過 Java 輕鬆使用 Aspose.Total for Android 和安裝 [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) 和 [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) 在您的應用程序中。

或者，您可以從 [下載](https://releases.aspose.com/total/androidjava) 獲取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PCL file with an instance of Document class
Document document = new Document("template.pcl");
// save PCL as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.OTT
outputDocument.save("output.ott", SaveFormat.OTT);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通過 Java 在 Android 上獲取 PCL 文件信息" %}}
在將 PCL 轉換為 OTT 之前，您可能需要有關文檔的信息，包括作者、創建日期、關鍵字、修改日期、主題和標題。此信息有助於轉換過程的決策。使用強大的 [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API，您可以獲得所有內容。要獲取有關 PCL 文件的文件特定信息，首先使用 [getInfo](https://參考.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) 方法。一旦檢索到 DocumentInfo 對象，您就可以獲取各個屬性的值。
{{% blocks/products/pf/feature-page-code %}}

```java
// load PCL document
Document doc = new Document("template.pcl");
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

{{% blocks/products/pf/feature-page-section  h2="通過 Java 在 Android 中的 OTT 文檔中插入尾註" %}}
除了文檔轉換，您還可以使用 [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API 在您的 Android 應用程序中添加許多其他功能。該功能之一是在 OTT 文檔中插入尾註和編號。如果要在 OTT 文檔中插入腳註或尾註，請使用 DocumentBuilder.InsertFootnote 方法。此方法在文檔中插入腳註或尾註。 EndnoteOptions 和 FootnoteOptions 類表示腳註和尾註的編號選項。
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
{{< blocks/products/pf/agp/about-autogen-total >}}{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}