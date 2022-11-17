---
title: Exportar XSLFO para POWERPOINT no Android
description: API do Android para converter XSLFO em POWERPOINT sem usar o Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: XSLFO
outformat: PPT
otherformats: POT PPSX PPT OTP SWF POTX PPTM PPSM ODP PPS XAML POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converter XSLFO para POWERPOINT no Android via Java" h2="Transforme XSLFO em POWERPOINT em seus aplicativos Android sem usar o Microsoft<sup>&reg;</sup> PowerPoint ou Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Você pode integrar o recurso de conversão XSLFO para POWERPOINT dentro de seus aplicativos Android usando duas etapas simples. Na primeira etapa, você pode exportar XSLFO para PPTX usando [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Depois disso, usando [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), você pode converter PPTX para POWERPOINT. Ambas as APIs estão no pacote [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android para exportar XSLFO para POWERPOINT" %}}
1. Abra o arquivo XSLFO usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converta XSLFO para PPTX usando o método [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Carregue o documento PPTX usando a classe [Apresentação](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Salve o documento no formato POWERPOINT usando o método [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) e defina ` Powerpoint` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total for Android via Java diretamente do [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e instale [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) e [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) em seus aplicativos.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XSLFO file with an instance of Document class
Document document = new Document("template.xslfo");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Abra o arquivo XSLFO protegido por senha no Android via Java" %}}
Ao carregar o formato de arquivo XSLFO, seu documento pode estar protegido por senha. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) também permite abrir documentos criptografados. Para abrir o arquivo criptografado, você pode inicializar uma nova instância do [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) e passe o nome do arquivo e a senha como argumentos.
{{% blocks/products/pf/feature-page-code %}}

```java
// open XSLFO document
Document doc = new Document("input.xslfo", "Your@Password");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
](https://
{{% blocks/products/pf/feature-page-section  h2="Criar imagem em miniatura do arquivo POWERPOINT em aplicativos Android" %}}
Depois de converter XSLFO para POWERPOINT, você também pode criar imagens em miniatura do seu documento de saída. Ao usar o rico recurso [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), você pode gerar imagens em miniatura dos slides criando uma instância do [Apresentação]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation). Depois disso, você pode obter a referência de qualquer slide desejado usando seu ID ou índice e obter a imagem em miniatura do slide referenciado em uma escala especificada.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a POWERPOINT file
Presentation presentation = new Presentation("output.powerpoint");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/xslfo-to-pot/" name="XSLFO Para POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/xslfo-to-ppsx/" name="XSLFO Para PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/xslfo-to-ppt/" name="XSLFO Para PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/xslfo-to-otp/" name="XSLFO Para OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/xslfo-to-swf/" name="XSLFO Para SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/xslfo-to-potx/" name="XSLFO Para POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/xslfo-to-pptm/" name="XSLFO Para PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/xslfo-to-ppsm/" name="XSLFO Para PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/xslfo-to-powerpoint/" name="XSLFO Para POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/xslfo-to-pps/" name="XSLFO Para PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/xslfo-to-xaml/" name="XSLFO Para XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/xslfo-to-potm/" name="XSLFO Para POTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}