---
title: Konvertieren Sie CGM über die C#-API in SVGZ
description: Exportieren Sie CGM in SVGZ in Ihren .NET-Anwendungen, ohne Anwendungen von Drittanbietern zu verwenden
url_ignore: /de/net/conversion/cgm-to-svgz/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: SVGZ
otherformats: TGA JPEG2000 IMAGE SVGZ WMF  WMZ PSD EMZ DXF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie die CGM-Datei über C# in SVGZ" h2="Exportieren Sie CGM innerhalb von .NET-Anwendungen nach SVGZ, ohne Adobe<sup>&reg;</sup> Acrobat Reader oder andere Anwendungen von Drittanbietern zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Mit [Aspose.Total for .NET](https://products.aspose.com/total/net/) können Sie in zwei einfachen Schritten CGM-Bilder in SVGZ-Bilder aus beliebigen .NET-Anwendungen exportieren. Zunächst einmal können Sie mit [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) CGM in JPEG exportieren. Danach können Sie mit der Bildverarbeitungs-API von [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) JPEG in SVGZ konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie die CGM-Datei über .NET in SVGZ" %}}
1. Öffnen Sie die CGM-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Initialisieren Sie das Klassenobjekt [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) und rendern Sie CGM mithilfe von [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) Methode
3. Laden Sie die JPEG-Datei mithilfe der Klasse [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image).
4. Speichern Sie das Dokument mit der Methode [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) im SVGZ-Format
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie CGM-Dateien in SVGZ in einer einzigen Datei über C#" %}}
Mit der API können Sie auch CGM-Dateien in SVGZ in eine einzelne Bilddatei konvertieren. Um alle Seiten zu konvertieren, können Sie Ihr CGM-Dokument zuerst in eine TIFF-Datei rendern und danach die TIFF-Datei nach SVGZ exportieren. Sie können die Eingabedatei mit der Klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) öffnen und Auflösungs-, TiffSettings- und TIFF-Geräteobjekte erstellen. Sie können ein einzelnes TIFF-Bild mit der Methode [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) von [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) Klasse. Schließlich können Sie die TIFF-Datei mit der Klasse [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) laden
und speichern Sie es im SVGZ-Format mit der Methode [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren und Drehen von CGM-Dateien in SVGZ über C#" %}}
Mit der API können Sie das ausgegebene SVGZ-Bild auch nach Ihren Bedürfnissen drehen. Die Image.RotateFlip-Methode kann verwendet werden, um das Bild um 90/180/270 Grad zu drehen und das Bild horizontal oder vertikal zu spiegeln. Sie können die Art der Drehung und Spiegelung angeben, die auf das Bild angewendet werden soll. Um das Bild zu drehen und zu spiegeln, können Sie das konvertierte JPEG-Bild mit der Factory-Methode laden, die von der Klasse [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) bereitgestellt wird, und das Bild aufrufen .RotateFlip-Methode, während Sie den entsprechenden [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) angeben. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="CGM-Dateien programmgesteuert in SVGZ umwandeln: Anwendungsfälle" %}}
CGM-Dateien (Computer Graphics Metafile) werden zur Speicherung von Vektorgrafikinformationen verwendet, was sie ideal für die Erstellung statischer Grafiken und Illustrationen macht. Die Arbeit mit dynamischen Daten führt jedoch zu einem Einsatz von Tabellen wie Excel, um Datenvisualisierung und Analyse zu ermöglichen.

Die Umwandlung von CGM-Dateien in SVGZ-Formate ist notwendig, um die volle Potenz deiner Vektorgrafik- und Illustrationsfähigkeiten freizusetzen. Diese Umwandlung ermöglicht:

**Benutzerszenarien:**

*   **Statistische Grafiken erstellen**: Wandeln Sie CGM-Dateien in statische Grafiken, Illustrationen und Logos um, die ideal für Druck oder Webnutzung sind.
*   **Markenidentität und -design**: Verwenden Sie SVGZ, um Markenidentitäten, Icons und Grafiken zu entwerfen, die skalabel sind und ihre Qualität bei der Anpassung beibehalten.
*   **Verpackung- und Etikettentwurf**: Wandeln Sie CGM-Dateien in visuell ansprechende Verpackungs- und Etikett Designs um, die sich auf den Regale ausheben.
*   **Digitales Vermögensmanagement**: Speichern Sie CGM-Dateien in SVGZ-Formaten für effizientes digitales Vermögensmanagement, sodass sich leichter Zugriff und Teilen von Vektorgrafiken über Teams ermöglicht.
*   **Web- und Mobilgrafikoptimierung**: Verwenden Sie SVGZ, um CGM-Dateien für Web- und Mobilgeräte zu optimieren, was schnelle Ladezeiten und hohe Qualität für visuelle Elemente garantiert.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}