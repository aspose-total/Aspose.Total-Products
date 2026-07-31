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
semantic: true
page_type: generated_detail
hero:
  h1: Convert PDF to DXF via C#, .NET Core
  h2: Export PDF to DXF within .NET applications without using Adobe<sup>&reg;</sup> Acrobat Reader or any other third party applications
sections:
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: markdown
      markdown: "Why Convert PDF to DXF format?\n\nConverting PDF files to DXF (Drawing Exchange Format) format using .NET can offer several advantages. Firstly, DXF is a widely supported format in the CAD (Computer-Aided Design) industry, making it compatible with various CAD software applications. By converting PDF to DXF, you can easily extract and preserve vector-based drawing elements, such as lines, curves, and text, which can be further edited and modified in CAD software. This conversion allows for seamless integration of PDF-based designs or drawings into CAD workflows, facilitating collaboration and interoperability between different design tools. Additionally, converting PDF to DXF enables accurate scaling and measurements, ensuring that the transferred drawings maintain their precision and accuracy. \n\nHow Aspose.Total can help in PDF to DXF Conversion?\n\nBy utilizing the comprehensive [Aspose.Total for .NET](https://products.aspose.com/total/net/) libraries, developers gain\
        \ the necessary tools to streamline the PDF to DXF conversion process within their .NET applications. With the help of [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), the first step involves exporting the PDF file to JPEG format. Following this, [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Image Processing API enables the conversion from JPEG to DXF. This two-step approach simplifies and automates the conversion, allowing developers to seamlessly integrate PDF content into CAD workflows. With the power of Aspose.Total for .NET, the conversion from PDF to DXF becomes efficient and optimized, providing developers with the means to automate this process effortlessly within their .NET applications."
      role: summary
- layout: columns
  columns:
  - width: 6
    blocks:
    - type: steps
      role: api
      title: How to Convert PDF to DXF via .NET?
      items:
      - Open PDF file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
      - Initialize [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) class object and render PDF to JPEG by using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) method
      - Load JPEG file by using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class
      - Save the document to DXF format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method
  - width: 6
    blocks:
    - type: markdown
      title: PDF to DXF Converter API for .NET
      markdown: Install from command line as ```nuget install Aspose.Total``` or install directly from Package Manager Console of Visual Studio. Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
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
      markdown: "Using the API, you can also convert PDF file to DXF to a single image file. In order to convert all pages, you can first render your PDF document to one TIFF file and after that you can export TIFF file to DXF. You can open the input file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and create Resolution, TiffSettings, & TIFF device objects. You can get a single TIFF image using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) method of [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) class. Finally, you can load TIFF file using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class \nand save it to DXF format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method."
      title: Convert PDF to DXF in a Single File via C#
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
      markdown: Using the API, you can also convert PDF file to DXF with watermark in your DXF document. In order to add a watermark, you can first render your PDF document to JPEG and add a watermark in it. To demonstrate the operation, you can load your converted JPEG image, add transformations using an object of Matrix class and draw a string as the watermark on the image surface using the [Graphics](https://reference.aspose.com/imaging/net/aspose.imaging/graphics) class' [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) method. After adding the watermark in it, you can save the JPEG as DXF format.  Below is a code example that demonstrates how to add a diagonal watermark to your document.
      title: Export PDF to DXF with Watermark via C#
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
      title: Convert & Rotate PDF to DXF via C#
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
      markdown: 'PDF (Portable Document Format) files are used to store document information, making them ideal for creating static documents and publications. However, when working with detailed drawings and designs, DXF (Drawing Exchange Format) becomes essential for accurate representation and manipulation.


        The conversion of PDF files into DXF formats is necessary to unlock the full potential of your design capabilities. This conversion enables you to:


        **Use Cases:**


        *   **Architectural and Engineering Design**: Convert PDF files to create detailed drawings, designs, and schematics that can be easily edited and shared.

        *   **Product Manufacturing and Prototyping**: Use DXF to generate 2D and 3D models from existing designs, facilitating the creation of prototypes, molds, and tooling.

        *   **CADCAM (Computer-Aided Design/Computer-Aided Manufacturing)**: Convert PDF files to create precise digital models for CNC machining, fabrication, and assembly.

        *   **Geospatial Data Conversion**: Use DXF to convert PDF files containing geospatial data into a format that can be used with GIS software, enabling detailed mapping and analysis.

        *   **Automotive and Aerospace Design**: Convert PDF files to generate 2D and 3D models from existing designs, facilitating the creation of prototypes, tooling, and manufacturing plans.'
      title: 'Transforming PDF File to DXF Programmatically : Use Cases'
- type: autogen_total
---

