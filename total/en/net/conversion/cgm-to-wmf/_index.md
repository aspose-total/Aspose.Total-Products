---
title: Convert CGM to WMF via C# API
description: Export CGM to WMF in your .NET applications without using any third party application
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: WMF
otherformats: EMZ SVGZ APNG TGA JPEG2000 DXF  PSD WMZ IMAGE DICOM
semantic: true
page_type: generated_detail
hero:
  h1: Convert CGM file to WMF via C#
  h2: Export CGM to WMF within .NET applications without using Adobe<sup>&reg;</sup> Acrobat Reader or any other third party applications
sections:
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: markdown
      markdown: 'With Aspose.Total for .NET, converting CGM files to WMF (Windows Metafile) images within any .NET application is a breeze. This can be accomplished in just two simple steps using Aspose.PDF for .NET and Aspose.Imaging for .NET Image Processing API.


        Firstly, using Aspose.PDF for .NET, you can export CGM files to JPEG format. Aspose.PDF for .NET provides a robust API for working with PDF documents, ensuring a seamless CGM to JPEG conversion process.


        Next, by leveraging Aspose.Imaging for .NET''s Image Processing API, you can effortlessly convert the JPEG image obtained in the previous step to WMF format. Aspose.Imaging for .NET offers a comprehensive set of tools and features for image manipulation, facilitating the conversion of JPEG to WMF.'
      role: summary
- layout: columns
  columns:
  - width: 6
    blocks:
    - type: steps
      role: api
      title: Convert CGM file to WMF via .NET
      items:
      - Open CGM file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
      - Initialize [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) class object and render CGM to JPEG by using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) method
      - Load JPEG file by using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class
      - Save the document to WMF format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method
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
      markdown: "Using the API, you can also convert CGM file to WMF to a single image file. In order to convert all pages, you can first render your CGM document to one TIFF file and after that you can export TIFF file to WMF. You can open the input file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and create Resolution, TiffSettings, & TIFF device objects. You can get a single TIFF image using [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) method of [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) class. Finally, you can load TIFF file using [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class \nand save it to WMF format using [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) method."
      title: Convert CGM File to WMF in a Single File via C#
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
      markdown: Using the API, you can also convert CGM file to WMF with watermark in your WMF document. In order to add a watermark, you can first render your CGM document to JPEG and add a watermark in it. To demonstrate the operation, you can load your converted JPEG image, add transformations using an object of Matrix class and draw a string as the watermark on the image surface using the [Graphics](https://reference.aspose.com/imaging/net/aspose.imaging/graphics) class' [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) method. After adding the watermark in it, you can save the JPEG as WMF format.  Below is a code example that demonstrates how to add a diagonal watermark to your document.
      title: Convert CGM to WMF With Watermark via C#
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
      markdown: Using the API, you can also rotate the output WMF image as per your needs. The Image.RotateFlip method can be used to rotate the image by 90/180/270-degrees and flip the image horizontally or vertically. You can specify the type of rotation and flip to apply to the image. In order to rotate and flip the image you can load the converted JPEG image using the factory method exposed by [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) class and call the Image.RotateFlip method while specifying the appropriate [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype).
      title: Convert & Rotate CGM File to WMF via C#
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
      markdown: 'Conversion of CGM Files into WMF Formats is Necessary to Unlock the Full Potential of Your Graphic Designs and Visualizations.


        The conversion of CGM files into WMF (Windows Metafile) formats is essential to unlock the full potential of your graphic designs and visualizations. This conversion enables you to:


        **Use Cases:**


        *   **Graphic Design and Illustration**: Convert CGM files to create complex and detailed graphics, illustrations, and logos, making them ideal for use in various media.

        *   **Architectural Visualization**: Use WMF to visualize 3D models, building designs, and architectural plans, allowing for better collaboration and communication with clients and stakeholders.

        *   **Technical Drawing and CAD**: Convert CGM files to create technical drawings, blueprints, and CAD designs, making them essential for product development, manufacturing, and engineering applications.

        *   **Artistic Expressions**: Use WMF to create intricate and detailed artistic expressions, such as graphics, icons, and logos, showcasing your creativity and skill.

        *   **Digital Signage and Displays**: Convert CGM files to create dynamic and interactive digital signage, displays, and presentations, engaging audiences and conveying messages effectively.'
      title: 'Transforming CGM File to WMF Programmatically : Use Cases'
- type: autogen_total
---

