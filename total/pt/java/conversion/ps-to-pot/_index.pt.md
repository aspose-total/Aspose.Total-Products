---
title: Converter PS para POT via API Java
description: API Java para converter PS para POT sem usar o Microsoft Word
url_ignore: /pt/java/conversion/ps-to-pot/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: POT
otherformats: PPSX POT XAML POTM SWF OTP PPSM PPT PPS POWERPOINT POTX PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java para exportar PS para POT" h2="Exporte PS para POT via API Java local sem usar o Microsoft<sup>&reg;</sup> PowerPoint ou Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total for Java](https://products.aspose.com/total/java/) você pode facilmente converter PS para POT em qualquer aplicativo Java J2SE, J2EE, J2ME. Em primeiro lugar, usando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), você pode exportar PS para PPTX. Depois disso, usando [Aspose.Slides for Java](https://products.aspose.com/slides/java/) API de processamento do PowerPoint, você pode converter PPTX para POT.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java para converter PS em POT" %}}
1. Abra o arquivo PS usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converta PS para PPTX usando o método [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Carregue o documento PPTX usando a classe [Apresentação](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Salve o documento no formato POT usando o método [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) e defina ` Pot` como SaveFormat
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
Depois de converter PS para POT, você também pode adicionar um tipo de visualização predefinido para sua apresentação. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) fornece um recurso para definir o tipo de exibição para a apresentação gerada quando ela é aberta no PowerPoint por meio de [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties). A propriedade [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) é usada para definir o tipo de visualização usando o [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType). 
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
```
{{< blocks/products/pf/agp/feature-section >}}

Converter arquivos PS (PostScript) para POT (Modelo do PowerPoint) permite que organizações transformem slides estáticos em PostScript em arquivos de modelo reutilizáveis. O POT garante designs de apresentação consistentes entre equipes, preservando o layout original do PS.

{{% blocks/products/pf/agp/feature-section-col title="Principais Casos de Uso" %}}

* Transformar conjuntos de slides PS em modelos reutilizáveis do PowerPoint.
* Padronizar apresentações corporativas e visuais de marketing.
* Criar modelos de slides educacionais a partir de relatórios PostScript.
* Preparar diagramas baseados em PS para fluxos de trabalho de apresentação recorrentes.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Cenários de Automação" %}}

* Conversão em lote automatizada de PS para POT para bibliotecas de modelos.
* Integração com sistemas de gerenciamento de documentos para modelos de slides reutilizáveis.
* Atualizações agendadas de modelos a partir de arquivos PS.
* Otimização assistida por IA de layouts para padronização de modelos.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}