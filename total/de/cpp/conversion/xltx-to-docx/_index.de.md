---
title: Konvertieren Sie XLTX in DOCX mit C++
description: Konvertieren Sie XLTX in DOCX innerhalb von C++-Anwendungen

family: total
platformtag: cpp
feature: conversion
informat: XLTX
outformat: DOCX
otherformats: DOC POWERPOINT WORD PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertieren Sie XLTX über C++ in DOCX" h2="Excel exportieren&reg; XLTX zu DOCX innerhalb voll funktionsfähiger C++-Anwendungen" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLTX-zu-DOCX-Konvertierung in C++" %}}
1. Öffnen Sie die XLTX-Datei mit der Member-Funktion [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) von [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) Klassenreferenz
2. Konvertieren Sie XLTX in PDF und setzen Sie SaveFormat auf Pdf
3. Laden Sie die konvertierte PDF-Datei mithilfe der Klassenreferenz [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document).
4. Speichern Sie das Dokument im DOCX-Format mit der Member-Funktion [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) und legen Sie Docx als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total.Cpp``` oder über die Paket-Manager-Konsole von Visual Studio mit ```Install-Package Aspose.Total.Cpp```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://downloads.aspose.com/total/cpp) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLTX file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xltx");
// save XLTX as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Document class reference
auto docx = MakeObject<Document>(u"pdfOutput.pdf");
// save document in DOCX format
docx->Save(u"convertedFile.docx", SaveFormat::DocxX);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/xltx-to-docx/" name="XLTX Zu DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/xltx-to-powerpoint/" name="XLTX Zu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/xltx-to-word/" name="XLTX Zu WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/xltx-to-pptx/" name="XLTX Zu PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}