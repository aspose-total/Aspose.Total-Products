---
title: Konvertieren Sie PCL über die C#-API in WMZ
description: Exportieren Sie PCL in WMZ in Ihren .NET-Anwendungen, ohne Anwendungen von Drittanbietern zu verwenden
url: /de/net/conversion/pcl-to-wmz/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: WMZ
otherformats: WMZ IMAGE PSD TGA WMF SVGZ  DXF JPEG2000 EMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie die PCL-Datei über C# in WMZ" h2="Exportieren Sie PCL innerhalb von .NET-Anwendungen nach WMZ, ohne Adobe<sup>&reg;</sup> Acrobat Reader oder andere Anwendungen von Drittanbietern zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Mit [Aspose.Total for .NET](https://products.aspose.com/total/net/) können Sie in zwei einfachen Schritten PCL-Bilder in WMZ-Bilder aus beliebigen .NET-Anwendungen exportieren. Zunächst einmal können Sie mit [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) PCL in JPEG exportieren. Danach können Sie mit der Bildverarbeitungs-API von [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) JPEG in WMZ konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie die PCL-Datei über .NET in WMZ" %}}
1. Öffnen Sie die PCL-Datei mit der Klasse [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document).
2. Initialisieren Sie das Klassenobjekt [JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) und rendern Sie PCL mithilfe von [Process](https://apireference.aspose. com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) Methode
3. Laden Sie die JPEG-Datei mithilfe der Klasse [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image).
4. Speichern Sie das Dokument mit der Methode [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) im WMZ-Format
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://downloads.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie PCL-Dateien in WMZ in einer einzigen Datei über C#" %}}
Mit der API können Sie auch PCL-Dateien in WMZ in eine einzelne Bilddatei konvertieren. Um alle Seiten zu konvertieren, können Sie Ihr PCL-Dokument zuerst in eine TIFF-Datei rendern und danach die TIFF-Datei nach WMZ exportieren. Sie können die Eingabedatei mit der Klasse [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) öffnen und Auflösungs-, TiffSettings- und TIFF-Geräteobjekte erstellen. Sie können ein einzelnes TIFF-Bild mit der Methode [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) von [TiffDevice](https:// apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) Klasse. Schließlich können Sie die TIFF-Datei mit der Klasse [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) laden
und speichern Sie es im WMZ-Format mit der Methode [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren und Drehen von PCL-Dateien in WMZ über C#" %}}
Mit der API können Sie das ausgegebene WMZ-Bild auch nach Ihren Bedürfnissen drehen. Die Image.RotateFlip-Methode kann verwendet werden, um das Bild um 90/180/270 Grad zu drehen und das Bild horizontal oder vertikal zu spiegeln. Sie können die Art der Drehung und Spiegelung angeben, die auf das Bild angewendet werden soll. Um das Bild zu drehen und zu spiegeln, können Sie das konvertierte JPEG-Bild mit der Factory-Methode laden, die von der Klasse [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) bereitgestellt wird, und das Bild aufrufen .RotateFlip-Methode, während Sie den entsprechenden [RotateFlipType](https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) angeben. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pcl-to-emz/" name="PCL Zu EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pcl-to-tga/" name="PCL Zu TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pcl-to-jpeg2000/" name="PCL Zu JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pcl-to-image/" name="PCL Zu IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pcl-to-psd/" name="PCL Zu PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pcl-to-wmz/" name="PCL Zu WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pcl-to-svgz/" name="PCL Zu SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pcl-to/" name="PCL Zu" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pcl-to-wmf/" name="PCL Zu WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pcl-to-dxf/" name="PCL Zu DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pcl-to-dicom/" name="PCL Zu DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}