---
title: Convert XSLFO to DXF via Java
description: Export XSLFO file to DXF  in your Java applications without using any third party application 
url_ignore: /java/conversion/xslfo-to-dxf/
family: total
platformtag: java
feature: conversion
informat: XSLFO
outformat: DXF
otherformats: WMZ PSD TGA JPEG2000 WMF IMAGE SVGZ EMZ APNG DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert XSLFO to DXF via Java" h2="Export XSLFO file to DXF within any within any Java J2SE, J2EE, J2ME applications without using Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Converting an XSLFO file to a DXF image in Java is a simple two-step process. The first step is to use the Aspose.PDF for Java API to export the XSLFO file to a JPEG image. Aspose.PDF for Java is part of the Aspose.Total for Java package, which includes a wide range of APIs for manipulating documents, images, and other file formats. 

Once the XSLFO file has been converted to a JPEG image, the second step is to use the Aspose.Imaging for Java API to render the JPEG image to a DXF image. Aspose.Imaging for Java is an image processing API that provides a range of features for manipulating images, including the ability to convert images from one format to another. 

Using Aspose.PDF for Java and Aspose.Imaging for Java, you can easily convert an XSLFO file to a DXF image in Java. The process is straightforward and requires only two steps. First, you export the XSLFO file to a JPEG image using Aspose.PDF for Java, and then you render the JPEG image to a DXF image using Aspose.Imaging for Java. Both APIs are part of the Aspose.Total for Java package, which provides a comprehensive set of APIs for manipulating documents, images, and other file formats.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Export XSLFO to DXF via Java" %}}
1. Open XSLFO file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Initialize class object and render XSLFO to JPEG by using [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) method
3. Load JPEG file by using [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) class 
4. Save the document to DXF format using [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include libraries in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert XSLFO to DXF in a Single File via Java" %}}
The API also allows you to export XSLFO file to DXF to a single file. In order to convert all pages, you can first render your XSLFO document to one TIFF file and after that, you can export the TIFF file to DXF. You can open the input file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class and create Resolution, TiffSettings, & TIFF device objects. You can get a single TIFF image using [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) method of [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) class. Finally, you can load TIFF file using [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)  class and save it to DXF format using [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert XSLFO to DXF With Watermark via Java" %}}
Using the API, you can also export XSLFO file to DXF with watermark in your DXF document. In order to add a watermark to you can first convert XSLFO to JPEG and add a watermark in it. In order to add watermark, load an image file using the [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) class, create an object of the [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) class and initialize it with Image object, create a new [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) object and set translation and transformation to the desired angle and add watermark using [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) method. After adding the watermark in your image, you can save the JPEG as DXF format.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert & Rotate XSLFO to DXF File via Java" %}}
Using the API, you can also rotate the output DXF image as per your needs. The Image.rotateFlip method can be used to rotate the image by 90/180/270-degrees and flip the image horizontally or vertically. The library provides simple methods to perform complex operations while encapsulating all ugly details. You can specify the type of rotation and flip to apply to the image. In order to rotate and flip the image, you can load the converted JPEG image using the [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) class and call the Image.rotateFlip method while specifying the appropriate [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType).
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}