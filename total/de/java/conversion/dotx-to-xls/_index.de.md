---
title: Java-API zum Konvertieren von DOTX in XLS
description: Konvertieren Sie DOTX über Java in XLS, ohne Microsoft Word oder Microsoft Excel zu verwenden
url_ignore: /de/java/conversion/dotx-to-xls/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: XLS
otherformats: XLAM ODS TSV XLT FODS XLS DIF XLTM XLS SXC XLSM XLSB EXCEL XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie DOTX über Java in XLS" h2="Lokale Java-API zum Konvertieren von DOTX in XLS, ohne Microsoft<sup>&reg;</sup> Word oder Microsoft<sup>&reg;</sup> Excel zu verwenden" >}}
{{% blocks/products/pf/feature-page-summary %}}
Das Konvertieren von DOTX in XLS über [Aspose.Total for Java](https://products.aspose.com/total/java/) ist ein einfacher zweistufiger Prozess. Durch die Verwendung der funktionsreichen Dokumentbearbeitungs- und Konvertierungs-API [Aspose.Words for Java](https://products.aspose.com/words/java/) können Sie DOTX in HTML exportieren. Danach können Sie mit [Aspose.Cells for Java](https://products.aspose.com/cells/java/) HTML in XLS konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++-API zum Konvertieren von DOTX in XLS" %}}
1. Öffnen Sie die DOTX-Datei mit der Klasse [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
2. Konvertieren Sie DOTX in HTML mit [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) Methode
3. Laden Sie das HTML-Dokument mithilfe der Klasse [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Speichern Sie das Dokument im XLS-Format mit [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String.%20com.aspose.cells.SaveOptions))-Methode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Java direkt aus einem auf [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) basierenden Projekt verwenden und enthalten [Aspose.Words for Java](https://dotxs.aspose.com/words/java/installation/) und [Aspose.Cells for Java](https://dotxs.aspose.com/cells/java/installation/) in Ihrer pom.xml.

Alternativ können Sie eine ZIP-Datei von [downloads](https://downloads.aspose.com/total/java) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertierungsanforderungen" %}}[UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles)
Vor dem Konvertieren von DOTX in XLS können Sie nicht verwendete Informationen aus dem DOTX-Dokument über [Aspose.Words for Java](https://products.aspose.com/words/java/) entfernen. Manchmal müssen Sie nicht verwendete oder doppelte Informationen entfernen, um die Größe des Ausgabedokuments und die Verarbeitungszeit zu reduzieren. Mit der Klasse [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) können Sie Optionen für die Dokumentbereinigung angeben. Um doppelte Stile oder einfach nicht verwendete Stile oder Listen aus dem Dokument zu entfernen, können Sie die Methode [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Document#cleanup()) verwenden. Sie können die [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) und [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles)-Eigenschaften zum Erkennen und Entfernen von Stilen, die als „nicht verwendet“ markiert sind.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-protected-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Entfernen Sie nicht verwendete Informationen aus einem DOTX-Dokument über Java" %}}
Nach der Konvertierung von DOTX in XLS können Sie mit [Aspose.Cells for Java](https://products.aspose.com/cells/java/) Ihr Dokument zum Streamen speichern. Wenn Sie Dateien in einem Stream speichern müssen, sollten Sie ein FileOutputStream-Objekt erstellen und dann [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) die Datei zu diesem Stream-Objekt durch Aufrufen der save-Methode von [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) Objekt. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-protected-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotx-to-xlsm/" name="DOTX Zu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotx-to-xlt/" name="DOTX Zu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotx-to-ods/" name="DOTX Zu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotx-to-tsv/" name="DOTX Zu TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotx-to-xls/" name="DOTX Zu XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotx-to-xlsb/" name="DOTX Zu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotx-to-fods/" name="DOTX Zu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotx-to-dif/" name="DOTX Zu DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotx-to-xltx/" name="DOTX Zu XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotx-to-xlam/" name="DOTX Zu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotx-to-xlsx/" name="DOTX Zu XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotx-to-xltm/" name="DOTX Zu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotx-to-sxc/" name="DOTX Zu SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/dotx-to-excel/" name="DOTX Zu EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}