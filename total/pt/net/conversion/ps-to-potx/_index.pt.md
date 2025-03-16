---
title: Exportar PS para POTX via API C#
description: API .NET para converter PS em POTX sem usar o Microsoft Word
url_ignore: /pt/net/conversion/ps-to-potx/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: POTX
otherformats: PPS SWF PPTM XAML OTP PPSX POT POWERPOINT PPSM PPT POTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar PS para POTX via .NET" h2="API .NET para exportar PS para POTX no Windows, macOS e Linux sem usar o Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando um pacote de APIs poderosas de automação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) você pode facilmente renderizar PS para POTX em duas etapas simples. Usando a API de processamento de PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), você pode transformar o formato de arquivo PS em PPTX. Depois disso, usando a API de processamento de apresentação [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), você pode converter PPTX para POTX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para converter PS em POTX" %}}
1. Abra o arquivo PS usando a classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Converta PS para PPTX usando o método [Salvar](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Carregue o arquivo PPTX usando a classe [Apresentação](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Salve o documento no formato POTX usando o método [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) e defina `Potx` como SaveFormat
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
Ao converter PS para POTX, você pode precisar de informações extras de metadados XMP para priorizar seu processo de conversão em lote. Por exemplo, você pode obter e classificar seus documentos de conversão com base na data de criação e processar os documentos de acordo. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) permite que você acesse os metadados XMP de um arquivo PS. Para obter os metadados de um arquivo PS, você pode criar um objeto [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) e abrir o arquivo PS de entrada. Depois disso, você pode obter os metadados do arquivo usando a propriedade [Metadados](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
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

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos PS a POTX mediante programación: casos de uso" %}}
Arquivos em formato de documento portátil (PS - Portable Document Format) são usados para armazenar informações de layout, tornando-os ideais para criar documentos estáticos como folhetos, cartazes e apresentações. No entanto, quando se trabalha com dados dinâmicos, as apresentações do Microsoft Office como a PowerPoint se tornam essenciais para a visualização e análise de dados.

A conversão de arquivos PS para formatos da PowerPoint é necessária para desbloquear o máximo potencial das suas capacidades de apresentação e análise. Essa conversão permite que você:

**Usos Casuais:**

*   **Otimização de Presentações de Venda**: Converter arquivos PS para otimizar as presentações de venda, organizar conteúdo de forma mais eficiente e criar narrativas envolventes.
*   **Materiais de Marketing de Evento**: Usar a PowerPoint para visualizar materiais de marketing de evento, simular experiências do público e validar conceitos de design.
*   **Criação de Guias Técnicos Interativos**: Converter arquivos PS para criar guias técnicos interativos, simular experiências de uso do usuário e validar conteúdo documental.
*   **Design de Apresentações Corporativas**: Usar a PowerPoint para projetar apresentações corporativas, otimizar layout e formatoização e aprimorar impacto visual geral.
*   **Visualização de Dados para Stakeholders**: Converter arquivos PS para criar visuais de dados envolventes para stakeholders, facilitando decisões mais informadas e comunicação.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}