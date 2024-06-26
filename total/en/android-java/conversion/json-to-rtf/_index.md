---
title: Convert JSON Format to RTF in Android Apps 
description: Parse JSON to RTF in Java without using Microsoft Word
url_ignore: /android-java/conversion/json-to-rtf/
family: total
platformtag: android-java
feature: conversion
informat: JSON
outformat: RTF
otherformats: WORD FLATOPC ODT WORDML EPUB CHM DOC MOBI DOTX PS DOT PCL OTT DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert JSON Format to RTF in Android Applications" h2="Parse JSON to RTF within Android applications without using Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

Converting JSON to RTF in Android applications is a two-step process that can be accomplished using the Aspose.Total for Android via Java product family. The first step is to use the Powerful Spreadsheet Processing API, Aspose.Cells for Android via Java, to parse the JSON into a PDF. This API is available as part of the Aspose.Total for Android via Java product family. The second step is to use the Word Processing API, Aspose.Words for Android via Java, to convert the PDF into an RTF file. This API is also available as part of the Aspose.Total for Android via Java product family.

Using the Aspose.Total for Android via Java product family, developers can easily and quickly convert JSON to RTF in their Android applications. The Powerful Spreadsheet Processing API, Aspose.Cells for Android via Java, can be used to parse the JSON into a PDF. Then, the Word Processing API, Aspose.Words for Android via Java, can be used to convert the PDF into an RTF file. This two-step process is simple and efficient, allowing developers to quickly and easily convert JSON to RTF in their Android applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert JSON Format to RTF in Android Apps" %}}
1. Create a new [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) object and read valid JSON data from file
2. Import JSON file to worksheet using [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) class and [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) it as PDF 
3. Load PDF document by using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class 
4. Save the document to RTF format using [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Android via Java APIs" %}}
You can easily use Aspose.Total for Android via Java directly from [Maven](https://releases.aspose.com/total/java/) and install libraries in your app.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Set Layout & Convert JSON Format to RTF in Android Apps" %}}
Furthermore, the API allows you to set layout options for your JSON format while parsing JSON to RTF using [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). It allows you to process Array as a table, ignore nulls, ignore array title, ignore object title, convert string to number or date, set date and number format, and set title style. All of these options allow you to present your data as per your needs. The following code snippet shows you how to set the layout options.    
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert JSON Format to RTF with Watermark in Android Apps" %}}
Using the API, you can also convert JSON to RTF with watermark. In order to add a watermark to your RTF document, you can first parse the JSON file to PDF and add a watermark to it. In order to add a watermark, load the newly created PDF file using the [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class, create an instance of TextWatermarkOptions and set its properties, Call Watermark.setText method and pass watermark text & object of TextWatermarkOptions. After adding the watermark, you can save the document to RTF.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}