---
title: Konvertieren Sie EPUB über Java in TGA
description: Exportieren Sie die EPUB-Datei in TGA in Ihren Java-Anwendungen, ohne eine Anwendung von Drittanbietern zu verwenden
url_ignore: /de/java/conversion/epub-to-tga/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: TGA
otherformats: PSD DXF TGA IMAGE EMZ WMZ WMF JPEG2000 SVGZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie EPUB über Java in TGA" h2="Exportieren Sie die EPUB-Datei in TGA innerhalb einer beliebigen Java J2SE-, J2EE-, J2ME-Anwendung, ohne Adobe<sup>&reg;</sup> Acrobat Reader zu verwenden" >}}
{{% blocks/products/pf/feature-page-summary %}}
Sie können in zwei einfachen Schritten eine epub-Datei in ein TGA-Bild in Java konvertieren. Erstens können Sie mit [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) EPUB in JPEG exportieren. Danach können Sie mit der Bildverarbeitungs-API von [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) JPEG in TGA rendern. Beide APIs sind im Paket [Aspose.Total for Java](https://products.aspose.com/total/java/) enthalten.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Exportieren Sie EPUB über Java nach TGA" %}}
1. Öffnen Sie die EPUB-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Initialisieren Sie das Klassenobjekt und rendern Sie EPUB mithilfe von [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-)-Methode
3. Laden Sie die JPEG-Datei mithilfe der Klasse [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image).
4. Speichern Sie das Dokument im TGA-Format mit [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) Methode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Java direkt aus einem auf [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) basierenden Projekt verwenden und fügen Sie Bibliotheken in Ihre pom.xml ein.

Alternativ können Sie eine ZIP-Datei von [downloads](https://downloads.aspose.com/total/java) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie EPUB in TGA in einer einzigen Datei über Java" %}}
Die API ermöglicht Ihnen auch, EPUB-Dateien in TGA in eine einzelne Datei zu exportieren. Um alle Seiten zu konvertieren, können Sie Ihr EPUB-Dokument zunächst in eine TIFF-Datei rendern und anschließend die TIFF-Datei nach TGA exportieren. Sie können die Eingabedatei mit der Klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) öffnen und Auflösungs-, TiffSettings- und TIFF-Geräteobjekte erstellen. Sie können ein einzelnes TIFF-Bild mit [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-)-Methode der [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice)-Klasse. Schließlich können Sie die TIFF-Datei mit der Klasse [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) laden und mit [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) Methode.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie EPUB in TGA mit Wasserzeichen über Java" %}}
Mit der API können Sie auch EPUB-Dateien mit Wasserzeichen in Ihrem TGA-Dokument nach TGA exportieren. Um ein Wasserzeichen hinzuzufügen, können Sie zuerst EPUB in JPEG konvertieren und ein Wasserzeichen hinzufügen. Um ein Wasserzeichen hinzuzufügen, laden Sie eine Bilddatei mit der Klasse [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), erstellen Sie ein Objekt der Klasse [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) und initialisieren Sie sie mit dem Image-Objekt, erstellen Sie eine neue [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) Objekt und setzen Sie die Übersetzung und Transformation auf den gewünschten Winkel und fügen Sie Wasserzeichen mit [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-)-Methode. Nachdem Sie das Wasserzeichen in Ihr Bild eingefügt haben, können Sie das JPEG im TGA-Format speichern. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren und drehen Sie EPUB über Java in eine TGA-Datei" %}}
Mit der API können Sie das ausgegebene TGA-Bild auch nach Ihren Bedürfnissen drehen. Die Image.rotateFlip-Methode kann verwendet werden, um das Bild um 90/180/270 Grad zu drehen und das Bild horizontal oder vertikal zu spiegeln. Die Bibliothek bietet einfache Methoden, um komplexe Operationen durchzuführen und gleichzeitig alle hässlichen Details zu kapseln. Sie können die Art der Drehung und Spiegelung angeben, die auf das Bild angewendet werden soll. Um das Bild zu drehen und zu spiegeln, können Sie das konvertierte JPEG-Bild mit der Klasse [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) laden und Image aufrufen. RotateFlip-Methode, während Sie den entsprechenden [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-emz/" name="EPUB Zu EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-tga/" name="EPUB Zu TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-jpeg2000/" name="EPUB Zu JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-image/" name="EPUB Zu IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-psd/" name="EPUB Zu PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-wmz/" name="EPUB Zu WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-svgz/" name="EPUB Zu SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to/" name="EPUB Zu" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-wmf/" name="EPUB Zu WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-dxf/" name="EPUB Zu DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/epub-to-dicom/" name="EPUB Zu DICOM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}