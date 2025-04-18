---
title: Java API to Export PS to FLATOPC
description: Convert PS to FLATOPC using on premise Java API
url_ignore: /java/conversion/ps-to-flatopc/
family: total
platformtag: java
feature: conversion
informat: PS
outformat: FLAT_OPC
otherformats: PCL MARKDOWN WORDML XAMLFLOW DOTX DOT DOTM RTF OTT MHTML ODT DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transform PS to FLATOPC via Java" h2="On Premise Java API to Render PS to FLATOPC without using any third party application" >}}

{{% blocks/products/pf/feature-page-summary %}}


Converting a PostScript (PS) file to a Flat OPC (FLATOPC) file is a simple two-step process that can be accomplished with the help of Aspose.Total for Java. Aspose.Total for Java is a comprehensive suite of APIs that provide powerful document processing capabilities. 

The first step in the conversion process is to render the PS file to a DOC file using Aspose.PDF for Java. Aspose.PDF for Java is a powerful PDF processing API that enables developers to create, edit, convert, and manipulate PDF documents. It also provides the ability to render a PS file to a DOC file. 

The second step is to convert the DOC file to a FLATOPC file using Aspose.Words for Java. Aspose.Words for Java is a powerful document processing API that enables developers to create, edit, convert, and manipulate Word documents. It also provides the ability to convert a DOC file to a FLATOPC file. 

By using Aspose.Total for Java, developers can easily convert a PS file to a FLATOPC file in just two simple steps. Aspose.PDF for Java can be used to render the PS file to a DOC file, and Aspose.Words for Java can be used to convert the DOC file to a FLATOPC file. This makes it easy for developers to quickly and easily convert PS files to FLATOPC files.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert PS to FLATOPC" %}}
1. Open PS file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert PS to DOC by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load DOC file by using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class of Aspose.Words  
4. Save the document to FLAT_OPC format using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) method and set FLAT_OPC as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "f5707d58ebee8d2889c8dbe5aa739d87" "convert-ps-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Password Protected PS Document via Java" %}}
While converting PS to FLATOPC, even if your document is password protected, you can still open it using PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). In order to open the encrypted file, you need to create a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) object and open the PS using the owner’s password. 
{{% blocks/products/pf/feature-page-code %}}
```cs// open encrypted document
Document document = new Document("input.ps", "password");
// save PS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Save FLATOPC Document to a Database via Java" %}}
While saving your input document to FLATOPC file format, you can also save your document to database instead of a file system. You may need to implement storing and retrieving Document objects to and from a database. This would be necessary if you were implementing any type of content management system. In order to save your FLATOPC to database it is often necessary to serialize the document to obtain a byte array. This can be done using [Aspose.Words for Java](https://products.aspose.com/words/Java/) API. After getting your byte array, you can store it in the database using SQL statement. 
{{% blocks/products/pf/feature-page-code %}}
```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.FLAT_OPC);
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