---
title: Java API to Export MD to OTT
description: Convert MD to OTT using on premise Java API
url_ignore: /java/conversion/md-to-ott/
family: total
platformtag: java
feature: conversion
informat: MD
outformat: OTT
otherformats: DOT FLATOPC DOTX ODT XAMLFLOW PS WORDML PCL MHTML MARKDOWN DOTM DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transform MD to OTT via Java" h2="On Premise Java API to Render MD to OTT without using any third party application" >}}

{{% blocks/products/pf/feature-page-summary %}}


Converting Markdown (MD) to OpenDocument Text (OTT) is a simple two-step process. The first step is to render the MD file to a DOC file using the powerful Aspose.PDF for Java API. Aspose.PDF for Java is part of the Aspose.Total for Java package, which provides a comprehensive set of APIs for document processing. 

Once the MD file is converted to a DOC file, the second step is to use the Aspose.Words for Java API to convert the DOC file to an OTT file. Aspose.Words for Java is a powerful document processing API that enables you to easily convert documents from one format to another. It also provides a wide range of features, such as document manipulation, text extraction, and document conversion. 

Using the two APIs, Aspose.PDF for Java and Aspose.Words for Java, you can quickly and easily convert MD files to OTT files. Aspose.Total for Java provides a comprehensive set of APIs for document processing, making it the perfect choice for converting MD to OTT. With just two simple steps, you can easily convert MD files to OTT files.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert MD to OTT" %}}
1. Open MD file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert MD to DOC by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load DOC file by using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class of Aspose.Words  
4. Save the document to OTT format using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) method and set OTT as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-ott.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Password Protected MD Document via Java" %}}
While converting MD to OTT, even if your document is password protected, you can still open it using PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). In order to open the encrypted file, you need to create a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) object and open the MD using the owner’s password. 
{{% blocks/products/pf/feature-page-code %}}
```cs// open encrypted document
Document document = new Document("input.md", "password");
// save MD as a DOC 
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

{{< blocks/products/pf/agp/feature-section >}}



Converting Markdown (MD) into OTT (OpenDocument Text Template) supports scalable template creation for open-source office suites. OTT templates maintain consistent formatting while allowing teams to generate multiple documents from a stable style foundation.



{{% blocks/products/pf/agp/feature-section-col title="Key Use Cases" %}}



* Creating OTT templates for multilingual document production.

* Building structured report templates from Markdown-based guidelines.

* Standardizing office documentation for open-source environments.

* Generating reusable ODT document formats for NGOs or public institutions.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Automation Scenarios" %}}



* Automated OTT generation in open-source publishing workflows.

* Rolling template updates synchronized from Markdown version control.

* Batch producing template sets for distributed teams using LibreOffice.

* Government or non-profit systems generating OTT templates on schedule.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}