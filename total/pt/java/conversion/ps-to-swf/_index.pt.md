---
title: Converter PS para SWF via API Java
description: API Java para converter PS para SWF sem usar o Microsoft Word
url_ignore: /pt/java/conversion/ps-to-swf/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: SWF
otherformats: XAML POTX PPT PPSM SWF PPTM POWERPOINT POT PPS PPSX POTM OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java para exportar PS para SWF" h2="Exporte PS para SWF via API Java local sem usar o Microsoft<sup>&reg;</sup> PowerPoint ou Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total for Java](https://products.aspose.com/total/java/) você pode facilmente converter PS para SWF em qualquer aplicativo Java J2SE, J2EE, J2ME. Em primeiro lugar, usando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), você pode exportar PS para PPTX. Depois disso, usando [Aspose.Slides for Java](https://products.aspose.com/slides/java/) API de processamento do PowerPoint, você pode converter PPTX para SWF.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java para converter PS em SWF" %}}
1. Abra o arquivo PS usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converta PS para PPTX usando o método [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Carregue o documento PPTX usando a classe [Apresentação](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Salve o documento no formato SWF usando o método [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) e defina ` Swf` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://releases.aspose.com/total/java/) e inclua [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "f5707d58ebee8d2889c8dbe5aa739d87" "convert-ps-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversão" %}}
Ao carregar o formato de arquivo PS, seu documento pode estar protegido por senha. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) também permite abrir documentos criptografados. Para abrir o arquivo criptografado, você pode inicializar uma nova instância do [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) e passe o nome do arquivo e a senha como argumentos.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open PS document
Document doc = new Document("input.ps", "Your@Password");
// save PS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Abrir arquivo PS criptografado via Java" %}}
Depois de converter PS para SWF, você também pode adicionar um tipo de visualização predefinido para sua apresentação. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) fornece um recurso para definir o tipo de exibição para a apresentação gerada quando ela é aberta no PowerPoint por meio de [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties). A propriedade [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) é usada para definir o tipo de visualização usando o [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType). 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Swf format
presentation.save("output.swf", SaveFormat.Swf);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}

Converter arquivos PS (PostScript) para SWF (Shockwave Flash) permite a transformação de conteúdo estático em PostScript em animações web interativas. Isso é ideal para criar gráficos animados leves, módulos educacionais e apresentações interativas derivadas de layouts PS.

{{% blocks/products/pf/agp/feature-section-col title="Principais Casos de Uso" %}}

* Transformar diagramas baseados em PS em animações web interativas.
* Incorporar gráficos e visuais em PostScript em plataformas de e-learning.
* Converter brochuras de marketing de PS para animações amigáveis para a web.
* Criar tutoriais interativos e demonstrações usando saídas SWF.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Cenários de Automação" %}}

* Conversão em lote de PS para SWF para fluxos de trabalho de publicação na web.
* Integração em LMS ou portais educacionais para geração automatizada de animações.
* Conversão agendada de relatórios PS em conteúdo web interativo.
* Renderização assistida por IA de layouts complexos de PS em animações SWF.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}