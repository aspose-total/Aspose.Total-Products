---
title: Convert MD to EMZ via Java
description: Export MD file to EMZ  in your Java applications without using any third party application 
url_ignore: /java/conversion/md-to-emz/
family: total
platformtag: java
feature: conversion
informat: MD
outformat: EMZ
otherformats: WMF JPEG2000 PSD WMZ TGA DXF APNG  SVGZ IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert MD to EMZ via Java" h2="Export MD file to EMZ within any within any Java J2SE, J2EE, J2ME applications without using Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Converting an MD file to an EMZ image in Java can be done in two easy steps. The first step is to use the Aspose.PDF for Java API, which is part of the Aspose.Total for Java package. This API allows you to export MD files to JPEG images. The second step is to use the Aspose.Imaging for Java Image Processing API to render the JPEG image to an EMZ image. 

Aspose.PDF for Java is a powerful PDF manipulation API that enables developers to create, read, edit, convert, and print PDF documents from within their Java applications. It also allows developers to export MD files to JPEG images. The API supports a wide range of features, including the ability to add text, images, and annotations to PDF documents, as well as the ability to extract text and images from PDF documents. 

Aspose.Imaging for Java is an image processing API that enables developers to manipulate images in a variety of ways. It supports a wide range of image formats, including EMZ. With this API, developers can render JPEG images to EMZ images. The API also supports a range of features, including the ability to resize, crop, rotate, and flip images, as well as the ability to apply various image effects, such as blur, sharpen, and emboss. 

Both Aspose.PDF for Java and Aspose.Imaging for Java are part of the Aspose.Total for Java package. This package provides developers with a comprehensive set of APIs for manipulating a wide range of file formats, including PDF, DOC, XLS, PPT, and more. With Aspose.Total for Java, developers can easily convert MD files to EMZ images in Java.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Export MD to EMZ via Java" %}}
1. Open MD file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Initialize class object and render MD to JPEG by using [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) method
3. Load JPEG file by using [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) class 
4. Save the document to EMZ format using [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include libraries in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert MD to EMZ in a Single File via Java" %}}
The API also allows you to export MD file to EMZ to a single file. In order to convert all pages, you can first render your MD document to one TIFF file and after that, you can export the TIFF file to EMZ. You can open the input file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class and create Resolution, TiffSettings, & TIFF device objects. You can get a single TIFF image using [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) method of [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) class. Finally, you can load TIFF file using [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)  class and save it to EMZ format using [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert MD to EMZ With Watermark via Java" %}}
Using the API, you can also export MD file to EMZ with watermark in your EMZ document. In order to add a watermark to you can first convert MD to JPEG and add a watermark in it. In order to add watermark, load an image file using the [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) class, create an object of the [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) class and initialize it with Image object, create a new [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) object and set translation and transformation to the desired angle and add watermark using [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) method. After adding the watermark in your image, you can save the JPEG as EMZ format.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert & Rotate MD to EMZ File via Java" %}}
Using the API, you can also rotate the output EMZ image as per your needs. The Image.rotateFlip method can be used to rotate the image by 90/180/270-degrees and flip the image horizontally or vertically. The library provides simple methods to perform complex operations while encapsulating all ugly details. You can specify the type of rotation and flip to apply to the image. In order to rotate and flip the image, you can load the converted JPEG image using the [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) class and call the Image.rotateFlip method while specifying the appropriate [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType).
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}