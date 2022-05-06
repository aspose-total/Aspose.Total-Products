---
title: API C# para exportar XPS para DOT
description: Converter XPS para DOT sem usar o Microsoft Word
url_ignore: /pt/net/conversion/xps-to-dot/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: DOT
otherformats: WORDML PCL DOTX MARKDOWN PS XAMLFLOW ODT FLATOPC OTT DOT RTF DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar XPS para DOT via .NET" h2="API .NET para exportar XPS para DOT no Windows, macOS e Linux sem usar o Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) é uma API poderosa para adicionar recursos de manipulação e conversão de documentos dentro de seu aplicativo .NET. Usando a API avançada de processamento de PDF [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/), você pode converter o formato de arquivo XPS para DOC. Depois disso, usando a poderosa API de processamento de documentos [Aspose.Words for .NET](https://products.aspose.com/words/net/), você pode renderizar DOC para DOT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# para converter XPS em DOT" %}}
1. Abra o arquivo XPS usando a classe [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Converta XPS para Doc usando o método [Salvar](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Carregue o arquivo Doc usando a classe [Document](https://apireference.aspose.com/words/net/aspose.words/document) de Aspose.Words
4. Salve o documento no formato DOT usando o método [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) e defina Dot como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.xps");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.dot", SaveFormat.Dot);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Descriptografar o arquivo XPS usando a senha do proprietário via .NET" %}}
Antes de converter XPS para DOT, se você quiser descriptografar seu documento, pode fazê-lo usando a API. Para descriptografar o arquivo PDF, primeiro você precisa criar um objeto [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) e abrir o XPS usando a senha do proprietário. Depois disso, você precisa chamar o método [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) do objeto Document. Por fim, salve o arquivo atualizado usando o método Save do objeto Document.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.xps", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Criar arquivo DOT somente leitura via .NET" %}}
Para proteger seu DOT da edição e impedir que outras pessoas editem informações confidenciais em seu documento, você também pode definir a proteção do documento usando a API. Você pode limitar a capacidade de editar um documento e permitir apenas determinadas ações com ele. Isso pode ser feito usando a API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Ele permite que você controle a maneira como restringe o conteúdo usando o parâmetro de enumeração [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype). Você pode definir seu documento como somente leitura usando as seguintes linhas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dot", SaveFormat.Dot);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras opções de conversão" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xps-to-ott/" name="XPS Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xps-to-mhtml/" name="XPS Para MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xps-to-wordml/" name="XPS Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xps-to-dot/" name="XPS Para DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xps-to-odt/" name="XPS Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xps-to-rtf/" name="XPS Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xps-to-ps/" name="XPS Para PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xps-to-flatopc/" name="XPS Para FLAParaPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xps-to-pcl/" name="XPS Para PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xps-to-markdown/" name="XPS Para MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xps-to-xamlflow/" name="XPS Para XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xps-to-dotx/" name="XPS Para DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}