---
title: Converter TSV para DOC com C++
description: Converter TSV para DOC em aplicativos C++
url: /pt/cpp/conversion/tsv-to-doc/
family: total
platformtag: cpp
feature: conversion
informat: TSV
outformat: DOC
otherformats: POWERPOINT PPTX DOCX WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converter TSV para DOC via C++" h2="Exportar Excel<sup>&reg;</sup> TSV para DOC em aplicativos C++ totalmente funcionais" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversão de TSV para DOC em C++" %}}
1. Abra o arquivo TSV usando a função de membro [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) de [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) referência de classe
2. Converta TSV para PDF e defina SaveFormat para PDF
3. Carregue o arquivo PDF convertido usando a referência de classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
4. Salve o documento no formato DOC usando a função de membro [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) e defina Doc como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total.Cpp``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the TSV file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.tsv");
// save TSV as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Document class reference
auto doc = MakeObject<Document>(u"pdfOutput.pdf");
// save document in DOC format
doc->Save(u"convertedFile.doc", SaveFormat::Doc);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/tsv-to-powerpoint/" name="TSV Para POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/tsv-to-pptx/" name="TSV Para PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/tsv-to-docx/" name="TSV Para DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/tsv-to-word/" name="TSV Para WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}