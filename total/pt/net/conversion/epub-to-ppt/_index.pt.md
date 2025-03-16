---
title: Exportar EPUB para PPT via API C#
description: API .NET para converter EPUB em PPT sem usar o Microsoft Word
url_ignore: /pt/net/conversion/epub-to-ppt/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PPT
otherformats: PPT PPS PPTM OTP POTM PPSX POTX XAML POT PPSM SWF POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar EPUB para PPT via .NET" h2="API .NET para exportar EPUB para PPT no Windows, macOS e Linux sem usar o Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando um pacote de APIs poderosas de automação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) você pode facilmente renderizar EPUB para PPT em duas etapas simples. Usando a API de processamento de PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), você pode transformar o formato de arquivo EPUB em PPTX. Depois disso, usando a API de processamento de apresentação [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), você pode converter PPTX para PPT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para converter EPUB em PPT" %}}
1. Abra o arquivo EPUB usando a classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Converta EPUB para PPTX usando o método [Salvar](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Carregue o arquivo PPTX usando a classe [Apresentação](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Salve o documento no formato PPT usando o método [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) e defina `Ppt` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "convert-epub-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenha metadados XMP do arquivo EPUB via .NET" %}}
Ao converter EPUB para PPT, você pode precisar de informações extras de metadados XMP para priorizar seu processo de conversão em lote. Por exemplo, você pode obter e classificar seus documentos de conversão com base na data de criação e processar os documentos de acordo. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) permite que você acesse os metadados XMP de um arquivo EPUB. Para obter os metadados de um arquivo EPUB, você pode criar um objeto [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) e abrir o arquivo EPUB de entrada. Depois disso, você pode obter os metadados do arquivo usando a propriedade [Metadados](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
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

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EPUB a PPT mediante programación: casos de uso" %}}
Arquivos EPUB (Publicação Eletrônica) são usados para armazenar conteúdo digital, tornando-os ideais para criar livros eletrônicos, revistas e outros tipos de publicações digitais. No entanto, quando se apresenta dados ou apresentações de forma visual, formatos como PowerPoint se tornam essenciais para envolver públicos e comunicar informações complexas.

A conversão de arquivos EPUB para formatos de PowerPoint é necessária para desbloquear a plena capacidade das suas habilidades de apresentação visual e comunicação. Essa conversão permite que você:

*   **Apresentar Encontrados de Pesquisa**: Converter arquivos EPUB para criar apresentações visuais atraentes, destacando os principais achados de pesquisa e compartilhando-os com colegas acadêmicos ou profissionais.
*   Comunicação Corporativa: Use PowerPoint para apresentar notícias da empresa, atualizações e anúncios em um formato atraente e acessível, garantindo comunicação eficaz interna.
*   **Conteúdo Digital de História**: Converter arquivos EPUB para criar histórias digitais interativas e imersivas, utilizando elementos multimídia e animações para capturar a atenção do público.
*   Materiais de Cursos Online: Converter arquivos EPUB para apresentações PowerPoint, tornando os materiais curriculares complexos mais envolventes e fáceis de digerir para estudantes.
*   Promoção de Eventos e Marketing: Use PowerPoint para projetar materiais promocionais atraentes, como pós-ers, folhetos e gráficos de mídia social, para atrair comparecentes e gerar movimento em torno dos eventos.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}