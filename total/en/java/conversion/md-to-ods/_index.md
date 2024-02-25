---
title: Java API to Render MD to ODS
description: Export MD to ODS via Java API without using Microsoft Excel or Adobe Reader
url_ignore: /java/conversion/md-to-ods/
family: total
platformtag: java
feature: conversion
informat: MD
outformat: ODS
otherformats: TXT XLT TSV CSV XLAM EXCEL XLTX DIF FODS SXC XLSB XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Export MD to ODS via Java" h2="Convert MD file to ODS by using on premise Java API within any Java J2SE, J2EE, J2ME applications" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is a comprehensive suite of components that enables developers to easily integrate MD to ODS conversion feature in their Java applications. This suite includes Aspose.PDF for Java and Aspose.Cells for Java, which are two powerful APIs that can be used to render MD to XLSX and convert XLSX to ODS respectively. 

The process of converting MD to ODS involves two steps. In the first step, Aspose.PDF for Java can be used to render MD to XLSX. This API provides a wide range of features that enable developers to create, manipulate, and convert PDF documents in their Java applications. It also provides the ability to render MD to XLSX, which is a format that is supported by Aspose.Cells for Java. 

In the second step, Aspose.Cells for Java can be used to convert XLSX to ODS. This Spreadsheet Programming API provides a comprehensive set of features that enable developers to create, manipulate, and convert spreadsheets in their Java applications. It also provides the ability to convert XLSX to ODS, which is a format that is supported by Aspose.Total for Java. 

By using Aspose.Total for Java, developers can easily integrate MD to ODS conversion feature in their Java applications. This suite of components provides a two-step process that enables developers to render MD to XLSX and convert XLSX to ODS. Aspose.PDF for Java and Aspose.Cells for Java are two powerful APIs that can be used to achieve this conversion.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert MD File to ODS via Java" %}}
1. Open MD file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert MD to XLSX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method
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

{{% blocks/products/pf/feature-page-section  h2="Convert Protected MD to ODS via Java" %}}
If your MD document is password protected, you cannot convert it to ODS without the password. Using the API, you can first open the protected document using a valid password and convert it after it. In order to open the encrypted file, you can initialize a new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert MD File to ODS with Watermark via Java" %}}
While converting MD file to ODS, you can also add watermark to your output ODS file format. In order to add a watermark, create a new Workbook to open the converted XLSX file. Select Worksheet via its index, create a Shape and use its addTextEffect function, set colors, transparency and more. After that you can save your XLSX document as ODS with Watermark.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}