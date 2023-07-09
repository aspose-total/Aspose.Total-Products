---
title: Android API to Render TEX to MHTML
description: Transform TEX to MHTML via Android via Java API
url_ignore: /android-java/conversion/tex-to-mhtml/
family: total
platformtag: android-java
feature: conversion
informat: TEX
outformat: MHTML
otherformats: WORDML FLATOPC OTT PCL ODT XAMLFLOW PS DOCM DOTM MARKDOWN DOT DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render TEX to MHTML on Android via Java" h2="Convert TEX to MHTML in mobile apps without installing any software" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

The need to convert TEX to MHTML arises when you want to integrate the feature of TEX to MHTML conversion in your mobile apps. MHTML is a web page archive format which is used to combine resources such as HTML, images, and other media into a single file. It is used to save webpages for offline viewing and is also used to transfer webpages from one computer to another.

<h2>How Aspose.Total helps for tex to mhtml conversion</h2>

Aspose.Total for Android Java is a package that provides two APIs to help you integrate the feature of TEX to MHTML conversion in your mobile apps. The first API is Aspose.PDF for Android via Java which helps you to convert TEX file to DOC. The second API is Aspose.Words for Android Java which helps you to render DOC to MHTML. 

To use these APIs, you need to add the Aspose.Total for Android Java package to your project. After that, you can use the APIs to convert TEX to MHTML. The Aspose.PDF for Android via Java API provides a wide range of features to help you convert TEX to DOC. It supports various formats such as TEX, HTML, XPS, and PDF. It also provides features such as text extraction, image extraction, and page manipulation. 

The Aspose.Words for Android Java API provides features to help you render DOC to MHTML. It supports various formats such as DOC, DOCX, RTF, HTML, and MHTML. It also provides features such as document manipulation, text manipulation, and image manipulation. 

By using the two APIs of Aspose.Total for Android Java package, you can easily integrate the feature of TEX to MHTML conversion in your mobile apps. The APIs provide a wide range of features to help you convert TEX to MHTML quickly and easily.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert TEX to MHTML on Android via Java" %}}
1. Open TEX file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert TEX to DOC by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load DOC file by using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class of Aspose.Words  
4. Save the document to MHTML format using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) method and set MHTML as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Android via Java APIs" %}}
You can easily use Aspose.Total for Android via Java directly from [Maven](https://releases.aspose.com/total/java/) and install [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) and [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in your applications.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```java
// load TEX file with an instance of Document class
Document document = new Document("template.tex");
// save TEX as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.MHTML
outputDocument.save("output.mhtml", SaveFormat.MHTML);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get TEX File Information on Android via Java" %}}
Before converting TEX to MHTML, you might need information about the document including author, creation date, keywords, modify date, subject, and title. This information is helpful for the decision making for the conversion process. Using the powerful [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API, you can get all of it. To get file-specific information about a TEX file, first get the [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) object using [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) method. Once the DocumentInfo object is retrieved, you can get the values of the individual properties.
{{% blocks/products/pf/feature-page-code %}}
```java
// load TEX document
Document doc = new Document("template.tex");
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

{{% blocks/products/pf/feature-page-section  h2="Insert Endnotes in MHTML Document in Android via Java" %}}
Apart from document conversion, you can also add a bunch of other features inside your Android Applications using [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API. One of that feature is inserting endnotes and numbering in MHTML document. If you want to insert a footnote or an endnote in a MHTML document, please use DocumentBuilder.InsertFootnote method. This method inserts a footnote or endnote into the document. EndnoteOptions and FootnoteOptions classes represent numbering options for footnote and endnote. 
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
doc.save("output.mhtml", SaveFormat.MHTML);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}