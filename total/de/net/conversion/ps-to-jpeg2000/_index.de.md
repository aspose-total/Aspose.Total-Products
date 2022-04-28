---
title: Konvertieren Sie PS über die C#-API in JPEG2000
description: Exportieren Sie PS in JPEG2000 in Ihren .NET-Anwendungen, ohne Anwendungen von Drittanbietern zu verwenden
url: /de/net/conversion/ps-to-jpeg2000/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: JPEG2000
otherformats: TGA WMZ SVGZ WMF PSD IMAGE DXF  EMZ JPEG2000 DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie die PS-Datei über C# in JPEG2000" h2="Exportieren Sie PS innerhalb von .NET-Anwendungen nach JPEG2000, ohne Adobe<sup>&reg;</sup> Acrobat Reader oder andere Anwendungen von Drittanbietern zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Mit [Aspose.Total for .NET](https://products.aspose.com/total/net/) können Sie in zwei einfachen Schritten PS-Bilder in JPEG2000-Bilder aus beliebigen .NET-Anwendungen exportieren. Zunächst einmal können Sie mit [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) PS in JPEG exportieren. Danach können Sie mit der Bildverarbeitungs-API von [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) JPEG in JPEG2000 konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie die PS-Datei über .NET in JPEG2000" %}}
1. Öffnen Sie die PS-Datei mit der Klasse [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document).
2. Initialisieren Sie das Klassenobjekt [JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) und rendern Sie PS mithilfe von [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) Methode
3. Laden Sie die JPEG-Datei mithilfe der Klasse [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image).
4. Speichern Sie das Dokument mit der Methode [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) im JPEG2000-Format
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://downloads.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie PS-Dateien in JPEG2000 in einer einzigen Datei über C#" %}}
Mit der API können Sie auch PS-Dateien in JPEG2000 in eine einzelne Bilddatei konvertieren. Um alle Seiten zu konvertieren, können Sie Ihr PS-Dokument zuerst in eine TIFF-Datei rendern und danach die TIFF-Datei nach JPEG2000 exportieren. Sie können die Eingabedatei mit der Klasse [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) öffnen und Auflösungs-, TiffSettings- und TIFF-Geräteobjekte erstellen. Sie können ein einzelnes TIFF-Bild mit der Methode [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) von [TiffDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) Klasse. Schließlich können Sie die TIFF-Datei mit der Klasse [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) laden
und speichern Sie es im JPEG2000-Format mit der Methode [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren und Drehen von PS-Dateien in JPEG2000 über C#" %}}
Mit der API können Sie das ausgegebene JPEG2000-Bild auch nach Ihren Bedürfnissen drehen. Die Image.RotateFlip-Methode kann verwendet werden, um das Bild um 90/180/270 Grad zu drehen und das Bild horizontal oder vertikal zu spiegeln. Sie können die Art der Drehung und Spiegelung angeben, die auf das Bild angewendet werden soll. Um das Bild zu drehen und zu spiegeln, können Sie das konvertierte JPEG-Bild mit der Factory-Methode laden, die von der Klasse [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) bereitgestellt wird, und das Bild aufrufen .RotateFlip-Methode, während Sie den entsprechenden [RotateFlipType](https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) angeben. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/ps-to-emz/" name="PS Zu EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/ps-to-tga/" name="PS Zu TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/ps-to-jpeg2000/" name="PS Zu JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/ps-to-image/" name="PS Zu IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/ps-to-psd/" name="PS Zu PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/ps-to-wmz/" name="PS Zu WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/ps-to-svgz/" name="PS Zu SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/ps-to/" name="PS Zu" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/ps-to-wmf/" name="PS Zu WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/ps-to-dxf/" name="PS Zu DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/ps-to-dicom/" name="PS Zu DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}