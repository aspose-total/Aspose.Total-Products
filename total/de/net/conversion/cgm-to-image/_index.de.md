---
title: Konvertieren Sie CGM über die C#-API in IMAGE
description: Exportieren Sie CGM in IMAGE in Ihren .NET-Anwendungen, ohne Anwendungen von Drittanbietern zu verwenden
url_ignore: /de/net/conversion/cgm-to-image/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: JPEG2000
otherformats: TGA DXF IMAGE WMZ JPEG2000 WMF SVGZ  PSD EMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie die CGM-Datei über C# in IMAGE" h2="Exportieren Sie CGM innerhalb von .NET-Anwendungen nach IMAGE, ohne Adobe<sup>&reg;</sup> Acrobat Reader oder andere Anwendungen von Drittanbietern zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Mit [Aspose.Total for .NET](https://products.aspose.com/total/net/) können Sie in zwei einfachen Schritten CGM-Bilder in IMAGE-Bilder aus beliebigen .NET-Anwendungen exportieren. Zunächst einmal können Sie mit [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) CGM in JPEG exportieren. Danach können Sie mit der Bildverarbeitungs-API von [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) JPEG in IMAGE konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie die CGM-Datei über .NET in IMAGE" %}}
1. Öffnen Sie die CGM-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Initialisieren Sie das Klassenobjekt [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) und rendern Sie CGM mithilfe von [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) Methode
3. Laden Sie die JPEG-Datei mithilfe der Klasse [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image).
4. Speichern Sie das Dokument mit der Methode [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) im IMAGE-Format
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie CGM-Dateien in IMAGE in einer einzigen Datei über C#" %}}
Mit der API können Sie auch CGM-Dateien in IMAGE in eine einzelne Bilddatei konvertieren. Um alle Seiten zu konvertieren, können Sie Ihr CGM-Dokument zuerst in eine TIFF-Datei rendern und danach die TIFF-Datei nach IMAGE exportieren. Sie können die Eingabedatei mit der Klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) öffnen und Auflösungs-, TiffSettings- und TIFF-Geräteobjekte erstellen. Sie können ein einzelnes TIFF-Bild mit der Methode [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) von [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) Klasse. Schließlich können Sie die TIFF-Datei mit der Klasse [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) laden
und speichern Sie es im IMAGE-Format mit der Methode [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren und Drehen von CGM-Dateien in IMAGE über C#" %}}
Mit der API können Sie das ausgegebene IMAGE-Bild auch nach Ihren Bedürfnissen drehen. Die Image.RotateFlip-Methode kann verwendet werden, um das Bild um 90/180/270 Grad zu drehen und das Bild horizontal oder vertikal zu spiegeln. Sie können die Art der Drehung und Spiegelung angeben, die auf das Bild angewendet werden soll. Um das Bild zu drehen und zu spiegeln, können Sie das konvertierte JPEG-Bild mit der Factory-Methode laden, die von der Klasse [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) bereitgestellt wird, und das Bild aufrufen .RotateFlip-Methode, während Sie den entsprechenden [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) angeben. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="CGM-Dateien programmgesteuert in IMAGE umwandeln: Anwendungsfälle" %}}
CGM-Dateien (Computer Graphics Metafile) werden zur Speicherung von Vektorgrafikinformationen verwendet, was sie für die Erstellung statischer Bilder ideal macht. Dennoch sind bei der Arbeit mit dynamischen Daten Bildmappen wie PNG entscheidend für die Speicherung und Verteilung von Bildern.

Die Umwandlung von CGM-Dateien in Bildformate ist erforderlich, um das volle Potenzial Ihrer visuellen Inhalte und Präsentationsmöglichkeiten zu nutzen. Diese Umwandlung ermöglicht Ihnen:

**Anwendungsbereiche:**

*   **Logo-Design und Markenführung**: Konvertieren Sie CGM-Dateien zur Erstellung skalierten Vektorlogos, um Konsistenz in verschiedenen Medien sicherzustellen.
*   **Infografik-Erstellung**: Verwenden Sie PNG, um komplexe Daten in einer ansprechenden und leicht verständlichen Formatart zu visualisieren.
*   **Bildbearbeitung und Manipulation**: Konvertieren Sie CGM-Dateien, um Bilder zu bearbeiten, Filter und Effekte anzuwenden, ohne die Qualität beeinträchtigen zu müssen.
*   **Webdesign und Webentwicklung**: Verwenden Sie PNG, um responsiven Bilder zu erstellen, die schnell geladen werden, um eine reibungslose Nutzererfahrung sicherzustellen.
*   **Druckdesign und Verlagsvertrieb**: Konvertieren Sie CGM-Dateien zur Erstellung hochwertiger Bilder für Druckpublikationen, wie z. B. Broschüren, Magazinen und Zeitungen.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}