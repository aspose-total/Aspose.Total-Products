---
title: Convert XPS to EMZ via C# API
description: Export XPS to EMZ in your .NET applications without using any third party application 
url_ignore: /net/conversion/xps-to-emz/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: EMZ
otherformats: DXF WMZ WMF PSD APNG  SVGZ IMAGE JPEG2000 TGA DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert XPS file to EMZ via C#" h2="Export XPS to EMZ within .NET applications without using Adobe<sup>&reg;</sup> Acrobat Reader or any other third party applications" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a comprehensive suite of .NET components that enables developers to easily create, manipulate and convert various file formats within their .NET applications. It includes components for manipulating PDF, Word, Excel, PowerPoint, Outlook, Project, Visio, Barcode, OCR, HTML, Email, CAD and many more. With Aspose.Total for .NET, developers can easily export XPS to EMZ image within any .NET applications in two simple steps. 

The first step is to use Aspose.PDF for .NET to export XPS to JPEG. Aspose.PDF for .NET is a powerful PDF manipulation API that enables developers to create, read, edit, convert and print PDF documents within their .NET applications. It supports a wide range of features such as document conversion, text extraction, document signing, document security, document compression, document splitting and merging, and much more. With Aspose.PDF for .NET, developers can easily export XPS to JPEG. 

The second step is to use Aspose.Imaging for .NET to convert JPEG to EMZ. Aspose.Imaging for .NET is an advanced image processing API that enables developers to create, edit, convert and manipulate various image file formats within their .NET applications. It supports a wide range of features such as image resizing, cropping, rotating, flipping, color adjustment, image effects, image compression, and much more. With Aspose.Imaging for .NET, developers can easily convert JPEG to EMZ. 

In conclusion, Aspose.Total for .NET makes it easy for developers to export XPS to EMZ image within any .NET applications in two simple steps. First, they can use Aspose.PDF for .NET to export XPS to JPEG. Then, they can use Aspose.Imaging for .NET to convert JPEG to EMZ. With Aspose.Total for .NET, developers can easily create, manipulate and convert various file formats within their .NET applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert XPS file to EMZ via .NET" %}}
1. Open XPS file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Initialize [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) class object and render XPS to JPEG by using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) method
3. Load JPEG file by using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class 
4. Save the document to EMZ format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Automation APIs" %}}
Install from command line as ```nuget install Aspose.Total``` or install directly from Package Manager Console of Visual Studio.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert XPS File to EMZ in a Single File via C#" %}}
Using the API, you can also convert XPS file to EMZ to a single image file. In order to convert all pages, you can first render your XPS document to one TIFF file and after that you can export TIFF file to EMZ. You can open the input file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and create Resolution, TiffSettings, & TIFF device objects. You can get a single TIFF image using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) method of [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) class. Finally, you can load TIFF file using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class 
and save it to EMZ format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert XPS to EMZ With Watermark via C#" %}}
Using the API, you can also convert XPS file to EMZ with watermark in your EMZ document. In order to add a watermark, you can first render your XPS document to JPEG and add a watermark in it. To demonstrate the operation, you can load your converted JPEG image, add transformations using an object of Matrix class and draw a string as the watermark on the image surface using the [Graphics](https://reference.aspose.com/imaging/net/aspose.imaging/graphics) class' [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) method. After adding the watermark in it, you can save the JPEG as EMZ format.  Below is a code example that demonstrates how to add a diagonal watermark to your document. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert & Rotate XPS File to EMZ via C#" %}}
Using the API, you can also rotate the output EMZ image as per your needs. The Image.RotateFlip method can be used to rotate the image by 90/180/270-degrees and flip the image horizontally or vertically. You can specify the type of rotation and flip to apply to the image. In order to rotate and flip the image you can load the converted JPEG image using the factory method exposed by [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class and call the Image.RotateFlip method while specifying the appropriate [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype).
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}