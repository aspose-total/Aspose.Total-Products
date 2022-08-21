---
title: API C++ para converter PPTM em TEXT
description: Exporte PPTM para TEXT em seus aplicativos C++
url: /pt/cpp/conversion/pptm-to-text/
family: total
platformtag: cpp
feature: conversion
informat: PPTM
outformat: TEXT
otherformats: FLATOPC DOCX DOTM DOTX ODT WORD DOCM OTT RTF WORDML DOC DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ para renderizar PPTM para TEXT" h2="Exporte PPTM para TEXT em aplicativos C++ sem dependências do Microsoft PowerPoint ou Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) é um pacote completo de bibliotecas de automação de formato de arquivo C++. Usando os recursos avançados das APIs disponíveis no pacote, podemos facilmente converter PowerPoint PPTM em Word TEXT. Para realizar a conversão, você pode primeiro usar a API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) para converter PPTM em HTML. Depois disso, usando a API de processamento de texto rica em recursos [Aspose.Words for C++](https://products.aspose.com/words/cpp/), você pode converter o HTML para TEXT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ para converter PPTM em TEXT" %}}
1. Carregue o arquivo PPTM usando a referência de classe [Apresentação](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Renderize PPTM para HTML usando a função de membro [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) e defina Html como SaveFormat
3. Carregue o arquivo HTML convertido usando a referência de classe [Textument](https://reference.aspose.com/words/cpp/class/aspose.words.textument)
4. Salve o textumento no formato TEXT usando a função de membro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.textument#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total.Cpp``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPTM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pptm");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Textument
System::SharedPtr<Textument> text = System::MakeObject<Textument>(u"htmlOutput.html");
// save textument in TEXT format
text->Save(u"output.text"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pptm-to-flatopc/" name="PPTM Para FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pptm-to-textx/" name="PPTM Para TEXTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pptm-to-dotm/" name="PPTM Para DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pptm-to-dotx/" name="PPTM Para DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pptm-to-odt/" name="PPTM Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pptm-to-word/" name="PPTM Para WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pptm-to-textm/" name="PPTM Para TEXTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pptm-to-ott/" name="PPTM Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pptm-to-rtf/" name="PPTM Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pptm-to-wordml/" name="PPTM Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pptm-to-text/" name="PPTM Para TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pptm-to-dot/" name="PPTM Para DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}