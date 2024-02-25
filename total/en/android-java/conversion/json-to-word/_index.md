---
title: Convert JSON to Word Formats in Android Apps
description: JSON to Word Conversion via Java without using Microsoft Word
url_ignore: /android-java/conversion/json-to-word/
family: total
platformtag: android-java
feature: conversion
informat: JSON
outformat: WORD
otherformats: DOT PS RTF MOBI EPUB WORDML DOTX CHM OTT PCL DOCM FLATOPC DOC ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert JSON Format to WORD in Android Applications" h2="Parse JSON to WORD within Android applications without using Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">Why Convert JSON to Word formats?</h2>

Converting JSON data to Word file formats, such as DOCX or RTF, via code or in Android apps can be beneficial in various scenarios. One common reason is to generate dynamic and customizable reports, documents, or templates from structured JSON data. By converting JSON to Word, developers can programmatically populate document templates with data, allowing for the automatic generation of invoices, reports, certificates, or other documents without manual intervention. Additionally, this process is useful when integrating mobile applications with backend systems, as it enables seamless data transfer and document generation for tasks like generating contracts, agreements, or client-specific reports directly from Android devices.

<h2 class="heading-border">How Aspose.Total can help in JSON to Word Conversion?</h2>

[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) provides a comprehensive solution for efficiently converting JSON data to Word documents within your Android applications. This process involves a two-step approach for seamless conversion. 

1. Firstly, you can utilize the powerful Spreadsheet Processing API, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/), which is part of the Aspose.Total product family. With this API, you can parse and manipulate JSON data and transform it into PDF format, ensuring data accuracy and formatting.
1. In the second step, Aspose.Total offers the Word Processing API, [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/), which enables you to take the generated PDF and convert it into Word format. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert JSON Format to WORD in Android Apps" %}}
1. Create a new [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) object and read valid JSON data from file
2. Import JSON file to worksheet using [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) class and [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) it as PDF 
3. Load PDF document by using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class 
4. Save the document to DOC format using [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Android via Java APIs" %}}
You can easily use Aspose.Total for Android via Java directly from [Maven](https://releases.aspose.com/total/java/) and install libraries in your app.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Set Layout & Convert JSON Format to WORD in Android Apps" %}}
Furthermore, the API allows you to set layout options for your JSON format while parsing JSON to WORD using [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). It allows you to process Array as a table, ignore nulls, ignore array title, ignore object title, convert string to number or date, set date and number format, and set title style. All of these options allow you to present your data as per your needs. The following code snippet shows you how to set the layout options.    
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert JSON Format to WORD with Watermark in Android Apps" %}}
Using the API, you can also convert JSON to WORD with watermark. In order to add a watermark to your WORD document, you can first parse the JSON file to PDF and add a watermark to it. In order to add a watermark, load the newly created PDF file using the [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class, create an instance of TextWatermarkOptions and set its properties, Call Watermark.setText method and pass watermark text & object of TextWatermarkOptions. After adding the watermark, you can save the document to WORD.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}