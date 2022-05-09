---
title: Java-API zum Rendern von SVG in EXCEL
description: Exportieren Sie SVG über die Java-API in EXCEL, ohne Microsoft Excel oder Adobe Reader zu verwenden
url_ignore: /de/java/conversion/svg-to-excel/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: EXCEL
otherformats: TXT MD TSV XLTX XLAM XLSB EXCEL DIF XLSM XLTM SXC ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="SVG über Java nach EXCEL exportieren" h2="Konvertieren Sie die SVG-Datei in EXCEL, indem Sie die lokale Java-API in beliebigen Java J2SE-, J2EE-, J2ME-Anwendungen verwenden" >}}
{{% blocks/products/pf/feature-page-summary %}}
Durch die Verwendung von [Aspose.Total for Java](https://products.aspose.com/total/java/) können Sie die SVG-zu-EXCEL-Konvertierungsfunktion in Ihren Java-Anwendungen in einem zweistufigen Prozess integrieren. Erstens können Sie mit [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) SVG in XLSX rendern. Im zweiten Schritt können Sie XLSX in EXCEL konvertieren, indem Sie die Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) verwenden.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie die SVG-Datei über Java in EXCEL" %}}
1. Öffnen Sie die SVG-Datei mit der Klasse [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Konvertieren Sie SVG in XLSX mit [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) Methode
3. Laden Sie das XLSX-Dokument mithilfe der Klasse [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Speichern Sie das Dokument im EXCEL-Format mit [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions))-Methode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Java direkt aus einem auf [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) basierenden Projekt verwenden und enthalten [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) und [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) in Ihrer pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertierungsanforderungen" %}}
Wenn Ihr SVG-Dokument passwortgeschützt ist, können Sie es ohne das Passwort nicht in EXCEL konvertieren. Mit der API können Sie das geschützte Dokument zunächst mit einem gültigen Passwort öffnen und anschließend konvertieren. Um die verschlüsselte Datei zu öffnen, können Sie eine neue Instanz des [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) Klasse und übergeben Sie Dateiname und Passwort als Argumente.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie geschütztes SVG über Java in EXCEL" %}}
Während Sie eine SVG-Datei in EXCEL konvertieren, können Sie Ihrem Ausgabe-EXCEL-Dateiformat auch Wasserzeichen hinzufügen. Um ein Wasserzeichen hinzuzufügen, erstellen Sie eine neue Arbeitsmappe, um die konvertierte XLSX-Datei zu öffnen. Wählen Sie das Arbeitsblatt über seinen Index aus, erstellen Sie eine Form und verwenden Sie die Funktion addTextEffect, stellen Sie Farben, Transparenz und mehr ein. Danach können Sie Ihr XLSX-Dokument als EXCEL mit Wasserzeichen speichern. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/svg-to-dif/" name="SVG Zu DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/svg-to-xltx/" name="SVG Zu XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/svg-to-md/" name="SVG Zu MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/svg-to-fods/" name="SVG Zu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/svg-to-xltm/" name="SVG Zu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/svg-to-excel/" name="SVG Zu EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/svg-to-xlsm/" name="SVG Zu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/svg-to-xlam/" name="SVG Zu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/svg-to-xlt/" name="SVG Zu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/svg-to-xlsb/" name="SVG Zu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/svg-to-ods/" name="SVG Zu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/svg-to-sxc/" name="SVG Zu SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}