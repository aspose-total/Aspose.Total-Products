---
title: Convert XSLFO to DXF via C# API
description: Export XSLFO to DXF in your .NET applications without using any third party application 
url_ignore: /net/conversion/xslfo-to-dxf/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: DXF
otherformats: WMZ PSD TGA JPEG2000 WMF IMAGE SVGZ EMZ APNG DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert XSLFO file to DXF via C#" h2="Export XSLFO to DXF within .NET applications without using Adobe<sup>&reg;</sup> Acrobat Reader or any other third party applications" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for .NET is a comprehensive suite of .NET components that enables developers to easily create, edit, convert, and export documents within their .NET applications. With Aspose.Total for .NET, you can easily export XSLFO to DXF image in two simple steps. 

The first step is to use Aspose.PDF for .NET to export XSLFO to JPEG. Aspose.PDF for .NET is a powerful .NET library that enables developers to create, read, edit, and convert PDF documents within their .NET applications. It provides a wide range of features such as document manipulation, text extraction, image extraction, and much more. With Aspose.PDF for .NET, you can easily export XSLFO to JPEG with just a few lines of code. 

The second step is to use Aspose.Imaging for .NET to convert JPEG to DXF. Aspose.Imaging for .NET is a powerful .NET library that enables developers to create, edit, and convert images within their .NET applications. It provides a wide range of features such as image manipulation, image conversion, image resizing, and much more. With Aspose.Imaging for .NET, you can easily convert JPEG to DXF with just a few lines of code. 

In conclusion, Aspose.Total for .NET makes it easy to export XSLFO to DXF image within any .NET applications in two simple steps. First, you can use Aspose.PDF for .NET to export XSLFO to JPEG. Then, you can use Aspose.Imaging for .NET to convert JPEG to DXF. With Aspose.Total for .NET, you can easily create, edit, convert, and export documents within your .NET applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert XSLFO file to DXF via .NET" %}}
1. Open XSLFO file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Initialize [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) class object and render XSLFO to JPEG by using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) method
3. Load JPEG file by using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class 
4. Save the document to DXF format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
Install from command line as ```nuget install Aspose.Total``` or install directly from Package Manager Console of Visual Studio.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert XSLFO File to DXF in a Single File via C#" %}}
Using the API, you can also convert XSLFO file to DXF to a single image file. In order to convert all pages, you can first render your XSLFO document to one TIFF file and after that you can export TIFF file to DXF. You can open the input file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and create Resolution, TiffSettings, & TIFF device objects. You can get a single TIFF image using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) method of [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) class. Finally, you can load TIFF file using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class 
and save it to DXF format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert XSLFO to DXF With Watermark via C#" %}}
Using the API, you can also convert XSLFO file to DXF with watermark in your DXF document. In order to add a watermark, you can first render your XSLFO document to JPEG and add a watermark in it. To demonstrate the operation, you can load your converted JPEG image, add transformations using an object of Matrix class and draw a string as the watermark on the image surface using the [Graphics](https://reference.aspose.com/imaging/net/aspose.imaging/graphics) class' [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) method. After adding the watermark in it, you can save the JPEG as DXF format.  Below is a code example that demonstrates how to add a diagonal watermark to your document. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert & Rotate XSLFO File to DXF via C#" %}}
Using the API, you can also rotate the output DXF image as per your needs. The Image.RotateFlip method can be used to rotate the image by 90/180/270-degrees and flip the image horizontally or vertically. You can specify the type of rotation and flip to apply to the image. In order to rotate and flip the image you can load the converted JPEG image using the factory method exposed by [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class and call the Image.RotateFlip method while specifying the appropriate [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype).
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}