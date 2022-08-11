---
title: Konvertálja a XLTM-t PPTX-ba a C++ segítségével
description: A XLTM konvertálása PPTX formátumba a C++ alkalmazásokon belül
url: /hu/cpp/conversion/xltm-to-pptx/
family: total
platformtag: cpp
feature: conversion
informat: XLTM
outformat: PPTX
otherformats: DOC POWERPOINT DOCX WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="A XLTM konvertálása PPTX formátumba C++ segítségével" h2="Exportálás Excel&reg; XLTM-ből PPTX-ba a teljes funkcionalitású C++ alkalmazásokon belül" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLTM-ből PPTX-ba konvertálás C++-on" %}}
1. Nyissa meg a XLTM-fájlt a [Factory](https://reference.aspose.com/cells) [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) tagfüggvényével /cpp/class/aspose.cells.factory) osztályhivatkozás
2. Alakítsa át a XLTM-t PDF-be, és állítsa a SaveFormat-ot PDF-re
3. Töltse be a konvertált PDF-fájlt a [Pptxument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument) osztályhivatkozás használatával
4. Mentse a dokumentumot PPTX formátumba a [Mentés](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument#a6383c010776212483f51cc41235924db) tagfüggvénnyel, és állítsa be a dokumentumot SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLTM file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xltm");
// save XLTM as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Pptxument class reference
auto pptx = MakeObject<Pptxument>(u"pdfOutput.pdf");
// save pptxument in PPTX format
pptx->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/xltm-to-pptx/" name="XLTM Nak nek PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/xltm-to-powerpoint/" name="XLTM Nak nek POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/xltm-to-pptxx/" name="XLTM Nak nek PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/xltm-to-word/" name="XLTM Nak nek WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}