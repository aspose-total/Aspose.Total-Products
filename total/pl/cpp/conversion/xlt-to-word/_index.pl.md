---
title: Konwertuj XLT na WORD za pomocą C++
description: Konwertuj XLT na WORD w aplikacjach C++

family: total
platformtag: cpp
feature: conversion
informat: XLT
outformat: DOC
otherformats: POWERPOINT DOCX PPTX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwertuj XLT na WORD za pomocą C++" h2="Eksportuj Excel<sup>&reg;</sup> XLT do WORD w ramach w pełni funkcjonalnych aplikacji C++" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwersja XLT do WORD w C++" %}}
1. Otwórz plik XLT za pomocą funkcji członkowskiej [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) [Fabryka](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) — odniesienie do klasy
2. Konwertuj XLT na PDF i ustaw SaveFormat na Pdf
3. Załaduj przekonwertowany plik PDF, korzystając z odwołania do klasy [Wordument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument)
4. Zapisz dokument w formacie WORD za pomocą funkcji członka [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument#a6383c010776212483f51cc41235924db) i ustaw Word jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLT file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlt");
// save XLT as PDF
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xlt-to-powerpoint/" name="XLT Do POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xlt-to-wordx/" name="XLT Do WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xlt-to-pptx/" name="XLT Do PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xlt-to-word/" name="XLT Do WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}