---
title: Konwertuj XLTX na DOCX za pomocą C++
description: Konwertuj XLTX na DOCX w aplikacjach C++
url: /pl/cpp/conversion/xltx-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: XLTX
outformat: DOCX
otherformats: DOC POWERPOINT WORD PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwertuj XLTX na DOCX za pomocą C++" h2="Eksportuj Excel<sup>&reg;</sup> XLTX do DOCX w ramach w pełni funkcjonalnych aplikacji C++" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwersja XLTX do DOCX w C++" %}}
1. Otwórz plik XLTX za pomocą funkcji członkowskiej [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) [Fabryka](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) — odniesienie do klasy
2. Konwertuj XLTX na PDF i ustaw SaveFormat na Pdf
3. Załaduj przekonwertowany plik PDF, korzystając z odwołania do klasy [Docxument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.docxument)
4. Zapisz dokument w formacie DOCX za pomocą funkcji członka [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.docxument#a6383c010776212483f51cc41235924db) i ustaw Docx jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLTX file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xltx");
// save XLTX as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Docxument class reference
auto docx = MakeObject<Docxument>(u"pdfOutput.pdf");
// save docxument in DOCX format
docx->Save(u"convertedFile.docx", SaveFormat::DocxX);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xltx-to-docx/" name="XLTX Do DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xltx-to-powerpoint/" name="XLTX Do POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xltx-to-word/" name="XLTX Do WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xltx-to-pptx/" name="XLTX Do PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}