---
title: API C# para exportar PS para PCL
description: Converter PS para PCL sem usar o Microsoft Word
url_ignore: /pt/net/conversion/ps-to-pcl/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: PCL
otherformats: MHTML WORDML MARKDOWN DOTM FLATOPC XAMLFLOW ODT DOTX RTF PCL OTT DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar PS para PCL via .NET" h2="API .NET para exportar PS para PCL no Windows, macOS e Linux sem usar o Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) é uma API poderosa para adicionar recursos de manipulação e conversão de documentos dentro de seu aplicativo .NET. Usando a API avançada de processamento de PDF [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/), você pode converter o formato de arquivo PS para DOC. Depois disso, usando a poderosa API de processamento de documentos [Aspose.Words for .NET](https://products.aspose.com/words/net/), você pode renderizar DOC para PCL.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# para converter PS em PCL" %}}
1. Abra o arquivo PS usando a classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Converta PS para Doc usando o método [Salvar](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Carregue o arquivo Doc usando a classe [Document](https://reference.aspose.com/words/net/aspose.words/document) de Aspose.Words
4. Salve o documento no formato PCL usando o método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) e defina Pcl como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Descriptografar o arquivo PS usando a senha do proprietário via .NET" %}}
Antes de converter PS para PCL, se você quiser descriptografar seu documento, pode fazê-lo usando a API. Para descriptografar o arquivo PDF, primeiro você precisa criar um objeto [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) e abrir o PS usando a senha do proprietário. Depois disso, você precisa chamar o método [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) do objeto Document. Por fim, salve o arquivo atualizado usando o método Save do objeto Document.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Criar arquivo PCL somente leitura via .NET" %}}
Para proteger seu PCL da edição e impedir que outras pessoas editem informações confidenciais em seu documento, você também pode definir a proteção do documento usando a API. Você pode limitar a capacidade de editar um documento e permitir apenas determinadas ações com ele. Isso pode ser feito usando a API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Ele permite que você controle a maneira como restringe o conteúdo usando o parâmetro de enumeração [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). Você pode definir seu documento como somente leitura usando as seguintes linhas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pcl", SaveFormat.Pcl);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos PS a PCL mediante programación: casos de uso" %}}
Arquivos PS (PostScript) são usados para armazenar informações de gráficos raster, tornando-os ideais para criar imagens e ilustrações complexas. No entanto, quando trabalhamos com dados de gráficos vetoriais, arquivos EPS (Encapsulated PostScript) se tornam essenciais para o controle preciso sobre a layout e design.

A conversão de arquivos PS para formatos EPS é necessária para desbloquear as capacidades do seu potencial de design. Essa conversão permite que você:

**Cenários de Uso:**

*   **Design de Logotipos e Marcas**: Converter arquivos PS para criar logotipos vetoriais, manter escalabilidade e garantir consistência em diferentes meios.
*   **Ilustração Técnica e Documentação**: Usar EPS para criar ilustrações detalhadas, anotar projetos complexos e fornecer informações técnicas precisas.
*   **Design Gráfico e Publicação**: Converter arquivos PS para criar gráficos de alta qualidade, produzir publicações profissionais e atender aos padrões de design.
*   **Visualização de Engenharia e Arquitetura**: Usar EPS para visualizar modelos complexos, simular cenários reais e comunicar conceitos de design de forma eficaz.
*   **Visualização de Dados e Presentação**: Converter arquivos PS para criar visuais dinâmicos, apresentar dados complexos de maneira atraente e facilitar a compreensão de informações técnicas.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}