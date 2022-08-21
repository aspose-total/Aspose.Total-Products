---
title: Exportar SVG para PPT no Android
description: API do Android para converter SVG em PPT sem usar o Microsoft Word
url: /pt/android-java/conversion/svg-to-ppt/
family: total
platformtag: cpp
feature: conversion
informat: SVG
outformat: PPT
otherformats: PPTM OTP PPSX POWERPOINT POTX ODP XAML PPS SWF POTM PPSM POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converter SVG para PPT no Android via Java" h2="Transforme SVG em PPT em seus aplicativos Android sem usar o Microsoft<sup>&reg;</sup> PowerPoint ou Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Você pode integrar o recurso de conversão SVG para PPT dentro de seus aplicativos Android usando duas etapas simples. Na primeira etapa, você pode exportar SVG para PPTX usando [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Depois disso, usando [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), você pode converter PPTX para PPT. Ambas as APIs estão no pacote [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android para exportar SVG para PPT" %}}
1. Abra o arquivo SVG usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converta SVG para PPTX usando o método [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Carregue o documento PPTX usando a classe [Apresentação](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Salve o documento no formato PPT usando o método [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) e defina ` Ppt` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total for Android via Java diretamente do [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e instale [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) e [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) em seus aplicativos.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load SVG file with an instance of Document class
Document document = new Document("template.svg");
// save SVG as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Abra o arquivo SVG protegido por senha no Android via Java" %}}
Ao carregar o formato de arquivo SVG, seu documento pode estar protegido por senha. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) também permite abrir documentos criptografados. Para abrir o arquivo criptografado, você pode inicializar uma nova instância do [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) e passe o nome do arquivo e a senha como argumentos.
{{% blocks/products/pf/feature-page-code %}}

```java
// open SVG document
Document doc = new Document("input.svg", "Your@Password");
// save SVG as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Criar imagem em miniatura do arquivo PPT em aplicativos Android" %}}
Depois de converter SVG para PPT, você também pode criar imagens em miniatura do seu documento de saída. Ao usar o rico recurso [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), você pode gerar imagens em miniatura dos slides criando uma instância do [Apresentação]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation). Depois disso, você pode obter a referência de qualquer slide desejado usando seu ID ou índice e obter a imagem em miniatura do slide referenciado em uma escala especificada.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPT file
Presentation presentation = new Presentation("output.ppt");
// access the first slide
ISlide sld = pres.getSlides().get_Item(0);
// create a full scale image
BufferedImage image = sld.getThumbnail(1f, 1f);
 // save the image to disk in PNG format
ImageIO.write(image, "PNG", new java.io.File("Thumbnail_out.png"));
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/svg-to-pptm/" name="SVG Para PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/svg-to-otp/" name="SVG Para OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/svg-to-ppsx/" name="SVG Para PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/svg-to-powerpoint/" name="SVG Para POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/svg-to-potx/" name="SVG Para POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/svg-to-ppt/" name="SVG Para PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/svg-to-xaml/" name="SVG Para XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/svg-to-pps/" name="SVG Para PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/svg-to-swf/" name="SVG Para SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/svg-to-potm/" name="SVG Para POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/svg-to-ppsm/" name="SVG Para PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/svg-to-pot/" name="SVG Para POT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}