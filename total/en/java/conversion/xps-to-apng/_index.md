---
title: Convert XPS to APNG via Java
description: Export XPS file to APNG  in your Java applications without using any third party application 
url_ignore: /java/conversion/xps-to-apng/
family: total
platformtag: java
feature: conversion
informat: XPS
outformat: APNG
otherformats: DXF  PSD TGA IMAGE SVGZ JPEG2000 WMZ EMZ WMF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert XPS to APNG via Java" h2="Export XPS file to APNG within any within any Java J2SE, J2EE, J2ME applications without using Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Converting an XPS file to an APNG image in Java is a straightforward process that can be completed in two simple steps. The first step is to use the Aspose.PDF for Java API, which is part of the Aspose.Total for Java package. This API allows you to export XPS files to JPEG format. The second step is to use the Aspose.Imaging for Java Image Processing API to render the JPEG file to an APNG image. 

The Aspose.PDF for Java API is a powerful tool for manipulating PDF documents. It allows you to convert XPS files to JPEG format, as well as other popular image formats such as PNG, TIFF, and BMP. It also provides features such as text extraction, document splitting, and page manipulation. 

The Aspose.Imaging for Java Image Processing API is a comprehensive library for manipulating images. It provides features such as image resizing, cropping, and color adjustment. It also allows you to render JPEG files to APNG format. This API is designed to be easy to use and provides a wide range of features for manipulating images. 

Using the Aspose.Total for Java package, you can easily convert XPS files to APNG images in Java. The Aspose.PDF for Java API allows you to export XPS files to JPEG format, and the Aspose.Imaging for Java Image Processing API allows you to render the JPEG file to an APNG image. With these two APIs, you can quickly and easily convert XPS files to APNG images in Java.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Export XPS to APNG via Java" %}}
1. Open XPS file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Initialize class object and render XPS to JPEG by using [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) method
3. Load JPEG file by using [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) class 
4. Save the document to APNG format using [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include libraries in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert XPS to APNG in a Single File via Java" %}}
The API also allows you to export XPS file to APNG to a single file. In order to convert all pages, you can first render your XPS document to one TIFF file and after that, you can export the TIFF file to APNG. You can open the input file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class and create Resolution, TiffSettings, & TIFF device objects. You can get a single TIFF image using [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) method of [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) class. Finally, you can load TIFF file using [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)  class and save it to APNG format using [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert XPS to APNG With Watermark via Java" %}}
Using the API, you can also export XPS file to APNG with watermark in your APNG document. In order to add a watermark to you can first convert XPS to JPEG and add a watermark in it. In order to add watermark, load an image file using the [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) class, create an object of the [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) class and initialize it with Image object, create a new [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) object and set translation and transformation to the desired angle and add watermark using [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) method. After adding the watermark in your image, you can save the JPEG as APNG format.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert & Rotate XPS to APNG File via Java" %}}
Using the API, you can also rotate the output APNG image as per your needs. The Image.rotateFlip method can be used to rotate the image by 90/180/270-degrees and flip the image horizontally or vertically. The library provides simple methods to perform complex operations while encapsulating all ugly details. You can specify the type of rotation and flip to apply to the image. In order to rotate and flip the image, you can load the converted JPEG image using the [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) class and call the Image.rotateFlip method while specifying the appropriate [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType).
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}