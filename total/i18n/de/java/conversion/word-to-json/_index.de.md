---
title: Konvertieren Sie WORD über Java in das JSON-Format
description: Konvertieren Sie WORD über Java in das JSON-Format, ohne Microsoft Word oder Microsoft Excel zu verwenden
url: /de/java/conversion/word-to-json/
family: total
platformtag: net
feature: conversion
informat: WORD
outformat: JSON
otherformats: SXC XLSX XLS DIF XLSB XLT XLAM TSV XLTM XLSM EXCEL XLTX FODS CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie WORD über Java in das JSON-Format" h2="Lokale Java-API zum Konvertieren von WORD in JSON, ohne Microsoft<sup>&reg;</sup> Word oder Microsoft<sup>&reg;</sup> Excel zu verwenden" >}}
{{% blocks/products/pf/feature-page-summary %}}
Das Konvertieren von WORD in das JSON-Format über [Aspose.Total for Java](https://products.aspose.com/total/java/) ist ein einfacher zweistufiger Prozess. Durch die Verwendung der funktionsreichen Dokumentbearbeitungs- und Konvertierungs-API [Aspose.Words for Java](https://products.aspose.com/words/java/) können Sie WORD in HTML exportieren. Danach können Sie mithilfe von [Aspose.Cells for Java](https://products.aspose.com/cells/java/) HTML in JSON konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie WORD über Java in das JSON-Format" %}}
1. Öffnen Sie die WORD-Datei mit der Klasse [Wordument](https://apireference.aspose.com/words/java/com.aspose.words/Wordument).
2. Konvertieren Sie WORD in HTML mit [Save](https://apireference.aspose.com/words/java/com.aspose.words/Wordument#save(java.lang.String,com.aspose.words.SaveOptions) ) Methode
3. Laden Sie das HTML-Dokument mithilfe der Klasse [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Speichern Sie das Dokument im JSON-Format mit [Save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions))-Methode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Sie können Aspose.Total für Java direkt aus einem auf [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) basierenden Projekt verwenden und fügen Sie Bibliotheken in Ihre pom.xml ein.

Alternativ können Sie eine ZIP-Datei von [downloads](https://downloads.aspose.com/total/java) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konvertierungsanforderungen" %}}
Über die API können Sie das passwortgeschützte Dokument auch öffnen. Wenn Ihr WORD-Eingabedokument kennwortgeschützt ist, können Sie es ohne Verwendung des Kennworts nicht in das JSON-Format konvertieren. Die API ermöglicht es Ihnen, das verschlüsselte Dokument zu öffnen, indem Sie das richtige Kennwort in einem LoadOptions-Objekt übergeben. Das folgende Codebeispiel zeigt, wie Sie versuchen, ein verschlüsseltes Dokument mit einem Kennwort zu öffnen:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie geschütztes WORD über Java in das JSON-Format" %}}
Während Sie WORD in JSON konvertieren, können Sie den Bereich auch auf Ihr Ausgabe-JSON-Format festlegen. Um den Bereich festzulegen, können Sie das konvertierte HTML mithilfe der Workbook-Klasse öffnen, einen zu exportierenden Datenbereich mithilfe der Cells.createRange-Methode erstellen, die JsonUtility.exportRangeToJson-Methode mit Verweisen auf Range & ExportRangeToJsonOptions aufrufen und String-JSON-Daten über in eine Datei schreiben BufferedWriter.write-Methode. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/word-to-xlam/" name="WORD Zu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/word-to-xlt/" name="WORD Zu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/word-to-csv/" name="WORD Zu CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/word-to-xlsx/" name="WORD Zu XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/word-to-fods/" name="WORD Zu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/word-to-xltm/" name="WORD Zu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/word-to-xlsm/" name="WORD Zu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/word-to-xltx/" name="WORD Zu XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/word-to-ods/" name="WORD Zu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/word-to-xlsb/" name="WORD Zu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/word-to-excel/" name="WORD Zu EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/word-to-sxc/" name="WORD Zu SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/word-to-tsv/" name="WORD Zu TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/word-to-dif/" name="WORD Zu DIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}