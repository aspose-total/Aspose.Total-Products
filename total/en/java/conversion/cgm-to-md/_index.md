---
title: Java API to Render CGM to MD
description: Export CGM to MD via Java API without using Microsoft Excel or Adobe Reader
url_ignore: /java/conversion/cgm-to-md/
family: total
platformtag: java
feature: conversion
informat: CGM
outformat: MD
otherformats: XLSB XLT XLTM XLTX FODS EXCEL TXT TSV DIF XLSM ODS XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Export CGM to MD via Java" h2="Convert CGM file to MD by using on premise Java API within any Java J2SE, J2EE, J2ME applications" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is a comprehensive suite of components that enables developers to easily integrate CGM to MD conversion feature in their Java applications. It provides two components, Aspose.PDF for Java and Aspose.Cells for Java, that can be used to render CGM to XLSX and then convert XLSX to MD respectively. 

Aspose.PDF for Java is a powerful PDF manipulation API that enables developers to render CGM to XLSX in a few simple steps. It provides a wide range of features that can be used to create, edit, convert, and manipulate PDF documents. It also supports a wide range of file formats, including CGM, XLSX, and MD. 

Aspose.Cells for Java is a powerful Spreadsheet Programming API that enables developers to convert XLSX to MD. It provides a wide range of features that can be used to create, edit, convert, and manipulate spreadsheets. It also supports a wide range of file formats, including XLSX and MD. 

By using Aspose.Total for Java, developers can easily integrate CGM to MD conversion feature in their Java applications. It provides two components, Aspose.PDF for Java and Aspose.Cells for Java, that can be used to render CGM to XLSX and then convert XLSX to MD respectively. It provides a wide range of features that can be used to create, edit, convert, and manipulate PDF documents and spreadsheets. It also supports a wide range of file formats, including CGM, XLSX, and MD.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert CGM File to MD via Java" %}}
1. Open CGM file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert CGM to XLSX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load XLSX document by using [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class
4. Save the document to MD format using [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) in your pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected CGM to MD via Java" %}}
If your CGM document is password protected, you cannot convert it to MD without the password. Using the API, you can first open the protected document using a valid password and convert it after it. In order to open the encrypted file, you can initialize a new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert CGM File to MD with Watermark via Java" %}}
While converting CGM file to MD, you can also add watermark to your output MD file format. In order to add a watermark, create a new Workbook to open the converted XLSX file. Select Worksheet via its index, create a Shape and use its addTextEffect function, set colors, transparency and more. After that you can save your XLSX document as MD with Watermark.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}