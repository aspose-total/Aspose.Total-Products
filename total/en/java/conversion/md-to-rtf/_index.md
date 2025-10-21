---
title: Java API to Export MD to RTF
description: Convert MD to RTF using on premise Java API
url_ignore: /java/conversion/md-to-rtf/
family: total
platformtag: java
feature: conversion
informat: MD
outformat: RTF
otherformats: DOTM DOT PCL ODT PS MARKDOWN DOCM XAMLFLOW WORDML OTT DOTX FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transform MD to RTF via Java" h2="On Premise Java API to Render MD to RTF without using any third party application" >}}

{{% blocks/products/pf/feature-page-summary %}}

Converting a Markdown (MD) file to Rich Text Format (RTF) is a simple two-step process. The first step is to render the MD file to a DOC file using Aspose.PDF for Java. Aspose.PDF for Java is a powerful PDF processing API that is part of the Aspose.Total for Java package. Once the MD file is rendered to a DOC file, the second step is to use Aspose.Words for Java to convert the DOC file to RTF. Aspose.Words for Java is a powerful document processing API that is also part of the Aspose.Total for Java package. 

Using Aspose.PDF for Java, you can easily render MD files to DOC files. This API provides a wide range of features such as the ability to convert MD to DOC, PDF, HTML, XPS, and other formats. It also supports various image formats such as JPEG, PNG, TIFF, and BMP. Additionally, it can be used to extract text from PDF documents and to add annotations and bookmarks to PDF documents. 

Once the MD file is rendered to a DOC file, Aspose.Words for Java can be used to convert the DOC file to RTF. This API provides a wide range of features such as the ability to convert DOC to RTF, DOCX, HTML, PDF, and other formats. It also supports various image formats such as JPEG, PNG, TIFF, and BMP. Additionally, it can be used to extract text from documents and to add annotations and bookmarks to documents. 

By using Aspose.PDF for Java and Aspose.Words for Java, you can easily convert MD files to RTF files. Both APIs are part of the Aspose.Total for Java package, which provides a comprehensive set of APIs for working with various file formats. With these APIs, you can easily render MD files to DOC files and then convert the DOC files to RTF files.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert MD to RTF" %}}
1. Open MD file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert MD to DOC by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load DOC file by using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class of Aspose.Words  
4. Save the document to RTF format using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) method and set RTF as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Password Protected MD Document via Java" %}}
While converting MD to RTF, even if your document is password protected, you can still open it using PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). In order to open the encrypted file, you need to create a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) object and open the MD using the owner’s password. 
{{% blocks/products/pf/feature-page-code %}}
```cs// open encrypted document
Document document = new Document("input.md", "password");
// save MD as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Save RTF Document to a Database via Java" %}}
While saving your input document to RTF file format, you can also save your document to database instead of a file system. You may need to implement storing and retrieving Document objects to and from a database. This would be necessary if you were implementing any type of content management system. In order to save your RTF to database it is often necessary to serialize the document to obtain a byte array. This can be done using [Aspose.Words for Java](https://products.aspose.com/words/Java/) API. After getting your byte array, you can store it in the database using SQL statement. 
{{% blocks/products/pf/feature-page-code %}}
```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.RTF);
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