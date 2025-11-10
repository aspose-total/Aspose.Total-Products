---
title: Conversão online de TEX para MHTML ou desenvolvimento de aplicativo baseado em Java para converter arquivos TEX
description: Aplicativo online gratuito para converter arquivos TEX para MHTML. Código de biblioteca de conversão Java para documentos TEX. 

family: total
platformtag: Java
feature: conversion
informat: TEX
outformat: MHTML
otherformats: WORDML MARKDOWN DOTM DOT ODT FLATOPC OTT XAMLFLOW DOTX PCL PS RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aplicativo de conversão online TEX para MHTML e código Java para converter arquivos TEX" h2="Desenvolva um poderoso aplicativo de conversão e exportação TEX baseado em Java. Converta arquivos TEX únicos ou múltiplos para MHTML e outros formatos via API de automação Java. Converta arquivos TEX gratuitamente online via aplicativo com download instantâneo." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="Aplicativo de conversão TEX para MHTML online gratuito" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=mhtml&from=tex" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converta arquivos TEX para MHTML online usando o aplicativo" %}}

1. Carregar arquivos TEX para converter
1. Aguarde alguns segundos ou mais dependendo do tamanho do TEX
1. Fique de olho na barra de status do upload
1. Clique no botão "Converter"
1. TEX será convertido em documento MHTML
1. Baixe o arquivo MHTML convertido

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Converter TEX para MHTML via API de automação Java" %}}


1. Abra o arquivo TEX usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converta TEX para DOC usando [salvar](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) método
3. Carregue o arquivo DOC usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Salve o documento no formato MHTML usando o método [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) e defina o MHTML como SalvarFormato



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}


```java
// load TEX file with an instance of Document class
Document document = new Document("template.tex");
// save TEX as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.MHTML
outputDocument.save("output.mhtml", SaveFormat.MHTML);   
```



{{% /blocks/products/pf/feature-page-code %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

Mais alguns casos para salvar TEX em MHTML com outros recursos como Requisitos de conversão, Abrir documento TEX protegido por senha via Java.

{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.tex", "password");
// save TEX as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.MHTML);
    // get the byte array from output steam
    // the byte array now contains the document
    byte[] buffer = aout.toByteArray();
    // get the filename from the document.
    String fileName = doc.getOriginalFileName();
    String filePath = fileName.replace("\\", "\\\\");
    // create the SQL command.
    String commandString = "INSERT INTO Documents (FileName, FileContent) VALUES('" + filePath + "', '" + buffer + "')";
    Statement statement = mConnection.createStatement();
    statement.executeUpdate(commandString);
}  
```


{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>Desenvolver aplicativo de conversão de arquivo TEX usando Java</h2>

Precisa desenvolver um aplicativo de software baseado em Java para salvar e exportar facilmente arquivos TEX para um documento MHTML? Com o [Aspose.Total for Java](https://products.aspose.com/total/pt/java/), qualquer desenvolvedor Java pode integrar o código API acima para programar o aplicativo de conversão em vários formatos, incluindo Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, arquivos de e-mail, imagens (JPG, PNG, BMP, GIF) e outros formatos. Poderosa biblioteca Java para conversão de documentos, suporta muitos formatos populares, incluindo o formato TEX. Para exportar e renderizar documentos para outros formatos, os programadores podem usar APIs filhas do Aspose.Total for Java, incluindo [Aspose.Words for Java](https://products.aspose.com/words/pt/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/pt/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/pt/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/pt/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/pt/java/) e mais.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="TEX Biblioteca de conversão para Java" %}}

Existem opções alternativas para integrar o Aspose.Total for Java ao seu sistema. Escolha uma que se adeque às suas necessidades e siga as instruções passo a passo:<br /><br />

- Use o Aspose.Total for Java diretamente de um projeto baseado em Maven e inclua a API filha relevante em pom.xml.
- Alternativamente, é possível obter um arquivo ZIP do [baixar](https://releases.aspose.com/total/java).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Salvando TEX em MHTML Requisitos do aplicativo" %}}

Qualquer sistema operacional que possa executar o Java Runtime Environment (JRE) pode executar o Aspose.Total for Java. A seguir estão listados os principais sistemas operacionais suportados, mas não todos. <br /><br />
- Microsoft Windows
- Linux: Ubuntu, OpenSUSE, CentOS e outros
- macOS: 10.9 (Mavericks) e posterior
- Móvel: Android, iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

```
{{< blocks/products/pf/agp/feature-section >}}



Converter TEX para **MHTML (MIME HTML)** permite que documentos LaTeX sejam renderizados como uma página da web de arquivo único, preservando equações, tabelas e gráficos para visualização offline ou online.



{{% blocks/products/pf/agp/feature-section-col title="Principais Casos de Uso" %}}



* Arquivar artigos de pesquisa LaTeX como páginas da web autocontidas.

* Compartilhar relatórios baseados em LaTeX com gráficos e equações incorporados.

* Gerar materiais de palestra interativos em um único arquivo MHTML.

* Converter conteúdo técnico para módulos de e-learning offline.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Cenários de Automação" %}}



* Conversão em lote de TEX para MHTML para bibliotecas de cursos.

* Integração na geração automatizada de conteúdo de e-learning.

* Atualizações programadas de MHTML a partir de fontes LaTeX.

* Conversão acionada para compartilhamento de publicações de pesquisa.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}


{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}