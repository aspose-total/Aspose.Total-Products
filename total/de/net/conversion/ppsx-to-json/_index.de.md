---
title: Konvertieren Sie PPSX in das JSON-Format über .NET
description: Konvertieren Sie PPSX in C# in JSON, ohne Microsoft Excel oder Powerpoint zu verwenden
url_ignore: /de/net/conversion/ppsx-to-json/
family: total
platformtag: net
feature: conversion
informat: PPSX
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie PPSX in das JSON-Format über C#" h2="Exportieren Sie PPSX über C# nach JSON, ohne Microsoft<sup>&reg;</sup> Excel oder PowerPoint zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Durch die Verwendung von [Aspose.Total for .NET](https://products.aspose.com/total/net/) können Sie PPSX in das JSON-Format innerhalb jeder .NET-, C#-, ASP.NET- und VB.NET-Anwendung in zwei konvertieren einfache Schritte. Erstens können Sie mit [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) PPSX in HTML exportieren. Danach können Sie mithilfe der Spreadsheet Programming API [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) HTML in JSON konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie PPSX in das JSON-Format über C#" %}}
1. Öffnen Sie die PPSX-Datei mit der Klasse [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation).
2. Konvertieren Sie PPSX in HTML, indem Sie die Methode [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) verwenden
3. Laden Sie das HTML-Dokument mithilfe der Klasse [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook).
4. Speichern Sie das Dokument mit der Methode [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) im JSON-Format
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie geschütztes PPSX über C# in das JSON-Format" %}}
Über die API können Sie das passwortgeschützte Dokument auch öffnen. Wenn Ihr eingegebenes PPSX-Dokument kennwortgeschützt ist, können Sie es ohne Verwendung des Kennworts nicht in das JSON-Format konvertieren. Die API ermöglicht es Ihnen, das verschlüsselte Dokument zu öffnen, indem Sie das richtige Kennwort in einem LoadOptions-Objekt übergeben. Das folgende Codebeispiel zeigt, wie Sie ein verschlüsseltes Dokument mit einem Kennwort öffnen.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-protected-powerpoint-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie PPSX in JSON in Range über C#" %}}
Während Sie PPSX in JSON konvertieren, können Sie den Bereich auch auf Ihr Ausgabe-JSON-Format festlegen. Um den Bereich festzulegen, können Sie das konvertierte HTML mithilfe der Workbook-Klasse öffnen, CellsCollection des Arbeitsblatts abrufen, das die Daten enthält, einen Bereich aus CellsCollection erstellen, indem Sie Zeilen- und Spaltenindizes angeben, und die ExportRangeToJson-Methode mit Verweisen auf Range- und ExportRangeToJsonOptions-Objekte aufrufen. Schließlich können Sie die JSON-Daten über die File.WriteAllText-Methode in einer Datei speichern. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}