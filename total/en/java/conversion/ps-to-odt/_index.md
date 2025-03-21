---
title: Java API to Export PS to ODT
description: Convert PS to ODT using on premise Java API
url_ignore: /java/conversion/ps-to-odt/
family: total
platformtag: java
feature: conversion
informat: PS
outformat: ODT
otherformats: DOTX FLATOPC XAMLFLOW RTF DOT DOTM DOCM MARKDOWN OTT MHTML PCL WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transform PS to ODT via Java" h2="On Premise Java API to Render PS to ODT without using any third party application" >}}

{{% blocks/products/pf/feature-page-summary %}}


Converting a PostScript (PS) file to OpenDocument Text (ODT) format can be done in two easy steps. The first step is to render the PS file to a Microsoft Word (DOC) format using the powerful Aspose.PDF for Java API. Aspose.PDF for Java is a part of the Aspose.Total for Java package, which provides a comprehensive set of APIs for document processing.

Once the PS file is converted to DOC, the second step is to use the Aspose.Words for Java API to convert the DOC file to ODT. Aspose.Words for Java is a powerful document processing API that can be used to convert documents from one format to another. It supports a wide range of document formats, including DOC, ODT, and many more.

By using the two APIs provided by Aspose.Total for Java, you can easily convert a PS file to ODT format. The process is simple and straightforward, and the results are of high quality. Furthermore, the APIs are easy to use and can be integrated into any application.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert PS to ODT" %}}
1. Open PS file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert PS to DOC by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load DOC file by using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class of Aspose.Words  
4. Save the document to ODT format using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) method and set ODT as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "f5707d58ebee8d2889c8dbe5aa739d87" "convert-ps-to-odt.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Password Protected PS Document via Java" %}}
While converting PS to ODT, even if your document is password protected, you can still open it using PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). In order to open the encrypted file, you need to create a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) object and open the PS using the owner’s password. 
{{% blocks/products/pf/feature-page-code %}}
```cs// open encrypted document
Document document = new Document("input.ps", "password");
// save PS as a DOC 
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

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}