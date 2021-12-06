---
title: Convert MHTML to IMAGE via Java
description: Convert MHTML to IMAGE in your Java applications without using any third party application 
url: /java/conversion/mhtml-to-image/
family: total
platformtag: java
feature: conversion
informat: MHTML
outformat: JPEG2000
otherformats: EMZ WMZ SVGZ WMF DXF PSD TGA APNG JPEG2000 DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert MHTML to IMAGE via Java" h2="Render MHTML to IMAGE within any within any Java J2SE, J2EE, J2ME applications without using Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
You can convert MHTML to IMAGE in Java in two simple steps. Firstly, by using [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), you can convert MHTML to JPEG. After that, by using [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API, you can render JPEG to IMAGE. Both APIs come under the [Aspose.Total for Java](https://products.aspose.com/total/java/) package. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert MHTML to IMAGE via Java" %}}
1. Open MHTML file using [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Initialize [JpegDevice](JpegDevice) class object and render MHTML to JPEG by using [Process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) method
3. Load JPEG file by using [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) class 
4. Save the document to JPEG2000 format using [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Automation APIs" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) based project and include libraries in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert MHTML to IMAGE in a Single File via Java" %}}
The API also allows you to convert MHTML to IMAGE to a single file. In order to convert all pages, you can first render your MHTML document to one TIFF file and after that you can convert your TIFF file to IMAGE. You can open the input file using [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) class and create Resolution, TiffSettings, & TIFF device objects. You can get a single TIFF image using [process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) method of [TiffDevice](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) class. Finally, you can load TIFF file using [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image)  class and save it to JPEG2000 format using [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert MHTML to IMAGE With Watermark via Java" %}}
Using the API, you can also convert MHTML to IMAGE with watermark in your IMAGE document. In order to add an watermark to you can first convert MHTML to JPEG and add watermark in it. In order to add watermark, Load an image file using the [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) class, create an object of the [Graphics](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) class and initialize it with Image object, create a new [Matrix](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Matrix) object and set translation and transformation to the desired angle and add watermark using [Graphics.drawString](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) method. After adding the watermark in your image, you can save the JPEG as JPEG2000 format.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}