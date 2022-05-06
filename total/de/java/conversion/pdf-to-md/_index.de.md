---
title: Java-API zum Rendern von PDF in MD
description: Exportieren Sie PDF über die Java-API in MD, ohne Microsoft Excel oder Adobe Reader zu verwenden
url_ignore: /de/java/conversion/pdf-to-md/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: MD
otherformats: FODS XLTX XLSB XLSM MD SXC EXCEL DIF XLAM TSV ODS TXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="PDF über Java nach MD exportieren" h2="Konvertieren Sie die PDF-Datei in MD, indem Sie die lokale Java-API in beliebigen Java J2SE-, J2EE-, J2ME-Anwendungen verwenden" >}}
{{% blocks/products/pf/feature-page-summary %}}
Durch die Verwendung von [Aspose.Total for Java](https://products.aspose.com/total/java/) können Sie die PDF-zu-MD-Konvertierungsfunktion in Ihren Java-Anwendungen in einem zweistufigen Prozess integrieren. Erstens können Sie mit [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) PDF in XLSX rendern. Im zweiten Schritt können Sie XLSX in MD konvertieren, indem Sie die Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) verwenden.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie die PDF-Datei über Java in MD" %}}
1. Öffnen Sie die PDF-Datei mit der Klasse [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Konvertieren Sie PDF in XLSX mit [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) Methode
3. Laden Sie das XLSX-Dokument mithilfe der Klasse [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Speichern Sie das Dokument im MD-Format mit [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions))-Methode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Java direkt aus einem auf [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) basierenden Projekt verwenden und enthalten [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) und [Aspose.Cells for Java](https://docs.aspose.com/cells/java/ installation/) in Ihrer pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertierungsanforderungen" %}}String-java.lang.String-
Wenn Ihr PDF-Dokument passwortgeschützt ist, können Sie es ohne das Passwort nicht in MD konvertieren. Mit der API können Sie das geschützte Dokument zunächst mit einem gültigen Passwort öffnen und anschließend konvertieren. Um die verschlüsselte Datei zu öffnen, können Sie eine neue Instanz des [Dokuments](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String- java.lang.String-) Klasse und übergeben Sie Dateiname und Passwort als Argumente.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie geschütztes PDF über Java in MD" %}}
Während Sie eine PDF-Datei in MD konvertieren, können Sie Ihrem Ausgabe-MD-Dateiformat auch Wasserzeichen hinzufügen. Um ein Wasserzeichen hinzuzufügen, erstellen Sie eine neue Arbeitsmappe, um die konvertierte XLSX-Datei zu öffnen. Wählen Sie das Arbeitsblatt über seinen Index aus, erstellen Sie eine Form und verwenden Sie die Funktion addTextEffect, stellen Sie Farben, Transparenz und mehr ein. Danach können Sie Ihr XLSX-Dokument als MD mit Wasserzeichen speichern. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pdf-to-dif/" name="PDF Zu DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pdf-to-xltx/" name="PDF Zu XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pdf-to-md/" name="PDF Zu MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pdf-to-fods/" name="PDF Zu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pdf-to-xltm/" name="PDF Zu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pdf-to-excel/" name="PDF Zu EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pdf-to-xlsm/" name="PDF Zu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pdf-to-xlam/" name="PDF Zu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pdf-to-xlt/" name="PDF Zu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pdf-to-xlsb/" name="PDF Zu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pdf-to-ods/" name="PDF Zu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pdf-to-sxc/" name="PDF Zu SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}