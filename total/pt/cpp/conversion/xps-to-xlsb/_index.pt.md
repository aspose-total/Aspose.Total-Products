---
title: API C++ para converter XPS em XLSB
description: Converta XPS para XLSB via API C++ sem usar o Microsoft Excel ou Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: XLSB
otherformats: ODS TXT XLTM CSV XLTX FODS XLT XLSM EXCEL DIF XLAM MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderizar XPS para XLSB em aplicativos C++" h2="Converta XPS para XLSB em aplicativos C++ nativos sem precisar do Microsoft<sup>&reg;</sup> Excel ou Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Converter XPS para XLSB em C++ por meio de bibliotecas de automação de formato de arquivo [Aspose.Total for C++](https://products.aspose.com/total/cpp/) é um processo simples de duas etapas. Na primeira etapa, você pode exportar XPS para XLSX usando [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), depois disso, usando [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API de programação de planilha, você pode converter XLSX para XLSB. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ para converter XPS em XLSB" %}}
1. Abra o arquivo XPS usando a referência de classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Converta XPS para XLSX usando a função de membro [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)
3. Carregue o documento XLSX usando a referência de classe [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Salve o documento no formato XLSB usando a função de membro [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total.Cpp``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obter ou definir informações do arquivo XPS via C++" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) também permite que você obtenha informações sobre seu documento XPS e tome decisões informadas antes do processo de conversão. Para obter informações específicas de um arquivo XPS, primeiro você precisa chamar o método [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) de [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) classe. Depois que o objeto DocumentInfo for recuperado, você poderá obter os valores das propriedades individuais. Além disso, você também pode definir as propriedades usando os respectivos métodos da classe DocumentInfo.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Salvar formato de arquivo XLSB para transmitir via C++" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/) permite salvar o formato de arquivo XLSB para transmitir. Para salvar arquivos em um fluxo, crie um objeto MemoryStream ou FileStream e salve o arquivo nesse objeto de fluxo chamando o [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) método [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) do objeto. Especifique o formato de arquivo desejado usando a enumeração [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) ao chamar o método Save.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-xlsb-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}