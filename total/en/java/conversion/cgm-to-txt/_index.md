---
title: Java API to Render CGM to TXT
description: Export CGM to TXT via Java API without using Microsoft Excel or Adobe Reader
url_ignore: /java/conversion/cgm-to-txt/
family: total
platformtag: java
feature: conversion
informat: CGM
outformat: TXT
otherformats: XLAM FODS XLTM ODS MD DIF EXCEL CSV XLTX XLT SXC XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Export CGM to TXT via Java" h2="Convert CGM file to TXT by using on premise Java API within any Java J2SE, J2EE, J2ME applications" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for Java is a comprehensive suite of components that enables developers to easily integrate CGM to TXT conversion feature into their Java applications. This two-step process begins with Aspose.PDF for Java, which is used to render CGM to XLSX. Once the XLSX file is created, Aspose.Cells for Java can be used to convert it to TXT.

Aspose.PDF for Java is a powerful PDF manipulation API that enables developers to create, edit, convert, and manipulate PDF documents without the need for any external dependencies. It can be used to render CGM to XLSX, allowing developers to quickly and easily convert CGM files to the XLSX format.

Aspose.Cells for Java is a Spreadsheet Programming API that enables developers to create, edit, and manipulate spreadsheets without the need for any external dependencies. It can be used to convert XLSX to TXT, allowing developers to quickly and easily convert XLSX files to the TXT format.

By using Aspose.Total for Java, developers can easily integrate CGM to TXT conversion feature into their Java applications. This two-step process begins with Aspose.PDF for Java, which is used to render CGM to XLSX. Once the XLSX file is created, Aspose.Cells for Java can be used to convert it to TXT. This process is quick and easy, and allows developers to quickly and easily convert CGM files to the TXT format.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert CGM File to TXT via Java" %}}
1. Open CGM file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert CGM to XLSX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load XLSX document by using [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class
4. Save the document to TXT format using [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Format APIs" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) in your pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected CGM to TXT via Java" %}}
If your CGM document is password protected, you cannot convert it to TXT without the password. Using the API, you can first open the protected document using a valid password and convert it after it. In order to open the encrypted file, you can initialize a new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert CGM File to TXT with Watermark via Java" %}}
While converting CGM file to TXT, you can also add watermark to your output TXT file format. In order to add a watermark, create a new Workbook to open the converted XLSX file. Select Worksheet via its index, create a Shape and use its addTextEffect function, set colors, transparency and more. After that you can save your XLSX document as TXT with Watermark.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}