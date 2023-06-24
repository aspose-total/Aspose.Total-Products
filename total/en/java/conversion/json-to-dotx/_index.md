---
title: Convert JSON Format to DOTX via Java 
description: Parse JSON to DOTX in Java without using Microsoft Word
url_ignore: /java/conversion/json-to-dotx/
family: total
platformtag: java
feature: conversion
informat: JSON
outformat: DOTX
otherformats: DOCM PS OTT WORD PCL RTF DOT FLATOPC EPUB ODT CHM DOC WORDML MOBI
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert JSON Format to DOTX via Java" h2="On premise Java API to parse JSON to DOTX without using Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is a comprehensive suite of APIs that enables developers to create, manipulate, and convert a wide range of file formats in their Java applications. It includes APIs for manipulating documents, spreadsheets, images, and emails. One of the many features of Aspose.Total for Java is the ability to convert JSON to DOTX. This can be achieved in two steps.

The first step is to use Aspose.Cells for Java to parse JSON to PDF. Aspose.Cells for Java is a powerful spreadsheet API that enables developers to create, manipulate, and convert spreadsheets in their Java applications. It supports a wide range of file formats, including PDF, and provides a comprehensive set of features for manipulating spreadsheets. With Aspose.Cells for Java, developers can easily parse JSON to PDF.

The second step is to use Word Processing API Aspose.Words for Java to convert PDF to DOTX. Aspose.Words for Java is a powerful API for creating, manipulating, and converting documents in Java applications. It supports a wide range of file formats, including DOTX, and provides a comprehensive set of features for manipulating documents. With Aspose.Words for Java, developers can easily convert PDF to DOTX.

In summary, Aspose.Total for Java provides a comprehensive suite of APIs for manipulating and converting a wide range of file formats in Java applications. It includes APIs for manipulating documents, spreadsheets, images, and emails. One of the many features of Aspose.Total for Java is the ability to convert JSON to DOTX. This can be achieved in two steps: firstly, by using Aspose.Cells for Java to parse JSON to PDF, and secondly, by using Aspose.Words for Java to convert PDF to DOTX.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert JSON Format to DOTX via Java" %}}
1. Create a new [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) object and read valid JSON data from file
2. Import JSON file to worksheet using [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) class and [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) it as PDF 
3. Load PDF document by using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class 
4. Save the document to DOTX format using [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Automation APIs" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include libraries in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Set Layout & Convert JSON Format to DOTX via Java" %}}
Furthermore, the API allows you to set layout options for your JSON while parsing JSON to DOTX using [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). It allows you to process Array as a table, ignore nulls, ignore array title, ignore object title, convert string to number or date, set date and number format, and set title style. All of these options allow you to present your data as per your needs. The following code snippet shows you how to set the layout options.    
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert JSON Format to DOTX with Watermark via Java" %}}
Using the API, you can also parse JSON to DOTX with watermark. In order to add a watermark to your DOTX document, you can first convert the JSON file to PDF and add a watermark to it. In order to add a watermark, load the newly created PDF file using the [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class, create an instance of TextWatermarkOptions and set its properties, Call Watermark.setText method and pass watermark text & object of TextWatermarkOptions. After adding the watermark, you can save the document to DOTX.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}