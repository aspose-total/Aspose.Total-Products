---
title: Android API to Render MHTML to DOTM
description: Transform MHTML to DOTM via Android via Java API
url_ignore: /android-java/conversion/mhtml-to-dotm/
family: total
platformtag: android-java
feature: conversion
informat: MHTML
outformat: DOTM
otherformats: MARKDOWN FLATOPC OTT ODT RTF PS XAMLFLOW PCL WORDML DOT DOCM DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render MHTML to DOTM on Android via Java" h2="Convert MHTML to DOTM in mobile apps without installing any software" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>
MHTML to DOTM conversion is a useful feature for mobile apps. MHTML is a web page archive format which is used to save web pages for offline viewing. It is a combination of HTML code and resources such as images, audio, and video. DOTM is a Microsoft Word template file format which is used to store settings and macros. It is used to create documents with the same formatting and styles. Converting MHTML to DOTM allows users to create documents with the same formatting and styles as the original web page.

<h2>How Aspose.Total Helps for MHTML to DOTM Conversion</h2>
Aspose.Total for Android Java is a comprehensive package of APIs that can be used to integrate MHTML to DOTM conversion feature in mobile apps. It includes two APIs, Aspose.PDF for Android via Java and Aspose.Words for Android Java. 

The Aspose.PDF for Android via Java API can be used to convert MHTML files to DOC. It supports a wide range of features such as text extraction, image extraction, document conversion, and much more. 

The Aspose.Words for Android Java API can be used to render DOC to DOTM. It supports a wide range of features such as document manipulation, document conversion, mail merge, and much more. It also supports a variety of file formats such as DOC, DOCX, DOT, DOTX, and DOTM. 

By using the two APIs of Aspose.Total for Android Java package, developers can easily integrate MHTML to DOTM conversion feature in their mobile apps. It provides a simple and efficient way to convert MHTML files to DOTM documents with the same formatting and styles as the original web page.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert MHTML to DOTM on Android via Java" %}}
1. Open MHTML file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert MHTML to DOC by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load DOC file by using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class of Aspose.Words  
4. Save the document to DOTM format using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) method and set DOTM as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Android via Java APIs" %}}
You can easily use Aspose.Total for Android via Java directly from [Maven](https://releases.aspose.com/total/java/) and install [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) and [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in your applications.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```java
// load MHTML file with an instance of Document class
Document document = new Document("template.mhtml");
// save MHTML as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOTM
outputDocument.save("output.dotm", SaveFormat.DOTM);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get MHTML File Information on Android via Java" %}}
Before converting MHTML to DOTM, you might need information about the document including author, creation date, keywords, modify date, subject, and title. This information is helpful for the decision making for the conversion process. Using the powerful [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API, you can get all of it. To get file-specific information about a MHTML file, first get the [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) object using [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) method. Once the DocumentInfo object is retrieved, you can get the values of the individual properties.
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

{{% blocks/products/pf/feature-page-section  h2="Insert Endnotes in DOTM Document in Android Apps" %}}
Apart from document conversion, you can also add a bunch of other features inside your Android Applications using [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API. One of that feature is inserting endnotes and numbering in DOTM document. If you want to insert a footnote or an endnote in a DOTM document, please use DocumentBuilder.InsertFootnote method. This method inserts a footnote or endnote into the document. EndnoteOptions and FootnoteOptions classes represent numbering options for footnote and endnote. 
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
doc.save("output.dotm", SaveFormat.DOTM);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}