---
title: Converter o formato JSON para PCL via C++
description: API C++ t0 Analisa JSON para PCL sem usar o Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: PCL
otherformats: ODT RTF DOT DOC EPUB PS OTT WORDML WORD DOTX DOCM MOBI FLATOPC CHM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converter o formato JSON para PCL via C++" h2="Analisar JSON para PCL em aplicativos C++ sem usar o Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total for C++](https://products.aspose.com/total/cpp/), você pode analisar JSON para PCL em seus aplicativos C++ em duas etapas simples. Em primeiro lugar, usando [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), você pode exportar JSON para PDF. Depois disso, usando [Aspose.Words for C++](https://products.aspose.com/words/cppp/), você pode converter PDF para PCL. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter o formato JSON para PCL em C++" %}}
1. Crie um novo objeto [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) e leia dados JSON válidos do arquivo
2. Salve JSON como PDF usando o método [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. Carregue o documento PDF usando a classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Salve o documento no formato PCL usando o método [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Definir layout e converter o formato JSON para PCL em C++" %}}
Ao analisar JSON para PCL, você também pode definir o tamanho de linhas e colunas carregando JSON com a classe [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Se você precisar definir a mesma altura de linha para todas as linhas na planilha, poderá fazê-lo usando o [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) da coleção [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). Da mesma forma, para definir a mesma largura de coluna para todas as colunas na planilha, use o método [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) da coleção ICells.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converter o formato JSON para PCL com marca d'água em C++" %}}
Usando a API, você também pode analisar JSON para PCL com marca d'água. Para adicionar uma marca d'água ao seu documento PCL, você pode primeiro converter JSON em PDF e adicionar uma marca d'água a ele. Para adicionar uma marca d'água, carregue o arquivo PDF recém-criado usando a classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document), defina propriedades diferentes para marca d'água de texto,
chame o método SetText e passe o texto da marca d'água e o objeto de TextWatermarkOptions. Depois de adicionar a marca d'água, você pode salvar o documento no PCL.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}