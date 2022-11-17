---
title: Преобразование TSV в WORD с помощью C++
description: Преобразование TSV в WORD в приложениях C++

family: total
platformtag: cpp
feature: conversion
informat: TSV
outformat: DOC
otherformats: DOC PPTX DOCX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Конвертировать TSV в WORD через C++" h2="Экспорт Excel<sup>&reg;</sup> TSV в WORD в полнофункциональных приложениях C++" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование TSV в WORD на C++" %}}
1. Откройте TSV-файл, используя [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) функцию-член [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) ссылка на класс
2. Преобразуйте TSV в PDF и установите SaveFormat в Pdf.
3. Загрузите преобразованный PDF-файл, используя ссылку на класс [Wordument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument).
4. Сохраните документ в формате WORD с помощью функции-члена [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument#a6383c010776212483f51cc41235924db) и установите Word как SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Установите из командной строки как ```nuget install Aspose.Total.Cpp``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total.Cpp```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the TSV file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.tsv");
// save TSV as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Wordument class reference
auto word = MakeObject<Wordument>(u"pdfOutput.pdf");
// save wordument in WORD format
word->Save(u"convertedFile.word", SaveFormat::Word);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/tsv-to-word/" name="TSV К WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/tsv-to-pptx/" name="TSV К PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/tsv-to-wordx/" name="TSV К WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/tsv-to-powerpoint/" name="TSV К POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}