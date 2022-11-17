---
title: Konvertálja a FODS-t DOCX-ba a C++ segítségével
description: A FODS konvertálása DOCX formátumba a C++ alkalmazásokon belül

family: total
platformtag: cpp
feature: conversion
informat: FODS
outformat: DOCX
otherformats: DOC WORD PPTX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="A FODS konvertálása DOCX formátumba C++ segítségével" h2="Exportálás Excel<sup>&reg;</sup> FODS-ből DOCX-ba a teljes funkcionalitású C++ alkalmazásokon belül" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="FODS-ből DOCX-ba konvertálás C++-on" %}}
1. Nyissa meg a FODS-fájlt a [Factory](https://reference.aspose.com/cells) [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) tagfüggvényével /cpp/class/aspose.cells.factory) osztályhivatkozás
2. Alakítsa át a FODS-t PDF-be, és állítsa a SaveFormat-ot PDF-re
3. Töltse be a konvertált PDF-fájlt a [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) osztályhivatkozás használatával
4. Mentse a dokumentumot DOCX formátumba a [Mentés](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) tagfüggvénnyel, és állítsa be a dokumentumot SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the FODS file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.fods");
// save FODS as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Document class reference
auto docx = MakeObject<Document>(u"pdfOutput.pdf");
// save document in DOCX format
docx->Save(u"convertedFile.docx", SaveFormat::DocxX);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/fods-to-docx/" name="FODS Nak nek DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/fods-to-word/" name="FODS Nak nek WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/fods-to-pptx/" name="FODS Nak nek PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/fods-to-powerpoint/" name="FODS Nak nek POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}