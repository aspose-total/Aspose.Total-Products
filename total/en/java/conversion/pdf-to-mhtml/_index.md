---
title: Online PDF to MHTML Conversion or Develop Java based Application to Convert PDF Files
description: Free online app to convert PDF to MHTML files. Java conversion library code for PDF documents. 

family: total
platformtag: Java
feature: conversion
informat: PDF
outformat: MHTML
otherformats: XAMLFLOW DOTX OTT RTF WORDML MARKDOWN PCL PS FLATOPC DOTM DOT DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Online PDF to MHTML Conversion App and Java Code to Convert PDF Files" h2="Develop powerful Java based PDF conversion and exporting application. Convert single or multiple PDF files to MHTML and other formats via Java automation API. Freely convert PDF files online via app with instant download." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="Free Online PDF to MHTML Conversion App" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=mhtml&from=pdf" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert PDF to MHTML Files Online using App" %}}

1. Upload PDF files to convert
1. Wait for few seconds or more depending on PDF size
1. Keep an eye on uploading status bar
1. Click the "Convert" button
1. PDF will be converted into MHTML document
1. Download the converted MHTML file

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Convert PDF to MHTML via Java Automation API" %}}


1. Open PDF file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert PDF to DOC by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load DOC file by using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class of Aspose.Words  
4. Save the document to MHTML format using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) method and set MHTML as SaveFormat



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Java Code for PDF to MHTML Conversion" offSpacer="" %}}

```java
// load PDF file with an instance of Document class
Document document = new Document("template.pdf");
// save PDF as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.MHTML
outputDocument.save("output.mhtml", SaveFormat.MHTML);   
```


{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

Few more cases for saving PDF to MHTML with other features like Open Password Protected PDF Document via Java, Save MHTML Document to a Database via Java.

{{% blocks/products/pf/feature-page-code %}}

```cs// open encrypted document
Document document = new Document("input.pdf", "password");
// save PDF as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.MHTML);
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

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>Develop PDF File Conversion Application using Java</h2>

Need to develop Java based software application to easily save and export PDF files to MHTML document ? With [Aspose.Total for Java](https://products.aspose.com/total/java/), any Java developer can integrate the above API code to program the conversion application across variety of formats including Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, Email files, Images (JPG, PNG, BMP, GIF) and other formats. Powerful Java library for document conversion, supports many popular formats including PDF format. Exporting and rendering documents to other formats, programmers can use Aspose.Total for Java child APIs inlcluding [Aspose.Words for Java](https://products.aspose.com/words/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) and more.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PDF Conversion Library for Java" %}}

There are alternative options to integrate Aspose.Total for Java onto your system. Please choose one that resembles your needs and follow the step-by-step instructions:<br /><br />

- Use Aspose.Total for Java directly from a Maven based project and include relevant child API in pom.xml.
- Alternatively, one can get a ZIP file from [downloads](https://releases.aspose.com/total/java).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Saving PDF to MHTML App Requirements" %}}

Any Operating System that can run the Java Runtime Environment (JRE) can run Aspose.Total for Java. The following lists mostly, but not all, supported Operating Systems. <br /><br />
- Microsoft Windows
- Linux : Ubuntu, OpenSUSE, CentOS and others
- macOS : 10.9 (Mavericks) and later
- Mobile : Android, iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}