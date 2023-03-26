---
title: Konvertieren Sie DOCM über .NET in das JSON-Format
description: Konvertieren Sie DOCM in C# in JSON, ohne Microsoft Excel oder Adobe Reader zu verwenden
url_ignore: /de/net/conversion/docm-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: JSON
otherformats: ODS XLTM XLAM FODS DIF XLS XLSM TSV XLTX EXCEL XLSB SXC CSV XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie DOCM in das JSON-Format über C#" h2="Analysieren Sie DOCM über C# in JSON, ohne Microsoft<sup>&reg;</sup> Word oder Excel zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Durch die Verwendung von [Aspose.Total for .NET](https://products.aspose.com/total/net/) können Sie DOCM in das JSON-Format innerhalb jeder .NET-, C#-, ASP.NET- und VB.NET-Anwendung in zwei konvertieren einfache Schritte. Erstens können Sie mit [Aspose.Words for .NET](https://products.aspose.com/words/net/) DOCM in HTML exportieren. Danach können Sie mithilfe der Spreadsheet Programming API [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) HTML in JSON konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie DOCM in das JSON-Format über C#" %}}
1. Öffnen Sie die DOCM-Datei mit der Klasse [Document](https://reference.aspose.com/words/net/aspose.words/document).
2. Konvertieren Sie DOCM in HTML, indem Sie die Methode [Save](https://reference.aspose.com/words/net/aspose.words.documentsave/methods/4) verwenden
3. Laden Sie das HTML-Dokument mithilfe der Klasse [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook).
4. Speichern Sie das Dokument mit der Methode [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) im JSON-Format
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie geschütztes DOCM über C# in das JSON-Format" %}}
Über die API können Sie das passwortgeschützte Dokument auch öffnen. Wenn Ihr DOCM-Eingabedokument kennwortgeschützt ist, können Sie es ohne Verwendung des Kennworts nicht in das JSON-Format konvertieren. Die API ermöglicht es Ihnen, das verschlüsselte Dokument zu öffnen, indem Sie das richtige Kennwort in einem LoadOptions-Objekt übergeben. Das folgende Codebeispiel zeigt, wie Sie versuchen, ein verschlüsseltes Dokument mit einem Kennwort zu öffnen:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie DOCM in JSON in Range über C#" %}}
Während Sie DOCM in JSON konvertieren, können Sie den Bereich auch auf Ihr Ausgabe-JSON-Format festlegen. Um den Bereich festzulegen, können Sie das konvertierte HTML mithilfe der Workbook-Klasse öffnen, CellsCollection des Arbeitsblatts abrufen, das die Daten enthält, einen Bereich aus CellsCollection erstellen, indem Sie Zeilen- und Spaltenindizes angeben, und die ExportRangeToJson-Methode mit Verweisen auf Range- und ExportRangeToJsonOptions-Objekte aufrufen. Schließlich können Sie die JSON-Daten über die File.WriteAllText-Methode in einer Datei speichern. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}