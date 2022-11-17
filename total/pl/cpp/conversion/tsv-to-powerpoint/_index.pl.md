---
title: Konwertuj TSV na POWERPOINT za pomocą C++
description: Konwertuj TSV na POWERPOINT w aplikacjach C++

family: total
platformtag: cpp
feature: conversion
informat: TSV
outformat: PPTX
otherformats: PPTX DOCX DOC WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwertuj TSV na POWERPOINT za pomocą C++" h2="Eksportuj Excel<sup>&reg;</sup> TSV do POWERPOINT w ramach w pełni funkcjonalnych aplikacji C++" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwersja TSV do POWERPOINT w C++" %}}
1. Otwórz plik TSV za pomocą funkcji członkowskiej [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) [Fabryka](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) — odniesienie do klasy
2. Konwertuj TSV na PDF i ustaw SaveFormat na Pdf
3. Załaduj przekonwertowany plik PDF, korzystając z odwołania do klasy [Powerpointument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument)
4. Zapisz dokument w formacie POWERPOINT za pomocą funkcji członka [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument#a6383c010776212483f51cc41235924db) i ustaw Powerpoint jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the TSV file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.tsv");
// save TSV as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Powerpointument class reference
auto powerpoint = MakeObject<Powerpointument>(u"pdfOutput.pdf");
// save powerpointument in PPTX format
powerpoint->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/tsv-to-pptx/" name="TSV Do PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/tsv-to-powerpointx/" name="TSV Do POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/tsv-to-powerpoint/" name="TSV Do POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/tsv-to-word/" name="TSV Do WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}