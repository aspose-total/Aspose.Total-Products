---
title: Konvertieren Sie PCL über Java in DICOM
description: Exportieren Sie die PCL-Datei in DICOM in Ihren Java-Anwendungen, ohne eine Anwendung von Drittanbietern zu verwenden
url_ignore: /de/java/conversion/pcl-to-dicom/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: DICOM
otherformats: DICOM DXF WMF TGA IMAGE WMZ PSD JPEG2000 EMZ SVGZ
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie PCL über Java in DICOM" h2="Exportieren Sie die PCL-Datei in DICOM innerhalb einer beliebigen Java J2SE-, J2EE-, J2ME-Anwendung, ohne Adobe<sup>&reg;</sup> Acrobat Reader zu verwenden" >}}
{{% blocks/products/pf/feature-page-summary %}}
Sie können in zwei einfachen Schritten eine pcl-Datei in ein DICOM-Bild in Java konvertieren. Erstens können Sie mit [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) PCL in JPEG exportieren. Danach können Sie mit der Bildverarbeitungs-API von [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) JPEG in DICOM rendern. Beide APIs sind im Paket [Aspose.Total for Java](https://products.aspose.com/total/java/) enthalten.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Exportieren Sie PCL über Java nach DICOM" %}}
1. Öffnen Sie die PCL-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Initialisieren Sie das Klassenobjekt und rendern Sie PCL mithilfe von [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-)-Methode
3. Laden Sie die JPEG-Datei mithilfe der Klasse [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image).
4. Speichern Sie das Dokument im DICOM-Format mit [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) Methode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Java direkt aus einem auf [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) basierenden Projekt verwenden und fügen Sie Bibliotheken in Ihre pom.xml ein.

Alternativ können Sie eine ZIP-Datei von [downloads](https://releases.aspose.comtotal/java) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie PCL in DICOM in einer einzigen Datei über Java" %}}
Die API ermöglicht Ihnen auch, PCL-Dateien in DICOM in eine einzelne Datei zu exportieren. Um alle Seiten zu konvertieren, können Sie Ihr PCL-Dokument zunächst in eine TIFF-Datei rendern und anschließend die TIFF-Datei nach DICOM exportieren. Sie können die Eingabedatei mit der Klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) öffnen und Auflösungs-, TiffSettings- und TIFF-Geräteobjekte erstellen. Sie können ein einzelnes TIFF-Bild mit [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-)-Methode der [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice)-Klasse. Schließlich können Sie die TIFF-Datei mit der Klasse [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) laden und mit [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) Methode.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie PCL in DICOM mit Wasserzeichen über Java" %}}
Mit der API können Sie auch PCL-Dateien mit Wasserzeichen in Ihrem DICOM-Dokument nach DICOM exportieren. Um ein Wasserzeichen hinzuzufügen, können Sie zuerst PCL in JPEG konvertieren und ein Wasserzeichen hinzufügen. Um ein Wasserzeichen hinzuzufügen, laden Sie eine Bilddatei mit der Klasse [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), erstellen Sie ein Objekt der Klasse [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) und initialisieren Sie sie mit dem Image-Objekt, erstellen Sie eine neue [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) Objekt und setzen Sie die Übersetzung und Transformation auf den gewünschten Winkel und fügen Sie Wasserzeichen mit [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-)-Methode. Nachdem Sie das Wasserzeichen in Ihr Bild eingefügt haben, können Sie das JPEG im DICOM-Format speichern. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren und drehen Sie PCL über Java in eine DICOM-Datei" %}}
Mit der API können Sie das ausgegebene DICOM-Bild auch nach Ihren Bedürfnissen drehen. Die Image.rotateFlip-Methode kann verwendet werden, um das Bild um 90/180/270 Grad zu drehen und das Bild horizontal oder vertikal zu spiegeln. Die Bibliothek bietet einfache Methoden, um komplexe Operationen durchzuführen und gleichzeitig alle hässlichen Details zu kapseln. Sie können die Art der Drehung und Spiegelung angeben, die auf das Bild angewendet werden soll. Um das Bild zu drehen und zu spiegeln, können Sie das konvertierte JPEG-Bild mit der Klasse [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) laden und Image aufrufen. RotateFlip-Methode, während Sie den entsprechenden [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

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