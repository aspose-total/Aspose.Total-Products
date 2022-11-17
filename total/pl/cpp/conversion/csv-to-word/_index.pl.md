---
title: Konwertuj CSV na WORD za pomocą C++
description: Konwertuj CSV na WORD w aplikacjach C++

family: total
platformtag: cpp
feature: conversion
informat: CSV
outformat: DOC
otherformats: POWERPOINT PPTX DOCX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwertuj CSV na WORD za pomocą C++" h2="Eksportuj Excel<sup>&reg;</sup> CSV do WORD w ramach w pełni funkcjonalnych aplikacji C++" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwersja CSV do WORD w C++" %}}
1. Otwórz plik CSV za pomocą funkcji członkowskiej [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) [Fabryka](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) — odniesienie do klasy
2. Konwertuj CSV na PDF i ustaw SaveFormat na Pdf
3. Załaduj przekonwertowany plik PDF, korzystając z odwołania do klasy [Wordument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument)
4. Zapisz dokument w formacie WORD za pomocą funkcji członka [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument#a6383c010776212483f51cc41235924db) i ustaw Word jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the CSV file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.csv");
// save CSV as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Wordument class reference
auto word = MakeObject<Wordument>(u"pdfOutput.pdf");
// save wordument in WORD format
word->Save(u"convertedFile.word", SaveFormat::Word);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/csv-to-powerpoint/" name="CSV Do POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/csv-to-pptx/" name="CSV Do PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/csv-to-wordx/" name="CSV Do WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/csv-to-word/" name="CSV Do WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}