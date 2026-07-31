---
title: Convert CGM to TGA via C# API
description: Export CGM to TGA in your .NET applications without using any third party application
url_ignore: /net/conversion/cgm-to-tga/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TGA
otherformats: EMZ APNG SVGZ IMAGE WMF  JPEG2000 WMZ DXF PSD DICOM
semantic: true
page_type: generated_detail
hero:
  h1: Convert CGM file to TGA via C#
  h2: Export CGM to TGA within .NET applications without using Adobe<sup>&reg;</sup> Acrobat Reader or any other third party applications
sections:
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: markdown
      markdown: "Aspose.Total for .NET is a comprehensive suite of .NET components that enables developers to easily export CGM to TGA image within any .NET applications. This suite includes Aspose.PDF for .NET and Aspose.Imaging for .NET, which are two powerful components that can be used to export CGM to TGA image. \n\nThe process of exporting CGM to TGA image is quite simple and can be done in two steps. First, you need to use Aspose.PDF for .NET to export CGM to JPEG. This component provides a wide range of features that can be used to manipulate PDF documents. It also allows you to export CGM to JPEG with just a few lines of code. \n\nOnce you have exported CGM to JPEG, you can then use Aspose.Imaging for .NET to convert JPEG to TGA. This component provides a comprehensive set of image processing features that can be used to manipulate various image formats. It also allows you to convert JPEG to TGA with just a few lines of code. \n\nOverall, Aspose.Total for .NET is a great suite of\
        \ components that can be used to easily export CGM to TGA image within any .NET applications. It provides a wide range of features that can be used to manipulate PDF documents and various image formats. With just a few lines of code, you can easily export CGM to TGA image with Aspose.Total for .NET."
      role: summary
- layout: columns
  columns:
  - width: 6
    blocks:
    - type: steps
      role: api
      title: Convert CGM file to TGA via .NET
      items:
      - Open CGM file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
      - Initialize [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) class object and render CGM to JPEG by using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) method
      - Load JPEG file by using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class
      - Save the document to TGA format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method
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
      markdown: "Using the API, you can also convert CGM file to TGA to a single image file. In order to convert all pages, you can first render your CGM document to one TIFF file and after that you can export TIFF file to TGA. You can open the input file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and create Resolution, TiffSettings, & TIFF device objects. You can get a single TIFF image using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) method of [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) class. Finally, you can load TIFF file using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class \nand save it to TGA format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method."
      title: Convert CGM File to TGA in a Single File via C#
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
      markdown: Using the API, you can also convert CGM file to TGA with watermark in your TGA document. In order to add a watermark, you can first render your CGM document to JPEG and add a watermark in it. To demonstrate the operation, you can load your converted JPEG image, add transformations using an object of Matrix class and draw a string as the watermark on the image surface using the [Graphics](https://reference.aspose.com/imaging/net/aspose.imaging/graphics) class' [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) method. After adding the watermark in it, you can save the JPEG as TGA format.  Below is a code example that demonstrates how to add a diagonal watermark to your document.
      title: Convert CGM to TGA With Watermark via C#
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
      markdown: Using the API, you can also rotate the output TGA image as per your needs. The Image.RotateFlip method can be used to rotate the image by 90/180/270-degrees and flip the image horizontally or vertically. You can specify the type of rotation and flip to apply to the image. In order to rotate and flip the image you can load the converted JPEG image using the factory method exposed by [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class and call the Image.RotateFlip method while specifying the appropriate [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype).
      title: Convert & Rotate CGM File to TGA via C#
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
      markdown: 'Converting CGM (Computer Graphics Metafile) files into TGA (Truevision TGA Image File) formats unlocks a world of creative possibilities, making them ideal for various applications. However, when working with dynamic content, image editors like GIMP become essential for editing and manipulation.


        The conversion of CGM files to TGA formats is necessary to unlock the full potential of your editing capabilities. This conversion enables you to:


        **Use Cases:**


        *   **Image Editing**: Convert CGM files to edit images, adjust brightness, contrast, and saturation levels.

        *   **Graphic Design**: Use TGA to create and manipulate graphics, logos, icons, and other visual elements.

        *   **Digital Painting**: Convert CGM files to digital painting, creating vibrant artwork with a wide range of colors and effects.

        *   **Architectural Visualization**: Use TGA to visualize 3D models, creating photorealistic images for architects, designers, and builders.

        *   **Medical Imaging Analysis**: Convert CGM files to medical imaging analysis, examining detailed images of organs, tissues, and cells.'
      title: 'Transforming CGM File to TGA Programmatically : Use Cases'
- type: autogen_total
---

