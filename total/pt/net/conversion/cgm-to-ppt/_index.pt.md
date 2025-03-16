---
title: Exportar CGM para PPT via API C#
description: API .NET para converter CGM em PPT sem usar o Microsoft Word
url_ignore: /pt/net/conversion/cgm-to-ppt/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PPT
otherformats: PPSX PPS PPSM POT XAML POTM SWF OTP POWERPOINT PPT POTX PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar CGM para PPT via .NET" h2="API .NET para exportar CGM para PPT no Windows, macOS e Linux sem usar o Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando um pacote de APIs poderosas de automação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) você pode facilmente renderizar CGM para PPT em duas etapas simples. Usando a API de processamento de PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), você pode transformar o formato de arquivo CGM em PPTX. Depois disso, usando a API de processamento de apresentação [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), você pode converter PPTX para PPT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para converter CGM em PPT" %}}
1. Abra o arquivo CGM usando a classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Converta CGM para PPTX usando o método [Salvar](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Carregue o arquivo PPTX usando a classe [Apresentação](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Salve o documento no formato PPT usando o método [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) e defina `Ppt` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenha metadados XMP do arquivo CGM via .NET" %}}
Ao converter CGM para PPT, você pode precisar de informações extras de metadados XMP para priorizar seu processo de conversão em lote. Por exemplo, você pode obter e classificar seus documentos de conversão com base na data de criação e processar os documentos de acordo. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) permite que você acesse os metadados XMP de um arquivo CGM. Para obter os metadados de um arquivo CGM, você pode criar um objeto [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) e abrir o arquivo CGM de entrada. Depois disso, você pode obter os metadados do arquivo usando a propriedade [Metadados](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Criar arquivo PPT somente leitura via .NET" %}}
Ao usar a API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), você pode aprimorar ainda mais os recursos do seu aplicativo de conversão. Um dos recursos pode ser criar seu arquivo de saída somente leitura para aumentar a segurança. A API permite que você defina seu arquivo PPT como somente leitura, o que significa que os usuários (depois de abrirem a apresentação) veem a recomendação somente leitura. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.ppt", SaveFormat.Ppt);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos CGM a PPT mediante programación: casos de uso" %}}
A conversão de arquivos CGM para formatos PPT é essencial para desbloquear as capacidades completas de suas capacidades de apresentação. Essa conversão permite:

**Cenários de Uso:**

*   **Design e Desenvolvimento de Slides**: Converter arquivos CGM para criar designs interativos de slides, simular experiências de usuário e validar conceitos de design.
*   **Gerenciamento de Conteúdo de Apresentação**: Usar PPT para gerenciar conteúdo de apresentação, organizar dados e rastrear mudanças em tempo real.
*   **Criação de Identidade e Marca**: Converter arquivos CGM para criar identidades consistentes de marca, logos e elementos visuais para apresentações e materiais de marketing.
*   **Conteúdo Interativo**: Usar PPT para criar apresentações interativas, adicionar animações e incorporar elementos multimídia para envolver o público.
*   **Visualização de Dados e Relatórios**: Converter arquivos CGM para criar dashboards interativos, relatórios e visualizações visuais para stakeholders, permitindo decisões mais informadas.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}