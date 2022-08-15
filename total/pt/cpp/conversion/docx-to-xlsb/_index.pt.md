---
title: Converter DOCX para XLSB em C++
description: API C++ para converter DOCX para XLSB sem usar o Microsoft Word ou o Microsoft Excel
url: /pt/cpp/conversion/docx-to-xlsb/
family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: XLSB
otherformats: CSV EXCEL DIF ODS XLTX XLS XLTM XLSX XLAM XLSM FODS SXC TSV XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ para converter DOCX para XLSB" h2="Exporte DOCX para XLSB via C++ sem usar o Microsoft<sup>&reg;</sup> Word ou o Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Você pode incluir o recurso de conversão de DOCX para XLSB em seus aplicativos C++ facilmente. Usando a API de conversão e manipulação de docxumentos [Aspose.Words for C++](https://products.aspose.com/words/cpp/) rica em recursos, poderosa e fácil de usar, você pode exportar DOCX para HTML. Depois disso, usando [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), você pode converter HTML para XLSB. Ambas as APIs estão no pacote [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ para converter DOCX para XLSB" %}}
1. Abra o arquivo DOCX usando a referência de classe [Docxument](https://reference.aspose.com/words/cpp/class/aspose.words.docxument)
2. Converta DOCX para HTML usando a função de membro [Salvar](https://reference.aspose.com/words/cpp/class/aspose.words.docxument#save_string_saveformat)
3. Carregue o docxumento HTML usando a referência de classe [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Salve o docxumento no formato XLSB usando a função de membro [Salvar](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total.Cpp``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Acesse as propriedades do docxumento DOCX via C++" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) também permite acessar as propriedades do docxumento do arquivo DOCX e permite que você tome uma decisão informada antes do processo de conversão. Para acessar as propriedades do docxumento, você pode usar [BuiltInDocxumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_docxument_properties) para obter propriedades internas e [CustomDocxumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_docxument_properties) para obter propriedades personalizadas. O exemplo de código a seguir mostra como enumerar todas as propriedades internas e personalizadas em um docxumento.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-docxument-properties.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Salvar arquivo XLSB para transmitir via C++" %}}
Depois de converter DOCX para XLSB, o [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) permite que você salve seu docxumento para transmitir. Para salvar arquivos em um fluxo, crie um objeto MemoryStream ou FileStream e salve o arquivo nesse objeto de fluxo chamando o [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) método [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) do objeto. Especifique o formato de arquivo desejado usando a enumeração [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) ao chamar o [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/docx-to-xlsb/" name="DOCX Para XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/docx-to-excel/" name="DOCX Para EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/docx-to-dif/" name="DOCX Para DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/docx-to-ods/" name="DOCX Para ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/docx-to-xltx/" name="DOCX Para XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/docx-to-xls/" name="DOCX Para XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/docx-to-xltm/" name="DOCX Para XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/docx-to-xlsx/" name="DOCX Para XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/docx-to-xlam/" name="DOCX Para XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/docx-to-xlsm/" name="DOCX Para XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/docx-to-fods/" name="DOCX Para FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/docx-to-sxc/" name="DOCX Para SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/docx-to-tsv/" name="DOCX Para TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/docx-to-xlt/" name="DOCX Para XLT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}