---
title: Android API to Render CGM to GIF
description: Transform CGM to GIF via Android via Java API
url_ignore: /android-java/conversion/cgm-to-gif/
family: total
platformtag: android-java
feature: conversion
informat: CGM
outformat: GIF
otherformats: XAMLFLOW DOT MARKDOWN DOCM PCL ODT WORDML DOTM MHTML FLATOPC RTF PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render CGM to GIF on Android via Java" h2="Convert CGM to GIF in mobile apps without installing any software" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

CGM (Computer Graphics Metafile) is a vector graphics format used for storing and exchanging graphics data. It is widely used in the engineering and technical drawing fields. GIF (Graphics Interchange Format) is a bitmap image format which is widely used for web graphics. Converting CGM to GIF can be useful for displaying technical drawings on the web.

<h2>How Aspose.Total helps for cgm to gif conversion</h2>

Aspose.Total for Android Java is a comprehensive package of APIs which can be used to integrate various features into mobile applications. It includes APIs for PDF, Word Processing, Email, and other file formats. By using two APIs of Aspose.Total for Android Java package, you can easily integrate CGM to GIF conversion feature in your mobile apps. 

First you need to convert CGM file to DOC using Aspose.PDF for Android via Java. This API provides a wide range of features for manipulating PDF documents. It can be used to convert CGM to DOC with just a few lines of code. 

Secondly, by using Word Processing API Aspose.Words for Android Java, you can render DOC to GIF. This API provides a wide range of features for manipulating Word documents. It can be used to convert DOC to GIF with just a few lines of code. 

Thus, Aspose.Total for Android Java package can be used to integrate CGM to GIF conversion feature in your mobile apps. It is a comprehensive package of APIs which can be used to integrate various features into mobile applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert CGM to GIF on Android via Java" %}}
1. Open CGM file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert CGM to DOC by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load DOC file by using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class of Aspose.Words  
4. Save the document to GIF format using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) method and set GIF as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Android via Java APIs" %}}
You can easily use Aspose.Total for Android via Java directly from [Maven](https://releases.aspose.com/total/java/) and install [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) and [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in your applications.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```java
// load CGM file with an instance of Document class
Document document = new Document("template.cgm");
// save CGM as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.GIF
outputDocument.save("output.gif", SaveFormat.GIF);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get CGM File Information on Android via Java" %}}
Before converting CGM to GIF, you might need information about the document including author, creation date, keywords, modify date, subject, and title. This information is helpful for the decision making for the conversion process. Using the powerful [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API, you can get all of it. To get file-specific information about a CGM file, first get the [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) object using [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) method. Once the DocumentInfo object is retrieved, you can get the values of the individual properties.
{{% blocks/products/pf/feature-page-code %}}
```java
// load CGM document
Document doc = new Document("template.cgm");
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

{{% blocks/products/pf/feature-page-section  h2="Insert Endnotes in GIF Document in Android via Java" %}}
Apart from document conversion, you can also add a bunch of other features inside your Android Applications using [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API. One of that feature is inserting endnotes and numbering in GIF document. If you want to insert a footnote or an endnote in a GIF document, please use DocumentBuilder.InsertFootnote method. This method inserts a footnote or endnote into the document. EndnoteOptions and FootnoteOptions classes represent numbering options for footnote and endnote. 
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
doc.save("output.gif", SaveFormat.GIF);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}