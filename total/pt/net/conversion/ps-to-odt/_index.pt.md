---
title: API C# para exportar PS para ODT
description: Converter PS para ODT sem usar o Microsoft Word
url_ignore: /pt/net/conversion/ps-to-odt/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: ODT
otherformats: RTF WORDML DOTM ODT OTT DOTX XAMLFLOW FLATOPC DOT MHTML PCL MARKDOWN
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar PS para ODT via .NET" h2="API .NET para exportar PS para ODT no Windows, macOS e Linux sem usar o Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) é uma API poderosa para adicionar recursos de manipulação e conversão de documentos dentro de seu aplicativo .NET. Usando a API avançada de processamento de PDF [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/), você pode converter o formato de arquivo PS para DOC. Depois disso, usando a poderosa API de processamento de documentos [Aspose.Words for .NET](https://products.aspose.com/words/net/), você pode renderizar DOC para ODT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# para converter PS em ODT" %}}
1. Abra o arquivo PS usando a classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Converta PS para Doc usando o método [Salvar](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Carregue o arquivo Doc usando a classe [Document](https://reference.aspose.com/words/net/aspose.words/document) de Aspose.Words
4. Salve o documento no formato ODT usando o método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) e defina Odt como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.ps");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.odt", SaveFormat.Odt);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Descriptografar o arquivo PS usando a senha do proprietário via .NET" %}}
Antes de converter PS para ODT, se você quiser descriptografar seu documento, pode fazê-lo usando a API. Para descriptografar o arquivo PDF, primeiro você precisa criar um objeto [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) e abrir o PS usando a senha do proprietário. Depois disso, você precisa chamar o método [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) do objeto Document. Por fim, salve o arquivo atualizado usando o método Save do objeto Document.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.ps", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Criar arquivo ODT somente leitura via .NET" %}}
Para proteger seu ODT da edição e impedir que outras pessoas editem informações confidenciais em seu documento, você também pode definir a proteção do documento usando a API. Você pode limitar a capacidade de editar um documento e permitir apenas determinadas ações com ele. Isso pode ser feito usando a API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Ele permite que você controle a maneira como restringe o conteúdo usando o parâmetro de enumeração [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). Você pode definir seu documento como somente leitura usando as seguintes linhas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.odt", SaveFormat.Odt);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras opções de conversão" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/ps-to-ott/" name="PS Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/ps-to-mhtml/" name="PS Para MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/ps-to-wordml/" name="PS Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/ps-to-dot/" name="PS Para DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/ps-to-odt/" name="PS Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/ps-to-rtf/" name="PS Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/ps-to-ps/" name="PS Para PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/ps-to-flatopc/" name="PS Para FLAParaPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/ps-to-pcl/" name="PS Para PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/ps-to-markdown/" name="PS Para MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/ps-to-xamlflow/" name="PS Para XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/ps-to-dotx/" name="PS Para DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}