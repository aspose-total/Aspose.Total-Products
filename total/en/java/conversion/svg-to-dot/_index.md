---
title: Java API to Export SVG to DOT
description: Convert SVG to DOT using on premise Java API
url_ignore: /java/conversion/svg-to-dot/
family: total
platformtag: java
feature: conversion
informat: SVG
outformat: DOT
otherformats: PS WORDML RTF FLATOPC XAMLFLOW ODT MARKDOWN OTT PCL DOTM DOCM MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transform SVG to DOT via Java" h2="On Premise Java API to Render SVG to DOT without using any third party application" >}}

{{% blocks/products/pf/feature-page-summary %}}

Converting SVG to DOT is a simple two-step process. To begin, you need to render the SVG file to DOC using Aspose.PDF for Java. Aspose.PDF for Java is a powerful document processing API that is part of the Aspose.Total for Java package. Once the SVG file is rendered to DOC, you can then use Aspose.Words for Java to convert the DOC to DOT. Aspose.Words for Java is also part of the Aspose.Total for Java package. 

The Aspose.Total for Java package provides a comprehensive set of APIs for document processing. It includes APIs for working with a variety of file formats, including PDF, DOC, DOT, and SVG. Aspose.PDF for Java is a powerful API for rendering SVG files to DOC. It provides a range of features for manipulating PDF documents, including the ability to convert SVG to DOC. Aspose.Words for Java is a powerful API for converting DOC to DOT. It provides a range of features for manipulating DOC documents, including the ability to convert DOC to DOT. 

By using Aspose.Total for Java, you can easily convert SVG to DOT in two simple steps. First, you need to render the SVG file to DOC using Aspose.PDF for Java. Then, you can use Aspose.Words for Java to convert the DOC to DOT. With Aspose.Total for Java, you can quickly and easily convert SVG to DOT.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert SVG to DOT" %}}
1. Open SVG file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert SVG to DOC by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load DOC file by using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class of Aspose.Words  
4. Save the document to DOT format using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) method and set DOT as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Manipulation APIs" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```java
// load SVG file with an instance of Document class
Document document = new Document("template.svg");
// save SVG as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOT
outputDocument.save("output.dot", SaveFormat.DOT);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Password Protected SVG Document via Java" %}}
While converting SVG to DOT, even if your document is password protected, you can still open it using PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). In order to open the encrypted file, you need to create a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) object and open the SVG using the owner’s password. 
{{% blocks/products/pf/feature-page-code %}}
```cs// open encrypted document
Document document = new Document("input.svg", "password");
// save SVG as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Save DOT Document to a Database via Java" %}}
While saving your input document to DOT file format, you can also save your document to database instead of a file system. You may need to implement storing and retrieving Document objects to and from a database. This would be necessary if you were implementing any type of content management system. In order to save your DOT to database it is often necessary to serialize the document to obtain a byte array. This can be done using [Aspose.Words for Java](https://products.aspose.com/words/Java/) API. After getting your byte array, you can store it in the database using SQL statement. 
{{% blocks/products/pf/feature-page-code %}}
```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.DOT);
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
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}