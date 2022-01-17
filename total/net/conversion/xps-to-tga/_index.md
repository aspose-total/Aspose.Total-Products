---
title: Convert XPS to TGA via C# API
description: Export XPS to TGA in your .NET applications without using any third party application 
url: /net/conversion/xps-to-tga/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: TGA
otherformats:  EMZ SVGZ PSD APNG DXF WMF JPEG2000 IMAGE WMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert XPS file to TGA via C#" h2="Export XPS to TGA within .NET applications without using Adobe<sup>&reg;</sup> Acrobat Reader or any other third party applications" >}}

{{% blocks/products/pf/feature-page-summary %}}
Using [Aspose.Total for .NET](https://products.aspose.com/total/net/) you can easily export XPS to TGA image within any .NET applications in two simple steps. First of all, by using [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), you can export XPS to JPEG. After that, by using [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Image Processing API, you can convert JPEG to TGA. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert XPS file to TGA via .NET" %}}
1. Open XPS file using [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) class
2. Initialize [JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) class object and render XPS to JPEG by using [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) method
3. Load JPEG file by using [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) class 
4. Save the document to TGA format using [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Automation APIs" %}}
Install from command line as ```nuget install Aspose.Total``` or install directly from Package Manager Console of Visual Studio.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert XPS File to TGA in a Single File via C#" %}}
Using the API, you can also convert XPS file to TGA to a single image file. In order to convert all pages, you can first render your XPS document to one TIFF file and after that you can export TIFF file to TGA. You can open the input file using [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) class and create Resolution, TiffSettings, & TIFF device objects. You can get a single TIFF image using [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) method of [TiffDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) class. Finally, you can load TIFF file using [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) class 
and save it to TGA format using [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert XPS to TGA With Watermark via C#" %}}
Using the API, you can also convert XPS file to TGA with watermark in your TGA document. In order to add a watermark, you can first render your XPS document to JPEG and add a watermark in it. To demonstrate the operation, you can load your converted JPEG image, add transformations using an object of Matrix class and draw a string as the watermark on the image surface using the [Graphics](https://apireference.aspose.com/imaging/net/aspose.imaging/graphics) class' [DrawString](https://apireference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) method. After adding the watermark in it, you can save the JPEG as TGA format.  Below is a code example that demonstrates how to add a diagonal watermark to your document. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert & Rotate XPS File to TGA via C#" %}}
Using the API, you can also rotate the output TGA image as per your needs. The Image.RotateFlip method can be used to rotate the image by 90/180/270-degrees and flip the image horizontally or vertically. You can specify the type of rotation and flip to apply to the image. In order to rotate and flip the image you can load the converted JPEG image using the factory method exposed by [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) class and call the Image.RotateFlip method while specifying the appropriate [RotateFlipType](https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype).
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}