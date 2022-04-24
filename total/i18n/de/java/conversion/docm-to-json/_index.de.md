---
title: Konvertieren Sie DOCM über Java in das JSON-Format
description: Konvertieren Sie DOCM über Java in das JSON-Format, ohne Microsoft Word oder Microsoft Excel zu verwenden
url: /de/java/conversion/docm-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: JSON
otherformats: XLT XLTM FODS SXC XLAM XLS EXCEL ODS XLSM DIF XLSB XLTX TSV CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie DOCM über Java in das JSON-Format" h2="Lokale Java-API zum Konvertieren von DOCM in JSON, ohne Microsoft<sup>&reg;</sup> Word oder Microsoft<sup>&reg;</sup> Excel zu verwenden" >}}
{{% blocks/products/pf/feature-page-summary %}}
Das Konvertieren von DOCM in das JSON-Format über [Aspose.Total for Java](https://products.aspose.com/total/java/) ist ein einfacher zweistufiger Prozess. Durch die Verwendung der funktionsreichen Dokumentbearbeitungs- und Konvertierungs-API [Aspose.Words for Java](https://products.aspose.com/words/java/) können Sie DOCM in HTML exportieren. Danach können Sie mithilfe von [Aspose.Cells for Java](https://products.aspose.com/cells/java/) HTML in JSON konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie DOCM über Java in das JSON-Format" %}}
1. Öffnen Sie die DOCM-Datei mit der Klasse [Docmument](https://apireference.aspose.com/words/java/com.aspose.words/Docmument).
2. Konvertieren Sie DOCM in HTML mit [Save](https://apireference.aspose.com/words/java/com.aspose.words/Docmument#save(java.lang.String,com.aspose.words.SaveOptions) ) Methode
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
Über die API können Sie das passwortgeschützte Dokument auch öffnen. Wenn Ihr DOCM-Eingabedokument kennwortgeschützt ist, können Sie es ohne Verwendung des Kennworts nicht in das JSON-Format konvertieren. Die API ermöglicht es Ihnen, das verschlüsselte Dokument zu öffnen, indem Sie das richtige Kennwort in einem LoadOptions-Objekt übergeben. Das folgende Codebeispiel zeigt, wie Sie versuchen, ein verschlüsseltes Dokument mit einem Kennwort zu öffnen:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie geschütztes DOCM über Java in das JSON-Format" %}}
Während Sie DOCM in JSON konvertieren, können Sie den Bereich auch auf Ihr Ausgabe-JSON-Format festlegen. Um den Bereich festzulegen, können Sie das konvertierte HTML mithilfe der Workbook-Klasse öffnen, einen zu exportierenden Datenbereich mithilfe der Cells.createRange-Methode erstellen, die JsonUtility.exportRangeToJson-Methode mit Verweisen auf Range & ExportRangeToJsonOptions aufrufen und String-JSON-Daten über in eine Datei schreiben BufferedWriter.write-Methode. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docm-to-xlam/" name="DOCM Zu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docm-to-xlt/" name="DOCM Zu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docm-to-csv/" name="DOCM Zu CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docm-to-xlsx/" name="DOCM Zu XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docm-to-fods/" name="DOCM Zu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docm-to-xltm/" name="DOCM Zu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docm-to-xlsm/" name="DOCM Zu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docm-to-xltx/" name="DOCM Zu XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docm-to-ods/" name="DOCM Zu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docm-to-xlsb/" name="DOCM Zu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docm-to-excel/" name="DOCM Zu EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docm-to-sxc/" name="DOCM Zu SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docm-to-tsv/" name="DOCM Zu TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docm-to-dif/" name="DOCM Zu DIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}