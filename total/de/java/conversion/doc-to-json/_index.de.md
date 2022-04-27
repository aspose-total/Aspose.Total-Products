---
title: Konvertieren Sie DOC über Java in das JSON-Format
description: Konvertieren Sie DOC über Java in das JSON-Format, ohne Microsoft Word oder Microsoft Excel zu verwenden
url: /de/java/conversion/doc-to-json/
family: total
platformtag: net
feature: conversion
informat: DOC
outformat: JSON
otherformats: XLAM XLT CSV XLSX FODS XLTM XLSM XLTX ODS XLSB EXCEL SXC TSV DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie DOC über Java in das JSON-Format" h2="Lokale Java-API zum Konvertieren von DOC in JSON, ohne Microsoft<sup>&reg;</sup> Word oder Microsoft<sup>&reg;</sup> Excel zu verwenden" >}}
{{% blocks/products/pf/feature-page-summary %}}
Das Konvertieren von DOC in das JSON-Format über [Aspose.Total for Java](https://products.aspose.com/total/java/) ist ein einfacher zweistufiger Prozess. Durch die Verwendung der funktionsreichen Dokumentbearbeitungs- und Konvertierungs-API [Aspose.Words for Java](https://products.aspose.com/words/java/) können Sie DOC in HTML exportieren. Danach können Sie mithilfe von [Aspose.Cells for Java](https://products.aspose.com/cells/java/) HTML in JSON konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie DOC über Java in das JSON-Format" %}}
1. Öffnen Sie die DOC-Datei mit der Klasse [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document).
2. Konvertieren Sie DOC in HTML mit [Save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) Methode
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
Über die API können Sie das passwortgeschützte Dokument auch öffnen. Wenn Ihr DOC-Eingabedokument kennwortgeschützt ist, können Sie es ohne Verwendung des Kennworts nicht in das JSON-Format konvertieren. Die API ermöglicht es Ihnen, das verschlüsselte Dokument zu öffnen, indem Sie das richtige Kennwort in einem LoadOptions-Objekt übergeben. Das folgende Codebeispiel zeigt, wie Sie versuchen, ein verschlüsseltes Dokument mit einem Kennwort zu öffnen:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie geschütztes DOC über Java in das JSON-Format" %}}
Während Sie DOC in JSON konvertieren, können Sie den Bereich auch auf Ihr Ausgabe-JSON-Format festlegen. Um den Bereich festzulegen, können Sie das konvertierte HTML mithilfe der Workbook-Klasse öffnen, einen zu exportierenden Datenbereich mithilfe der Cells.createRange-Methode erstellen, die JsonUtility.exportRangeToJson-Methode mit Verweisen auf Range & ExportRangeToJsonOptions aufrufen und String-JSON-Daten über in eine Datei schreiben BufferedWriter.write-Methode. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-xlam/" name="DOC Zu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-xlt/" name="DOC Zu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-csv/" name="DOC Zu CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-xlsx/" name="DOC Zu XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-fods/" name="DOC Zu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-xltm/" name="DOC Zu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-xlsm/" name="DOC Zu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-xltx/" name="DOC Zu XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-ods/" name="DOC Zu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-xlsb/" name="DOC Zu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-excel/" name="DOC Zu EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-sxc/" name="DOC Zu SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-tsv/" name="DOC Zu TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/doc-to-dif/" name="DOC Zu DIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}