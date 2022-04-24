---
title: Konvertieren Sie XPS über die C#-API in DXF
description: Exportieren Sie XPS in DXF in Ihren .NET-Anwendungen, ohne Anwendungen von Drittanbietern zu verwenden
url: /de/net/conversion/xps-to-dxf/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: DXF
otherformats: WMZ IMAGE DXF EMZ WMF SVGZ TGA JPEG2000  PSD DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie die XPS-Datei über C# in DXF" h2="Exportieren Sie XPS innerhalb von .NET-Anwendungen nach DXF, ohne Adobe<sup>&reg;</sup> Acrobat Reader oder andere Anwendungen von Drittanbietern zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Mit [Aspose.Total for .NET](https://products.aspose.com/total/net/) können Sie in zwei einfachen Schritten XPS-Bilder in DXF-Bilder aus beliebigen .NET-Anwendungen exportieren. Zunächst einmal können Sie mit [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) XPS in JPEG exportieren. Danach können Sie mit der Bildverarbeitungs-API von [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) JPEG in DXF konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie die XPS-Datei über .NET in DXF" %}}
1. Öffnen Sie die XPS-Datei mit der Klasse [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document).
2. Initialisieren Sie das Klassenobjekt [JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) und rendern Sie XPS mithilfe von [Process](https://apireference.aspose. com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) Methode
3. Laden Sie die JPEG-Datei mithilfe der Klasse [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image).
4. Speichern Sie das Dokument mit der Methode [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) im DXF-Format
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://downloads.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie XPS-Dateien in DXF in einer einzigen Datei über C#" %}}
Mit der API können Sie auch XPS-Dateien in DXF in eine einzelne Bilddatei konvertieren. Um alle Seiten zu konvertieren, können Sie Ihr XPS-Dokument zuerst in eine TIFF-Datei rendern und danach die TIFF-Datei nach DXF exportieren. Sie können die Eingabedatei mit der Klasse [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) öffnen und Auflösungs-, TiffSettings- und TIFF-Geräteobjekte erstellen. Sie können ein einzelnes TIFF-Bild mit der Methode [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) von [TiffDevice](https:// apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) Klasse. Schließlich können Sie die TIFF-Datei mit der Klasse [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) laden
und speichern Sie es im DXF-Format mit der Methode [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren und Drehen von XPS-Dateien in DXF über C#" %}}
Mit der API können Sie das ausgegebene DXF-Bild auch nach Ihren Bedürfnissen drehen. Die Image.RotateFlip-Methode kann verwendet werden, um das Bild um 90/180/270 Grad zu drehen und das Bild horizontal oder vertikal zu spiegeln. Sie können die Art der Drehung und Spiegelung angeben, die auf das Bild angewendet werden soll. Um das Bild zu drehen und zu spiegeln, können Sie das konvertierte JPEG-Bild mit der Factory-Methode laden, die von der Klasse [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) bereitgestellt wird, und das Bild aufrufen .RotateFlip-Methode, während Sie den entsprechenden [RotateFlipType](https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) angeben. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xps-to-emz/" name="XPS Zu EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xps-to-tga/" name="XPS Zu TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xps-to-jpeg2000/" name="XPS Zu JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xps-to-image/" name="XPS Zu IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xps-to-psd/" name="XPS Zu PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xps-to-wmz/" name="XPS Zu WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xps-to-svgz/" name="XPS Zu SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xps-to/" name="XPS Zu" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xps-to-wmf/" name="XPS Zu WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xps-to-dxf/" name="XPS Zu DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xps-to-dicom/" name="XPS Zu DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}