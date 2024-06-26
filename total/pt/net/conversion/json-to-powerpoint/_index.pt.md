---
title: Converter o formato JSON para POWERPOINT via .NET
description: Analise JSON para POWERPOINT em C# sem usar o Microsoft PowerPoint
url_ignore: /pt/net/conversion/json-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: POWERPOINT
otherformats: OTP PPS PPSM PPTM POTX PPT POTM POWERPOINT POT PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converter o formato JSON para POWERPOINT via C#" h2="API C# para analisar JSON para POWERPOINT sem usar o Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Você pode converter JSON para POWERPOINT em qualquer aplicativo .NET, C#, ASP.NET e VB.NET em duas etapas simples. Em primeiro lugar, usando [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), você pode analisar JSON para PPTX. Depois disso, usando [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), você pode converter PPTX para POWERPOINT. Ambas as APIs estão no pacote [Aspose.Total for .NET](https://products.aspose.com/total/net/).
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter o formato JSON para POWERPOINT via C#" %}}
1. Crie um novo objeto [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) e leia dados JSON válidos do arquivo
2. Importe o arquivo JSON para a planilha usando a classe [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) e [Salvar](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) como PPTX
3. Carregue o documento PPTX usando a classe [Apresentação](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Salve o documento no formato POWERPOINT usando o método [Salvar](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Defina o layout e converta o formato JSON para POWERPOINT via C#" %}}
Ao analisar JSON para POWERPOINT, você também pode definir opções de layout para seu formato JSON usando [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayouttoptions). Ele permite que você processe array como uma tabela, ignore nulos, ignore o título do array, ignore o título do objeto, converta string em número ou data, defina data e formato de número e defina estilo de título. Todas essas opções permitem que você apresente seus dados conforme suas necessidades. O trecho de código a seguir mostra como definir as opções de layout.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "set-layout-and-parse-json-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converter o formato JSON para POWERPOINT com marca d'água" %}}
Usando a API, você também pode converter JSON em POWERPOINT com marca d'água. Para adicionar uma marca d'água ao seu documento POWERPOINT, você pode primeiro analisar JSON para PPTX e adicionar uma marca d'água a ele. Para adicionar uma marca d'água, carregue o arquivo PPTX recém-criado usando a classe [Apresentação](https://reference.aspose.com/slides/net/aspose.slides/presentation), selecione a apresentação principal, adicione o tipo de forma usando AddAutoShape e adicione texto de marca d'água usando AddTextFrame. Depois de adicionar a marca d'água, você pode salvar o documento no POWERPOINT. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}