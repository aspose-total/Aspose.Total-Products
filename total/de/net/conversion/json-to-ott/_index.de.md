---
title: Konvertieren Sie das JSON-Format über .NET in OTT
description: Analysieren Sie JSON in OTT in C#, ohne Microsoft Word zu verwenden
url_ignore: /de/net/conversion/json-to-ott/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: OTT
otherformats: OTT DOT PS DOTX EPUB FLATOPC WORD RTF DOC PCL WORDML DOCM ODT MOBI
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertieren Sie das JSON-Format über C# in OTT" h2="C#-API zum Analysieren von JSON in OTT ohne Verwendung von Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Durch die Verwendung von [Aspose.Total for .NET](https://products.aspose.com/total/net/) können Sie JSON in OTT innerhalb jeder .NET-, C#-, ASP.NET- und VB.NET-Anwendung in zwei einfachen Schritten parsen Schritte. Erstens können Sie mit [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) JSON in PDF exportieren. Danach können Sie mit [Aspose.Words for .NET](https://products.aspose.com/words/net/) PDF in OTT konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie das JSON-Format über C# in OTT" %}}
1. Erstellen Sie ein neues [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)-Objekt und lesen Sie gültige JSON-Daten aus der Datei
2. Importieren Sie die JSON-Datei in das Arbeitsblatt mit der Klasse [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) und [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) als PDF
3. Laden Sie das PDF-Dokument mithilfe der Klasse [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Speichern Sie das Dokument im OTT-Format mit der Methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/3).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Legen Sie das Layout fest und konvertieren Sie das JSON-Format über C# in OTT" %}}
Beim Analysieren von JSON zu OTT können Sie auch Layoutoptionen für Ihr JSON mit [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions) festlegen. Es ermöglicht Ihnen, Array als Tabelle zu verarbeiten, Nullen zu ignorieren, Array-Titel zu ignorieren, Objekttitel zu ignorieren, Zeichenfolge in Zahl oder Datum umzuwandeln, Datums- und Zahlenformat festzulegen und Titelstil festzulegen. Alle diese Optionen ermöglichen es Ihnen, Ihre Daten nach Ihren Bedürfnissen zu präsentieren. Das folgende Code-Snippet zeigt Ihnen, wie Sie die Layout-Optionen festlegen.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Analysieren Sie das JSON-Format in OTT mit Wasserzeichen" %}}
Mit der API können Sie auch JSON in OTT mit Wasserzeichen konvertieren. Um Ihrem OTT-Dokument ein Wasserzeichen hinzuzufügen, können Sie zuerst die JSON-Datei in eine PDF-Datei parsen und ihr ein Wasserzeichen hinzufügen. Um ein Wasserzeichen hinzuzufügen, laden Sie die neu erstellte PDF-Datei mit der Klasse [Document](https://reference.aspose.com/words/net/aspose.words/document), erstellen Sie eine Instanz von TextWatermarkOptions und legen Sie ihre Eigenschaften fest, Watermark.SetText-Methode aufrufen und Wasserzeichentext und Objekt von TextWatermarkOptions übergeben. Nachdem Sie das Wasserzeichen hinzugefügt haben, können Sie das Dokument in OTT speichern. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}