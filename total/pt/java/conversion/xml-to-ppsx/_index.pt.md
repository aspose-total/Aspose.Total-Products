---
title: Converter XML para PPSX via API Java
description: API Java para converter XML para PPSX sem usar o Microsoft Word
url: /pt/java/conversion/xml-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: XML
outformat: PPSX
otherformats: POTM PPSX POTX OTP XAML PPS POWERPOINT PPSM PPTM POT SWF PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java para exportar XML para PPSX" h2="Exporte XML para PPSX via API Java local sem usar o Microsoft<sup>&reg;</sup> PowerPoint ou Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total for Java](https://products.aspose.com/total/java/) você pode facilmente converter XML para PPSX em qualquer aplicativo Java J2SE, J2EE, J2ME. Em primeiro lugar, usando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), você pode exportar XML para PPTX. Depois disso, usando [Aspose.Slides for Java](https://products.aspose.com/slides/java/) API de processamento do PowerPoint, você pode converter PPTX para PPSX.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java para converter XML em PPSX" %}}
1. Abra o arquivo XML usando a classe [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converta XML para PPTX usando o método [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Carregue o documento PPTX usando a classe [Apresentação](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Salve o documento no formato PPSX usando o método [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) e defina ` Ppsx` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e inclua [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Slides for Java](https://docs.aspose.com/slides/java/ install/) em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XML file with an instance of Document class
Document document = new Document("template.xml");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppsx format
presentation.save("output.ppsx", SaveFormat.Ppsx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversão" %}}Document#Document-java.lang.String-java.lang.String-
Ao carregar o formato de arquivo XML, seu documento pode estar protegido por senha. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) também permite abrir documentos criptografados. Para abrir o arquivo criptografado, você pode inicializar uma nova instância do [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) e passe o nome do arquivo e a senha como argumentos.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open XML document
Document doc = new Document("input.xml", "Your@Password");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Abrir arquivo XML criptografado via Java" %}}
Depois de converter XML para PPSX, você também pode adicionar um tipo de visualização predefinido para sua apresentação. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) fornece um recurso para definir o tipo de exibição para a apresentação gerada quando ela é aberta no PowerPoint por meio de [ViewProperties](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties). A propriedade [setLastView](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) é usada para definir o tipo de visualização usando o [ViewType](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewType). 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppsx format
presentation.save("output.ppsx", SaveFormat.Ppsx);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras opções de conversão" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xml-to-pps/" name="XML Para PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xml-to-swf/" name="XML Para SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xml-to-potx/" name="XML Para POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xml-to-ppsx/" name="XML Para PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xml-to-potm/" name="XML Para POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xml-to-ppt/" name="XML Para PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xml-to-ppsm/" name="XML Para PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xml-to-xaml/" name="XML Para XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xml-to-otp/" name="XML Para OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xml-to-pptm/" name="XML Para PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xml-to-pot/" name="XML Para POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xml-to-powerpoint/" name="XML Para POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}