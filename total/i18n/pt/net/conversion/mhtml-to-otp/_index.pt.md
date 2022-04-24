---
title: Exportar MHTML para OTP via API C#
description: API .NET para converter MHTML em OTP sem usar o Microsoft Word
url: /pt/net/conversion/mhtml-to-otp/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: OTP
otherformats: POT PPS PPTM XAML OTP PPSX POTX PPSM PPT SWF POWERPOINT POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar MHTML para OTP via .NET" h2="API .NET para exportar MHTML para OTP no Windows, macOS e Linux sem usar o Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando um pacote de APIs poderosas de automação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) você pode facilmente renderizar MHTML para OTP em duas etapas simples. Usando a API de processamento de PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), você pode transformar o formato de arquivo MHTML em PPTX. Depois disso, usando a API de processamento de apresentação [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), você pode converter PPTX para OTP.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para converter MHTML em OTP" %}}
1. Abra o arquivo MHTML usando a classe [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Converta MHTML para PPTX usando o método [Salvar](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Carregue o arquivo PPTX usando a classe [Apresentação](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
4. Salve o documento no formato OTP usando o método [Save](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) e defina `Otp` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("input.mhtml");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.otp", SaveFormat.Otp);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenha metadados XMP do arquivo MHTML via .NET" %}}
Ao converter MHTML para OTP, você pode precisar de informações extras de metadados XMP para priorizar seu processo de conversão em lote. Por exemplo, você pode obter e classificar seus documentos de conversão com base na data de criação e processar os documentos de acordo. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) permite que você acesse os metadados XMP de um arquivo MHTML. Para obter os metadados de um arquivo MHTML, você pode criar um objeto [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) e abrir o arquivo MHTML de entrada. Depois disso, você pode obter os metadados do arquivo usando a propriedade [Metadados](https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
```cs

Document doc = new Document("input.mhtml");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Criar arquivo OTP somente leitura via .NET" %}}
Ao usar a API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), você pode aprimorar ainda mais os recursos do seu aplicativo de conversão. Um dos recursos pode ser criar seu arquivo de saída somente leitura para aumentar a segurança. A API permite que você defina seu arquivo OTP como somente leitura, o que significa que os usuários (depois de abrirem a apresentação) veem a recomendação somente leitura. 
```cs
```cs
Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.otp", SaveFormat.Otp);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras opções de conversão" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/mhtml-to-pot/" name="MHTML Para POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/mhtml-to-ppsx/" name="MHTML Para PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/mhtml-to-swf/" name="MHTML Para SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/mhtml-to-powerpoint/" name="MHTML Para POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/mhtml-to-otp/" name="MHTML Para OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/mhtml-to-potm/" name="MHTML Para POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/mhtml-to-ppt/" name="MHTML Para PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/mhtml-to-pps/" name="MHTML Para PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/mhtml-to-potx/" name="MHTML Para POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/mhtml-to-xaml/" name="MHTML Para XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/mhtml-to-ppsm/" name="MHTML Para PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/mhtml-to-pptm/" name="MHTML Para PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}