---
title: Android API to Render XPS to DOTM
description: Transform XPS to DOTM via Android via Java API
url_ignore: /android-java/conversion/xps-to-dotm/
family: total
platformtag: android-java
feature: conversion
informat: XPS
outformat: DOTM
otherformats: WORDML DOT DOTX XAMLFLOW OTT PCL FLATOPC PS MHTML MARKDOWN ODT DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render XPS to DOTM on Android via Java" h2="Convert XPS to DOTM in mobile apps without installing any software" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>
XPS to DOTM conversion is a useful feature for mobile apps. XPS is a fixed document format developed by Microsoft, while DOTM is a template file format used by Microsoft Word. By converting XPS to DOTM, users can create documents with a consistent look and feel, and can also save time by reusing existing templates.

<h2>How Aspose.Total Helps for XPS to DOTM Conversion</h2>
Aspose.Total for Android Java is a comprehensive suite of APIs that can be used to integrate XPS to DOTM conversion feature in mobile apps. The package includes two APIs: Aspose.PDF for Android via Java and Aspose.Words for Android Java.

Using Aspose.PDF for Android via Java, you can convert XPS files to DOC format. This API supports a wide range of features, including text extraction, image extraction, page manipulation, and more.

Once the XPS file is converted to DOC, you can use Aspose.Words for Android Java to render the DOC file to DOTM. This API supports a wide range of features, including document manipulation, text manipulation, mail merge, and more.

By using Aspose.Total for Android Java, you can quickly and easily integrate XPS to DOTM conversion feature in your mobile apps. This will help you save time and effort, and will also ensure that your documents have a consistent look and feel.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert XPS to DOTM on Android via Java" %}}
1. Open XPS file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert XPS to DOC by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load DOC file by using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class of Aspose.Words  
4. Save the document to DOTM format using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) method and set DOTM as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Android via Java APIs" %}}
You can easily use Aspose.Total for Android via Java directly from [Maven](https://releases.aspose.com/total/java/) and install [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) and [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in your applications.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOTM
outputDocument.save("output.dotm", SaveFormat.DOTM);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get XPS File Information on Android via Java" %}}
Before converting XPS to DOTM, you might need information about the document including author, creation date, keywords, modify date, subject, and title. This information is helpful for the decision making for the conversion process. Using the powerful [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API, you can get all of it. To get file-specific information about a XPS file, first get the [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) object using [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) method. Once the DocumentInfo object is retrieved, you can get the values of the individual properties.
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

{{% blocks/products/pf/feature-page-section  h2="Insert Endnotes in DOTM Document in Android via Java" %}}
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
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}