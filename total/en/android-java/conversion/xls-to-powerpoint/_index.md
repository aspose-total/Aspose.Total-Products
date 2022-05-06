---
title: Export XLS to POWERPOINT in Android 
description: Android API to Convert XLS to POWERPOINT without using Microsoft Word
url_ignore: /android-java/conversion/xls-to-powerpoint/
family: total
platformtag: android-java
feature: conversion
informat: XLS
outformat: PPTX
otherformats: PPTX DOC DOCX WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render XLS to POWERPOINT on Android via Java" h2="Transform XLS to POWERPOINT within your Android Applications without using Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) is a package of powerful File Automation APIs. By using two of its APIs, you can integrate XLS to POWERPOINT conversion feature inside your Android applications. In the first step you can export XLS to PDF by using [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). After that, by using [Aspose.PDF for Android via  Java](https://products.aspose.com/pdf/android-java/), you can convert PDF to POWERPOINT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API to Export XLS to POWERPOINT" %}}
1. Open XLS file using [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) class
2. Convert XLS to PDF and set SaveFormat to AUTO
3. Load the converted PDF file using [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) class
4. Save the document to PPTX format using [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Android via Java APIs" %}}
You can easily use Aspose.Total for Android via Java directly from [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) and install [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) and [Aspose.Cells for Android via Java](https://docs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) in your applications.

Alternatively, you can get a ZIP file from [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```java
// load the XLS file using Workbook class
Workbook book = new Workbook("input.xls");
// save XLS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in PPTX format
document.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Remove Custom Properties from XLS File in Android via Java" %}}
Apart from document conversion, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) provides tons of other features as well. Before the conversion process, you can remove custom properties of XLS document. To remove custom properties, call the [DocumentPropertyCollection.remove](https://apireference.aspose.com/cells/java/com.aspose.cells/documentpropertycollection#remove(java.lang.String)) method and pass the name of the document property to be removed.
{{% blocks/products/pf/feature-page-code %}}
```java
// load the XLS file using Workbook class
Workbook book = new Workbook("input.xls");
// retrieve a list of all custom document properties of the Excel file
DocumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocumentProperties();
// remove a custom document property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}