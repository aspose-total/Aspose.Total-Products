---
title: Converter XLT para DOCX com C++
description: Converter XLT para DOCX em aplicativos C++
url: /pt/cpp/conversion/xlt-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: XLT
outformat: DOCX
otherformats: DOC PPTX WORD POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converter XLT para DOCX via C++" h2="Exportar Excel<sup>&reg;</sup> XLT para DOCX em aplicativos C++ totalmente funcionais" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversão de XLT para DOCX em C++" %}}
1. Abra o arquivo XLT usando a função de membro [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) de [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) referência de classe
2. Converta XLT para PDF e defina SaveFormat para PDF
3. Carregue o arquivo PDF convertido usando a referência de classe [Docxument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.docxument)
4. Salve o docxumento no formato DOCX usando a função de membro [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.docxument#a6383c010776212483f51cc41235924db) e defina Docx como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total.Cpp``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLT file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlt");
// save XLT as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Docxument class reference
auto docx = MakeObject<Docxument>(u"pdfOutput.pdf");
// save docxument in DOCX format
docx->Save(u"convertedFile.docx", SaveFormat::DocxX);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/xlt-to-docx/" name="XLT Para DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/xlt-to-pptx/" name="XLT Para PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/xlt-to-word/" name="XLT Para WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/xlt-to-powerpoint/" name="XLT Para POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}