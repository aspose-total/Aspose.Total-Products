---
title: Exportar MD para POTX via API C#
description: API .NET para converter MD em POTX sem usar o Microsoft Word
url_ignore: /pt/net/conversion/md-to-potx/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: POTX
otherformats: PPSX PPS PPTM XAML PPT POTM POTX PPSM POT POWERPOINT OTP SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar MD para POTX via .NET" h2="API .NET para exportar MD para POTX no Windows, macOS e Linux sem usar o Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando um pacote de APIs poderosas de automação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) você pode facilmente renderizar MD para POTX em duas etapas simples. Usando a API de processamento de PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), você pode transformar o formato de arquivo MD em PPTX. Depois disso, usando a API de processamento de apresentação [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), você pode converter PPTX para POTX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para converter MD em POTX" %}}
1. Abra o arquivo MD usando a classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Converta MD para PPTX usando o método [Salvar](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Carregue o arquivo PPTX usando a classe [Apresentação](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Salve o documento no formato POTX usando o método [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) e defina `Potx` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "convert-md-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenha metadados XMP do arquivo MD via .NET" %}}
Ao converter MD para POTX, você pode precisar de informações extras de metadados XMP para priorizar seu processo de conversão em lote. Por exemplo, você pode obter e classificar seus documentos de conversão com base na data de criação e processar os documentos de acordo. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) permite que você acesse os metadados XMP de um arquivo MD. Para obter os metadados de um arquivo MD, você pode criar um objeto [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) e abrir o arquivo MD de entrada. Depois disso, você pode obter os metadados do arquivo usando a propriedade [Metadados](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "decrypt-md-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Criar arquivo POTX somente leitura via .NET" %}}
Ao usar a API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), você pode aprimorar ainda mais os recursos do seu aplicativo de conversão. Um dos recursos pode ser criar seu arquivo de saída somente leitura para aumentar a segurança. A API permite que você defina seu arquivo POTX como somente leitura, o que significa que os usuários (depois de abrirem a apresentação) veem a recomendação somente leitura. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.potx", SaveFormat.Potx);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos MD a POTX mediante programación: casos de uso" %}}
Arquivos MD (Markdown) são usados para armazenar conteúdo baseado em texto, tornando-os ideais para criar documentos simples e páginas web. No entanto, quando se trabalha com requisitos de análise e visualização de dados complexos, apresentações como o PowerPoint se tornam essenciais.

A conversão de arquivos MD para formatos do PowerPoint (.potx) é necessária para desbloquear as capacidades totais de suas capacidades de apresentação. Essa conversão permite que você:

**Cenários de Uso:**

*   **Presentações de Conferência**: Converter arquivos MD para criar presentes de conferência envolventes, repletos de imagens, gráficos e gráficos.
*   **Documentação Técnica**: Usar o PowerPoint para visualizar documentação técnica, como manuais do usuário e orientações instrutivas.
*   **Materiais de Treinamento**: Converter arquivos MD para criar materiais de treinamento interativos, incluindo testes, avaliações e mecanismos de retroalimentação.
*   ** Conteúdo de Venda e Marketing**: Usar o PowerPoint para criar conteúdo persuasivo de vendas e marketing, incluindo demonstrações de produtos e depoimentos de clientes.
*   **Presentações Acadêmicas**: Converter arquivos MD para criar apresentações acadêmicas profissionais, repletas de citações, referências e ajuda visual.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}