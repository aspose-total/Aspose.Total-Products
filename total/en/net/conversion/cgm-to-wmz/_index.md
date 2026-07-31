---
title: Convert CGM to WMZ via C# API
description: Export CGM to WMZ in your .NET applications without using any third party application
url_ignore: /net/conversion/cgm-to-wmz/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: WMZ
otherformats: WMF APNG SVGZ JPEG2000 EMZ DXF TGA IMAGE PSD DICOM
semantic: true
page_type: generated_detail
hero:
  h1: Convert CGM file to WMZ via C#
  h2: Export CGM to WMZ within .NET applications without using Adobe<sup>&reg;</sup> Acrobat Reader or any other third party applications
sections:
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: markdown
      markdown: 'Aspose.Total for .NET is a comprehensive suite of .NET components that enables developers to easily export CGM to WMZ image within any .NET applications. This suite includes Aspose.PDF for .NET and Aspose.Imaging for .NET, two powerful components that can be used to perform the conversion.


        The first step in the process is to use Aspose.PDF for .NET to export CGM to JPEG. This component provides a wide range of features that make it easy to convert CGM to JPEG. It supports a variety of formats, including CGM, PDF, TIFF, JPEG, PNG, and more. It also provides a range of options for customizing the output, such as setting the resolution, color depth, and compression level.


        Once the CGM has been converted to JPEG, the next step is to use Aspose.Imaging for .NET to convert the JPEG to WMZ. This component provides a comprehensive set of image processing features, including the ability to convert between different image formats. It also provides a range of options for customizing the output, such as setting the resolution, color depth, and compression level.


        By using Aspose.Total for .NET, developers can easily export CGM to WMZ image within any .NET applications in two simple steps. First, they can use Aspose.PDF for .NET to export CGM to JPEG. Then, they can use Aspose.Imaging for .NET to convert the JPEG to WMZ. This suite of components provides a comprehensive set of features that make it easy to perform the conversion quickly and accurately.'
      role: summary
- layout: columns
  columns:
  - width: 6
    blocks:
    - type: steps
      role: api
      title: Convert CGM file to WMZ via .NET
      items:
      - Open CGM file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
      - Initialize [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) class object and render CGM to JPEG by using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) method
      - Load JPEG file by using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class
      - Save the document to WMZ format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method
  - width: 6
    blocks:
    - type: markdown
      title: Conversion Requirements
      markdown: 'Install from command line as ```nuget install Aspose.Total``` or install directly from Package Manager Console of Visual Studio.


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
      markdown: "Using the API, you can also convert CGM file to WMZ to a single image file. In order to convert all pages, you can first render your CGM document to one TIFF file and after that you can export TIFF file to WMZ. You can open the input file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and create Resolution, TiffSettings, & TIFF device objects. You can get a single TIFF image using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) method of [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) class. Finally, you can load TIFF file using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class \nand save it to WMZ format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method."
      title: Convert CGM File to WMZ in a Single File via C#
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
      markdown: Using the API, you can also convert CGM file to WMZ with watermark in your WMZ document. In order to add a watermark, you can first render your CGM document to JPEG and add a watermark in it. To demonstrate the operation, you can load your converted JPEG image, add transformations using an object of Matrix class and draw a string as the watermark on the image surface using the [Graphics](https://reference.aspose.com/imaging/net/aspose.imaging/graphics) class' [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) method. After adding the watermark in it, you can save the JPEG as WMZ format.  Below is a code example that demonstrates how to add a diagonal watermark to your document.
      title: Convert CGM to WMZ With Watermark via C#
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
      markdown: Using the API, you can also rotate the output WMZ image as per your needs. The Image.RotateFlip method can be used to rotate the image by 90/180/270-degrees and flip the image horizontally or vertically. You can specify the type of rotation and flip to apply to the image. In order to rotate and flip the image you can load the converted JPEG image using the factory method exposed by [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class and call the Image.RotateFlip method while specifying the appropriate [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype).
      title: Convert & Rotate CGM File to WMZ via C#
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
      markdown: ''
      title: 'Transforming CGM File to WMZ Programmatically : Use Cases'
- type: autogen_total
---

