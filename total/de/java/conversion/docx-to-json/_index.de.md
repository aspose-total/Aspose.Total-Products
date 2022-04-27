---
title: Konvertieren Sie DOCX über Java in das JSON-Format
description: Konvertieren Sie DOCX über Java in das JSON-Format, ohne Microsoft Word oder Microsoft Excel zu verwenden
url: /de/java/conversion/docx-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCXX
outformat: JSON
otherformats: XLAM XLSM DIF XLT CSV XLTX XLSX TSV ODS XLTM EXCEL FODS XLS XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie DOCX über Java in das JSON-Format" h2="Lokale Java-API zum Konvertieren von DOCX in JSON, ohne Microsoft<sup>&reg;</sup> Word oder Microsoft<sup>&reg;</sup> Excel zu verwenden" >}}
{{% blocks/products/pf/feature-page-summary %}}
Das Konvertieren von DOCX in das JSON-Format über [Aspose.Total for Java](https://products.aspose.com/total/java/) ist ein einfacher zweistufiger Prozess. Durch die Verwendung der funktionsreichen Dokumentbearbeitungs- und Konvertierungs-API [Aspose.Words for Java](https://products.aspose.com/words/java/) können Sie DOCX in HTML exportieren. Danach können Sie mithilfe von [Aspose.Cells for Java](https://products.aspose.com/cells/java/) HTML in JSON konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie DOCX über Java in das JSON-Format" %}}
1. Öffnen Sie die DOCX-Datei mit der Klasse [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document).
2. Konvertieren Sie DOCX in HTML mit [Save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) Methode
3. Laden Sie das HTML-Dokument mithilfe der Klasse [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Speichern Sie das Dokument im JSON-Format mit [Save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String.%20com.aspose.cells.SaveOptions))-Methode
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
Über die API können Sie das passwortgeschützte Dokument auch öffnen. Wenn Ihr DOCX-Eingabedokument kennwortgeschützt ist, können Sie es ohne Verwendung des Kennworts nicht in das JSON-Format konvertieren. Die API ermöglicht es Ihnen, das verschlüsselte Dokument zu öffnen, indem Sie das richtige Kennwort in einem LoadOptions-Objekt übergeben. Das folgende Codebeispiel zeigt, wie Sie versuchen, ein verschlüsseltes Dokument mit einem Kennwort zu öffnen:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie geschütztes DOCX über Java in das JSON-Format" %}}
Während Sie DOCX in JSON konvertieren, können Sie den Bereich auch auf Ihr Ausgabe-JSON-Format festlegen. Um den Bereich festzulegen, können Sie das konvertierte HTML mithilfe der Workbook-Klasse öffnen, einen zu exportierenden Datenbereich mithilfe der Cells.createRange-Methode erstellen, die JsonUtility.exportRangeToJson-Methode mit Verweisen auf Range & ExportRangeToJsonOptions aufrufen und String-JSON-Daten über in eine Datei schreiben BufferedWriter.write-Methode. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-xlam/" name="DOCX Zu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-xlt/" name="DOCX Zu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-csv/" name="DOCX Zu CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-xlsx/" name="DOCX Zu XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-fods/" name="DOCX Zu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-xltm/" name="DOCX Zu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-xlsm/" name="DOCX Zu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-xltx/" name="DOCX Zu XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-ods/" name="DOCX Zu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-xlsb/" name="DOCX Zu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-excel/" name="DOCX Zu EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-sxc/" name="DOCX Zu SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-tsv/" name="DOCX Zu TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-dif/" name="DOCX Zu DIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}