---
title: Conversão online de PDF para ODT ou desenvolvimento de aplicativo baseado em Java para converter arquivos PDF
description: Aplicativo online gratuito para converter arquivos PDF para ODT. Código de biblioteca de conversão Java para documentos PDF. 

family: total
platformtag: Java
feature: conversion
informat: PDF
outformat: ODT
otherformats: XAMLFLOW DOTX OTT ODT RTF DOTM PCL MARKDOWN FLATOPC MHTML DOT PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aplicativo de conversão online PDF para ODT e código Java para converter arquivos PDF" h2="Desenvolva um poderoso aplicativo de conversão e exportação PDF baseado em Java. Converta arquivos PDF únicos ou múltiplos para ODT e outros formatos via API de automação Java. Converta arquivos PDF gratuitamente online via aplicativo com download instantâneo." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="Aplicativo de conversão PDF para ODT online gratuito" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=odt&from=pdf" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converta arquivos PDF para ODT online usando o aplicativo" %}}

1. Carregar arquivos PDF para converter
1. Aguarde alguns segundos ou mais dependendo do tamanho do PDF
1. Fique de olho na barra de status do upload
1. Clique no botão "Converter"
1. PDF será convertido em documento ODT
1. Baixe o arquivo ODT convertido

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Converter PDF para ODT via API de automação Java" %}}


1. Abra o arquivo PDF usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converta PDF para DOC usando [salvar](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) método
3. Carregue o arquivo DOC usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Salve o documento no formato ODT usando o método [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) e defina o ODT como SalvarFormato



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "48b55393e52dd85032905dea500a496b" "convert-pdf-to-odt.java" >}}
{{% /blocks/products/pf/feature-page-code %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

Mais alguns casos para salvar PDF em ODT com outros recursos como Requisitos de conversão, Abrir documento PDF protegido por senha via Java.

{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.pdf", "password");
// save PDF as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.ODT);
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

<h2>Desenvolver aplicativo de conversão de arquivo PDF usando Java</h2>

Precisa desenvolver um aplicativo de software baseado em Java para salvar e exportar facilmente arquivos PDF para um documento ODT? Com o [Aspose.Total for Java](https://products.aspose.com/total/pt/java/), qualquer desenvolvedor Java pode integrar o código API acima para programar o aplicativo de conversão em vários formatos, incluindo Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, arquivos de e-mail, imagens (JPG, PNG, BMP, GIF) e outros formatos. Poderosa biblioteca Java para conversão de documentos, suporta muitos formatos populares, incluindo o formato PDF. Para exportar e renderizar documentos para outros formatos, os programadores podem usar APIs filhas do Aspose.Total for Java, incluindo [Aspose.Words for Java](https://products.aspose.com/words/pt/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/pt/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/pt/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/pt/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/pt/java/) e mais.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PDF Biblioteca de conversão para Java" %}}

Existem opções alternativas para integrar o Aspose.Total for Java ao seu sistema. Escolha uma que se adeque às suas necessidades e siga as instruções passo a passo:<br /><br />

- Use o Aspose.Total for Java diretamente de um projeto baseado em Maven e inclua a API filha relevante em pom.xml.
- Alternativamente, é possível obter um arquivo ZIP do [baixar](https://releases.aspose.com/total/java).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Salvando PDF em ODT Requisitos do aplicativo" %}}

Qualquer sistema operacional que possa executar o Java Runtime Environment (JRE) pode executar o Aspose.Total for Java. A seguir estão listados os principais sistemas operacionais suportados, mas não todos. <br /><br />
- Microsoft Windows
- Linux: Ubuntu, OpenSUSE, CentOS e outros
- macOS: 10.9 (Mavericks) e posterior
- Móvel: Android, iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}
Converter **PDF para ODT** é essencial para produzir documentos **OpenDocument Text** a partir de PDFs estáticos. Isso garante flexibilidade de edição no LibreOffice Writer e em outros processadores de texto de código aberto, tornando-o valioso para governos, empresas e publicações acadêmicas.
{{% blocks/products/pf/agp/feature-section-col title="Principais Casos de Uso" %}}
- Documentação governamental e jurídica
- Armazenamento de políticas empresariais em formatos abertos
- Publicação de pesquisas acadêmicas
- Escrita e edição colaborativas
- Arquivamento de documentos de texto a longo prazo
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Cenários de Automação" %}}
- Pipelines de conteúdo automatizados de PDF para ODT
- Sistemas de gerenciamento de documentos com integração ODT
- Fluxos de trabalho de publicação automatizados
- Conversão de documentação empresarial em grande escala
- Processamento em lote para governos e ONGs
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}


{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}