---
title: API C++ para converter POTX em ODT
description: Exporte POTX para ODT em seus aplicativos C++

family: total
platformtag: cpp
feature: conversion
informat: POTX
outformat: ODT
otherformats: DOTM DOTX DOC OTT RTF DOCM TEXT WORD DOCX DOT WORDML FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ para renderizar POTX para ODT" h2="Exporte POTX para ODT em aplicativos C++ sem dependências do Microsoft PowerPoint ou Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) é um pacote completo de bibliotecas de automação de formato de arquivo C++. Usando os recursos avançados das APIs disponíveis no pacote, podemos facilmente converter PowerPoint POTX em Word ODT. Para realizar a conversão, você pode primeiro usar a API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) para converter POTX em HTML. Depois disso, usando a API de processamento de texto rica em recursos [Aspose.Words for C++](https://products.aspose.com/words/cpp/), você pode converter o HTML para ODT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ para converter POTX em ODT" %}}
1. Carregue o arquivo POTX usando a referência de classe [Apresentação](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Renderize POTX para HTML usando a função de membro [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) e defina Html como SaveFormat
3. Carregue o arquivo HTML convertido usando a referência de classe [Odtument](https://reference.aspose.com/words/cpp/class/aspose.words.odtument)
4. Salve o odtumento no formato ODT usando a função de membro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.odtument#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total.Cpp``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.potx");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Odtument
System::SharedPtr<Odtument> odt = System::MakeObject<Odtument>(u"htmlOutput.html");
// save odtument in ODT format
odt->Save(u"output.odt"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/potx-to-dotm/" name="POTX Para DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/potx-to-dotx/" name="POTX Para DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/potx-to-odt/" name="POTX Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/potx-to-ott/" name="POTX Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/potx-to-rtf/" name="POTX Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/potx-to-odtm/" name="POTX Para ODTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/potx-to-text/" name="POTX Para TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/potx-to-word/" name="POTX Para WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/potx-to-odtx/" name="POTX Para ODTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/potx-to-dot/" name="POTX Para DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/potx-to-wordml/" name="POTX Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/potx-to-flatopc/" name="POTX Para FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}