---
title: Convert PS to WMF via Java
description: Export PS file to WMF  in your Java applications without using any third party application 
url_ignore: /java/conversion/ps-to-wmf/
family: total
platformtag: java
feature: conversion
informat: PS
outformat: WMF
otherformats: APNG WMZ SVGZ DXF IMAGE TGA EMZ JPEG2000  PSD DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PS to WMF via Java" h2="Export PS file to WMF within any within any Java J2SE, J2EE, J2ME applications without using Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Converting a PostScript (PS) file to a Windows Metafile (WMF) image in Java can be done in two simple steps. The first step is to use the Aspose.PDF for Java API to export the PS file to a JPEG image. Aspose.PDF for Java is a powerful PDF manipulation API that is part of the Aspose.Total for Java package. It allows developers to create, edit, convert, and manipulate PDF documents in Java applications. 

The second step is to use the Aspose.Imaging for Java API to render the JPEG image to a WMF image. Aspose.Imaging for Java is an advanced image processing API that enables developers to create, edit, and convert images in Java applications. It supports a wide range of image formats, including WMF, and provides a comprehensive set of features for manipulating images. 

By using the two APIs together, developers can easily convert a PS file to a WMF image in Java. Aspose.Total for Java is a suite of APIs that provides a comprehensive set of features for manipulating documents, images, and other file formats. It includes Aspose.PDF for Java and Aspose.Imaging for Java, as well as other APIs for manipulating Microsoft Office documents, email messages, and more.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Export PS to WMF via Java" %}}
1. Open PS file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Initialize class object and render PS to JPEG by using [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) method
3. Load JPEG file by using [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) class 
4. Save the document to WMF format using [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include libraries in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert PS to WMF in a Single File via Java" %}}
The API also allows you to export PS file to WMF to a single file. In order to convert all pages, you can first render your PS document to one TIFF file and after that, you can export the TIFF file to WMF. You can open the input file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class and create Resolution, TiffSettings, & TIFF device objects. You can get a single TIFF image using [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) method of [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) class. Finally, you can load TIFF file using [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)  class and save it to WMF format using [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PS to WMF With Watermark via Java" %}}
Using the API, you can also export PS file to WMF with watermark in your WMF document. In order to add a watermark to you can first convert PS to JPEG and add a watermark in it. In order to add watermark, load an image file using the [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) class, create an object of the [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) class and initialize it with Image object, create a new [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) object and set translation and transformation to the desired angle and add watermark using [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) method. After adding the watermark in your image, you can save the JPEG as WMF format.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert & Rotate PS to WMF File via Java" %}}
Using the API, you can also rotate the output WMF image as per your needs. The Image.rotateFlip method can be used to rotate the image by 90/180/270-degrees and flip the image horizontally or vertically. The library provides simple methods to perform complex operations while encapsulating all ugly details. You can specify the type of rotation and flip to apply to the image. In order to rotate and flip the image, you can load the converted JPEG image using the [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) class and call the Image.rotateFlip method while specifying the appropriate [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType).
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section >}}

Converting PS (PostScript) files to WMF (Windows Metafile) enables high-quality vector graphics compatible with Microsoft Office and legacy Windows applications. This ensures scalable graphics with precise PostScript fidelity.

{{% blocks/products/pf/agp/feature-section-col title="Key Use Cases" %}}

* Embedding PS diagrams into PowerPoint, Word, and Excel documents.
* Converting technical PostScript visuals into Windows-compatible vector graphics.
* Preparing marketing or business charts for Windows-based reporting tools.
* Migrating PostScript illustrations to legacy Windows environments.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Automation Scenarios" %}}

* Automated PS-to-WMF batch conversion for corporate document workflows.
* Integration with Office automation pipelines.
* Scheduled conversion of PS-based reports for presentation or printing.
* Cloud-based vector optimization for WMF generation.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}