---
title: Konvertieren Sie CSV in DOC mit .NET 
description: Konvertieren Sie CSV in DOC auf .NET Framework-, .NET Core-, Mono- oder Xamarin-Plattformen

family: total
platformtag: net
feature: conversion
informat: CSV
outformat: DOC
otherformats: WORD POWERPOINT PPTX DOCX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konvertieren Sie CSV in DOC über C#" h2="Excel exportieren&reg; CSV zu DOC auf .NET Framework-, .NET Core-, Mono- oder Xamarin-Plattformen">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="CSV-zu-DOC-Konvertierung auf .NET" %}}
1. Öffnen Sie die CSV-Datei mit der Klasse [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook).
2. Konvertieren Sie CSV in PDF und setzen Sie SaveFormat auf Auto
3. Laden Sie die konvertierte PDF-Datei mit der Klasse [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document).
4. Speichern Sie das Dokument mit der Methode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) im DOC-Format und legen Sie Doc als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://downloads.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C#-Code für die Konvertierung von CSV in DOC" gistPath="" %}}

```cs
// load the CSV file using Workbook class
var book = new Aspose.Cells.Workbook("input.csv");
// save CSV as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOC format
document.Save("output.doc", SaveFormat.Doc); 
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