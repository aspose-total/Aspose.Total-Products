---
title: Convert PDF to DXF via C# API
description: Export PDF to DXF in your .NET applications without using any third party application 
url_ignore: /net/conversion/pdf-to-dxf/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: DXF
otherformats: WMF PSD APNG IMAGE TGA EMZ WMZ JPEG2000 SVGZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PDF to DXF via C#, .NET Core" h2="Export PDF to DXF within .NET applications without using Adobe<sup>&reg;</sup> Acrobat Reader or any other third party applications" >}}

{{% blocks/products/pf/feature-page-summary %}}
<h2 class="heading-border">Why Convert PDF to DXF format?</h2>

Converting PDF files to DXF (Drawing Exchange Format) format using .NET can offer several advantages. Firstly, DXF is a widely supported format in the CAD (Computer-Aided Design) industry, making it compatible with various CAD software applications. By converting PDF to DXF, you can easily extract and preserve vector-based drawing elements, such as lines, curves, and text, which can be further edited and modified in CAD software. This conversion allows for seamless integration of PDF-based designs or drawings into CAD workflows, facilitating collaboration and interoperability between different design tools. Additionally, converting PDF to DXF enables accurate scaling and measurements, ensuring that the transferred drawings maintain their precision and accuracy. 

<h2 class="heading-border">How Aspose.Total can help in PDF to DXF Conversion?</h2>

By utilizing the comprehensive [Aspose.Total for .NET](https://products.aspose.com/total/net/) libraries, developers gain the necessary tools to streamline the PDF to DXF conversion process within their .NET applications. With the help of [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), the first step involves exporting the PDF file to JPEG format. Following this, [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Image Processing API enables the conversion from JPEG to DXF. This two-step approach simplifies and automates the conversion, allowing developers to seamlessly integrate PDF content into CAD workflows. With the power of Aspose.Total for .NET, the conversion from PDF to DXF becomes efficient and optimized, providing developers with the means to automate this process effortlessly within their .NET applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert PDF to DXF via .NET?" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Initialize [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) class object and render PDF to JPEG by using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) method
3. Load JPEG file by using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class 
4. Save the document to DXF format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="PDF to DXF Converter API for .NET" %}}
Install from command line as ```nuget install Aspose.Total``` or install directly from Package Manager Console of Visual Studio. Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF to DXF in a Single File via C#" %}}
Using the API, you can also convert PDF file to DXF to a single image file. In order to convert all pages, you can first render your PDF document to one TIFF file and after that you can export TIFF file to DXF. You can open the input file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and create Resolution, TiffSettings, & TIFF device objects. You can get a single TIFF image using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) method of [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) class. Finally, you can load TIFF file using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class 
and save it to DXF format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Export PDF to DXF with Watermark via C#" %}}
Using the API, you can also convert PDF file to DXF with watermark in your DXF document. In order to add a watermark, you can first render your PDF document to JPEG and add a watermark in it. To demonstrate the operation, you can load your converted JPEG image, add transformations using an object of Matrix class and draw a string as the watermark on the image surface using the [Graphics](https://reference.aspose.com/imaging/net/aspose.imaging/graphics) class' [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) method. After adding the watermark in it, you can save the JPEG as DXF format.  Below is a code example that demonstrates how to add a diagonal watermark to your document. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert & Rotate PDF to DXF via C#" %}}
Using the API, you can also rotate the output DXF image as per your needs. The Image.RotateFlip method can be used to rotate the image by 90/180/270-degrees and flip the image horizontally or vertically. You can specify the type of rotation and flip to apply to the image. In order to rotate and flip the image you can load the converted JPEG image using the factory method exposed by [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class and call the Image.RotateFlip method while specifying the appropriate [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype).
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}