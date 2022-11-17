---
title: Konvertieren Sie ODS in POWERPOINT mit C++
description: Konvertieren Sie ODS in POWERPOINT innerhalb von C++-Anwendungen

family: total
platformtag: cpp
feature: conversion
informat: ODS
outformat: PPTX
otherformats: DOCX PPTX WORD DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertieren Sie ODS über C++ in POWERPOINT" h2="Excel exportieren&reg; ODS zu POWERPOINT innerhalb voll funktionsfähiger C++-Anwendungen" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ODS-zu-POWERPOINT-Konvertierung in C++" %}}
1. Öffnen Sie die ODS-Datei mit der Member-Funktion [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) von [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) Klassenreferenz
2. Konvertieren Sie ODS in PDF und setzen Sie SaveFormat auf Pdf
3. Laden Sie die konvertierte PDF-Datei mithilfe der Klassenreferenz [Powerpointument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument).
4. Speichern Sie das Dokument im POWERPOINT-Format mit der Member-Funktion [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument#a6383c010776212483f51cc41235924db) und legen Sie Powerpoint als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total.Cpp``` oder über die Paket-Manager-Konsole von Visual Studio mit ```Install-Package Aspose.Total.Cpp```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://downloads.aspose.com/total/cpp) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the ODS file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.ods");
// save ODS as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Powerpointument class reference
auto powerpoint = MakeObject<Powerpointument>(u"pdfOutput.pdf");
// save powerpointument in PPTX format
powerpoint->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/ods-to-powerpointx/" name="ODS Zu POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/ods-to-pptx/" name="ODS Zu PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/ods-to-word/" name="ODS Zu WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/ods-to-powerpoint/" name="ODS Zu POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}