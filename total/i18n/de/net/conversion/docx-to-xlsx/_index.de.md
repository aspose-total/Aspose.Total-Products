---
title: .NET-API zum Konvertieren von DOCX in XLSX
description: C#-API zum Konvertieren von DOCX in XLSX ohne Verwendung von Microsoft Excel oder Adobe Reader
url: /de/net/conversion/docx-to-xlsx/
family: total
platformtag: net
feature: conversion
informat: DOCXX
outformat: XLSX
otherformats: XLSX SXC XLT XLSM XLSB XLTX XLS EXCEL TSV ODS XLAM XLTM FODS DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#-API zum Konvertieren von DOCX in XLSX" h2="DOCX über C# in XLSX exportieren, ohne Microsoft<sup>&reg;</sup> Word oder Microsoft<sup>&reg;</sup> Excel zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Durch die Verwendung von [Aspose.Total for .NET](https://products.aspose.com/total/net/) können Sie die DOCX-zu-XLSX-Konvertierungsfunktion in jede .NET-, C#-, ASP.NET- und VB.NET-Anwendung integrieren zwei einfache Schritte. Erstens können Sie mit [Aspose.Words for .NET](https://products.aspose.com/words/net/) DOCX in HTML exportieren. Danach können Sie mithilfe der Spreadsheet Programming API [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) HTML in XLSX konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET-API zum Konvertieren von DOCX in XLSX" %}}
1. Öffnen Sie die DOCX-Datei mit der Klasse [Docxument](https://apireference.aspose.com/words/net/aspose.words/docxument).
2. Konvertieren Sie DOCX in HTML, indem Sie die Methode [Save](https://apireference.aspose.com/words/net/aspose.words.docxument/save/methods/4) verwenden
3. Laden Sie das HTML-Dokument mithilfe der Klasse [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook).
4. Speichern Sie das Dokument mit der Methode [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) im XLSX-Format und legen Sie „XLSX“ als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads] (https://downloads.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="DOCX-Dokument aus Stream über C# laden" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) ermöglicht es Ihnen auch, DOCX-Dokumente per Stream zu laden. Um ein Dokument aus einem Stream zu öffnen, übergeben Sie einfach ein Stream-Objekt, das das Dokument enthält, an den Konstruktor [Docxument](https://apireference.aspose.com/words/net/aspose.words/docxument). Das folgende Codebeispiel zeigt, wie Sie ein Dokument aus einem Stream öffnen:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-protected-word-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Benutzerdefinierte Eigenschaften in XLSX-Datei über C# hinzufügen" %}}
Beim Konvertieren von DOCX in XLSX können Sie mit [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Ihren XLSX-Dokumenten benutzerdefinierte Eigenschaften hinzufügen. Um eine benutzerdefinierte Eigenschaft hinzuzufügen, können Sie die Methode [Add](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocxumentpropertycollection/methods/add/index) für die [CustomDocxumentPropertyCollection]( https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocxumentpropertycollection) Klasse. Die Add-Methode fügt die Eigenschaft zur Excel-Datei hinzu und gibt eine Referenz für die neue Dokumenteigenschaft als [Aspose.Cells.Properties.DocxumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties /docxumentproperty)-Objekt. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-protected-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-dif/" name="DOCX Zu DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-xlsb/" name="DOCX Zu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-tsv/" name="DOCX Zu TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-fods/" name="DOCX Zu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-xlt/" name="DOCX Zu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-excel/" name="DOCX Zu EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-xlsx/" name="DOCX Zu XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-ods/" name="DOCX Zu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-sxc/" name="DOCX Zu SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-xlam/" name="DOCX Zu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-xltm/" name="DOCX Zu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-xlsm/" name="DOCX Zu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-xls/" name="DOCX Zu XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/docx-to-xltx/" name="DOCX Zu XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}