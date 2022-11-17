---
title: Exportar PPSX para RTF no Andorid via Java
description: Converta PPSX para RTF em aplicativos móveis sem instalar nenhum software

family: total
platformtag: cpp
feature: conversion
informat: PPSX
outformat: RTF
otherformats: DOT DOTM DOTX DOCX TEXT FLATOPC ODT WORD WORDML DOCM DOC OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderize PPSX para RTF no Andorid via Java" h2="APIs de formato de arquivo para converter PPSX para RTF em aplicativos Android sem depender do Microsoft PowerPoint ou Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) permite a manipulação de formatos de arquivo dentro de aplicativos Android. Ao usar as APIs fornecidas no pacote, você pode automatizar o processo de conversão do PowerPoint PPSX para Word RTF em seus aplicativos.
Você pode converter seu rtfumento fornecido em duas etapas. Você pode usar [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) que é uma API do PowerPoint para aplicativos Android para renderizar PPSX em HTML. Depois disso, usando a API de processamento de rtfumentos [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) você pode converter o HTML para RTF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Renderização de PPSX para RTF no Android" %}}
1. Abra o arquivo PPSX usando a classe [Apresentação](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Converta PPSX em HTML usando [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) e defina Html como SaveFormat
3. Carregue o arquivo HTML convertido usando a classe [Rtfument](https://reference.aspose.com/words/java/com.aspose.words/Rtfument)
4. Salve o rtfumento no formato RTF usando o método [save](https://reference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String,int)) e defina Rtf como SalvarFormato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total for Android via Java diretamente do [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e instale [Aspose.Slides for Android via Java](https://rtfs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) e [Aspose.Words for Andorid via Java](https://rtfs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) em seu formulários.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPSX file
Presentation presentation = new Presentation("input.ppsx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Rtfument
Rtfument rtfument = new Rtfument("htmlOutput.html");
// save rtfument in RTF format
rtfument.save("output.rtf",SaveFormat.Rtf);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/ppsx-to-dot/" name="PPSX Para DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/ppsx-to-dotm/" name="PPSX Para DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/ppsx-to-dotx/" name="PPSX Para DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/ppsx-to-rtfx/" name="PPSX Para RTFX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/ppsx-to-text/" name="PPSX Para TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/ppsx-to-flatopc/" name="PPSX Para FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/ppsx-to-odt/" name="PPSX Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/ppsx-to-word/" name="PPSX Para WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/ppsx-to-wordml/" name="PPSX Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/ppsx-to-rtfm/" name="PPSX Para RTFM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/ppsx-to-rtf/" name="PPSX Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/ppsx-to-ott/" name="PPSX Para OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}