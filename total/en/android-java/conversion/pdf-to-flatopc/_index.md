---
title: Android API to Render PDF to FLATOPC
description: Transform PDF to FLATOPC via Android via Java API
url_ignore: /android-java/conversion/pdf-to-flatopc/
family: total
platformtag: android-java
feature: conversion
informat: PDF
outformat: FLAT_OPC
otherformats: MHTML DOTM PCL WORDML RTF OTT XAMLFLOW DOTX DOT ODT PS MARKDOWN
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PDF to FLATOPC on Android via Java" h2="Convert PDF to FLATOPC in mobile apps without installing any software" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

PDF to FLATOPC conversion is a useful feature for mobile apps. It allows users to convert PDF files to FLATOPC format, which is a popular format for document exchange. This conversion process can be done quickly and easily, making it a great addition to any mobile app.

<h2>How Aspose.Total Helps for PDF to FLATOPC Conversion</h2>

Aspose.Total for Android Java is a package that provides two APIs for PDF to FLATOPC conversion. The first API is Aspose.PDF for Android via Java, which is used to convert PDF files to DOC format. The second API is Aspose.Words for Android Java, which is used to render DOC files to FLATOPC format. By using these two APIs, developers can easily integrate PDF to FLATOPC conversion feature into their mobile apps. This makes it easy for users to quickly and easily convert PDF files to FLATOPC format.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert PDF to FLATOPC on Android via Java" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert PDF to DOC by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load DOC file by using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class of Aspose.Words  
4. Save the document to FLAT_OPC format using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) method and set FLAT_OPC as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Android via Java APIs" %}}
You can easily use Aspose.Total for Android via Java directly from [Maven](https://releases.aspose.com/total/java/) and install [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) and [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in your applications.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```java
// load PDF file with an instance of Document class
Document document = new Document("template.pdf");
// save PDF as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.FLAT_OPC
outputDocument.save("output.flat_opc", SaveFormat.FLAT_OPC);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get PDF File Information on Android via Java" %}}
Before converting PDF to FLATOPC, you might need information about the document including author, creation date, keywords, modify date, subject, and title. This information is helpful for the decision making for the conversion process. Using the powerful [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API, you can get all of it. To get file-specific information about a PDF file, first get the [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) object using [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) method. Once the DocumentInfo object is retrieved, you can get the values of the individual properties.
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