---
title: Exportar CGM para PPS via API C#
description: API .NET para converter CGM em PPS sem usar o Microsoft Word
url_ignore: /pt/net/conversion/cgm-to-pps/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PPS
otherformats: PPSM PPS PPTM POWERPOINT PPT PPSX XAML POTM POTX SWF OTP POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar CGM para PPS via .NET" h2="API .NET para exportar CGM para PPS no Windows, macOS e Linux sem usar o Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando um pacote de APIs poderosas de automação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) você pode facilmente renderizar CGM para PPS em duas etapas simples. Usando a API de processamento de PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), você pode transformar o formato de arquivo CGM em PPTX. Depois disso, usando a API de processamento de apresentação [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), você pode converter PPTX para PPS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para converter CGM em PPS" %}}
1. Abra o arquivo CGM usando a classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Converta CGM para PPTX usando o método [Salvar](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Carregue o arquivo PPTX usando a classe [Apresentação](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Salve o documento no formato PPS usando o método [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) e defina `Pps` como SaveFormat
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
Ao converter CGM para PPS, você pode precisar de informações extras de metadados XMP para priorizar seu processo de conversão em lote. Por exemplo, você pode obter e classificar seus documentos de conversão com base na data de criação e processar os documentos de acordo. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) permite que você acesse os metadados XMP de um arquivo CGM. Para obter os metadados de um arquivo CGM, você pode criar um objeto [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) e abrir o arquivo CGM de entrada. Depois disso, você pode obter os metadados do arquivo usando a propriedade [Metadados](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Criar arquivo PPS somente leitura via .NET" %}}
Ao usar a API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), você pode aprimorar ainda mais os recursos do seu aplicativo de conversão. Um dos recursos pode ser criar seu arquivo de saída somente leitura para aumentar a segurança. A API permite que você defina seu arquivo PPS como somente leitura, o que significa que os usuários (depois de abrirem a apresentação) veem a recomendação somente leitura. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.pps", SaveFormat.Pps);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos CGM a PPS mediante programación: casos de uso" %}}
Arquivos CGM (Metafile de Gráficos Computadorizados) são usados para armazenar informações de gráficos vetoriais, tornando-os ideais para criar gráficos estáticos e ilustrações. No entanto, quando trabalhamos com dados dinâmicos, planilhas como o Excel se tornam essenciais para a visualização e análise de dados.

A conversão de arquivos CGM em formatos PPS (Portátil de Presentação) é necessária para desbloquear o potencial máximo das suas apresentações e visualizações. Essa conversão permite que você:

**Caso de Uso:**

*   **Design de Apresentação:** Converter arquivos CGM para criar slides profissionais, animações e transições atraentes para audiências engajadas.
*   **Treinamento e Educação:** Usar PPS para criar materiais de treinamento interativos, simulações e tutoriais que melhoram os resultados de aprendizado.
*   **Materiais de Venda e Marketing:** Converter arquivos CGM para criar collateral vendável persuasivo, demonstrações de produtos e materiais de marketing.
*   **Comunicações Corporativas:** Usar PPS para criar comunicações internas, relatórios e infográficos para melhorar a compartilhamento de informações.
*   **Visualização de Eventos e Exposições:** Converter arquivos CGM para criar gráficos atraentes de eventos, projetos de exibição e exposições comerciais.

Converter seus arquivos CGM para PPS permite que você aproveite as últimas características do software de apresentação mais avançadas, incluindo animações, transições e efeitos. Isso garante que seu conteúdo visual seja exibido em sua melhor forma, tornando-o um passo essencial para qualquer projeto exigente apresentações profissionais.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}