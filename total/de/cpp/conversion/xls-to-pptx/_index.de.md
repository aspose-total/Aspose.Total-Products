---
title: Konvertieren Sie XLS in PPTX mit C++
description: Konvertieren Sie XLS in PPTX innerhalb von C++-Anwendungen
url: /de/cpp/conversion/xls-to-pptx/
family: total
platformtag: cpp
feature: conversion
informat: XLS
outformat: PPTX
otherformats: DOCX DOC POWERPOINT WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertieren Sie XLS über C++ in PPTX" h2="Excel exportieren&reg; XLS zu PPTX innerhalb voll funktionsfähiger C++-Anwendungen" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLS-zu-PPTX-Konvertierung in C++" %}}
1. Öffnen Sie die XLS-Datei mit der Member-Funktion [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) von [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) Klassenreferenz
2. Konvertieren Sie XLS in PDF und setzen Sie SaveFormat auf Pdf
3. Laden Sie die konvertierte PDF-Datei mithilfe der Klassenreferenz [Pptxument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument).
4. Speichern Sie das Dokument im PPTX-Format mit der Member-Funktion [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument#a6383c010776212483f51cc41235924db) und legen Sie Pptx als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total.Cpp``` oder über die Paket-Manager-Konsole von Visual Studio mit ```Install-Package Aspose.Total.Cpp```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://downloads.aspose.com/total/cpp) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLS file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xls");
// save XLS as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Pptxument class reference
auto pptx = MakeObject<Pptxument>(u"pdfOutput.pdf");
// save pptxument in PPTX format
pptx->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/xls-to-pptxx/" name="XLS Zu PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/xls-to-pptx/" name="XLS Zu PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/xls-to-powerpoint/" name="XLS Zu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/xls-to-word/" name="XLS Zu WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}