---
title: Conversão online de XSLFO para POTX ou desenvolvimento de aplicativo baseado em Java para converter arquivos XSLFO
description: Aplicativo online gratuito para converter arquivos XSLFO para POTX. Código de biblioteca de conversão Java para documentos XSLFO. 

family: total
platformtag: Java
feature: conversion
informat: XSLFO
outformat: POTX
otherformats: PPT PPSM POWERPOINT PPTM PPS POTM PPSX POTX OTP XAML SWF POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aplicativo de conversão online XSLFO para POTX e código Java para converter arquivos XSLFO" h2="Desenvolva um poderoso aplicativo de conversão e exportação XSLFO baseado em Java. Converta arquivos XSLFO únicos ou múltiplos para POTX e outros formatos via API de automação Java. Converta arquivos XSLFO gratuitamente online via aplicativo com download instantâneo." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="Aplicativo de conversão XSLFO para POTX online gratuito" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=potx&from=xslfo" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converta arquivos XSLFO para POTX online usando o aplicativo" %}}

1. Carregar arquivos XSLFO para converter
1. Aguarde alguns segundos ou mais dependendo do tamanho do XSLFO
1. Fique de olho na barra de status do upload
1. Clique no botão "Converter"
1. XSLFO será convertido em documento POTX
1. Baixe o arquivo POTX convertido

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Converter XSLFO para POTX via API de automação Java" %}}


1. Abra o arquivo XSLFO usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converta XSLFO para PPTX usando o método [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Carregue o documento PPTX usando a classe [Apresentação](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Salve o documento no formato POTX usando o método [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) e defina ` Potx` como SaveFormat



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}


```java
// load XSLFO file with an instance of Document class
Document document = new Document("template.xslfo");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Potx format
presentation.save("output.potx", SaveFormat.Potx);   
```



{{% /blocks/products/pf/feature-page-code %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

Mais alguns casos para salvar XSLFO em POTX com outros recursos como Requisitos de conversão, Abrir arquivo XSLFO criptografado via Java.

{{% blocks/products/pf/feature-page-code %}}


```java
// open XSLFO document
Document doc = new Document("input.xslfo", "Your@Password");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Potx format
presentation.save("output.potx", SaveFormat.Potx);    
```


{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>Desenvolver aplicativo de conversão de arquivo XSLFO usando Java</h2>

Precisa desenvolver um aplicativo de software baseado em Java para salvar e exportar facilmente arquivos XSLFO para um documento POTX? Com o [Aspose.Total for Java](https://products.aspose.com/total/pt/java/), qualquer desenvolvedor Java pode integrar o código API acima para programar o aplicativo de conversão em vários formatos, incluindo Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, arquivos de e-mail, imagens (JPG, PNG, BMP, GIF) e outros formatos. Poderosa biblioteca Java para conversão de documentos, suporta muitos formatos populares, incluindo o formato XSLFO. Para exportar e renderizar documentos para outros formatos, os programadores podem usar APIs filhas do Aspose.Total for Java, incluindo [Aspose.Words for Java](https://products.aspose.com/words/pt/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/pt/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/pt/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/pt/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/pt/java/) e mais.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XSLFO Biblioteca de conversão para Java" %}}

Existem opções alternativas para integrar o Aspose.Total for Java ao seu sistema. Escolha uma que se adeque às suas necessidades e siga as instruções passo a passo:<br /><br />

- Use o Aspose.Total for Java diretamente de um projeto baseado em Maven e inclua a API filha relevante em pom.xml.
- Alternativamente, é possível obter um arquivo ZIP do [baixar](https://releases.aspose.com/total/java).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Salvando XSLFO em POTX Requisitos do aplicativo" %}}

Qualquer sistema operacional que possa executar o Java Runtime Environment (JRE) pode executar o Aspose.Total for Java. A seguir estão listados os principais sistemas operacionais suportados, mas não todos. <br /><br />
- Microsoft Windows
- Linux: Ubuntu, OpenSUSE, CentOS e outros
- macOS: 10.9 (Mavericks) e posterior
- Móvel: Android, iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}