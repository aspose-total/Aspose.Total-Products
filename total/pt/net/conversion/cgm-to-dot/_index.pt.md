---
title: API C# para exportar CGM para DOT
description: Converter CGM para DOT sem usar o Microsoft Word
url_ignore: /pt/net/conversion/cgm-to-dot/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DOT
otherformats: PCL FLATOPC OTT WORDML ODT DOT RTF MARKDOWN XAMLFLOW DOTX PS MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar CGM para DOT via .NET" h2="API .NET para exportar CGM para DOT no Windows, macOS e Linux sem usar o Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) é uma API poderosa para adicionar recursos de manipulação e conversão de documentos dentro de seu aplicativo .NET. Usando a API avançada de processamento de PDF [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/), você pode converter o formato de arquivo CGM para DOC. Depois disso, usando a poderosa API de processamento de documentos [Aspose.Words for .NET](https://products.aspose.com/words/net/), você pode renderizar DOC para DOT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# para converter CGM em DOT" %}}
1. Abra o arquivo CGM usando a classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Converta CGM para Doc usando o método [Salvar](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Carregue o arquivo Doc usando a classe [Document](https://reference.aspose.com/words/net/aspose.words/document) de Aspose.Words
4. Salve o documento no formato DOT usando o método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) e defina Dot como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Descriptografar o arquivo CGM usando a senha do proprietário via .NET" %}}
Antes de converter CGM para DOT, se você quiser descriptografar seu documento, pode fazê-lo usando a API. Para descriptografar o arquivo PDF, primeiro você precisa criar um objeto [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) e abrir o CGM usando a senha do proprietário. Depois disso, você precisa chamar o método [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) do objeto Document. Por fim, salve o arquivo atualizado usando o método Save do objeto Document.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Criar arquivo DOT somente leitura via .NET" %}}
Para proteger seu DOT da edição e impedir que outras pessoas editem informações confidenciais em seu documento, você também pode definir a proteção do documento usando a API. Você pode limitar a capacidade de editar um documento e permitir apenas determinadas ações com ele. Isso pode ser feito usando a API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Ele permite que você controle a maneira como restringe o conteúdo usando o parâmetro de enumeração [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). Você pode definir seu documento como somente leitura usando as seguintes linhas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dot", SaveFormat.Dot);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos CGM a DOT mediante programación: casos de uso" %}}
A conversão de arquivos CGM para formatos DOT é necessária para desbloquear o potencial máximo da sua capacidade de visualização gráfica e layout. Essa conversão permite que você:

**Cenarios de Uso:**

*   **Visualização Gráfica**: Converter arquivos CGM para criar diagramas, fluxogramas e mapas processuais utilizando formatos DOT, ideais para ilustrar relações complexas entre pontos de dados.
*   **Otimização do Layout**: Utilizar formatos DOT para otimizar a disposição de nó e aresta nos seus gráficos, garantindo leitura máxima e eficiência.
*   **Cartografia do Processo Negociacional**: Converter arquivos CGM para criar mapas detalhados de processos negócios, destacando fluxos, tarefas e pontos de decisão.
*   **Diagramas Técnicos**: Utilizar formatos DOT para gerar diagramas técnicos, como diagramas de classes UML, diagramas de fluxo de dados e modelos ER.
*   **Hierarquia Gráfica e Estrutura**: Converter arquivos CGM para estabelecer hierarquias claras e estruturas nos seus gráficos, facilitando navegação fácil e entendimento.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}