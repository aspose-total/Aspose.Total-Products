---
title: Java API to Export PS to WORDML
description: Convert PS to WORDML using on premise Java API
url_ignore: /java/conversion/ps-to-wordml/
family: total
platformtag: java
feature: conversion
informat: PS
outformat: WORD_ML
otherformats: FLATOPC MARKDOWN XAMLFLOW PCL DOTM DOTX MHTML ODT RTF OTT DOT DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transform PS to WORDML via Java" h2="On Premise Java API to Render PS to WORDML without using any third party application" >}}

{{% blocks/products/pf/feature-page-summary %}}


Converting a PostScript (PS) file to WordML (Word Markup Language) can be done in two simple steps using Aspose.Total for Java. Aspose.Total for Java is a suite of powerful document processing APIs that can be used to convert, create, edit, and manipulate a wide range of document formats. 

The first step is to render the PS file to DOC using Aspose.PDF for Java. Aspose.PDF for Java is a powerful PDF processing API that can be used to create, edit, and manipulate PDF documents. It can also be used to convert PDF documents to other popular formats, such as DOC, HTML, and XPS. 

Once the PS file has been converted to DOC, the second step is to use Aspose.Words for Java to convert the DOC to WORDML. Aspose.Words for Java is a powerful document processing API that can be used to create, edit, and manipulate a wide range of document formats, including DOC, DOCX, ODT, and WORDML. It can also be used to convert documents from one format to another, such as from DOC to WORDML. 

By using Aspose.Total for Java, you can easily convert a PS file to WORDML in two simple steps. First, render the PS file to DOC using Aspose.PDF for Java, and then use Aspose.Words for Java to convert the DOC to WORDML. With Aspose.Total for Java, you can quickly and easily convert PS files to WORDML.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert PS to WORDML" %}}
1. Open PS file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert PS to DOC by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load DOC file by using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class of Aspose.Words  
4. Save the document to WORD_ML format using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) method and set WORD_ML as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "f5707d58ebee8d2889c8dbe5aa739d87" "convert-ps-to-wordml.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Password Protected PS Document via Java" %}}
While converting PS to WORDML, even if your document is password protected, you can still open it using PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). In order to open the encrypted file, you need to create a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) object and open the PS using the owner’s password. 
{{% blocks/products/pf/feature-page-code %}}
```cs// open encrypted document
Document document = new Document("input.ps", "password");
// save PS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Save WORDML Document to a Database via Java" %}}
While saving your input document to WORDML file format, you can also save your document to database instead of a file system. You may need to implement storing and retrieving Document objects to and from a database. This would be necessary if you were implementing any type of content management system. In order to save your WORDML to database it is often necessary to serialize the document to obtain a byte array. This can be done using [Aspose.Words for Java](https://products.aspose.com/words/Java/) API. After getting your byte array, you can store it in the database using SQL statement. 
{{% blocks/products/pf/feature-page-code %}}
```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.WORD_ML);
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