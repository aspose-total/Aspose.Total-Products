---
title: Converter o formato JSON para WORD via .NET
description: Analise JSON para WORD em C# sem usar o Microsoft Word
url_ignore: /pt/net/conversion/json-to-word/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DOC
otherformats: DOC MOBI DOT ODT WORDML DOTX FLATOPC EPUB DOCM OTT PS RTF WORD PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converter o formato JSON para WORD via C#" h2="API C# para analisar JSON para WORD sem usar o Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total for .NET](https://products.aspose.com/total/net/) você pode analisar JSON para WORD dentro de qualquer aplicativo .NET, C#, ASP.NET e VB.NET em duas simples degraus. Em primeiro lugar, usando [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), você pode exportar JSON para PDF. Depois disso, usando [Aspose.Words for .NET](https://products.aspose.com/words/net/), você pode converter PDF para WORD.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter o formato JSON para WORD via C#" %}}
1. Crie um novo objeto [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) e leia dados JSON válidos do arquivo
2. Importe o arquivo JSON para a planilha usando a classe [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) e [Salvar](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) como PDF
3. Carregue o documento PDF usando a classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Salve o documento no formato WORD usando o método [Salvar](https://reference.aspose.com/words/net/aspose.words.document/save/methods/3)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
C#
{{% blocks/products/pf/feature-page-section  h2="Defina o layout e converta o formato JSON para WORD via C#" %}}
Ao analisar JSON para WORD, você também pode definir opções de layout para seu JSON usando [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayouttoptions). Ele permite que você processe Array como uma tabela, ignore nulos, ignore título de array, ignore título de objeto, converta string em número ou data, defina data e formato de número e defina estilo de título. Todas essas opções permitem que você apresente seus dados conforme suas necessidades. O trecho de código a seguir mostra como definir as opções de layout.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Analisar o formato JSON para WORD com marca d'água" %}}
Usando a API, você também pode converter JSON em WORD com marca d'água. Para adicionar uma marca d'água ao seu documento WORD, você pode primeiro analisar o arquivo JSON para PDF e adicionar uma marca d'água a ele. Para adicionar uma marca d'água, carregue o arquivo PDF recém-criado usando a classe [Document](https://reference.aspose.com/words/net/aspose.words/document), crie uma instância de TextWatermarkOptions e defina suas propriedades, Chame o método Watermark.SetText e passe o texto da marca d'água e o objeto de TextWatermarkOptions. Depois de adicionar a marca d'água, você pode salvar o documento no WORD. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}