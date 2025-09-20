---
title: Converter EPUB para PPSX via API Java
description: API Java para converter EPUB para PPSX sem usar o Microsoft Word
url_ignore: /pt/java/conversion/epub-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PPSX
otherformats: POWERPOINT XAML PPTM PPT PPSM OTP PPS POT POTM POTX SWF PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java para exportar EPUB para PPSX" h2="Exporte EPUB para PPSX via API Java local sem usar o Microsoft<sup>&reg;</sup> PowerPoint ou Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total for Java](https://products.aspose.com/total/java/) você pode facilmente converter EPUB para PPSX em qualquer aplicativo Java J2SE, J2EE, J2ME. Em primeiro lugar, usando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), você pode exportar EPUB para PPTX. Depois disso, usando [Aspose.Slides for Java](https://products.aspose.com/slides/java/) API de processamento do PowerPoint, você pode converter PPTX para PPSX.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java para converter EPUB em PPSX" %}}
1. Abra o arquivo EPUB usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converta EPUB para PPTX usando o método [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Carregue o documento PPTX usando a classe [Apresentação](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Salve o documento no formato PPSX usando o método [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) e defina ` Ppsx` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://releases.aspose.com/total/java/) e inclua [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversão" %}}
Ao carregar o formato de arquivo EPUB, seu documento pode estar protegido por senha. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) também permite abrir documentos criptografados. Para abrir o arquivo criptografado, você pode inicializar uma nova instância do [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) e passe o nome do arquivo e a senha como argumentos.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open EPUB document
Document doc = new Document("input.epub", "Your@Password");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Abrir arquivo EPUB criptografado via Java" %}}
Depois de converter EPUB para PPSX, você também pode adicionar um tipo de visualização predefinido para sua apresentação. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) fornece um recurso para definir o tipo de exibição para a apresentação gerada quando ela é aberta no PowerPoint por meio de [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties). A propriedade [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) é usada para definir o tipo de visualização usando o [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType). 
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
```
{{< blocks/products/pf/agp/feature-section >}}
Converter **EPUB para PPSX (PowerPoint Open XML Show)** é essencial para gerar arquivos de **apresentação modernos** a partir de eBooks. Arquivos PPSX fornecem um formato baseado em XML aberto para apresentações de slides que são abertos diretamente no modo de apresentação, garantindo compatibilidade e exibição profissional. Ao transformar EPUB em PPSX, educadores, editores e empresas podem entregar eficientemente apresentações polidas, simplificar o compartilhamento de conteúdo e manter consistência em exibições digitais e ao vivo.

{{% blocks/products/pf/agp/feature-section-col title="Principais Casos de Uso" %}}
- **Previews de publicação** – Mostrar conteúdo de eBook como slides interativos para clientes ou leitores.
- **Palestras acadêmicas** – Converter conteúdo de livros didáticos em slides de palestras prontos para reprodução.
- **Apresentações de trabalhos de pesquisa** – Entregar slides estruturados para conferências e seminários.
- **Demonstrações de negócios** – Apresentar materiais corporativos em formato de apresentação de slides profissional e moderno.
- **Sessões de treinamento** – Criar slides instrucionais para workshops e programas de e-learning.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Cenários de Automação" %}}
- **Pipelines de EPUB para PPSX** – Automatizar a conversão de eBooks em arquivos de apresentação modernos.
- **Geração automatizada de slides** – Produzir slides prontos para reprodução diretamente de publicações digitais.
- **Conversão em massa de eBooks para PowerPoint** – Converter vários eBooks em apresentações de forma eficiente.
- **Fluxos de trabalho de publicação em nível empresarial** – Integrar a geração de PPSX em sistemas de distribuição de apresentações em larga escala e gerenciamento de conteúdo.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}