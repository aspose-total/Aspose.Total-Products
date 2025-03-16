---
title: Exportar EPUB para XAML via API C#
description: API .NET para converter EPUB em XAML sem usar o Microsoft Word
url_ignore: /pt/net/conversion/epub-to-xaml/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: XAML
otherformats: PPTM OTP SWF PPSX PPS POWERPOINT XAML POTM PPSM PPT POTX POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar EPUB para XAML via .NET" h2="API .NET para exportar EPUB para XAML no Windows, macOS e Linux sem usar o Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando um pacote de APIs poderosas de automação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) você pode facilmente renderizar EPUB para XAML em duas etapas simples. Usando a API de processamento de PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), você pode transformar o formato de arquivo EPUB em PPTX. Depois disso, usando a API de processamento de apresentação [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), você pode converter PPTX para XAML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para converter EPUB em XAML" %}}
1. Abra o arquivo EPUB usando a classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Converta EPUB para PPTX usando o método [Salvar](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Carregue o arquivo PPTX usando a classe [Apresentação](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Salve o documento no formato XAML usando o método [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) e defina `Xaml` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "convert-epub-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenha metadados XMP do arquivo EPUB via .NET" %}}
Ao converter EPUB para XAML, você pode precisar de informações extras de metadados XMP para priorizar seu processo de conversão em lote. Por exemplo, você pode obter e classificar seus documentos de conversão com base na data de criação e processar os documentos de acordo. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) permite que você acesse os metadados XMP de um arquivo EPUB. Para obter os metadados de um arquivo EPUB, você pode criar um objeto [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) e abrir o arquivo EPUB de entrada. Depois disso, você pode obter os metadados do arquivo usando a propriedade [Metadados](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Criar arquivo XAML somente leitura via .NET" %}}
Ao usar a API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), você pode aprimorar ainda mais os recursos do seu aplicativo de conversão. Um dos recursos pode ser criar seu arquivo de saída somente leitura para aumentar a segurança. A API permite que você defina seu arquivo XAML como somente leitura, o que significa que os usuários (depois de abrirem a apresentação) veem a recomendação somente leitura. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.xaml", SaveFormat.Xaml);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EPUB a XAML mediante programación: casos de uso" %}}
A conversão de Arquivos Epub para Formatos Xaml é Fundamental para Desbloquear o Potencial Pleno das Sua Visualizações.

A conversão dos arquivos Epub para formatos Xaml é necessária para desbloquear o potencial pleno de suas visualizações e capacidades de análise. Essa conversão permite:

**Cenários de Uso:**

*   **Design de Interface Usuário dinâmico**: Converter os arquivos Epub para criar interfaces de usuário interativas e dinâmicas para aplicativos móveis, permitindo navegação suave e experiências envolventes.
*   Desenvolvimento de conteúdo de aprendizado em linha (Elearning): Utilizar Xaml para desenvolver conteúdo de aprendizado envolvente, incluindo simulações interativas, provas e avaliações, melhorando a retenção do conhecimento e o desenvolvimento das habilidades.
*   Análise de imagens médicas: Converter os arquivos Epub para visualizar dados de imagem médica, como imagens MRI e CT, facilitando o planejamento de diagnóstico e tratamento.
*   Visualização de dados geoespaciais: Utilizar Xaml para criar visualizações interativas de dados geoespaciais, incluindo mapas, imagens satelitais e modelos tridimensionais, melhorando a compreensão de dados complexos.
*   Contagem de Histórias com Dados: Converter os arquivos Epub para criar histórias de dados interativas, incluindo gráficos interativos, diagramas e infográficos, aumentando o envolvimento do público e a compreensão.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}