---
title: API C++ para converter PDF em TXT
description: Converta PDF para TXT via API C++ sem usar o Microsoft Excel ou Adobe Reader
url: /pt/cpp/conversion/pdf-to-txt/
family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: TXT
otherformats: ODS EXCEL SXC MD CSV XLSM XLT TSV XLTX DIF XLSB XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderizar PDF para TXT em aplicativos C++" h2="Converta PDF para TXT em aplicativos C++ nativos sem precisar do Microsoft<sup>&reg;</sup> Excel ou Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Converter PDF para TXT em C++ por meio de bibliotecas de automação de formato de arquivo [Aspose.Total for C++](https://products.aspose.com/total/cpp/) é um processo simples de duas etapas. Na primeira etapa, você pode exportar PDF para XLSX usando [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), depois disso, usando [Aspose.Cells for C++]( https://products.aspose.com/cells/cpp/) API de programação de planilha, você pode converter XLSX para TXT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ para converter PDF em TXT" %}}
1. Abra o arquivo PDF usando a referência de classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Converta PDF para XLSX usando a função de membro [Salvar](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)
3. Carregue o documento XLSX usando a referência de classe [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Salve o documento no formato TXT usando a função de membro [Salvar](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total.Cpp``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obter ou definir informações do arquivo PDF via C++" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) também permite que você obtenha informações sobre seu documento PDF e tome decisões informadas antes do processo de conversão. Para obter informações específicas de um arquivo PDF, primeiro você precisa chamar o método [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) de [Documento](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) classe. Depois que o objeto DocumentInfo for recuperado, você poderá obter os valores das propriedades individuais. Além disso, você também pode definir as propriedades usando os respectivos métodos da classe DocumentInfo.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Salvar formato de arquivo TXT para transmitir via C++" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/) permite salvar o formato de arquivo TXT para transmitir. Para salvar arquivos em um fluxo, crie um objeto MemoryStream ou FileStream e salve o arquivo nesse objeto de fluxo chamando o [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) método [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) do objeto. Especifique o formato de arquivo desejado usando a enumeração [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) ao chamar o método Save.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-txt-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-ods/" name="PDF Para ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-excel/" name="PDF Para EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-sxc/" name="PDF Para SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-md/" name="PDF Para MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-txt/" name="PDF Para TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-xlsm/" name="PDF Para XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-xlt/" name="PDF Para XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-tsv/" name="PDF Para TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-xltx/" name="PDF Para XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-dif/" name="PDF Para DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-xlsb/" name="PDF Para XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-xlam/" name="PDF Para XLAM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}