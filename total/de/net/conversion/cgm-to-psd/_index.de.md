---
title: Konvertieren Sie CGM über die C#-API in PSD
description: Exportieren Sie CGM in PSD in Ihren .NET-Anwendungen, ohne Anwendungen von Drittanbietern zu verwenden
url_ignore: /de/net/conversion/cgm-to-psd/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PSD
otherformats: IMAGE  JPEG2000 TGA WMF SVGZ PSD EMZ WMZ DXF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie die CGM-Datei über C# in PSD" h2="Exportieren Sie CGM innerhalb von .NET-Anwendungen nach PSD, ohne Adobe<sup>&reg;</sup> Acrobat Reader oder andere Anwendungen von Drittanbietern zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Mit [Aspose.Total for .NET](https://products.aspose.com/total/net/) können Sie in zwei einfachen Schritten CGM-Bilder in PSD-Bilder aus beliebigen .NET-Anwendungen exportieren. Zunächst einmal können Sie mit [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) CGM in JPEG exportieren. Danach können Sie mit der Bildverarbeitungs-API von [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) JPEG in PSD konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie die CGM-Datei über .NET in PSD" %}}
1. Öffnen Sie die CGM-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Initialisieren Sie das Klassenobjekt [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) und rendern Sie CGM mithilfe von [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) Methode
3. Laden Sie die JPEG-Datei mithilfe der Klasse [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image).
4. Speichern Sie das Dokument mit der Methode [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) im PSD-Format
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie CGM-Dateien in PSD in einer einzigen Datei über C#" %}}
Mit der API können Sie auch CGM-Dateien in PSD in eine einzelne Bilddatei konvertieren. Um alle Seiten zu konvertieren, können Sie Ihr CGM-Dokument zuerst in eine TIFF-Datei rendern und danach die TIFF-Datei nach PSD exportieren. Sie können die Eingabedatei mit der Klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) öffnen und Auflösungs-, TiffSettings- und TIFF-Geräteobjekte erstellen. Sie können ein einzelnes TIFF-Bild mit der Methode [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) von [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) Klasse. Schließlich können Sie die TIFF-Datei mit der Klasse [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) laden
und speichern Sie es im PSD-Format mit der Methode [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren und Drehen von CGM-Dateien in PSD über C#" %}}
Mit der API können Sie das ausgegebene PSD-Bild auch nach Ihren Bedürfnissen drehen. Die Image.RotateFlip-Methode kann verwendet werden, um das Bild um 90/180/270 Grad zu drehen und das Bild horizontal oder vertikal zu spiegeln. Sie können die Art der Drehung und Spiegelung angeben, die auf das Bild angewendet werden soll. Um das Bild zu drehen und zu spiegeln, können Sie das konvertierte JPEG-Bild mit der Factory-Methode laden, die von der Klasse [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) bereitgestellt wird, und das Bild aufrufen .RotateFlip-Methode, während Sie den entsprechenden [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) angeben. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="CGM-Dateien programmgesteuert in PSD umwandeln: Anwendungsfälle" %}}
CGM-Dateien (Computer Graphics Metafile) werden verwendet, um Vektorgrafikinformationen zu speichern, was sie ideal für die Erstellung von statischen Grafiken und Illustrationen macht. Allerdings sind bei der Arbeit mit dynamischer Daten Rasterbildbearbeitungsprogramme wie Photoshop notwendig, um Bilder visuell darzustellen und zu bearbeiten.

Die Umwandlung von CGM-Dateien in PSD-Format ist erforderlich, um die volle Leistung Ihres Grafikdesign-Potenzials freizumachen. Diese Umwandlung ermöglicht es Ihnen:

**Verwendungsfälle:**

*   **Logo-Design**: Wandeln Sie CGM-Dateien in skalbare Vektorlogos um, die auf verschiedenen Medien verwendet werden können, wie z.B. Geschäftskaarten, Außenschildern und Websites.
*   **Marken-Identität**: Verwenden Sie PSD, um Brandanweisungen zu visualisieren, ein konsistentes visuelles Design zu erstellen und sicherzustellen, dass die Marke auf allen Marketingmaterialien einheitlich erscheint.
*   **Illustrationen und Kunstwerk**: Wandeln Sie CGM-Dateien in detaillierte Illustrationen um, bearbeiten Sie Vektorartwerken und feinjustieren Sie Designkonzepte.
*   **Druckdesign**: Verwenden Sie PSD, um Druckdesigns zu visualisieren, Layouts zu optimieren und sicherzustellen, dass die Bildqualität bei verschiedenen Druckanwendungen hochwertig ist.
*   **Grafik-Design-Assets**: Wandeln Sie CGM-Dateien in bearbare Grafik-Design-Assets um, die auf mehreren Projekten wiederholt werden können, was Zeit und Mühe spart.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}