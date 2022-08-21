---
title: Exportar EPUB para POTX no Android
description: API do Android para converter EPUB em POTX sem usar o Microsoft Word
url: /pt/android-java/conversion/epub-to-potx/
family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: POTX
otherformats: PPTM POWERPOINT SWF PPSX PPT PPS ODP XAML POTM PPSM POT OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converter EPUB para POTX no Android via Java" h2="Transforme EPUB em POTX em seus aplicativos Android sem usar o Microsoft<sup>&reg;</sup> PowerPoint ou Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Você pode integrar o recurso de conversão EPUB para POTX dentro de seus aplicativos Android usando duas etapas simples. Na primeira etapa, você pode exportar EPUB para PPTX usando [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Depois disso, usando [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), você pode converter PPTX para POTX. Ambas as APIs estão no pacote [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android para exportar EPUB para POTX" %}}
1. Abra o arquivo EPUB usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converta EPUB para PPTX usando o método [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Carregue o documento PPTX usando a classe [Apresentação](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Salve o documento no formato POTX usando o método [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) e defina ` Potx` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total for Android via Java diretamente do [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e instale [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) e [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) em seus aplicativos.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load EPUB file with an instance of Document class
Document document = new Document("template.epub");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Potx format
presentation.save("output.potx", SaveFormat.Potx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Abra o arquivo EPUB protegido por senha no Android via Java" %}}
Ao carregar o formato de arquivo EPUB, seu documento pode estar protegido por senha. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) também permite abrir documentos criptografados. Para abrir o arquivo criptografado, você pode inicializar uma nova instância do [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) e passe o nome do arquivo e a senha como argumentos.
{{% blocks/products/pf/feature-page-code %}}

```java
// open EPUB document
Document doc = new Document("input.epub", "Your@Password");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Criar imagem em miniatura do arquivo POTX em aplicativos Android" %}}
Depois de converter EPUB para POTX, você também pode criar imagens em miniatura do seu documento de saída. Ao usar o rico recurso [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), você pode gerar imagens em miniatura dos slides criando uma instância do [Apresentação]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation). Depois disso, você pode obter a referência de qualquer slide desejado usando seu ID ou índice e obter a imagem em miniatura do slide referenciado em uma escala especificada.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a POTX file
Presentation presentation = new Presentation("output.potx");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/epub-to-pptm/" name="EPUB Para PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/epub-to-powerpoint/" name="EPUB Para POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/epub-to-swf/" name="EPUB Para SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/epub-to-ppsx/" name="EPUB Para PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/epub-to-ppt/" name="EPUB Para PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/epub-to-pps/" name="EPUB Para PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/epub-to-potx/" name="EPUB Para POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/epub-to-xaml/" name="EPUB Para XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/epub-to-potm/" name="EPUB Para POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/epub-to-ppsm/" name="EPUB Para PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/epub-to-pot/" name="EPUB Para POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/epub-to-otp/" name="EPUB Para OTP" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}