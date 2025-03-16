---
title: Exportar PS para POWERPOINT via API C#
description: API .NET para converter PS em POWERPOINT sem usar o Microsoft Word
url_ignore: /pt/net/conversion/ps-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: POWERPOINT
otherformats: SWF PPTM XAML OTP PPSX POT PPT PPSM POTM PPS POTX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar PS para POWERPOINT via .NET" h2="API .NET para exportar PS para POWERPOINT no Windows, macOS e Linux sem usar o Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando um pacote de APIs poderosas de automação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) você pode facilmente renderizar PS para POWERPOINT em duas etapas simples. Usando a API de processamento de PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), você pode transformar o formato de arquivo PS em PPTX. Depois disso, usando a API de processamento de apresentação [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), você pode converter PPTX para POWERPOINT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para converter PS em POWERPOINT" %}}
1. Abra o arquivo PS usando a classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Converta PS para PPTX usando o método [Salvar](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Carregue o arquivo PPTX usando a classe [Apresentação](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Salve o documento no formato POWERPOINT usando o método [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) e defina `Powerpoint` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenha metadados XMP do arquivo PS via .NET" %}}
Ao converter PS para POWERPOINT, você pode precisar de informações extras de metadados XMP para priorizar seu processo de conversão em lote. Por exemplo, você pode obter e classificar seus documentos de conversão com base na data de criação e processar os documentos de acordo. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) permite que você acesse os metadados XMP de um arquivo PS. Para obter os metadados de um arquivo PS, você pode criar um objeto [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) e abrir o arquivo PS de entrada. Depois disso, você pode obter os metadados do arquivo usando a propriedade [Metadados](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Criar arquivo POWERPOINT somente leitura via .NET" %}}
Ao usar a API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), você pode aprimorar ainda mais os recursos do seu aplicativo de conversão. Um dos recursos pode ser criar seu arquivo de saída somente leitura para aumentar a segurança. A API permite que você defina seu arquivo POWERPOINT como somente leitura, o que significa que os usuários (depois de abrirem a apresentação) veem a recomendação somente leitura. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;
// call save method while passing SaveFormat.Ppt
presentation.Save("output.ppt", SaveFormat.Ppt);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos PS a POWERPOINT mediante programación: casos de uso" %}}
Arquivos em formato PDF (Portable Document Format) são ideais para armazenar documentos com layouts precisos, tornando-os perfeitos para criar relatórios profissionais, folhetos e apresentações. No entanto, ao trabalhar com conteúdo dinâmico, Microsoft PowerPoint se torna uma ferramenta essencial para a visualização de dados e análise.

A conversão de arquivos PDF em formatos do PowerPoint é necessária para desbloquear a potência completa do design de apresentação e das capacidades de colaboração. Esta conversão permite que você:

**Casos de Uso:**

*   **Presentações de Negócios**: Converter arquivos PDF para criar apresentações de negócios envolventes, exibindo produtos, serviços ou notícias da empresa.
*   **Materiais de Marketing**: Usar o PowerPoint para visualizar materiais de marketing, como folhetos de produto, folhas de venda e anúncios.
*   **Conteúdo Educativo**: Converter arquivos PDF para criar conteúdo educativo interativo, incluindo aulas, apresentações em slides e tutoriais.
*   **Colateral de Vendas**: Usar o PowerPoint para projetar material de vendas profissional, como decks de pitch, propostas e apresentações.
*   **Materiais de Eventos**: Converter arquivos PDF para criar materiais impressionantes de eventos, como programas de conferência, agendas e folhetos de mão.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}