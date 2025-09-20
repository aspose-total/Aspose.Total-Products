---
title: Konvertieren Sie HTML über Java in WMZ
description: Exportieren Sie die HTML-Datei in WMZ in Ihren Java-Anwendungen, ohne eine Anwendung von Drittanbietern zu verwenden
url_ignore: /de/java/conversion/html-to-wmz/
family: total
platformtag: net
feature: conversion
informat: HTML
outformat: WMZ
otherformats: TGA PSD WMZ IMAGE EMZ JPEG2000 WMF SVGZ DXF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie HTML über Java in WMZ" h2="Exportieren Sie die HTML-Datei in WMZ innerhalb einer beliebigen Java J2SE-, J2EE-, J2ME-Anwendung, ohne Adobe<sup>&reg;</sup> Acrobat Reader zu verwenden" >}}
{{% blocks/products/pf/feature-page-summary %}}
Sie können in zwei einfachen Schritten eine html-Datei in ein WMZ-Bild in Java konvertieren. Erstens können Sie mit [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) HTML in JPEG exportieren. Danach können Sie mit der Bildverarbeitungs-API von [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) JPEG in WMZ rendern. Beide APIs sind im Paket [Aspose.Total for Java](https://products.aspose.com/total/java/) enthalten.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Exportieren Sie HTML über Java nach WMZ" %}}
1. Öffnen Sie die HTML-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Initialisieren Sie das Klassenobjekt und rendern Sie HTML mithilfe von [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-)-Methode
3. Laden Sie die JPEG-Datei mithilfe der Klasse [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image).
4. Speichern Sie das Dokument im WMZ-Format mit [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) Methode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Java direkt aus einem auf [Maven](https://releases.aspose.com/total/java/) basierenden Projekt verwenden und fügen Sie Bibliotheken in Ihre pom.xml ein.

Alternativ können Sie eine ZIP-Datei von [downloads](https://releases.aspose.comtotal/java) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie HTML in WMZ in einer einzigen Datei über Java" %}}
Die API ermöglicht Ihnen auch, HTML-Dateien in WMZ in eine einzelne Datei zu exportieren. Um alle Seiten zu konvertieren, können Sie Ihr HTML-Dokument zunächst in eine TIFF-Datei rendern und anschließend die TIFF-Datei nach WMZ exportieren. Sie können die Eingabedatei mit der Klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) öffnen und Auflösungs-, TiffSettings- und TIFF-Geräteobjekte erstellen. Sie können ein einzelnes TIFF-Bild mit [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-)-Methode der [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice)-Klasse. Schließlich können Sie die TIFF-Datei mit der Klasse [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) laden und mit [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) Methode.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie HTML in WMZ mit Wasserzeichen über Java" %}}
Mit der API können Sie auch HTML-Dateien mit Wasserzeichen in Ihrem WMZ-Dokument nach WMZ exportieren. Um ein Wasserzeichen hinzuzufügen, können Sie zuerst HTML in JPEG konvertieren und ein Wasserzeichen hinzufügen. Um ein Wasserzeichen hinzuzufügen, laden Sie eine Bilddatei mit der Klasse [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), erstellen Sie ein Objekt der Klasse [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) und initialisieren Sie sie mit dem Image-Objekt, erstellen Sie eine neue [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) Objekt und setzen Sie die Übersetzung und Transformation auf den gewünschten Winkel und fügen Sie Wasserzeichen mit [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-)-Methode. Nachdem Sie das Wasserzeichen in Ihr Bild eingefügt haben, können Sie das JPEG im WMZ-Format speichern. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren und drehen Sie HTML über Java in eine WMZ-Datei" %}}
Mit der API können Sie das ausgegebene WMZ-Bild auch nach Ihren Bedürfnissen drehen. Die Image.rotateFlip-Methode kann verwendet werden, um das Bild um 90/180/270 Grad zu drehen und das Bild horizontal oder vertikal zu spiegeln. Die Bibliothek bietet einfache Methoden, um komplexe Operationen durchzuführen und gleichzeitig alle hässlichen Details zu kapseln. Sie können die Art der Drehung und Spiegelung angeben, die auf das Bild angewendet werden soll. Um das Bild zu drehen und zu spiegeln, können Sie das konvertierte JPEG-Bild mit der Klasse [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) laden und Image aufrufen. RotateFlip-Methode, während Sie den entsprechenden [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Die Umwandlung von **HTML in WMZ (komprimierte Windows-Metadatei)** ist entscheidend für die Erzeugung von **komprimierten Vektorgrafiken** aus Webseiten. WMZ bewahrt die Skalierbarkeit und Bearbeitbarkeit von Vektorgrafiken bei und reduziert gleichzeitig signifikant die Dateigrößen, was es ideal für leichtgewichtige Veröffentlichungen, archivarische Speicherung und plattformübergreifendes Teilen macht. Durch die Umwandlung von HTML in WMZ können Organisationen die Leistung optimieren, die Verteilung vereinfachen und hochwertige Visuals in einem kompakten Format beibehalten.

{{% blocks/products/pf/agp/feature-section-col title="Hauptanwendungsfälle" %}}

* **Leichtgewichtige Veröffentlichung** – Liefern skalierbare Vektorgrafiken mit reduzierten Dateigrößen für digitale Publikationen.
* **Archivkompression** – Bewahren historische Webinhalte effizient auf, ohne die visuelle Klarheit zu beeinträchtigen.
* **Plattformübergreifende Diagramme** – Teilen Sie Vektorgrafiken einfach über Windows und kompatible Anwendungen.
* **Bildungsmaterialien** – Erstellen Sie kompakte, hochwertige Grafiken für E-Learning und Lehrmaterialien.
* **Berichts-Workflows** – Integrieren Sie präzise Diagramme und Grafiken in Geschäftsberichte und minimieren Sie dabei den Speicherbedarf.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Automatisierungsszenarien" %}}

* **HTML-zu-WMZ-Pipelines** – Automatisieren Sie die Umwandlung von Webseiten in komprimierte Vektorgrafiken.
* **Automatisierte Metafile-Kompression** – Generieren Sie optimierte WMZ-Dateien konsistent über Projekte hinweg.
* **Massenveröffentlichung von Diagrammen** – Verarbeiten Sie mehrere Webseiten oder Diagramme gleichzeitig für Workflows im großen Maßstab.
* **Leichtgewichtige Workflows auf Unternehmensebene** – Integrieren Sie die WMZ-Generierung in organisatorische Veröffentlichungs- und Archivsysteme.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}