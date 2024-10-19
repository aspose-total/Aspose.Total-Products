---
title: Java API to Export EPUB to OTT
description: Convert EPUB to OTT using on premise Java API
url_ignore: /java/conversion/epub-to-ott/
family: total
platformtag: java
feature: conversion
informat: EPUB
outformat: OTT
otherformats: MARKDOWN XAMLFLOW RTF DOCM PCL DOTX DOT WORDML FLATOPC MHTML DOTM PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transform EPUB to OTT via Java" h2="On Premise Java API to Render EPUB to OTT without using any third party application" >}}

{{% blocks/products/pf/feature-page-summary %}}


Converting EPUB to OTT is a simple two-step process that can be done using the powerful Aspose.Total for Java package. The first step is to render the EPUB file to DOC using Aspose.PDF for Java. This API is a powerful PDF processing library that allows you to easily convert EPUB to DOC. It also provides a wide range of features such as creating, editing, and converting PDF documents.

The second step is to convert the DOC file to OTT using Aspose.Words for Java. This API is a powerful document processing library that enables you to easily convert DOC to OTT. It also provides a wide range of features such as creating, editing, and converting documents.

Aspose.Total for Java is a comprehensive package that includes both Aspose.PDF for Java and Aspose.Words for Java. It provides a wide range of features and tools that make it easy to convert EPUB to OTT. It also offers a range of other features such as creating, editing, and converting documents, as well as creating and manipulating PDF documents.

Overall, Aspose.Total for Java is an ideal solution for converting EPUB to OTT. It provides a simple two-step process that makes it easy to convert EPUB to OTT. It also offers a wide range of features and tools that make it easy to create, edit, and convert documents, as well as manipulate PDF documents.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert EPUB to OTT" %}}
1. Open EPUB file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert EPUB to DOC by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load DOC file by using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class of Aspose.Words  
4. Save the document to OTT format using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) method and set OTT as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```java
// load EPUB file with an instance of Document class
Document document = new Document("template.epub");
// save EPUB as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.OTT
outputDocument.save("output.ott", SaveFormat.OTT);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Password Protected EPUB Document via Java" %}}
While converting EPUB to OTT, even if your document is password protected, you can still open it using PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). In order to open the encrypted file, you need to create a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) object and open the EPUB using the owner’s password. 
{{% blocks/products/pf/feature-page-code %}}
```cs// open encrypted document
Document document = new Document("input.epub", "password");
// save EPUB as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Save OTT Document to a Database via Java" %}}
While saving your input document to OTT file format, you can also save your document to database instead of a file system. You may need to implement storing and retrieving Document objects to and from a database. This would be necessary if you were implementing any type of content management system. In order to save your OTT to database it is often necessary to serialize the document to obtain a byte array. This can be done using [Aspose.Words for Java](https://products.aspose.com/words/Java/) API. After getting your byte array, you can store it in the database using SQL statement. 
{{% blocks/products/pf/feature-page-code %}}
```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.OTT);
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