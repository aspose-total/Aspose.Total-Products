---
title: Android API to Render MHTML to FLATOPC
description: Transform MHTML to FLATOPC via Android via Java API
url_ignore: /android-java/conversion/mhtml-to-flatopc/
family: total
platformtag: android-java
feature: conversion
informat: MHTML
outformat: FLAT_OPC
otherformats: RTF OTT XAMLFLOW DOTM WORDML MARKDOWN ODT PCL DOTX PS DOCM DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render MHTML to FLATOPC on Android via Java" h2="Convert MHTML to FLATOPC in mobile apps without installing any software" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>
MHTML (MIME HTML) is a web page archive format used to save web pages in a single file. It is a combination of HTML code and resources like images, audio, and video. It is used to save webpages for offline viewing. FLATOPC is a file format used to store documents in an open XML format. It is used to store documents in a single file, which can be opened and edited in any text editor.

<h2>How Aspose.Total helps for mhtml to flatopc conversion</h2>
Integrating MHTML to FLATOPC conversion feature in mobile apps can be done by using two APIs of [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/) package. First, you need to convert MHTML file to DOC using [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). This API provides the capability to convert MHTML to PDF, XPS, TIFF, JPEG, PNG, and other image formats. Secondly, by using Word Processing API [Aspose.Words for Android Java](https://products.aspose.com/words/android-java/), you can render DOC to FLATOPC. This API provides the capability to convert DOC to PDF, XPS, TIFF, JPEG, PNG, and other image formats.

Aspose.Total for Android Java package is a suite of APIs that provides the capability to manipulate documents, images, and other file formats. It includes APIs for PDF, Word, Excel, PowerPoint, and other file formats. It also provides the capability to convert MHTML to DOC and DOC to FLATOPC. The APIs are easy to use and can be integrated into any mobile app. They are also highly reliable and secure.

In conclusion, Aspose.Total for Android Java package provides the capability to integrate MHTML to FLATOPC conversion feature in mobile apps. It includes APIs for PDF, Word, Excel, PowerPoint, and other file formats. It also provides the capability to convert MHTML to DOC and DOC to FLATOPC. The APIs are easy to use and can be integrated into any mobile app. They are also highly reliable and secure.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert MHTML to FLATOPC on Android via Java" %}}
1. Open MHTML file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert MHTML to DOC by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load DOC file by using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class of Aspose.Words  
4. Save the document to FLAT_OPC format using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) method and set FLAT_OPC as SaveFormat
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
// call save method while passing SaveFormat.FLAT_OPC
outputDocument.save("output.flat_opc", SaveFormat.FLAT_OPC);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get MHTML File Information on Android via Java" %}}
Before converting MHTML to FLATOPC, you might need information about the document including author, creation date, keywords, modify date, subject, and title. This information is helpful for the decision making for the conversion process. Using the powerful [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API, you can get all of it. To get file-specific information about a MHTML file, first get the [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) object using [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) method. Once the DocumentInfo object is retrieved, you can get the values of the individual properties.
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

{{% blocks/products/pf/feature-page-section  h2="Insert Endnotes in FLATOPC Document in Android Apps" %}}
Apart from document conversion, you can also add a bunch of other features inside your Android Applications using [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API. One of that feature is inserting endnotes and numbering in FLATOPC document. If you want to insert a footnote or an endnote in a FLATOPC document, please use DocumentBuilder.InsertFootnote method. This method inserts a footnote or endnote into the document. EndnoteOptions and FootnoteOptions classes represent numbering options for footnote and endnote. 
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
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}