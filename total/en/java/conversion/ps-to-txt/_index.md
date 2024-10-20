---
title: Java API to Render PS to TXT
description: Export PS to TXT via Java API without using Microsoft Excel or Adobe Reader
url_ignore: /java/conversion/ps-to-txt/
family: total
platformtag: java
feature: conversion
informat: PS
outformat: TXT
otherformats: XLSB TSV ODS XLTM XLSM SXC CSV MD DIF EXCEL XLAM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Export PS to TXT via Java" h2="Convert PS file to TXT by using on premise Java API within any Java J2SE, J2EE, J2ME applications" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is a comprehensive suite of APIs that enables developers to integrate a wide range of features into their Java applications. One of the features that can be integrated is the ability to convert PostScript (PS) files to plain text (TXT) files. This can be achieved in two steps. 

The first step is to use Aspose.PDF for Java to render the PS file to an Excel Spreadsheet (XLSX) file. Aspose.PDF for Java is a powerful API that enables developers to create, edit, convert, and manipulate PDF documents in Java applications. It supports a wide range of features, including the ability to render PS files to XLSX. 

The second step is to use Aspose.Cells for Java to convert the XLSX file to a TXT file. Aspose.Cells for Java is a powerful spreadsheet programming API that enables developers to create, manipulate, and convert spreadsheets in Java applications. It supports a wide range of features, including the ability to convert XLSX files to TXT files. 

By using Aspose.Total for Java, developers can easily integrate the ability to convert PS files to TXT files into their Java applications. The two-step process involves using Aspose.PDF for Java to render the PS file to an XLSX file, and then using Aspose.Cells for Java to convert the XLSX file to a TXT file. This makes it easy for developers to add this feature to their applications without having to write any additional code.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert PS File to TXT via Java" %}}
1. Open PS file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert PS to XLSX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load XLSX document by using [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class
4. Save the document to TXT format using [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) in your pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected PS to TXT via Java" %}}
If your PS document is password protected, you cannot convert it to TXT without the password. Using the API, you can first open the protected document using a valid password and convert it after it. In order to open the encrypted file, you can initialize a new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PS File to TXT with Watermark via Java" %}}
While converting PS file to TXT, you can also add watermark to your output TXT file format. In order to add a watermark, create a new Workbook to open the converted XLSX file. Select Worksheet via its index, create a Shape and use its addTextEffect function, set colors, transparency and more. After that you can save your XLSX document as TXT with Watermark.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}