---
title: Konvertieren Sie PS über die C#-API in CSV
description: C#-API zum Konvertieren von PS-Dateien in CSV ohne Verwendung von Microsoft Excel oder Adobe Reader
url_ignore: /de/net/conversion/ps-to-csv/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: CSV
otherformats: SXC XLTM TXT XLSB XLAM TSV XLT FODS XLSM DIF EXCEL MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#-API zum Rendern von PS in CSV" h2="PS-Datei über C# in CSV exportieren, ohne Microsoft<sup>&reg;</sup> Excel oder Adobe<sup>&reg;</sup> Acrobat Reader zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Mit [Aspose.Total for .NET](https://products.aspose.com/total/net/) können Sie PS-Dateien in allen .NET-, C#-, ASP.NET- und VB.NET-Anwendungen problemlos in CSV konvertieren. Erstens können Sie mit [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) PS nach XLSX exportieren. Danach können Sie mithilfe der [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API XLSX in CSV konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET-API zum Konvertieren von PS in CSV" %}}
1. Öffnen Sie die PS-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Konvertieren Sie PS mit der Methode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) in XLSX
3. Laden Sie das XLSX-Dokument mithilfe der Klasse [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook).
4. Speichern Sie das Dokument mit der Methode [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) im CSV-Format und legen Sie „Csv“ als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie geschütztes PS in CSV über C#" %}}
Wenn Ihr PS-Dokument passwortgeschützt ist, können Sie es ohne das Passwort nicht in CSV konvertieren. Mit der API können Sie das geschützte Dokument zunächst mit einem gültigen Passwort öffnen und anschließend konvertieren. Um die verschlüsselte Datei zu öffnen, können Sie eine neue Instanz der Klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) initialisieren und den Dateinamen und das Passwort als Argumente übergeben.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie die PS-Datei in CSV mit Wasserzeichen über C#" %}}
Während Sie eine PS-Datei in CSV konvertieren, können Sie Ihrem Ausgabe-CSV-Dateiformat auch Wasserzeichen hinzufügen. Um ein Wasserzeichen hinzuzufügen, können Sie ein neues Workbook-Objekt erstellen und das konvertierte XLSX-Dokument öffnen, Worksheet über seinen Index auswählen, eine Form erstellen und seine AddTextEffect-Funktion verwenden. Danach können Sie Ihr XLSX-Dokument als CSV mit Wasserzeichen speichern. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}