---
title: Convert CGM to DICOM via C# API
description: Export CGM to DICOM in your .NET applications without using any third party application 
url_ignore: /net/conversion/cgm-to-dicom/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DICOM
otherformats: EMZ PSD WMF WMZ TGA APNG DXF SVGZ IMAGE JPEG2000 DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert CGM file to DICOM via C#" h2="Export CGM to DICOM within .NET applications without using Adobe<sup>&reg;</sup> Acrobat Reader or any other third party applications" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a comprehensive suite of .NET components that enables developers to easily export CGM to DICOM image within any .NET applications. This suite includes Aspose.PDF for .NET and Aspose.Imaging for .NET, which are both powerful and feature-rich APIs that provide a wide range of features and capabilities. 

Using Aspose.PDF for .NET, developers can easily export CGM to JPEG. This API provides a wide range of features and capabilities, such as the ability to convert CGM to JPEG, as well as other image formats. It also provides support for various image formats, including TIFF, PNG, BMP, and more. Additionally, it offers a range of features for manipulating images, such as resizing, cropping, and rotating. 

Once the CGM has been converted to JPEG, Aspose.Imaging for .NET can be used to convert the JPEG to DICOM. This powerful Image Processing API provides a wide range of features and capabilities, such as the ability to convert JPEG to DICOM, as well as other image formats. It also provides support for various image formats, including TIFF, PNG, BMP, and more. Additionally, it offers a range of features for manipulating images, such as resizing, cropping, and rotating. 

In summary, Aspose.Total for .NET is a comprehensive suite of .NET components that enables developers to easily export CGM to DICOM image within any .NET applications. This suite includes Aspose.PDF for .NET and Aspose.Imaging for .NET, which are both powerful and feature-rich APIs that provide a wide range of features and capabilities. Using these APIs, developers can easily export CGM to JPEG and then convert the JPEG to DICOM.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert CGM file to DICOM via .NET" %}}
1. Open CGM file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Initialize [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) class object and render CGM to JPEG by using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) method
3. Load JPEG file by using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class 
4. Save the document to DICOM format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
Install from command line as ```nuget install Aspose.Total``` or install directly from Package Manager Console of Visual Studio.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert CGM File to DICOM in a Single File via C#" %}}
Using the API, you can also convert CGM file to DICOM to a single image file. In order to convert all pages, you can first render your CGM document to one TIFF file and after that you can export TIFF file to DICOM. You can open the input file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and create Resolution, TiffSettings, & TIFF device objects. You can get a single TIFF image using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) method of [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) class. Finally, you can load TIFF file using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class 
and save it to DICOM format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert CGM to DICOM With Watermark via C#" %}}
Using the API, you can also convert CGM file to DICOM with watermark in your DICOM document. In order to add a watermark, you can first render your CGM document to JPEG and add a watermark in it. To demonstrate the operation, you can load your converted JPEG image, add transformations using an object of Matrix class and draw a string as the watermark on the image surface using the [Graphics](https://reference.aspose.com/imaging/net/aspose.imaging/graphics) class' [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) method. After adding the watermark in it, you can save the JPEG as DICOM format.  Below is a code example that demonstrates how to add a diagonal watermark to your document. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert & Rotate CGM File to DICOM via C#" %}}
Using the API, you can also rotate the output DICOM image as per your needs. The Image.RotateFlip method can be used to rotate the image by 90/180/270-degrees and flip the image horizontally or vertically. You can specify the type of rotation and flip to apply to the image. In order to rotate and flip the image you can load the converted JPEG image using the factory method exposed by [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class and call the Image.RotateFlip method while specifying the appropriate [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype).
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}