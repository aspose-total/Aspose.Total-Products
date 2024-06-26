---
title: Convert MD to JPEG2000 via C# API
description: Export MD to JPEG2000 in your .NET applications without using any third party application 
url_ignore: /net/conversion/md-to-jpeg2000/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: JPEG2000
otherformats: WMF EMZ  DXF APNG WMZ TGA IMAGE SVGZ PSD DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert MD file to JPEG2000 via C#" h2="Export MD to JPEG2000 within .NET applications without using Adobe<sup>&reg;</sup> Acrobat Reader or any other third party applications" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a comprehensive suite of APIs that enables developers to easily export MD to JPEG2000 image within any .NET applications. This suite of APIs includes Aspose.PDF for .NET and Aspose.Imaging for .NET, which are both powerful and feature-rich APIs that allow developers to quickly and easily create, manipulate, and convert various file formats. 

Using Aspose.PDF for .NET, developers can export MD to JPEG. This API provides a wide range of features that allow developers to easily create, manipulate, and convert PDF documents. It also provides features such as text extraction, document splitting, page merging, and more. 

Once the MD has been exported to JPEG, Aspose.Imaging for .NET can be used to convert the JPEG to JPEG2000. This powerful Image Processing API provides a wide range of features that allow developers to easily manipulate, convert, and process various image formats. It also provides features such as image resizing, cropping, rotating, and more. 

With Aspose.Total for .NET, developers can easily export MD to JPEG2000 image within any .NET applications in two simple steps. First, by using Aspose.PDF for .NET, developers can export MD to JPEG. Then, by using Aspose.Imaging for .NET, developers can convert the JPEG to JPEG2000. This suite of APIs provides developers with a comprehensive set of features that allow them to quickly and easily create, manipulate, and convert various file formats.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert MD file to JPEG2000 via .NET" %}}
1. Open MD file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Initialize [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) class object and render MD to JPEG by using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) method
3. Load JPEG file by using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class 
4. Save the document to JPEG2000 format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Automation APIs" %}}
Install from command line as ```nuget install Aspose.Total``` or install directly from Package Manager Console of Visual Studio.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert MD File to JPEG2000 in a Single File via C#" %}}
Using the API, you can also convert MD file to JPEG2000 to a single image file. In order to convert all pages, you can first render your MD document to one TIFF file and after that you can export TIFF file to JPEG2000. You can open the input file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and create Resolution, TiffSettings, & TIFF device objects. You can get a single TIFF image using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) method of [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) class. Finally, you can load TIFF file using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class 
and save it to JPEG2000 format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert MD to JPEG2000 With Watermark via C#" %}}
Using the API, you can also convert MD file to JPEG2000 with watermark in your JPEG2000 document. In order to add a watermark, you can first render your MD document to JPEG and add a watermark in it. To demonstrate the operation, you can load your converted JPEG image, add transformations using an object of Matrix class and draw a string as the watermark on the image surface using the [Graphics](https://reference.aspose.com/imaging/net/aspose.imaging/graphics) class' [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) method. After adding the watermark in it, you can save the JPEG as JPEG2000 format.  Below is a code example that demonstrates how to add a diagonal watermark to your document. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert & Rotate MD File to JPEG2000 via C#" %}}
Using the API, you can also rotate the output JPEG2000 image as per your needs. The Image.RotateFlip method can be used to rotate the image by 90/180/270-degrees and flip the image horizontally or vertically. You can specify the type of rotation and flip to apply to the image. In order to rotate and flip the image you can load the converted JPEG image using the factory method exposed by [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class and call the Image.RotateFlip method while specifying the appropriate [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype).
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}