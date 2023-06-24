---
title: Java API to Export MHTML to GIF
description: Convert MHTML to GIF using on premise Java API
url_ignore: /java/conversion/mhtml-to-gif/
family: total
platformtag: java
feature: conversion
informat: MHTML
outformat: GIF
otherformats: DOT RTF ODT FLATOPC MARKDOWN PS WORDML PCL DOTM DOTX DOCM OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transform MHTML to GIF via Java" h2="On Premise Java API to Render MHTML to GIF without using any third party application" >}}

{{% blocks/products/pf/feature-page-summary %}}


Converting MHTML to GIF can be done in two simple steps using the powerful APIs from Aspose.Total for Java. Aspose.PDF for Java is a document rendering API that can be used to render MHTML files to DOC. Once the MHTML file is converted to DOC, Aspose.Words for Java can be used to convert the DOC file to GIF.

Aspose.PDF for Java is a powerful document rendering API that can be used to render MHTML files to DOC. It supports a wide range of document formats, including MHTML, HTML, XHTML, XML, and more. It also supports a variety of image formats, including GIF, JPEG, PNG, and more. It is easy to use and provides a wide range of features, such as text extraction, document conversion, and more.

Aspose.Words for Java is a powerful document processing API that can be used to convert DOC files to GIF. It supports a wide range of document formats, including DOC, DOCX, RTF, HTML, and more. It also supports a variety of image formats, including GIF, JPEG, PNG, and more. It is easy to use and provides a wide range of features, such as document conversion, text extraction, and more.

Both APIs come under the Aspose.Total for Java package. Aspose.Total for Java is a comprehensive suite of APIs that can be used to create, edit, and convert documents. It includes APIs for document rendering, document processing, document conversion, and more. It is easy to use and provides a wide range of features, such as text extraction, document conversion, and more.

By using Aspose.PDF for Java and Aspose.Words for Java, you can easily convert MHTML to GIF in two simple steps. First, you need to render MHTML file to DOC using Aspose.PDF for Java. After that, you can use Aspose.Words for Java to convert the DOC file to GIF. Both APIs come under the Aspose.Total for Java package, making it easy to access and use.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert MHTML to GIF" %}}
1. Open MHTML file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert MHTML to DOC by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load DOC file by using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class of Aspose.Words  
4. Save the document to GIF format using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) method and set GIF as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Manipulation APIs" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```java
// load MHTML file with an instance of Document class
Document document = new Document("template.mhtml");
// save MHTML as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.GIF
outputDocument.save("output.gif", SaveFormat.GIF);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Password Protected MHTML Document via Java" %}}
While converting MHTML to GIF, even if your document is password protected, you can still open it using PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). In order to open the encrypted file, you need to create a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) object and open the MHTML using the owner’s password. 
{{% blocks/products/pf/feature-page-code %}}
```cs// open encrypted document
Document document = new Document("input.mhtml", "password");
// save MHTML as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Save GIF Document to a Database via Java" %}}
While saving your input document to GIF file format, you can also save your document to database instead of a file system. You may need to implement storing and retrieving Document objects to and from a database. This would be necessary if you were implementing any type of content management system. In order to save your GIF to database it is often necessary to serialize the document to obtain a byte array. This can be done using [Aspose.Words for Java](https://products.aspose.com/words/Java/) API. After getting your byte array, you can store it in the database using SQL statement. 
{{% blocks/products/pf/feature-page-code %}}
```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.GIF);
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