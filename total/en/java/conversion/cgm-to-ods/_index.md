---
title: Java API to Render CGM to ODS
description: Export CGM to ODS via Java API without using Microsoft Excel or Adobe Reader
url_ignore: /java/conversion/cgm-to-ods/
family: total
platformtag: java
feature: conversion
informat: CGM
outformat: ODS
otherformats: XLTM XLSB XLSM XLT SXC MD DIF EXCEL CSV XLAM TXT FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Export CGM to ODS via Java" h2="Convert CGM file to ODS by using on premise Java API within any Java J2SE, J2EE, J2ME applications" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is a comprehensive suite of components that enables developers to integrate CGM to ODS conversion feature in their Java applications. This suite includes Aspose.PDF for Java and Aspose.Cells for Java, which can be used in a two-step process to convert CGM to ODS. 

The first step involves using Aspose.PDF for Java to render CGM to XLSX. This component is a powerful PDF manipulation API that enables developers to create, edit, convert, and print PDF documents from within their Java applications. It also provides the ability to render CGM to XLSX, which is a Microsoft Excel spreadsheet format. 

The second step involves using Aspose.Cells for Java to convert XLSX to ODS. This component is a powerful spreadsheet programming API that enables developers to create, manipulate, and convert spreadsheets from within their Java applications. It provides the ability to convert XLSX to ODS, which is an open document spreadsheet format. 

By using Aspose.Total for Java, developers can easily integrate CGM to ODS conversion feature in their Java applications. This suite provides the necessary components to render CGM to XLSX and then convert XLSX to ODS in a two-step process. Aspose.PDF for Java and Aspose.Cells for Java are both powerful APIs that enable developers to create, edit, manipulate, and convert PDF documents and spreadsheets from within their Java applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert CGM File to ODS via Java" %}}
1. Open CGM file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert CGM to XLSX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load XLSX document by using [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class
4. Save the document to ODS format using [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Format APIs" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) in your pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected CGM to ODS via Java" %}}
If your CGM document is password protected, you cannot convert it to ODS without the password. Using the API, you can first open the protected document using a valid password and convert it after it. In order to open the encrypted file, you can initialize a new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert CGM File to ODS with Watermark via Java" %}}
While converting CGM file to ODS, you can also add watermark to your output ODS file format. In order to add a watermark, create a new Workbook to open the converted XLSX file. Select Worksheet via its index, create a Shape and use its addTextEffect function, set colors, transparency and more. After that you can save your XLSX document as ODS with Watermark.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}