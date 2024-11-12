---
title: Conversão online de XPS para WORDML ou desenvolvimento de aplicativo baseado em Java para converter arquivos XPS
description: Aplicativo online gratuito para converter arquivos XPS para WORDML. Código de biblioteca de conversão Java para documentos XPS. 

family: total
platformtag: Java
feature: conversion
informat: XPS
outformat: WORDML
otherformats: MHTML PS DOTM PCL MARKDOWN FLATOPC XAMLFLOW WORDML DOTX RTF OTT ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aplicativo de conversão online XPS para WORDML e código Java para converter arquivos XPS" h2="Desenvolva um poderoso aplicativo de conversão e exportação XPS baseado em Java. Converta arquivos XPS únicos ou múltiplos para WORDML e outros formatos via API de automação Java. Converta arquivos XPS gratuitamente online via aplicativo com download instantâneo." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="Aplicativo de conversão XPS para WORDML online gratuito" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=wordml&from=xps" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converta arquivos XPS para WORDML online usando o aplicativo" %}}

1. Carregar arquivos XPS para converter
1. Aguarde alguns segundos ou mais dependendo do tamanho do XPS
1. Fique de olho na barra de status do upload
1. Clique no botão "Converter"
1. XPS será convertido em documento WORDML
1. Baixe o arquivo WORDML convertido

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Converter XPS para WORDML via API de automação Java" %}}


1. Abra o arquivo XPS usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converta XPS para DOC usando [salvar](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) método
3. Carregue o arquivo DOC usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Salve o documento no formato WORDML usando o método [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) e defina o WORDML como SalvarFormato



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "ff4a1b9329c9c3428525cb1c7b528cc0" "convert-xps-to-wordml.java" >}}
{{% /blocks/products/pf/feature-page-code %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

Mais alguns casos para salvar XPS em WORDML com outros recursos como Requisitos de conversão, Abrir documento XPS protegido por senha via Java.

{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.xps", "password");
// save XPS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.WORD_ML);
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

<h2>Desenvolver aplicativo de conversão de arquivo XPS usando Java</h2>

Precisa desenvolver um aplicativo de software baseado em Java para salvar e exportar facilmente arquivos XPS para um documento WORDML? Com o [Aspose.Total for Java](https://products.aspose.com/total/pt/java/), qualquer desenvolvedor Java pode integrar o código API acima para programar o aplicativo de conversão em vários formatos, incluindo Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, arquivos de e-mail, imagens (JPG, PNG, BMP, GIF) e outros formatos. Poderosa biblioteca Java para conversão de documentos, suporta muitos formatos populares, incluindo o formato XPS. Para exportar e renderizar documentos para outros formatos, os programadores podem usar APIs filhas do Aspose.Total for Java, incluindo [Aspose.Words for Java](https://products.aspose.com/words/pt/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/pt/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/pt/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/pt/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/pt/java/) e mais.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XPS Biblioteca de conversão para Java" %}}

Existem opções alternativas para integrar o Aspose.Total for Java ao seu sistema. Escolha uma que se adeque às suas necessidades e siga as instruções passo a passo:<br /><br />

- Use o Aspose.Total for Java diretamente de um projeto baseado em Maven e inclua a API filha relevante em pom.xml.
- Alternativamente, é possível obter um arquivo ZIP do [baixar](https://releases.aspose.com/total/java).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Salvando XPS em WORDML Requisitos do aplicativo" %}}

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