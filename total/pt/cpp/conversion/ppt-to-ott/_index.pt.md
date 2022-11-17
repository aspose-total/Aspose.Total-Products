---
title: API C++ para converter PPT em OTT
description: Exporte PPT para OTT em seus aplicativos C++

family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: OTT
otherformats: RTF DOTX WORDML ODT WORD DOC DOCX DOT TEXT DOTM DOCM FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ para renderizar PPT para OTT" h2="Exporte PPT para OTT em aplicativos C++ sem dependências do Microsoft PowerPoint ou Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) é um pacote completo de bibliotecas de automação de formato de arquivo C++. Usando os recursos avançados das APIs disponíveis no pacote, podemos facilmente converter PowerPoint PPT em Word OTT. Para realizar a conversão, você pode primeiro usar a API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) para converter PPT em HTML. Depois disso, usando a API de processamento de texto rica em recursos [Aspose.Words for C++](https://products.aspose.com/words/cpp/), você pode converter o HTML para OTT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ para converter PPT em OTT" %}}
1. Carregue o arquivo PPT usando a referência de classe [Apresentação](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Renderize PPT para HTML usando a função de membro [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) e defina Html como SaveFormat
3. Carregue o arquivo HTML convertido usando a referência de classe [Ottument](https://reference.aspose.com/words/cpp/class/aspose.words.ottument)
4. Salve o ottumento no formato OTT usando a função de membro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.ottument#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total.Cpp``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPT file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.ppt");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Ottument
System::SharedPtr<Ottument> ott = System::MakeObject<Ottument>(u"htmlOutput.html");
// save ottument in OTT format
ott->Save(u"output.ott"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/ppt-to-rtf/" name="PPT Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/ppt-to-dotx/" name="PPT Para DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/ppt-to-wordml/" name="PPT Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/ppt-to-odt/" name="PPT Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/ppt-to-word/" name="PPT Para WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/ppt-to-ott/" name="PPT Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/ppt-to-ottx/" name="PPT Para OTTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/ppt-to-dot/" name="PPT Para DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/ppt-to-text/" name="PPT Para TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/ppt-to-dotm/" name="PPT Para DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/ppt-to-ottm/" name="PPT Para OTTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/ppt-to-flatopc/" name="PPT Para FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}