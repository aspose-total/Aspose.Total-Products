---
title: Converter PDF para POT via API Java
description: API Java para converter PDF para POT sem usar o Microsoft Word
url: /pt/java/conversion/pdf-to-pot/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: POT
otherformats: PPSM POTX POTM PPTM SWF POT OTP PPT POWERPOINT PPS PPSX XAML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java para exportar PDF para POT" h2="Exporte PDF para POT via API Java local sem usar o Microsoft<sup>&reg;</sup> PowerPoint ou Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total for Java](https://products.aspose.com/total/java/) você pode facilmente converter PDF para POT em qualquer aplicativo Java J2SE, J2EE, J2ME. Em primeiro lugar, usando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), você pode exportar PDF para PPTX. Depois disso, usando [Aspose.Slides for Java](https://products.aspose.com/slides/java/) API de processamento do PowerPoint, você pode converter PPTX para POT.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java para converter PDF em POT" %}}
1. Abra o arquivo PDF usando a classe [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converta PDF para PPTX usando o método [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Carregue o documento PPTX usando a classe [Apresentação](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Salve o documento no formato POT usando o método [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) e defina ` Pot` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e inclua [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Slides for Java](https://docs.aspose.com/slides/java/ install/) em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PDF file with an instance of Document class
Document document = new Document("template.pdf");
// save PDF as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pot format
presentation.save("output.pot", SaveFormat.Pot);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversão" %}}
Ao carregar o formato de arquivo PDF, seu documento pode estar protegido por senha. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) também permite abrir documentos criptografados. Para abrir o arquivo criptografado, você pode inicializar uma nova instância do [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java .lang.String-) e passe o nome do arquivo e a senha como argumentos.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open PDF document
Document doc = new Document("input.pdf", "Your@Password");
// save PDF as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Abrir arquivo PDF criptografado via Java" %}}
Depois de converter PDF para POT, você também pode adicionar um tipo de visualização predefinido para sua apresentação. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) fornece um recurso para definir o tipo de exibição para a apresentação gerada quando ela é aberta no PowerPoint por meio de [ViewProperties](https:/ /apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties). A propriedade [setLastView](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) é usada para definir o tipo de visualização usando o [ViewType](https:/ /apireference.aspose.com/slides/java/com.aspose.slides/ViewType). 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Pot format
presentation.save("output.pot", SaveFormat.Pot);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras opções de conversão" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-pps/" name="PDF Para PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-swf/" name="PDF Para SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-potx/" name="PDF Para POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-ppsx/" name="PDF Para PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-potm/" name="PDF Para POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-ppt/" name="PDF Para PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-ppsm/" name="PDF Para PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-xaml/" name="PDF Para XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-otp/" name="PDF Para OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-pptm/" name="PDF Para PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-pot/" name="PDF Para POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-powerpoint/" name="PDF Para POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}