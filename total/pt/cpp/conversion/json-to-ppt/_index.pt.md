---
title: Converter o formato JSON para PPT via C++
description: Analise JSON para PPT em C++ sem usar o Microsoft PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: PPT
otherformats: OTP PPSM PPSX POTM PPTM POT ODP PPS POWERPOINT POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converter o formato JSON para PPT via C++" h2="API C++ para analisar JSON para PPT sem usar o Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Você pode converter JSON para PPT em qualquer aplicativo C++ em duas etapas simples. Em primeiro lugar, usando [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), você pode analisar JSON para PPTX. Depois disso, usando [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), você pode converter PPTX para PPT. Ambas as APIs estão no pacote [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter o formato JSON para PPT via C++" %}}
1. Crie um novo objeto [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) e leia dados JSON válidos do arquivo
2. Salve JSON como PPTX usando o método [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. Carregue o documento PPTX usando a classe [Apresentação](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Salve o documento no formato PPT usando o método [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Definir layout e converter o formato JSON para PPT via C++" %}}
Ao analisar JSON para PPT, você também pode definir o tamanho de linhas e colunas carregando JSON com a classe [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Se você precisar definir a mesma altura de linha para todas as linhas na planilha, poderá fazê-lo usando o [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) da coleção [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). Da mesma forma, para definir a mesma largura de coluna para todas as colunas na planilha, use o método [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) da coleção ICells.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converter o formato JSON para PPT com marca d'água em C++" %}}
Usando a API, você também pode converter JSON em PPT com marca d'água. Para adicionar uma marca d'água ao seu documento PPT, você pode primeiro analisar JSON para PPTX e adicionar uma marca d'água a ele. Para adicionar uma marca d'água, carregue o arquivo PPTX recém-criado usando a classe [Apresentação](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation), obtenha o primeiro slide, adicione um AutoForma do tipo Retângulo, adicione TextFrame ao Retângulo, crie o objeto Paragraph para um quadro de texto, crie o objeto Portion para o parágrafo, adicione marca d'água usando set_Text() e pode salvar o documento em PPT.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}