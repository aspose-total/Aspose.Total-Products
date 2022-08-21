---
title: Konvertálja a EXCEL-t WORD-ba a C++ segítségével
description: A EXCEL konvertálása WORD formátumba a C++ alkalmazásokon belül
url: /hu/cpp/conversion/excel-to-word/
family: total
platformtag: cpp
feature: conversion
informat: CSV
outformat: DOC
otherformats: DOC PPTX POWERPOINT DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="A EXCEL konvertálása WORD formátumba C++ segítségével" h2="Exportálás Excel<sup>&reg;</sup> EXCEL-ből WORD-ba a teljes funkcionalitású C++ alkalmazásokon belül" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EXCEL-ből WORD-ba konvertálás C++-on" %}}
1. Nyissa meg a EXCEL-fájlt a [Factory](https://reference.aspose.com/cells) [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) tagfüggvényével /cpp/class/aspose.cells.factory) osztályhivatkozás
2. Alakítsa át a EXCEL-t PDF-be, és állítsa a SaveFormat-ot PDF-re
3. Töltse be a konvertált PDF-fájlt a [Wordument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument) osztályhivatkozás használatával
4. Mentse a dokumentumot WORD formátumba a [Mentés](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument#a6383c010776212483f51cc41235924db) tagfüggvénnyel, és állítsa be a dokumentumot SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EXCEL file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.excel");
// save EXCEL as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Wordument class reference
auto word = MakeObject<Wordument>(u"pdfOutput.pdf");
// save wordument in WORD format
word->Save(u"convertedFile.word", SaveFormat::Word);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/excel-to-word/" name="EXCEL Nak nek WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/excel-to-pptx/" name="EXCEL Nak nek PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/excel-to-powerpoint/" name="EXCEL Nak nek POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/excel-to-wordx/" name="EXCEL Nak nek WORDX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}