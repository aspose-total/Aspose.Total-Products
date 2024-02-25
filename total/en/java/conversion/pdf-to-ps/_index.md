---
title: Export PDF to PS with Java
description: Convert PDF to PS using on premise Java API
family: total
platformtag: java
feature: conversion
informat: PDF
outformat: PS
otherformats: DOTX MARKDOWN RTF DOTM XAMLFLOW ODT PCL OTT WORDML FLATOPC DOCM MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PDF to PS via Java" h2="Java API to Export PDF to PostScript without using any third party application" >}}

{{% blocks/products/pf/feature-page-summary %}}
<h2 class="heading-border">Why Convert PDF Documents to PostScript (PS) via Java?</h2>

There are various reasons for converting a PDF file to PostScript. One reason is printing: some printers and print servers may not be compatible with PDF files, so converting them to PostScript can ensure that the file can be printed on any PostScript-compatible printer. In pre-press, PostScript files are often preferred because they provide more control over the layout and formatting of a document. Converting a PDF file to PostScript can make it easier to adjust the layout and formatting of a document before it goes to print. In some cases, there may be issues with a PDF file that make it difficult to print or view correctly. Converting the file to PostScript can help diagnose and troubleshoot any problems with the file. Additionally, PostScript files are often used for long-term archiving of printed documents, so converting a PDF file to PostScript can ensure that the document is preserved in a format that will be readable in the future. 

<h2 class="heading-border">How Aspose.Total can help in PDF to PS Conversion?</h2>

It is possible to convert PDF to PostScript by following two simple steps. The first step involves rendering the PDF file to DOC using a tool such as Aspose.PDF for Java. The second step is to use a powerful Document Processing API like Aspose.Words for Java to convert the DOC file to PS. Both of these APIs are available as part of the [Aspose.Total for Java](https://products.aspose.com/total/java/).<br><br>

[Aspose.PDF for Java](https://products.aspose.com/pdf/java/) is a reliable tool that allows for the rendering of PDF files to DOC format. This can be useful in situations where a PDF file needs to be converted to a format that is more easily editable or compatible with certain printers.Once the PDF file has been converted to DOC format, Aspose.Words for Java can be used to convert it to PostScript. [Aspose.Words for Java](https://products.aspose.com/words/java/) is a powerful document processing API that allows for the conversion of various document formats to other formats such as PDF, HTML, and EPUB.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert PDF to PS via Java?" %}}
1. Load PDF file using [Aspose.PDF.Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert PDF to DOC by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load DOC file using [Aspose.Words.Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class  
4. Save the document to PS format using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) method and set PS as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Tools Required for PDF to PS Conversion" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```java
// load PDF file with an instance of Document class
Document document = new Document("template.pdf");
// save PDF as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.PS
outputDocument.save("output.ps", SaveFormat.PS);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Password Protected PDF Document via Java" %}}
While converting PDF to PS, even if your document is password protected, you can still open it using PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). In order to open the encrypted file, you need to create a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) object and open the PDF using the owner’s password. 
{{% blocks/products/pf/feature-page-code %}}
```java
// open encrypted document
Document document = new Document("input.pdf", "password");
// save PDF as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Save PS Document to Database as ByteArray via Java" %}}
While saving your input document to PS file format, you can also save your document to database instead of a file system. You may need to implement storing and retrieving Document objects to and from a database. This would be necessary if you were implementing any type of content management system. In order to save your PS to database it is often necessary to serialize the document to obtain a byte array. This can be done using [Aspose.Words for Java](https://products.aspose.com/words/Java/) API. After getting your byte array, you can store it in the database using SQL statement. 
{{% blocks/products/pf/feature-page-code %}}
```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.PS);
    // get the byte array from output steam
    // the byte array now contains the document
    byte[] buffer = aout.toByteArray();
    // get the filename from the document.
    String fileName = doc.getOriginalFileName();
    String filePath = fileName.replace("\\", "\\\\");
    // create the SQL command.
    String commandString = "INSERT INTO Documents (FileName, FileContent) VALUES('" + filePath + "', '" + buffer + "')";
    Statement statement = mConnection.createStatement();
    statement.executeUpdate(commandString);
}  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}