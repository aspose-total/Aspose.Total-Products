---
title: Konvertieren Sie XLSM in DOCX mit .NET 
description: Konvertieren Sie XLSM in DOCX auf .NET Framework-, .NET Core-, Mono- oder Xamarin-Plattformen
url: /de/net/conversion/xlsm-to-docx/
family: total
platformtag: net
feature: conversion
informat: XLSM
outformat: DOCX
otherformats: PPTX WORD DOC POWERPOINT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konvertieren Sie XLSM in DOCX über C#" h2="Excel exportieren&reg; XLSM zu DOCX auf .NET Framework-, .NET Core-, Mono- oder Xamarin-Plattformen">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLSM-zu-DOCX-Konvertierung auf .NET" %}}
1. Öffnen Sie die XLSM-Datei mit der Klasse [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook).
2. Konvertieren Sie XLSM in PDF und setzen Sie SaveFormat auf Auto
3. Laden Sie die konvertierte PDF-Datei mit der Klasse [Docxument](https://apireference.aspose.com/pdf/net/aspose.pdf/docxument).
4. Speichern Sie das Dokument mit der Methode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.docxument/save/methods/5) im DOCX-Format und legen Sie Docx als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://downloads.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C#-Code für die Konvertierung von XLSM in DOCX" gistPath="" %}}
```cs
// load the XLSM file using Workbook class
var book = new Aspose.Cells.Workbook("input.xlsm");
// save XLSM as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Docxument class
var docxument = new Aspose.Pdf.Docxument("pdfOutput.pdf");
// save docxument in DOCXX format
docxument.Save("output.docxx", SaveFormat.DocxX); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/csv-to-word/" name="CSV Zu WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/csv-to-powerpoint/" name="CSV Zu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/csv-to-pptx/" name="CSV Zu PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/csv-to-docx/" name="CSV Zu DOCX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}