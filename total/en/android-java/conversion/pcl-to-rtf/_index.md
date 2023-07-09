---
title: Android API to Render PCL to RTF
description: Transform PCL to RTF via Android via Java API
url_ignore: /android-java/conversion/pcl-to-rtf/
family: total
platformtag: android-java
feature: conversion
informat: PCL
outformat: RTF
otherformats: DOTM OTT DOTX FLATOPC PS DOT DOCM MHTML MARKDOWN WORDML XAMLFLOW ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PCL to RTF on Android via Java" h2="Convert PCL to RTF in mobile apps without installing any software" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

The Portable Document Format (PDF) is a widely used file format for documents. It is used to store and share documents, and is often used for printing and publishing documents. However, the Rich Text Format (RTF) is a more versatile format, and is often used for creating documents that can be edited and shared across multiple platforms. Therefore, it is often necessary to convert PDF files to RTF files.

<h2>How Aspose.Total Helps for PCL to RTF Conversion</h2>

Aspose.Total for Android Java is a comprehensive package of APIs that can be used to integrate PCL to RTF conversion feature in mobile apps. It includes two APIs, Aspose.PDF for Android via Java and Aspose.Words for Android Java. Aspose.PDF for Android via Java can be used to convert PCL files to DOC format. Aspose.Words for Android Java can then be used to render the DOC file to RTF format. This process is simple and efficient, and can be used to quickly and easily convert PCL files to RTF format.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert PCL to RTF on Android via Java" %}}
1. Open PCL file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert PCL to DOC by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load DOC file by using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class of Aspose.Words  
4. Save the document to RTF format using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) method and set RTF as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Android via Java APIs" %}}
You can easily use Aspose.Total for Android via Java directly from [Maven](https://releases.aspose.com/total/java/) and install [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) and [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in your applications.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```java
// load PCL file with an instance of Document class
Document document = new Document("template.pcl");
// save PCL as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.RTF
outputDocument.save("output.rtf", SaveFormat.RTF);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get PCL File Information on Android via Java" %}}
Before converting PCL to RTF, you might need information about the document including author, creation date, keywords, modify date, subject, and title. This information is helpful for the decision making for the conversion process. Using the powerful [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API, you can get all of it. To get file-specific information about a PCL file, first get the [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) object using [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) method. Once the DocumentInfo object is retrieved, you can get the values of the individual properties.
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

{{% blocks/products/pf/feature-page-section  h2="Insert Endnotes in RTF Document in Android via Java" %}}
Apart from document conversion, you can also add a bunch of other features inside your Android Applications using [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API. One of that feature is inserting endnotes and numbering in RTF document. If you want to insert a footnote or an endnote in a RTF document, please use DocumentBuilder.InsertFootnote method. This method inserts a footnote or endnote into the document. EndnoteOptions and FootnoteOptions classes represent numbering options for footnote and endnote. 
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
doc.save("output.rtf", SaveFormat.RTF);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}