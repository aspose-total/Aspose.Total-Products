---
title: Convert JSON to Image via Java 
description: Parse JSON to Image in Java without using Microsoft PowerPoint
url_ignore: /java/conversion/json-to-image/
family: total
platformtag: java
feature: conversion
informat: JSON
outformat: JPEG2000
otherformats: DICOM EMZ TGA APNG SVGZ JPEG2000 WMF WMZ PSD DXF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert JSON to Image via Java" h2="Parse & convert JSON to Image formats within any Java J2SE, J2EE, J2ME applications" >}}

{{% blocks/products/pf/feature-page-summary %}}
<h2 class="heading-border">Why Convert JSON to Image formats?</h2>

Exporting a JSON file to image formats can be useful in several scenarios. One common use case is when working with data visualizations and graphics that have been created using Java libraries. These libraries generate interactive visualizations that can be easily customized and manipulated using JSON data. By exporting the JSON data to an image format such as PNG, JPEG or SVG, the visualizations can be easily shared and integrated into other documents or presentations. This allows users to create dynamic and engaging data visualizations that can be easily understood and communicated to others. Another reason why someone might want to export a JSON file to an image format is to enable printing or publication of the visualization in a physical format. Image formats such as PNG or JPEG can be easily printed on paper or included in other physical media, such as magazines, books or posters.

<h2 class="heading-border">How Aspose.Total can help in creating JSON to Image Converter?</h2>

With the powerful [Aspose.Total for Java](https://products.aspose.com/total/java/) toolkit, you can effortlessly convert JSON data to an image format within any Java application by following two straightforward steps. Firstly, utilize the capabilities of [Aspose.Cells for Java](https://products.aspose.com/cells/java/) to parse the JSON data and convert it to the JPEG format. Then, leverage the functionalities of [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) to further convert the generated JPEG file to the desired image format. This two-step process ensures a seamless and efficient conversion process, enabling you to transform JSON data into an image representation with ease using the Aspose.Total for Java suite.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert JSON to Image via Java" %}}
1. Create a new [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) object and open JSON file 
2. Save JSON as JPEG using [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) method
3. Load JPEG document by using [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) class 
4. Save the document to JPEG2000 format using [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="JSON to Image Converter API for Java" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include libraries in your pom.xml. Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert JSON to Image with JsonLayoutOptions" %}}
Furthermore, the API allows you to parse JSON to Image with specified layout options. In order to specify the layout options, you can use [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) class. It allows you to process an array as a table, ignore nulls, ignore array title, ignore object title, convert string to number or date, set date and number format, and set title style. All of these options allow you to present your data as per your needs. The following code snippet shows you how to set the layout options. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert JSON to Image with Watermark via Java" %}}
Using the API, you can also convert JSON to Image with watermark in your Image document. In order to add a watermark to you can first convert JSON to JPEG and add a watermark in it. In order to add watermark, load an image file using the [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) class, create an object of the [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) class and initialize it with Image object, create a new [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) object and set translation and transformation to the desired angle and add watermark using [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) method. After adding the watermark in your image, you can save the JPEG as JPEG2000 format.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}