---
title: Java API to Render PDF to FODS
description: Export PDF to FODS via Java API without using Microsoft Excel or Adobe Reader
url_ignore: /java/conversion/pdf-to-fods/
family: total
platformtag: java
feature: conversion
informat: PDF
outformat: FODS
otherformats: SXC XLSM XLSB XLAM CSV DIF XLT TXT TSV XLTM XLTX MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Export PDF to FODS via Java" h2="Convert PDF file to FODS by using on premise Java API within any Java J2SE, J2EE, J2ME applications" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is a comprehensive suite of components that enables developers to integrate PDF to FODS conversion feature in their Java applications. It provides two distinct APIs, Aspose.PDF for Java and Aspose.Cells for Java, to achieve this goal. 

Aspose.PDF for Java is a powerful PDF manipulation API that enables developers to render PDF documents to XLSX format. It provides a wide range of features to manipulate PDF documents such as create, edit, convert, split, merge, and much more. It also supports a variety of image formats such as TIFF, JPEG, PNG, and BMP. 

Aspose.Cells for Java is a powerful spreadsheet programming API that enables developers to convert XLSX to FODS format. It provides a wide range of features to manipulate spreadsheets such as create, edit, convert, split, merge, and much more. It also supports a variety of other formats such as CSV, HTML, PDF, and XPS. 

By using Aspose.Total for Java, developers can easily integrate PDF to FODS conversion feature in their Java applications in two-step process. Firstly, they can render PDF documents to XLSX format by using Aspose.PDF for Java. In the second step, they can convert XLSX to FODS format by using Aspose.Cells for Java. This makes it easy for developers to integrate PDF to FODS conversion feature in their Java applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert PDF File to FODS via Java" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert PDF to XLSX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load XLSX document by using [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class
4. Save the document to FODS format using [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) in your pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected PDF to FODS via Java" %}}
If your PDF document is password protected, you cannot convert it to FODS without the password. Using the API, you can first open the protected document using a valid password and convert it after it. In order to open the encrypted file, you can initialize a new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF File to FODS with Watermark via Java" %}}
While converting PDF file to FODS, you can also add watermark to your output FODS file format. In order to add a watermark, create a new Workbook to open the converted XLSX file. Select Worksheet via its index, create a Shape and use its addTextEffect function, set colors, transparency and more. After that you can save your XLSX document as FODS with Watermark.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}