---
title: Konvertieren Sie XSLFO über Java in SVGZ
description: Exportieren Sie die XSLFO-Datei in SVGZ in Ihren Java-Anwendungen, ohne eine Anwendung von Drittanbietern zu verwenden
url_ignore: /de/java/conversion/xslfo-to-svgz/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: SVGZ
otherformats: DXF PSD EMZ SVGZ TGA  JPEG2000 WMF WMZ IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie XSLFO über Java in SVGZ" h2="Exportieren Sie die XSLFO-Datei in SVGZ innerhalb einer beliebigen Java J2SE-, J2EE-, J2ME-Anwendung, ohne Adobe<sup>&reg;</sup> Acrobat Reader zu verwenden" >}}
{{% blocks/products/pf/feature-page-summary %}}
Sie können in zwei einfachen Schritten eine xslfo-Datei in ein SVGZ-Bild in Java konvertieren. Erstens können Sie mit [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) XSLFO in JPEG exportieren. Danach können Sie mit der Bildverarbeitungs-API von [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) JPEG in SVGZ rendern. Beide APIs sind im Paket [Aspose.Total for Java](https://products.aspose.com/total/java/) enthalten.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Exportieren Sie XSLFO über Java nach SVGZ" %}}
1. Öffnen Sie die XSLFO-Datei mit der Klasse [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Initialisieren Sie das Klassenobjekt und rendern Sie XSLFO mithilfe von [Process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-)-Methode
3. Laden Sie die JPEG-Datei mithilfe der Klasse [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image).
4. Speichern Sie das Dokument im SVGZ-Format mit [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) Methode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Java direkt aus einem auf [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) basierenden Projekt verwenden und fügen Sie Bibliotheken in Ihre pom.xml ein.

Alternativ können Sie eine ZIP-Datei von [downloads](https://downloads.aspose.com/total/java) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie XSLFO in SVGZ in einer einzigen Datei über Java" %}}
Die API ermöglicht Ihnen auch, XSLFO-Dateien in SVGZ in eine einzelne Datei zu exportieren. Um alle Seiten zu konvertieren, können Sie Ihr XSLFO-Dokument zunächst in eine TIFF-Datei rendern und anschließend die TIFF-Datei nach SVGZ exportieren. Sie können die Eingabedatei mit der Klasse [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) öffnen und Auflösungs-, TiffSettings- und TIFF-Geräteobjekte erstellen. Sie können ein einzelnes TIFF-Bild mit [process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int- java.io.OutputStream-)-Methode der [TiffDevice](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice)-Klasse. Schließlich können Sie die TIFF-Datei mit der Klasse [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) laden und mit [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) Methode.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie XSLFO in SVGZ mit Wasserzeichen über Java" %}}
Mit der API können Sie auch XSLFO-Dateien mit Wasserzeichen in Ihrem SVGZ-Dokument nach SVGZ exportieren. Um ein Wasserzeichen hinzuzufügen, können Sie zuerst XSLFO in JPEG konvertieren und ein Wasserzeichen hinzufügen. Um ein Wasserzeichen hinzuzufügen, laden Sie eine Bilddatei mit der Klasse [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image), erstellen Sie ein Objekt der Klasse [Graphics](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) und initialisieren Sie sie mit dem Image-Objekt, erstellen Sie eine neue [Matrix](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Matrix) Objekt und setzen Sie die Übersetzung und Transformation auf den gewünschten Winkel und fügen Sie Wasserzeichen mit [Graphics.drawString](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics# drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-)-Methode. Nachdem Sie das Wasserzeichen in Ihr Bild eingefügt haben, können Sie das JPEG im SVGZ-Format speichern. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren und drehen Sie XSLFO über Java in eine SVGZ-Datei" %}}
Mit der API können Sie das ausgegebene SVGZ-Bild auch nach Ihren Bedürfnissen drehen. Die Image.rotateFlip-Methode kann verwendet werden, um das Bild um 90/180/270 Grad zu drehen und das Bild horizontal oder vertikal zu spiegeln. Die Bibliothek bietet einfache Methoden, um komplexe Operationen durchzuführen und gleichzeitig alle hässlichen Details zu kapseln. Sie können die Art der Drehung und Spiegelung angeben, die auf das Bild angewendet werden soll. Um das Bild zu drehen und zu spiegeln, können Sie das konvertierte JPEG-Bild mit der Klasse [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) laden und Image aufrufen. RotateFlip-Methode, während Sie den entsprechenden [RotateFlipType](https://apireference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xslfo-to-emz/" name="XSLFO Zu EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xslfo-to-tga/" name="XSLFO Zu TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xslfo-to-jpeg2000/" name="XSLFO Zu JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xslfo-to-image/" name="XSLFO Zu IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xslfo-to-psd/" name="XSLFO Zu PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xslfo-to-wmz/" name="XSLFO Zu WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xslfo-to-svgz/" name="XSLFO Zu SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xslfo-to/" name="XSLFO Zu" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xslfo-to-wmf/" name="XSLFO Zu WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xslfo-to-dxf/" name="XSLFO Zu DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xslfo-to-dicom/" name="XSLFO Zu DICOM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}