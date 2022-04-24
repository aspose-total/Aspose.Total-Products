---
title: API Java para exportar PDF para MHTML
description: Converter PDF para MHTML usando a API Java local
url: /pt/java/conversion/pdf-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: MHTML
otherformats: XAMLFLOW DOTX OTT RTF WORDML MARKDOWN PCL PS FLATOPC DOTM DOT MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Transforme PDF em MHTML via Java" h2="On Premise Java API para renderizar PDF para MHTML sem usar nenhum aplicativo de terceiros" >}}
{{% blocks/products/pf/feature-page-summary %}}
Você pode converter PDF para MHTML usando duas etapas simples. Primeiro você precisa renderizar o arquivo PDF para DOC usando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Depois disso, usando a poderosa API de processamento de documentos [Aspose.Words for Java](https://products.aspose.com/words/java/), você pode converter DOC para MHTML. Ambas as APIs estão no pacote [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java para converter PDF em MHTML" %}}
1. Abra o arquivo PDF usando a classe [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converta PDF para DOC usando [salvar](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) método
3. Carregue o arquivo DOC usando a classe [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Salve o documento no formato MHTML usando o método [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) e defina o MHTML como SalvarFormato
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e inclua [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Words for Java](https://docs.aspose.com/words/java/ install/) em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PDF file with an instance of Document class
Document document = new Document("template.pdf");
// save PDF as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.MHTML
outputDocument.save("output.mhtml", SaveFormat.MHTML);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversão" %}}
Ao converter PDF para MHTML, mesmo que seu documento esteja protegido por senha, você ainda pode abri-lo usando a API de manipulação de PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Para abrir o arquivo criptografado, você precisa criar um objeto [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) e abrir o PDF usando a senha do proprietário.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.pdf", "password");
// save PDF as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Abrir documento PDF protegido por senha via Java" %}}
Ao salvar seu documento de entrada no formato de arquivo MHTML, você também pode salvar seu documento no banco de dados em vez de em um sistema de arquivos. Pode ser necessário implementar o armazenamento e a recuperação de objetos Document de e para um banco de dados. Isso seria necessário se você estivesse implementando qualquer tipo de sistema de gerenciamento de conteúdo. Para salvar seu MHTML no banco de dados, muitas vezes é necessário serializar o documento para obter uma matriz de bytes. Isso pode ser feito usando a API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Depois de obter sua matriz de bytes, você pode armazená-la no banco de dados usando a instrução SQL. 
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
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras opções de conversão" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-rtf/" name="PDF Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-wordml/" name="PDF Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-odt/" name="PDF Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-flatopc/" name="PDF Para FLAParaPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-ps/" name="PDF Para PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-pcl/" name="PDF Para PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-mhtml/" name="PDF Para MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-dotm/" name="PDF Para DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-ott/" name="PDF Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-dotx/" name="PDF Para DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-xamlflow/" name="PDF Para XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-markdown/" name="PDF Para MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}