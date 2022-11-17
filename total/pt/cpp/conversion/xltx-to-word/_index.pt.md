---
title: Converter XLTX para WORD com C++
description: Converter XLTX para WORD em aplicativos C++

family: total
platformtag: cpp
feature: conversion
informat: XLTX
outformat: DOC
otherformats: DOCX POWERPOINT PPTX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converter XLTX para WORD via C++" h2="Exportar Excel<sup>&reg;</sup> XLTX para WORD em aplicativos C++ totalmente funcionais" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversão de XLTX para WORD em C++" %}}
1. Abra o arquivo XLTX usando a função de membro [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) de [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) referência de classe
2. Converta XLTX para PDF e defina SaveFormat para PDF
3. Carregue o arquivo PDF convertido usando a referência de classe [Wordument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument)
4. Salve o wordumento no formato WORD usando a função de membro [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument#a6383c010776212483f51cc41235924db) e defina Word como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total.Cpp``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLTX file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xltx");
// save XLTX as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Wordument class reference
auto word = MakeObject<Wordument>(u"pdfOutput.pdf");
// save wordument in WORD format
word->Save(u"convertedFile.word", SaveFormat::Word);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/xltx-to-wordx/" name="XLTX Para WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/xltx-to-powerpoint/" name="XLTX Para POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/xltx-to-pptx/" name="XLTX Para PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/xltx-to-word/" name="XLTX Para WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}