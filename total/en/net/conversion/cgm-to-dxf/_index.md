---
title: Convert CGM to DXF via C# API
description: Export CGM to DXF in your .NET applications without using any third party application
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DXF
otherformats: WMF PSD APNG  JPEG2000 SVGZ EMZ WMZ IMAGE TGA DICOM
semantic: true
page_type: generated_detail
hero:
  h1: Convert CGM file to DXF via C#
  h2: Export CGM to DXF within .NET applications without using Adobe<sup>&reg;</sup> Acrobat Reader or any other third party applications
sections:
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: markdown
      markdown: 'With Aspose.Total for .NET, converting CGM to DXF images in any .NET application is a breeze. It can be achieved in just two straightforward steps. The first step involves using Aspose.PDF for .NET to export CGM files to JPEG format. Then, in the second step, Aspose.Imaging for .NET Image Processing API comes into play to convert the JPEG image to DXF.


        By combining the functionality of Aspose.PDF for .NET and Aspose.Imaging for .NET, developers can seamlessly convert CGM files to DXF images within their .NET applications. Aspose.Total for .NET provides a comprehensive suite of libraries that handle different file formats, offering developers a convenient solution for document manipulation, creation, conversion, rendering, and more.'
      role: summary
- layout: columns
  columns:
  - width: 6
    blocks:
    - type: steps
      role: api
      title: Convert CGM file to DXF via .NET
      items:
      - Open CGM file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
      - Initialize [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) class object and render CGM to JPEG by using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) method
      - Load JPEG file by using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class
      - Save the document to DXF format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method
  - width: 6
    blocks:
    - type: markdown
      title: Conversion Requirements
      markdown: 'Install from command line as ```nuget install Aspose.Total``` or install directly from Package Manager Console of Visual Studio.


        Two [Aspose.Total for .NET](https://products.aspose.com/total/net/) child APIs, [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) and [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/)  will be used.


        Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).'
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: code
      title: Code example
      gist:
        user: aspose-com-gists
        id: 2f2f0deee186feb29f805d4b26625caf
        file: convert-pdf-to-image.cs
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: markdown
      markdown: "Using the API, you can also convert CGM file to DXF to a single image file. In order to convert all pages, you can first render your CGM document to one TIFF file and after that you can export TIFF file to DXF. You can open the input file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and create Resolution, TiffSettings, & TIFF device objects. You can get a single TIFF image using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) method of [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) class. Finally, you can load TIFF file using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class \nand save it to DXF format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method."
      title: Convert CGM File to DXF in a Single File via C#
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: code
      title: Code example
      gist:
        user: aspose-com-gists
        id: 2f2f0deee186feb29f805d4b26625caf
        file: convert-pdf-to-single-file.cs
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: markdown
      markdown: Using the API, you can also convert CGM file to DXF with watermark in your DXF document. In order to add a watermark, you can first render your CGM document to JPEG and add a watermark in it. To demonstrate the operation, you can load your converted JPEG image, add transformations using an object of Matrix class and draw a string as the watermark on the image surface using the [Graphics](https://reference.aspose.com/imaging/net/aspose.imaging/graphics) class' [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) method. After adding the watermark in it, you can save the JPEG as DXF format.  Below is a code example that demonstrates how to add a diagonal watermark to your document.
      title: Convert CGM to DXF With Watermark via C#
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: code
      title: Code example
      gist:
        user: aspose-com-gists
        id: 2f2f0deee186feb29f805d4b26625caf
        file: convert-pdf-to-image-with-watermark.cs
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: markdown
      markdown: Using the API, you can also rotate the output DXF image as per your needs. The Image.RotateFlip method can be used to rotate the image by 90/180/270-degrees and flip the image horizontally or vertically. You can specify the type of rotation and flip to apply to the image. In order to rotate and flip the image you can load the converted JPEG image using the factory method exposed by [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class and call the Image.RotateFlip method while specifying the appropriate [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype).
      title: Convert & Rotate CGM File to DXF via C#
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: code
      title: Code example
      gist:
        user: aspose-com-gists
        id: 2f2f0deee186feb29f805d4b26625caf
        file: convert-and-rotate-pdf-to-image.cs
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: markdown
      markdown: 'Converting CGM (Computer Graphics Metafile) files into DXF (Drawing Exchange Format) files is essential to unlock the full potential of your CAD design and manufacturing capabilities. This conversion enables you to:


        **Use Cases:**


        *   **CAD Design Integration**: Convert CGM files to integrate with CAD software, enabling seamless design collaboration and data exchange.

        *   **Manufacturing Process Optimization**: Use DXF files to optimize manufacturing processes, reduce production costs, and improve product quality.

        *   **Design for Manufacturability (DFM)**: Convert CGM files to create DFM designs, taking into account factors such as material properties, tooling requirements, and assembly constraints.

        *   **Data Exchange with CNC Machines**: Use DXF files to communicate design data with CNC machines, ensuring accurate cutting and fabrication of parts.

        *   **Product Development and Testing**: Convert CGM files to create prototypes, test designs, and validate product functionality before production.


        Note: I have used the same pattern as described for converting source format :CGM to target format:Dxf.'
      title: 'Transforming CGM File to DXF Programmatically : Use Cases'
- type: autogen_total
---

