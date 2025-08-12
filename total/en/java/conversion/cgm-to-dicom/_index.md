---
title: Convert CGM to DICOM via Java
description: Export CGM file to DICOM  in your Java applications without using any third party application 
url_ignore: /java/conversion/cgm-to-dicom/
family: total
platformtag: java
feature: conversion
informat: CGM
outformat: DICOM
otherformats: EMZ PSD WMF WMZ TGA APNG DXF SVGZ IMAGE JPEG2000 DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert CGM to DICOM via Java" h2="Export CGM file to DICOM within any within any Java J2SE, J2EE, J2ME applications without using Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Converting a CGM file to a DICOM image in Java can be done in two simple steps. The first step is to use the Aspose.PDF for Java API, which is part of the Aspose.Total for Java package. This API allows you to export CGM files to JPEG images. The second step is to use the Aspose.Imaging for Java Image Processing API to render the JPEG image to a DICOM image. 

The Aspose.PDF for Java API is a powerful PDF manipulation library that enables developers to create, edit, convert, and print PDF documents from within their Java applications. It supports a wide range of features, including the ability to export CGM files to JPEG images. The API also provides a range of other features, such as the ability to create PDF documents from scratch, convert PDF documents to other formats, and manipulate existing PDF documents. 

The Aspose.Imaging for Java Image Processing API is a powerful library that enables developers to manipulate images in a variety of ways. It supports a wide range of features, including the ability to render JPEG images to DICOM images. The API also provides a range of other features, such as the ability to create images from scratch, convert images to other formats, and manipulate existing images. 

By combining the Aspose.PDF for Java and Aspose.Imaging for Java APIs, developers can easily convert CGM files to DICOM images in Java. This makes it easy to create, edit, and manipulate medical images in Java applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Export CGM to DICOM via Java" %}}
1. Open CGM file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Initialize class object and render CGM to JPEG by using [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) method
3. Load JPEG file by using [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) class 
4. Save the document to DICOM format using [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include libraries in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert CGM to DICOM in a Single File via Java" %}}
The API also allows you to export CGM file to DICOM to a single file. In order to convert all pages, you can first render your CGM document to one TIFF file and after that, you can export the TIFF file to DICOM. You can open the input file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class and create Resolution, TiffSettings, & TIFF device objects. You can get a single TIFF image using [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) method of [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) class. Finally, you can load TIFF file using [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)  class and save it to DICOM format using [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert CGM to DICOM With Watermark via Java" %}}
Using the API, you can also export CGM file to DICOM with watermark in your DICOM document. In order to add a watermark to you can first convert CGM to JPEG and add a watermark in it. In order to add watermark, load an image file using the [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) class, create an object of the [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) class and initialize it with Image object, create a new [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) object and set translation and transformation to the desired angle and add watermark using [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) method. After adding the watermark in your image, you can save the JPEG as DICOM format.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert & Rotate CGM to DICOM File via Java" %}}
Using the API, you can also rotate the output DICOM image as per your needs. The Image.rotateFlip method can be used to rotate the image by 90/180/270-degrees and flip the image horizontally or vertically. The library provides simple methods to perform complex operations while encapsulating all ugly details. You can specify the type of rotation and flip to apply to the image. In order to rotate and flip the image, you can load the converted JPEG image using the [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) class and call the Image.rotateFlip method while specifying the appropriate [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType).
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-summary %}}
Converting **Computer Graphics Metafile (CGM)** files to **DICOM (Digital Imaging and Communications in Medicine)** format is crucial for ensuring compatibility with modern medical imaging workflows. In **Java-based medical imaging systems**, this conversion enables seamless integration with hospital data infrastructure, supports standardized image exchange, and enhances diagnostic visualization capabilities. By transforming CGM drawings or diagrams into DICOM, healthcare organizations can unify diverse imaging formats, making them accessible across **PACS**, **radiology viewers**, and AI-driven diagnostic tools.

## ✅ Key Use Cases

- **Java-Integrated Radiology Viewers**  
  Display CGM-based medical illustrations directly within Java-powered DICOM viewers for enhanced diagnostic interpretation.

- **Hospital Information Systems (HIS)**  
  Convert CGM to DICOM for standardized imaging records accessible across hospital networks.

- **Radiology Data Exchange**  
  Enable smooth transfer of converted imaging files between medical facilities using DICOM’s global standard.

- **Diagnostic Visualization**  
  Improve clinical workflows by embedding converted CGM data into multi-modality imaging studies.


## ⚙️ Automation Scenarios

- **Java APIs for DICOM Handling**  
  Automate CGM-to-DICOM conversion pipelines using Java libraries for image processing and DICOM metadata management.

- **PACS System Integration**  
  Feed converted DICOM images directly into Picture Archiving and Communication Systems for instant retrieval and storage.

- **Java-Based ETL Pipelines**  
  Integrate automated conversion in Extract-Transform-Load workflows for hospital-wide imaging data management.

- **AI-Powered Diagnostic Workflows**  
  Use Java-integrated AI models to analyze converted DICOM images for pattern recognition, anomaly detection, and predictive diagnostics.

{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}