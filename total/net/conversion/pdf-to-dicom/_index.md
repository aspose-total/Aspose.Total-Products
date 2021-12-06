---
title: Convert PDF to DICOM via C# API
description: Convert PDF to DICOM in your .NET applications without using any third party application 
url: /net/conversion/pdf-to-dicom/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: DICOM
otherformats: WMZ JPEG2000 SVGZ WMF TGA PSD DXF APNG EMZ IMAGE
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PDF to DICOM via C#" h2="Convert PDF to DICOM within .NET applications without using Adobe<sup>&reg;</sup> Acrobat Reader or any other third party applications" >}}

{{% blocks/products/pf/feature-page-summary %}}
Using [Aspose.Total for .NET](https://products.aspose.com/total/net/) you can easily convert PDF to DICOM within any .NET applications in two simple steps. First of all, by using [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), you can export PDF to JPEG. After that, by using [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Image Processing API, you can convert JPEG to DICOM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert PDF to DICOM via .NET" %}}
1. Open PDF file using [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) class
2. Initialize [JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) class object and render PDF to JPEG by using [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) method
3. Load JPEG file by using [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) class 
4. Save the document to DICOM format using [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Automation APIs" %}}
Install from command line as ```nuget install Aspose.Total``` or install directly from Package Manager Console of Visual Studio.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF to DICOM in a Single File via C#" %}}
Using the API, you can also convert PDF to DICOM to a single file. In order to convert all pages, you can first render your PDF document to one TIFF file and after that you can convert your TIFF file to DICOM. You can open the input file using [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) class and create Resolution, TiffSettings, & TIFF device objects. You can get a single TIFF image using [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) method of [TiffDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) class. Finally, you can load TIFF file using [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) class 
and save it to DICOM format using [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF to DICOM With Watermark via C#" %}}
Using the API, you can also convert PDF to DICOM with watermark in your DICOM document. In order to add a watermark, you can first render your PDF document to JPEG and add a watermark in it. To demonstrate the operation, you can load your converted JPEG image, add transformations using an object of Matrix class and draw a string as the watermark on the image surface using the [Graphics](https://apireference.aspose.com/imaging/net/aspose.imaging/graphics) class' [DrawString](https://apireference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) method. After adding the watermark in it, you can save the JPEG as DICOM format.  Below is a code example that demonstrates how to add a diagonal watermark to your document. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}