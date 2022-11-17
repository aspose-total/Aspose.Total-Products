---
title: Konvertálja a XLSX-t POWERPOINT-ba a C++ segítségével
description: A XLSX konvertálása POWERPOINT formátumba a C++ alkalmazásokon belül

family: total
platformtag: cpp
feature: conversion
informat: XLSX
outformat: PPTX
otherformats: PPTX DOCX DOC WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="A XLSX konvertálása POWERPOINT formátumba C++ segítségével" h2="Exportálás Excel<sup>&reg;</sup> XLSX-ből POWERPOINT-ba a teljes funkcionalitású C++ alkalmazásokon belül" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLSX-ből POWERPOINT-ba konvertálás C++-on" %}}
1. Nyissa meg a XLSX-fájlt a [Factory](https://reference.aspose.com/cells) [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) tagfüggvényével /cpp/class/aspose.cells.factory) osztályhivatkozás
2. Alakítsa át a XLSX-t PDF-be, és állítsa a SaveFormat-ot PDF-re
3. Töltse be a konvertált PDF-fájlt a [Powerpointument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument) osztályhivatkozás használatával
4. Mentse a dokumentumot POWERPOINT formátumba a [Mentés](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument#a6383c010776212483f51cc41235924db) tagfüggvénnyel, és állítsa be a dokumentumot SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSX file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlsx");
// save XLSX as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Powerpointument class reference
auto powerpoint = MakeObject<Powerpointument>(u"pdfOutput.pdf");
// save powerpointument in PPTX format
powerpoint->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/xlsx-to-pptx/" name="XLSX Nak nek PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/xlsx-to-powerpointx/" name="XLSX Nak nek POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/xlsx-to-powerpoint/" name="XLSX Nak nek POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/xlsx-to-word/" name="XLSX Nak nek WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}