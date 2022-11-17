---
title: Exportar PPSX para DOC no Andorid via Java
description: Converta PPSX para DOC em aplicativos móveis sem instalar nenhum software

family: total
platformtag: cpp
feature: conversion
informat: PPSX
outformat: DOC
otherformats: ODT FLATOPC DOCM RTF DOTX WORDML DOT DOCX OTT DOTM WORD TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderize PPSX para DOC no Andorid via Java" h2="APIs de formato de arquivo para converter PPSX para DOC em aplicativos Android sem depender do Microsoft PowerPoint ou Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) permite a manipulação de formatos de arquivo dentro de aplicativos Android. Ao usar as APIs fornecidas no pacote, você pode automatizar o processo de conversão do PowerPoint PPSX para Word DOC em seus aplicativos.
Você pode converter seu documento fornecido em duas etapas. Você pode usar [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) que é uma API do PowerPoint para aplicativos Android para renderizar PPSX em HTML. Depois disso, usando a API de processamento de documentos [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) você pode converter o HTML para DOC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Renderização de PPSX para DOC no Android" %}}
1. Abra o arquivo PPSX usando a classe [Apresentação](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Converta PPSX em HTML usando [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) e defina Html como SaveFormat
3. Carregue o arquivo HTML convertido usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Salve o documento no formato DOC usando o método [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) e defina Doc como SalvarFormato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total for Android via Java diretamente do [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e instale [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) e [Aspose.Words for Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) em seu formulários.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPSX file
Presentation presentation = new Presentation("input.ppsx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Document
Document document = new Document("htmlOutput.html");
// save document in DOC format
document.save("output.doc",SaveFormat.Doc);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/ppsx-to-odt/" name="PPSX Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/ppsx-to-flatopc/" name="PPSX Para FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/ppsx-to-docm/" name="PPSX Para DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/ppsx-to-rtf/" name="PPSX Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/ppsx-to-dotx/" name="PPSX Para DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/ppsx-to-wordml/" name="PPSX Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/ppsx-to-dot/" name="PPSX Para DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/ppsx-to-docx/" name="PPSX Para DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/ppsx-to-ott/" name="PPSX Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/ppsx-to-dotm/" name="PPSX Para DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/ppsx-to-word/" name="PPSX Para WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/ppsx-to-text/" name="PPSX Para TEXT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}