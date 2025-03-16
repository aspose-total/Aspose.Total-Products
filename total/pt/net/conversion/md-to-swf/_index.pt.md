---
title: Exportar MD para SWF via API C#
description: API .NET para converter MD em SWF sem usar o Microsoft Word
url_ignore: /pt/net/conversion/md-to-swf/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: SWF
otherformats: PPS PPSM PPSX OTP SWF POT PPTM POTX XAML POWERPOINT PPT POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar MD para SWF via .NET" h2="API .NET para exportar MD para SWF no Windows, macOS e Linux sem usar o Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando um pacote de APIs poderosas de automação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) você pode facilmente renderizar MD para SWF em duas etapas simples. Usando a API de processamento de PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), você pode transformar o formato de arquivo MD em PPTX. Depois disso, usando a API de processamento de apresentação [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), você pode converter PPTX para SWF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para converter MD em SWF" %}}
1. Abra o arquivo MD usando a classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Converta MD para PPTX usando o método [Salvar](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Carregue o arquivo PPTX usando a classe [Apresentação](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Salve o documento no formato SWF usando o método [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) e defina `Swf` como SaveFormat
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
Ao converter MD para SWF, você pode precisar de informações extras de metadados XMP para priorizar seu processo de conversão em lote. Por exemplo, você pode obter e classificar seus documentos de conversão com base na data de criação e processar os documentos de acordo. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) permite que você acesse os metadados XMP de um arquivo MD. Para obter os metadados de um arquivo MD, você pode criar um objeto [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) e abrir o arquivo MD de entrada. Depois disso, você pode obter os metadados do arquivo usando a propriedade [Metadados](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "decrypt-md-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Criar arquivo SWF somente leitura via .NET" %}}
Ao usar a API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), você pode aprimorar ainda mais os recursos do seu aplicativo de conversão. Um dos recursos pode ser criar seu arquivo de saída somente leitura para aumentar a segurança. A API permite que você defina seu arquivo SWF como somente leitura, o que significa que os usuários (depois de abrirem a apresentação) veem a recomendação somente leitura. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.swf", SaveFormat.Swf);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos MD a SWF mediante programación: casos de uso" %}}
A conversão de Arquivos do Tipo Markdown para o Formato SWF é Necessária para Desbloquear a Potencialidade Integridade da Sua Capacidade de Presentação.

Essa conversão permite que você:

**Usos Casuais:**

*   **Presentações Corporativas**: Converta arquivos de Markdown para criar apresentações envolventes e interativas, perfeitas para eventos corporativos, reuniões e conferências.
*   **Criação de Conteúdo de Aprendizado E-Learning**: Use o formato SWF para desenvolver módulos de aprendizado e simulações imersivas, tutoriais interativos que aprimoram a retenção do conhecimento e o desenvolvimento de habilidades.
*   **Desenvolvimento de Aplicativos Móveis**: Converta arquivos de Markdown para o formato SWF para criar aplicativos móveis com elementos interativos, animações e conteúdo dinâmico.
*   **Experiências de Jogo e Experiências Interativas**: Crie experiências envolventes de jogo e interativas usando o formato SWF, permitindo aos jogadores explorar ambientes 2D e 3D de forma imersiva.
*   **Publicação Digital e Revistas**: Converta arquivos de Markdown para o formato SWF para criar revistas digitais interativas, cómics gráficos e gráficos de quadrinhos que se animam com efeitos sonoros, gráficos de movimento.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}