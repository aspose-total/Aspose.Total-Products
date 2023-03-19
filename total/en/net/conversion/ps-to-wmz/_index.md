---
title: Convert PS to WMZ via C# API
description: Export PS to WMZ in your .NET applications without using any third party application 
url_ignore: /net/conversion/ps-to-wmz/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: WMZ
otherformats: TGA  DXF EMZ WMF PSD APNG JPEG2000 IMAGE SVGZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PS file to WMZ via C#" h2="Export PS to WMZ within .NET applications without using Adobe<sup>&reg;</sup> Acrobat Reader or any other third party applications" >}}

{{% blocks/products/pf/feature-page-summary %}}
Using [Aspose.Total for .NET](https://products.aspose.com/total/net/) you can easily export PS to WMZ image within any .NET applications in two simple steps. First of all, by using [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), you can export PS to JPEG. After that, by using [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Image Processing API, you can convert JPEG to WMZ. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert PS file to WMZ via .NET" %}}
1. Open PS file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Initialize [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) class object and render PS to JPEG by using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) method
3. Load JPEG file by using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class 
4. Save the document to WMZ format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Automation APIs" %}}
Install from command line as ```nuget install Aspose.Total``` or install directly from Package Manager Console of Visual Studio.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert PS File to WMZ in a Single File via C#" %}}
Using the API, you can also convert PS file to WMZ to a single image file. In order to convert all pages, you can first render your PS document to one TIFF file and after that you can export TIFF file to WMZ. You can open the input file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and create Resolution, TiffSettings, & TIFF device objects. You can get a single TIFF image using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) method of [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) class. Finally, you can load TIFF file using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class 
and save it to WMZ format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PS to WMZ With Watermark via C#" %}}
Using the API, you can also convert PS file to WMZ with watermark in your WMZ document. In order to add a watermark, you can first render your PS document to JPEG and add a watermark in it. To demonstrate the operation, you can load your converted JPEG image, add transformations using an object of Matrix class and draw a string as the watermark on the image surface using the [Graphics](https://reference.aspose.com/imaging/net/aspose.imaging/graphics) class' [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) method. After adding the watermark in it, you can save the JPEG as WMZ format.  Below is a code example that demonstrates how to add a diagonal watermark to your document. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert & Rotate PS File to WMZ via C#" %}}
Using the API, you can also rotate the output WMZ image as per your needs. The Image.RotateFlip method can be used to rotate the image by 90/180/270-degrees and flip the image horizontally or vertically. You can specify the type of rotation and flip to apply to the image. In order to rotate and flip the image you can load the converted JPEG image using the factory method exposed by [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class and call the Image.RotateFlip method while specifying the appropriate [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype).
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}