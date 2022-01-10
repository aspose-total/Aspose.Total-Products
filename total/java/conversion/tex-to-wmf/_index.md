---
title: Convert TEX to WMF via Java
description: Export TEX to WMF in your Java applications without using any third party application 
url: /java/conversion/tex-to-wmf/
family: total
platformtag: java
feature: conversion
informat: TEX
outformat: WMF
otherformats: DICOM APNG IMAGE TGA SVGZ PSD JPEG2000 EMZ WMZ DXF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert TEX to WMF via Java" h2="Export TEX to WMF within any within any Java J2SE, J2EE, J2ME applications without using Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
You can convert TEX to WMF in Java in two simple steps. Firstly, by using [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), you can export TEX to JPEG. After that, by using [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API, you can render JPEG to WMF. Both APIs come under the [Aspose.Total for Java](https://products.aspose.com/total/java/) package. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert TEX to WMF via Java" %}}
1. Open TEX file using [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Initialize [JpegDevice](JpegDevice) class object and render TEX to JPEG by using [Process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) method
3. Load JPEG file by using [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) class 
4. Save the document to WMF format using [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Automation APIs" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) based project and include libraries in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert TEX to WMF in a Single File via Java" %}}
The API also allows you to export TEX to WMF to a single file. In order to convert all pages, you can first render your TEX document to one TIFF file and after that you can export TIFF file to WMF. You can open the input file using [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) class and create Resolution, TiffSettings, & TIFF device objects. You can get a single TIFF image using [process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) method of [TiffDevice](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) class. Finally, you can load TIFF file using [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image)  class and save it to WMF format using [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert TEX to WMF With Watermark via Java" %}}
Using the API, you can also export TEX to WMF with watermark in your WMF document. In order to add an watermark to you can first convert TEX to JPEG and add watermark in it. In order to add watermark, Load an image file using the [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) class, create an object of the [Graphics](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) class and initialize it with Image object, create a new [Matrix](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Matrix) object and set translation and transformation to the desired angle and add watermark using [Graphics.drawString](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) method. After adding the watermark in your image, you can save the JPEG as WMF format.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}