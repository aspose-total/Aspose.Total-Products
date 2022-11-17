---
title: Exportar POTM para DOT no Andorid via Java
description: Converta POTM para DOT em aplicativos móveis sem instalar nenhum software

family: total
platformtag: cpp
feature: conversion
informat: POTM
outformat: DOT
otherformats: FLATOPC DOTM RTF WORDML OTT ODT DOCM DOTX DOCX WORD DOC TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderize POTM para DOT no Andorid via Java" h2="APIs de formato de arquivo para converter POTM para DOT em aplicativos Android sem depender do Microsoft PowerPoint ou Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) permite a manipulação de formatos de arquivo dentro de aplicativos Android. Ao usar as APIs fornecidas no pacote, você pode automatizar o processo de conversão do PowerPoint POTM para Word DOT em seus aplicativos.
Você pode converter seu dotumento fornecido em duas etapas. Você pode usar [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) que é uma API do PowerPoint para aplicativos Android para renderizar POTM em HTML. Depois disso, usando a API de processamento de dotumentos [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) você pode converter o HTML para DOT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Renderização de POTM para DOT no Android" %}}
1. Abra o arquivo POTM usando a classe [Apresentação](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Converta POTM em HTML usando [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) e defina Html como SaveFormat
3. Carregue o arquivo HTML convertido usando a classe [Dotument](https://reference.aspose.com/words/java/com.aspose.words/Dotument)
4. Salve o dotumento no formato DOT usando o método [save](https://reference.aspose.com/words/java/com.aspose.words/Dotument#save(java.lang.String,int)) e defina Dot como SalvarFormato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total for Android via Java diretamente do [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e instale [Aspose.Slides for Android via Java](https://dots.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) e [Aspose.Words for Andorid via Java](https://dots.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) em seu formulários.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POTM file
Presentation presentation = new Presentation("input.potm");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/potm-to-flatopc/" name="POTM Para FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/potm-to-dotm/" name="POTM Para DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/potm-to-rtf/" name="POTM Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/potm-to-wordml/" name="POTM Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/potm-to-ott/" name="POTM Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/potm-to-odt/" name="POTM Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/potm-to-dotm/" name="POTM Para DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/potm-to-dotx/" name="POTM Para DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/potm-to-dotx/" name="POTM Para DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/potm-to-word/" name="POTM Para WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/potm-to-dot/" name="POTM Para DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/potm-to-text/" name="POTM Para TEXT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}