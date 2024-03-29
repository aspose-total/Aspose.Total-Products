---
title: Java API to Export PDF to ODT
description: Convert PDF to ODT using on premise Java API
url_ignore: /java/conversion/pdf-to-odt/
family: total
platformtag: java
feature: conversion
informat: PDF
outformat: ODT
otherformats: XAMLFLOW DOTX OTT DOCM RTF DOTM PCL MARKDOWN FLATOPC MHTML DOT PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transform PDF to ODT via Java" h2="On Premise Java API to Render PDF to ODT without using any third party application" >}}

{{% blocks/products/pf/feature-page-summary %}}

Converting PDF to ODT is a simple two-step process. First, you need to render the PDF file to DOC using Aspose.PDF for Java. Aspose.PDF for Java is a powerful PDF rendering API that is part of the Aspose.Total for Java package. Once the PDF file is rendered to DOC, you can use Aspose.Words for Java to convert the DOC file to ODT. Aspose.Words for Java is a powerful Document Processing API that is also part of the Aspose.Total for Java package. 

The process of converting PDF to ODT is straightforward and easy to follow. First, you need to render the PDF file to DOC using Aspose.PDF for Java. This API provides a wide range of features and options to help you render the PDF file accurately and quickly. Once the PDF file is rendered to DOC, you can use Aspose.Words for Java to convert the DOC file to ODT. This API provides a wide range of features and options to help you convert the DOC file to ODT accurately and quickly. 

By using Aspose.PDF for Java and Aspose.Words for Java, you can easily and quickly convert PDF to ODT. Both APIs are part of the Aspose.Total for Java package, which provides a comprehensive set of APIs for working with a wide range of file formats. With Aspose.Total for Java, you can easily and quickly convert PDF to ODT.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert PDF to ODT" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert PDF to DOC by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load DOC file by using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class of Aspose.Words  
4. Save the document to ODT format using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) method and set ODT as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Manipulation APIs" %}}
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
// call save method while passing SaveFormat.ODT
outputDocument.save("output.odt", SaveFormat.ODT);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Password Protected PDF Document via Java" %}}
While converting PDF to ODT, even if your document is password protected, you can still open it using PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). In order to open the encrypted file, you need to create a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) object and open the PDF using the owner’s password. 
{{% blocks/products/pf/feature-page-code %}}
```cs// open encrypted document
Document document = new Document("input.pdf", "password");
// save PDF as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Save ODT Document to a Database via Java" %}}
While saving your input document to ODT file format, you can also save your document to database instead of a file system. You may need to implement storing and retrieving Document objects to and from a database. This would be necessary if you were implementing any type of content management system. In order to save your ODT to database it is often necessary to serialize the document to obtain a byte array. This can be done using [Aspose.Words for Java](https://products.aspose.com/words/Java/) API. After getting your byte array, you can store it in the database using SQL statement. 
{{% blocks/products/pf/feature-page-code %}}
```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.ODT);
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