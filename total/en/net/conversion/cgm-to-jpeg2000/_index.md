---
title: Convert CGM to JPEG2000 via C# API
description: Export CGM to JPEG2000 in your .NET applications without using any third party application
url_ignore: /net/conversion/cgm-to-jpeg2000/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: JPEG2000
otherformats: WMF  TGA DXF IMAGE WMZ APNG PSD SVGZ EMZ DICOM
semantic: true
page_type: generated_detail
hero:
  h1: Convert CGM file to JPEG2000 via C#
  h2: Export CGM to JPEG2000 within .NET applications without using Adobe<sup>&reg;</sup> Acrobat Reader or any other third party applications
sections:
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: markdown
      markdown: "Aspose.Total for .NET is a comprehensive suite of .NET components that enables developers to easily export CGM to JPEG2000 image within any .NET applications. This suite includes Aspose.PDF for .NET and Aspose.Imaging for .NET, which are two powerful components that can be used to export CGM to JPEG and convert JPEG to JPEG2000 respectively. \n\nThe process of exporting CGM to JPEG2000 image is quite simple and can be done in two steps. First of all, you need to use Aspose.PDF for .NET to export CGM to JPEG. This component provides a wide range of features that can be used to manipulate PDF documents. It also supports a variety of image formats, including CGM. With Aspose.PDF for .NET, you can easily export CGM to JPEG with just a few lines of code. \n\nOnce you have exported CGM to JPEG, you can then use Aspose.Imaging for .NET to convert JPEG to JPEG2000. This powerful Image Processing API provides a wide range of features that can be used to manipulate images. It also\
        \ supports a variety of image formats, including JPEG2000. With Aspose.Imaging for .NET, you can easily convert JPEG to JPEG2000 with just a few lines of code. \n\nIn conclusion, Aspose.Total for .NET is a great suite of .NET components that enables developers to easily export CGM to JPEG2000 image within any .NET applications. With Aspose.PDF for .NET and Aspose.Imaging for .NET, you can easily export CGM to JPEG and convert JPEG to JPEG2000 respectively. This makes the process of exporting CGM to JPEG2000 image quite simple and straightforward."
      role: summary
- layout: columns
  columns:
  - width: 6
    blocks:
    - type: steps
      role: api
      title: Convert CGM file to JPEG2000 via .NET
      items:
      - Open CGM file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
      - Initialize [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) class object and render CGM to JPEG by using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) method
      - Load JPEG file by using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class
      - Save the document to JPEG2000 format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method
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
      markdown: "Using the API, you can also convert CGM file to JPEG2000 to a single image file. In order to convert all pages, you can first render your CGM document to one TIFF file and after that you can export TIFF file to JPEG2000. You can open the input file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and create Resolution, TiffSettings, & TIFF device objects. You can get a single TIFF image using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) method of [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) class. Finally, you can load TIFF file using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class \nand save it to JPEG2000 format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method."
      title: Convert CGM File to JPEG2000 in a Single File via C#
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
      markdown: Using the API, you can also convert CGM file to JPEG2000 with watermark in your JPEG2000 document. In order to add a watermark, you can first render your CGM document to JPEG and add a watermark in it. To demonstrate the operation, you can load your converted JPEG image, add transformations using an object of Matrix class and draw a string as the watermark on the image surface using the [Graphics](https://reference.aspose.com/imaging/net/aspose.imaging/graphics) class' [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) method. After adding the watermark in it, you can save the JPEG as JPEG2000 format.  Below is a code example that demonstrates how to add a diagonal watermark to your document.
      title: Convert CGM to JPEG2000 With Watermark via C#
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
      markdown: Using the API, you can also rotate the output JPEG2000 image as per your needs. The Image.RotateFlip method can be used to rotate the image by 90/180/270-degrees and flip the image horizontally or vertically. You can specify the type of rotation and flip to apply to the image. In order to rotate and flip the image you can load the converted JPEG image using the factory method exposed by [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class and call the Image.RotateFlip method while specifying the appropriate [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype).
      title: Convert & Rotate CGM File to JPEG2000 via C#
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
      markdown: 'CGM (Computer Graphics Metafile) files are used to store vector graphics information, making them ideal for creating static graphics and illustrations. However, when working with dynamic data, images like JPEG 2000 become essential for optimal compression and quality.


        The conversion of CGM files into JPEG 2000 formats is necessary to unlock the full potential of your image compression and quality capabilities. This conversion enables you to:


        **Use Cases:**


        *   **High-Quality Image Editing**: Convert CGM files to create high-quality images, optimize graphics for web use, and ensure consistent branding across all marketing materials.

        *   **Archival and Preservation Applications**: Use JPEG 2000 to compress and store large image datasets, ensuring long-term preservation and accessibility of valuable visual content.

        *   **Medical Imaging and Diagnostics**: Convert CGM files to create detailed, high-quality medical images for diagnostic purposes, reducing errors and improving patient outcomes.

        *   **Scientific Research and Publication**: Use JPEG 2000 to compress and publish large datasets of scientific images, facilitating global collaboration and knowledge sharing.

        *   **Digital Libraries and Archives**: Convert CGM files to create scalable, high-quality digital libraries, preserving cultural heritage and historical artifacts for future generations.'
      title: 'Transforming CGM File to JPEG2000 Programmatically : Use Cases'
- type: autogen_total
---

