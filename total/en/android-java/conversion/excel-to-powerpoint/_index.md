---
title: Export EXCEL to POWERPOINT in Android 
description: Android API to Convert EXCEL to POWERPOINT without using Microsoft Word
url_ignore: /android-java/conversion/excel-to-powerpoint/
family: total
platformtag: android-java
feature: conversion
informat: EXCEL
outformat: POWERPOINT
otherformats: WORD DOC DOCX PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render EXCEL to POWERPOINT on Android via Java" h2="Transform EXCEL to POWERPOINT within your Android Applications without using Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

Converting Excel to PowerPoint is a common requirement for many businesses. It allows users to present their data in a visually appealing way, making it easier to understand and analyze. Additionally, PowerPoint presentations are often used to present data to clients and other stakeholders, making it an important tool for many organizations.

<h2>How Aspose.Total Helps for Excel to PowerPoint Conversion</h2>

Aspose.Total for Android via Java is a package of powerful File Automation APIs that can help you integrate Excel to PowerPoint conversion feature inside your Android applications. It includes two APIs, Aspose.Cells for Android via Java and Aspose.PDF for Android via Java. By using these APIs, you can export Excel to PDF and then convert PDF to PowerPoint.

Aspose.Cells for Android via Java is a powerful API that allows you to export Excel to PDF. It supports a wide range of features, including formatting, styling, and data manipulation. Additionally, it supports a variety of file formats, including XLSX, XLS, CSV, and ODS.

Aspose.PDF for Android via Java is a powerful API that allows you to convert PDF to PowerPoint. It supports a wide range of features, including text extraction, image extraction, and page manipulation. Additionally, it supports a variety of file formats, including PDF, XPS, and EPUB.

By using Aspose.Total for Android via Java, you can easily integrate Excel to PowerPoint conversion feature inside your Android applications. It is a powerful and reliable solution that can help you save time and effort when converting Excel to PowerPoint.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API to Export EXCEL to POWERPOINT" %}}
1. Open EXCEL file using [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class
2. Convert EXCEL to PDF and set SaveFormat to AUTO
3. Load the converted PDF file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
4. Save the document to PPTX format using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Android via Java APIs" %}}
You can easily use Aspose.Total for Android via Java directly from [Maven](https://releases.aspose.com/total/java/) and install [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) and [Aspose.Cells for Android via Java](https://docs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) in your applications.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```java
// load the EXCEL file using Workbook class
Workbook book = new Workbook("input.csv");
// save EXCEL as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in PPTX format
document.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Remove Custom Properties from EXCEL File in Android Apps" %}}
Apart from document conversion, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) provides tons of other features as well. Before the conversion process, you can remove custom properties of EXCEL document. To remove custom properties, call the [DocumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/documentpropertycollection#remove(java.lang.String)) method and pass the name of the document property to be removed.
{{% blocks/products/pf/feature-page-code %}}
```java
// load the EXCEL file using Workbook class
Workbook book = new Workbook("input.csv");
// retrieve a list of all custom document properties of the Excel file
DocumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocumentProperties();
// remove a custom document property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}