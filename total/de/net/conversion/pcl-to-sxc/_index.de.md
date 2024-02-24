---
title: Konvertieren Sie PCL über die C#-API in SXC
description: C#-API zum Konvertieren von PCL-Dateien in SXC ohne Verwendung von Microsoft Excel oder Adobe Reader
url_ignore: /de/net/conversion/pcl-to-sxc/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: SXC
otherformats: FODS DIF MD ODS XLTM SXC EXCEL XLAM XLTX XLSM TSV TXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#-API zum Rendern von PCL in SXC" h2="PCL-Datei über C# in SXC exportieren, ohne Microsoft<sup>&reg;</sup> Excel oder Adobe<sup>&reg;</sup> Acrobat Reader zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Mit [Aspose.Total for .NET](https://products.aspose.com/total/net/) können Sie PCL-Dateien in allen .NET-, C#-, ASP.NET- und VB.NET-Anwendungen problemlos in SXC konvertieren. Erstens können Sie mit [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) PCL nach XLSX exportieren. Danach können Sie mithilfe der [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API XLSX in SXC konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET-API zum Konvertieren von PCL in SXC" %}}
1. Öffnen Sie die PCL-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Konvertieren Sie PCL mit der Methode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) in XLSX
3. Laden Sie das XLSX-Dokument mithilfe der Klasse [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook).
4. Speichern Sie das Dokument mit der Methode [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) im SXC-Format und legen Sie „Sxc“ als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie geschütztes PCL in SXC über C#" %}}
Wenn Ihr PCL-Dokument passwortgeschützt ist, können Sie es ohne das Passwort nicht in SXC konvertieren. Mit der API können Sie das geschützte Dokument zunächst mit einem gültigen Passwort öffnen und anschließend konvertieren. Um die verschlüsselte Datei zu öffnen, können Sie eine neue Instanz der Klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) initialisieren und den Dateinamen und das Passwort als Argumente übergeben.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie die PCL-Datei in SXC mit Wasserzeichen über C#" %}}
Während Sie eine PCL-Datei in SXC konvertieren, können Sie Ihrem Ausgabe-SXC-Dateiformat auch Wasserzeichen hinzufügen. Um ein Wasserzeichen hinzuzufügen, können Sie ein neues Workbook-Objekt erstellen und das konvertierte XLSX-Dokument öffnen, Worksheet über seinen Index auswählen, eine Form erstellen und seine AddTextEffect-Funktion verwenden. Danach können Sie Ihr XLSX-Dokument als SXC mit Wasserzeichen speichern. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}