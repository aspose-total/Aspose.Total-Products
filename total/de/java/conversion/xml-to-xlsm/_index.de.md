---
title: Java-API zum Rendern von XML in XLSM
description: Exportieren Sie XML über die Java-API in XLSM, ohne Microsoft Excel oder Adobe Reader zu verwenden
url_ignore: /de/java/conversion/xml-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: XML
outformat: XLSM
otherformats: XLSM XLTM ODS MD FODS EXCEL DIF XLT TSV XLSB XLTX SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="XML über Java nach XLSM exportieren" h2="Konvertieren Sie die XML-Datei in XLSM, indem Sie die lokale Java-API in beliebigen Java J2SE-, J2EE-, J2ME-Anwendungen verwenden" >}}
{{% blocks/products/pf/feature-page-summary %}}
Durch die Verwendung von [Aspose.Total for Java](https://products.aspose.com/total/java/) können Sie die XML-zu-XLSM-Konvertierungsfunktion in Ihren Java-Anwendungen in einem zweistufigen Prozess integrieren. Erstens können Sie mit [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) XML in XLSX rendern. Im zweiten Schritt können Sie XLSX in XLSM konvertieren, indem Sie die Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) verwenden.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie die XML-Datei über Java in XLSM" %}}
1. Öffnen Sie die XML-Datei mit der Klasse [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Konvertieren Sie XML in XLSX mit [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) Methode
3. Laden Sie das XLSX-Dokument mithilfe der Klasse [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Speichern Sie das Dokument im XLSM-Format mit [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions))-Methode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Java direkt aus einem auf [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) basierenden Projekt verwenden und enthalten [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) und [Aspose.Cells for Java](https://docs.aspose.com/cells/java/ installation/) in Ihrer pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertierungsanforderungen" %}}String-java.lang.String-
Wenn Ihr XML-Dokument passwortgeschützt ist, können Sie es ohne das Passwort nicht in XLSM konvertieren. Mit der API können Sie das geschützte Dokument zunächst mit einem gültigen Passwort öffnen und anschließend konvertieren. Um die verschlüsselte Datei zu öffnen, können Sie eine neue Instanz des [Dokuments](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String- java.lang.String-) Klasse und übergeben Sie Dateiname und Passwort als Argumente.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie geschütztes XML über Java in XLSM" %}}
Während Sie eine XML-Datei in XLSM konvertieren, können Sie Ihrem Ausgabe-XLSM-Dateiformat auch Wasserzeichen hinzufügen. Um ein Wasserzeichen hinzuzufügen, erstellen Sie eine neue Arbeitsmappe, um die konvertierte XLSX-Datei zu öffnen. Wählen Sie das Arbeitsblatt über seinen Index aus, erstellen Sie eine Form und verwenden Sie die Funktion addTextEffect, stellen Sie Farben, Transparenz und mehr ein. Danach können Sie Ihr XLSX-Dokument als XLSM mit Wasserzeichen speichern. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xml-to-dif/" name="XML Zu DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xml-to-xltx/" name="XML Zu XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xml-to-md/" name="XML Zu MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xml-to-fods/" name="XML Zu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xml-to-xltm/" name="XML Zu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xml-to-excel/" name="XML Zu EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xml-to-xlsm/" name="XML Zu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xml-to-xlam/" name="XML Zu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xml-to-xlt/" name="XML Zu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xml-to-xlsb/" name="XML Zu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xml-to-ods/" name="XML Zu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/xml-to-sxc/" name="XML Zu SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}