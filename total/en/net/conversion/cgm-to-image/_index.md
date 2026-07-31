---
title: Convert CGM to Image via C# API
description: Export CGM to Images JPG, TIFF, GIF, PNG, BMP in your .NET applications without using any third party application
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: Image
otherformats: TGA DXF APNG WMZ JPEG2000 WMF SVGZ  PSD EMZ DICOM
semantic: true
page_type: generated_detail
hero:
  h1: Convert CGM file to Image via C#
  h2: Export CGM to Images within .NET applications without using Adobe<sup>&reg;</sup> Acrobat Reader or any other third party applications
sections:
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: markdown
      markdown: 'With Aspose.Total for .NET, you can easily export CGM files to various image formats within any .NET application in just two simple steps. First, using Aspose.PDF for .NET, you can export CGM to JPEG format. Afterward, by utilizing Aspose.Imaging for .NET Image Processing API, you can convert the JPEG image to a wide range of image formats.


        By combining the power of Aspose.PDF for .NET and Aspose.Imaging for .NET, you can seamlessly convert CGM files to popular image formats like JPEG, PNG, TIFF, GIF, BMP, and more. This versatility enables you to integrate image conversion capabilities into your .NET applications, catering to diverse requirements and preferences.'
      role: summary
- layout: columns
  columns:
  - width: 6
    blocks:
    - type: steps
      role: api
      title: Convert CGM file to  Image via .NET
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
      markdown: "Using the API, you can also convert CGM file to Image to a single image file. In order to convert all pages, you can first render your CGM document to one TIFF file and after that you can export TIFF file to  Image. You can open the input file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and create Resolution, TiffSettings, & TIFF device objects. You can get a single TIFF image using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) method of [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) class. Finally, you can load TIFF file using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class \nand save it to JPEG2000 format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method."
      title: Convert CGM File to Image in a Single File via C#
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
      markdown: Using the API, you can also convert CGM file to  Image with watermark in your Image document. In order to add a watermark, you can first render your CGM document to JPEG and add a watermark in it. To demonstrate the operation, you can load your converted JPEG image, add transformations using an object of Matrix class and draw a string as the watermark on the image surface using the [Graphics](https://reference.aspose.com/imaging/net/aspose.imaging/graphics) class' [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) method. After adding the watermark in it, you can save the JPEG as JPEG2000 format.  Below is a code example that demonstrates how to add a diagonal watermark to your document.
      title: Convert CGM to  Image With Watermark via C#
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
      markdown: Using the API, you can also rotate the output Image image as per your needs. The Image.RotateFlip method can be used to rotate the image by 90/180/270-degrees and flip the image horizontally or vertically. You can specify the type of rotation and flip to apply to the image. In order to rotate and flip the image you can load the converted JPEG image using the factory method exposed by [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class and call the Image.RotateFlip method while specifying the appropriate [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype).
      title: Convert & Rotate CGM File to Image via C#
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
      markdown: 'CGM (Computer Graphics Metafile) files are used to store vector graphics information, making them ideal for creating static images. However, when working with dynamic data, bitmaps like PNG become essential for image storage and distribution.


        The conversion of CGM files into image formats is necessary to unlock the full potential of your visual content and presentation capabilities. This conversion enables you to:


        **Use Cases:**


        *   **Logo Design and Branding**: Convert CGM files to create scalable vector logos, ensuring consistency across various mediums.

        *   **Infographic Creation**: Use PNG to visualize complex data in an engaging and easy-to-understand format.

        *   **Image Editing and Manipulation**: Convert CGM files to edit images, apply filters, and effects without compromising quality.

        *   **Web Design and Development**: Use PNG to create responsive images that load quickly, ensuring a seamless user experience.

        *   **Print Design and Publishing**: Convert CGM files to high-quality images for print publications, such as brochures, magazines, and newspapers.'
      title: 'Transforming CGM File to IMAGE Programmatically : Use Cases'
- type: autogen_total
---

