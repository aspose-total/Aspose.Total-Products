---
title: Java-API zum Konvertieren von DOTM in XLS
description: Konvertieren Sie DOTM über Java in XLS, ohne Microsoft Word oder Microsoft Excel zu verwenden
url_ignore: /de/java/conversion/dotm-to-xls/
family: total
platformtag: net
feature: conversion
informat: DOTM
outformat: XLS
otherformats: TSV XLAM SXC XLS EXCEL ODS FODS XLSM XLTX XLS XLSX DIF XLSB XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie DOTM über Java in XLS" h2="Lokale Java-API zum Konvertieren von DOTM in XLS, ohne Microsoft<sup>&reg;</sup> Word oder Microsoft<sup>&reg;</sup> Excel zu verwenden" >}}
{{% blocks/products/pf/feature-page-summary %}}
Das Konvertieren von DOTM in XLS über [Aspose.Total for Java](https://products.aspose.com/total/java/) ist ein einfacher zweistufiger Prozess. Durch die Verwendung der funktionsreichen Dokumentbearbeitungs- und Konvertierungs-API [Aspose.Words for Java](https://products.aspose.com/words/java/) können Sie DOTM in HTML exportieren. Danach können Sie mit [Aspose.Cells for Java](https://products.aspose.com/cells/java/) HTML in XLS konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++-API zum Konvertieren von DOTM in XLS" %}}
1. Öffnen Sie die DOTM-Datei mit der Klasse [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
2. Konvertieren Sie DOTM in HTML mit [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) Methode
3. Laden Sie das HTML-Dokument mithilfe der Klasse [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Speichern Sie das Dokument im XLS-Format mit [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String.%20com.aspose.cells.SaveOptions))-Methode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Java direkt aus einem auf [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) basierenden Projekt verwenden und enthalten [Aspose.Words for Java](https://dotms.aspose.com/words/java/installation/) und [Aspose.Cells for Java](https://dotms.aspose.com/cells/java/installation/) in Ihrer pom.xml.

Alternativ können Sie eine ZIP-Datei von [downloads](https://downloads.aspose.com/total/java) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertierungsanforderungen" %}}
Vor dem Konvertieren von DOTM in XLS können Sie nicht verwendete Informationen aus dem DOTM-Dokument über [Aspose.Words for Java](https://products.aspose.com/words/java/) entfernen. Manchmal müssen Sie nicht verwendete oder doppelte Informationen entfernen, um die Größe des Ausgabedokuments und die Verarbeitungszeit zu reduzieren. Mit der Klasse [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) können Sie Optionen für die Dokumentbereinigung angeben. Um doppelte Stile oder einfach nicht verwendete Stile oder Listen aus dem Dokument zu entfernen, können Sie die Methode [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Document#cleanup()) verwenden. Sie können die [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) und [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles)-Eigenschaften zum Erkennen und Entfernen von Stilen, die als „nicht verwendet“ markiert sind.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-protected-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Entfernen Sie nicht verwendete Informationen aus einem DOTM-Dokument über Java" %}}
Nach der Konvertierung von DOTM in XLS können Sie mit [Aspose.Cells for Java](https://products.aspose.com/cells/java/) Ihr Dokument zum Streamen speichern. Wenn Sie Dateien in einem Stream speichern müssen, sollten Sie ein FileOutputStream-Objekt erstellen und dann [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) die Datei zu diesem Stream-Objekt durch Aufrufen der save-Methode von [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) Objekt. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-protected-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotm-to-xlsm/" name="DOTM Zu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotm-to-xlt/" name="DOTM Zu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotm-to-ods/" name="DOTM Zu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotm-to-tsv/" name="DOTM Zu TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotm-to-xls/" name="DOTM Zu XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotm-to-xlsb/" name="DOTM Zu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotm-to-fods/" name="DOTM Zu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotm-to-dif/" name="DOTM Zu DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotm-to-xltx/" name="DOTM Zu XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotm-to-xlam/" name="DOTM Zu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotm-to-xlsx/" name="DOTM Zu XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotm-to-xltm/" name="DOTM Zu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotm-to-sxc/" name="DOTM Zu SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotm-to-excel/" name="DOTM Zu EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}