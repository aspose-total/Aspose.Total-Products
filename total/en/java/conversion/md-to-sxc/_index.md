---
title: Java API to Render MD to SXC
description: Export MD to SXC via Java API without using Microsoft Excel or Adobe Reader
url_ignore: /java/conversion/md-to-sxc/
family: total
platformtag: java
feature: conversion
informat: MD
outformat: SXC
otherformats: DIF EXCEL TXT XLTM CSV XLT XLTX XLSM XLSB FODS XLAM TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Export MD to SXC via Java" h2="Convert MD file to SXC by using on premise Java API within any Java J2SE, J2EE, J2ME applications" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is a comprehensive suite of components that enables developers to easily integrate MD to SXC conversion feature in their Java applications. It consists of two components, Aspose.PDF for Java and Aspose.Cells for Java, which can be used in a two-step process to achieve the desired result. 

The first step involves using Aspose.PDF for Java to render MD to XLSX. This component provides a wide range of features for manipulating PDF documents, including the ability to convert MD to XLSX. It supports a variety of formats, including PDF, XPS, HTML, and SVG, and provides a comprehensive set of APIs for creating, editing, and converting documents. 

The second step involves using Aspose.Cells for Java to convert XLSX to SXC. This component provides a comprehensive set of APIs for working with spreadsheets, including the ability to convert XLSX to SXC. It supports a variety of formats, including XLSX, XLS, CSV, and ODS, and provides a wide range of features for manipulating spreadsheets, such as formatting, data validation, and charting. 

By using Aspose.Total for Java, developers can easily integrate MD to SXC conversion feature in their Java applications. It provides a comprehensive set of APIs for creating, editing, and converting documents and spreadsheets, and supports a variety of formats. With its two-step process, developers can quickly and easily convert MD to SXC in their Java applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert MD File to SXC via Java" %}}
1. Open MD file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert MD to XLSX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
3. Load XLSX document by using [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class
4. Save the document to SXC format using [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Format APIs" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) in your pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected MD to SXC via Java" %}}
If your MD document is password protected, you cannot convert it to SXC without the password. Using the API, you can first open the protected document using a valid password and convert it after it. In order to open the encrypted file, you can initialize a new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert MD File to SXC with Watermark via Java" %}}
While converting MD file to SXC, you can also add watermark to your output SXC file format. In order to add a watermark, create a new Workbook to open the converted XLSX file. Select Worksheet via its index, create a Shape and use its addTextEffect function, set colors, transparency and more. After that you can save your XLSX document as SXC with Watermark.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}