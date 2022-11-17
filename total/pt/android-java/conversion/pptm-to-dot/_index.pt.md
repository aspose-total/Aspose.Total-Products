---
title: Exportar PPTM para DOT no Andorid via Java
description: Converta PPTM para DOT em aplicativos móveis sem instalar nenhum software

family: total
platformtag: cpp
feature: conversion
informat: PPTM
outformat: DOT
otherformats: DOTX DOCX WORDML RTF TEXT DOTM DOCM OTT FLATOPC ODT WORD DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderize PPTM para DOT no Andorid via Java" h2="APIs de formato de arquivo para converter PPTM para DOT em aplicativos Android sem depender do Microsoft PowerPoint ou Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) permite a manipulação de formatos de arquivo dentro de aplicativos Android. Ao usar as APIs fornecidas no pacote, você pode automatizar o processo de conversão do PowerPoint PPTM para Word DOT em seus aplicativos.
Você pode converter seu dotumento fornecido em duas etapas. Você pode usar [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) que é uma API do PowerPoint para aplicativos Android para renderizar PPTM em HTML. Depois disso, usando a API de processamento de dotumentos [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) você pode converter o HTML para DOT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Renderização de PPTM para DOT no Android" %}}
1. Abra o arquivo PPTM usando a classe [Apresentação](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Converta PPTM em HTML usando [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) e defina Html como SaveFormat
3. Carregue o arquivo HTML convertido usando a classe [Dotument](https://reference.aspose.com/words/java/com.aspose.words/Dotument)
4. Salve o dotumento no formato DOT usando o método [save](https://reference.aspose.com/words/java/com.aspose.words/Dotument#save(java.lang.String,int)) e defina Dot como SalvarFormato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total for Android via Java diretamente do [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e instale [Aspose.Slides for Android via Java](https://dots.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) e [Aspose.Words for Andorid via Java](https://dots.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) em seu formulários.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPTM file
Presentation presentation = new Presentation("input.pptm");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Dotument
Dotument dotument = new Dotument("htmlOutput.html");
// save dotument in DOT format
dotument.save("output.dot",SaveFormat.Dot);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/pptm-to-dotx/" name="PPTM Para DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/pptm-to-dotx/" name="PPTM Para DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/pptm-to-wordml/" name="PPTM Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/pptm-to-rtf/" name="PPTM Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/pptm-to-text/" name="PPTM Para TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/pptm-to-dotm/" name="PPTM Para DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/pptm-to-dotm/" name="PPTM Para DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/pptm-to-ott/" name="PPTM Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/pptm-to-flatopc/" name="PPTM Para FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/pptm-to-odt/" name="PPTM Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/pptm-to-word/" name="PPTM Para WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/pptm-to-dot/" name="PPTM Para DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}