---
title: Java-API zum Konvertieren von RTF in CSV
description: Konvertieren Sie RTF über Java in CSV, ohne Microsoft Word oder Microsoft Excel zu verwenden
url: /de/java/conversion/rtf-to-csv/
family: total
platformtag: net
feature: conversion
informat: RTF
outformat: CSV
otherformats: ODS XLTM XLSX XLS XLAM FODS XLSM DIF SXC XLSB XLT XLTX EXCEL TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie RTF über Java in CSV" h2="Lokale Java-API zum Konvertieren von RTF in CSV, ohne Microsoft<sup>&reg;</sup> Word oder Microsoft<sup>&reg;</sup> Excel zu verwenden" >}}
{{% blocks/products/pf/feature-page-summary %}}
Das Konvertieren von RTF in CSV über [Aspose.Total for Java](https://products.aspose.com/total/java/) ist ein einfacher zweistufiger Prozess. Durch die Verwendung der funktionsreichen Dokumentbearbeitungs- und Konvertierungs-API [Aspose.Words for Java](https://products.aspose.com/words/java/) können Sie RTF in HTML exportieren. Danach können Sie mit [Aspose.Cells for Java](https://products.aspose.com/cells/java/) HTML in CSV konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++-API zum Konvertieren von RTF in CSV" %}}
1. Öffnen Sie die RTF-Datei mit der Klasse [Rtfument](https://apireference.aspose.com/words/java/com.aspose.words/Rtfument).
2. Konvertieren Sie RTF in HTML mit [Save](https://apireference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String,com.aspose.words.SaveOptions) ) Methode
3. Laden Sie das HTML-Dokument mithilfe der Klasse [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Speichern Sie das Dokument im CSV-Format mit [Save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions))-Methode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Java direkt aus einem auf [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) basierenden Projekt verwenden und enthalten [Aspose.Words for Java](https://rtfs.aspose.com/words/java/installation/) und [Aspose.Cells for Java](https://rtfs.aspose.com/cells/java/ installation/) in Ihrer pom.xml.

Alternativ können Sie eine ZIP-Datei von [downloads](https://downloads.aspose.com/total/java) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertierungsanforderungen" %}}
Vor dem Konvertieren von RTF in CSV können Sie nicht verwendete Informationen aus dem RTF-Dokument über [Aspose.Words for Java](https://products.aspose.com/words/java/) entfernen. Manchmal müssen Sie nicht verwendete oder doppelte Informationen entfernen, um die Größe des Ausgabedokuments und die Verarbeitungszeit zu reduzieren. Mit der Klasse [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) können Sie Optionen für die Dokumentbereinigung angeben. Um doppelte Stile oder einfach nicht verwendete Stile oder Listen aus dem Dokument zu entfernen, können Sie die Methode [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Rtfument#cleanup()) verwenden. Sie können die [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) und [UnusedBuiltinStyles](https://apireference.aspose.com/words/java /com.aspose.words/cleanupoptions#UnusedBuiltinStyles)-Eigenschaften zum Erkennen und Entfernen von Stilen, die als „nicht verwendet“ markiert sind.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-rtfument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Entfernen Sie nicht verwendete Informationen aus einem RTF-Dokument über Java" %}}
Nach der Konvertierung von RTF in CSV können Sie mit [Aspose.Cells for Java](https://products.aspose.com/cells/java/) Ihr Dokument zum Streamen speichern. Wenn Sie Dateien in einem Stream speichern müssen, sollten Sie ein FileOutputStream-Objekt erstellen und dann [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io. OutputStream,%20com.aspose.cells.SaveOptions)) die Datei zu diesem Stream-Objekt durch Aufrufen der save-Methode von [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) Objekt. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/rtf-to-xlsm/" name="RTF Zu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/rtf-to-xlt/" name="RTF Zu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/rtf-to-ods/" name="RTF Zu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/rtf-to-tsv/" name="RTF Zu TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/rtf-to-xls/" name="RTF Zu XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/rtf-to-xlsb/" name="RTF Zu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/rtf-to-fods/" name="RTF Zu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/rtf-to-dif/" name="RTF Zu DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/rtf-to-xltx/" name="RTF Zu XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/rtf-to-xlam/" name="RTF Zu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/rtf-to-xlsx/" name="RTF Zu XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/rtf-to-xltm/" name="RTF Zu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/rtf-to-sxc/" name="RTF Zu SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/rtf-to-excel/" name="RTF Zu EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}