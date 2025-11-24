---
title: API Java para exportar MD para ODT
description: Converter MD para ODT usando a API Java local
url_ignore: /pt/java/conversion/md-to-odt/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: ODT
otherformats: RTF MHTML DOTM WORDML DOT OTT FLATOPC PCL MARKDOWN XAMLFLOW PS DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Transforme MD em ODT via Java" h2="On Premise Java API para renderizar MD para ODT sem usar nenhum aplicativo de terceiros" >}}
{{% blocks/products/pf/feature-page-summary %}}
Você pode converter MD para ODT usando duas etapas simples. Primeiro você precisa renderizar o arquivo MD para DOC usando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Depois disso, usando a poderosa API de processamento de documentos [Aspose.Words for Java](https://products.aspose.com/words/java/), você pode converter DOC para ODT. Ambas as APIs estão no pacote [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java para converter MD em ODT" %}}
1. Abra o arquivo MD usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converta MD para DOC usando [salvar](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) método
3. Carregue o arquivo DOC usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Salve o documento no formato ODT usando o método [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) e defina o ODT como SalvarFormato
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://releases.aspose.com/total/java/) e inclua [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-odt.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversão" %}}
Ao converter MD para ODT, mesmo que seu documento esteja protegido por senha, você ainda pode abri-lo usando a API de manipulação de PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Para abrir o arquivo criptografado, você precisa criar um objeto [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) e abrir o MD usando a senha do proprietário.  
{{% blocks/products/pf/feature-page-code %}}
```cs
// open encrypted document
Document document = new Document("input.md", "password");
// save MD as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Abrir documento MD protegido por senha via Java" %}}
Ao salvar seu documento de entrada no formato de arquivo ODT, você também pode salvar seu documento no banco de dados em vez de em um sistema de arquivos. Pode ser necessário implementar o armazenamento e a recuperação de objetos Document de e para um banco de dados. Isso seria necessário se você estivesse implementando qualquer tipo de sistema de gerenciamento de conteúdo. Para salvar seu ODT no banco de dados, muitas vezes é necessário serializar o documento para obter uma matriz de bytes. Isso pode ser feito usando a API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Depois de obter sua matriz de bytes, você pode armazená-la no banco de dados usando a instrução SQL. 
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

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



A conversão de MD (Markdown) para ODT (OpenDocument Text) possibilita fluxos de trabalho de documentação amigáveis ao código aberto. Arquivos ODT são ideais para equipes que utilizam o LibreOffice ou o OpenOffice, oferecendo uma alternativa flexível e leve aos formatos de Word proprietários, ao mesmo tempo em que permitem formatação avançada.



{{% blocks/products/pf/agp/feature-section-col title="Principais Casos de Uso" %}}



* Publicar documentação de código aberto como arquivos ODT formatados profissionalmente.

* Converter guias em Markdown em documentos editáveis no LibreOffice.

* Criar documentos multiplataforma para organizações que evitam formatos proprietários.

* Produzir manuais ODT localizados a partir de conteúdo em MD.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Cenários de Automação" %}}



* Conversão em lote de repositórios Markdown em ODT para distribuição pública.

* Geração automatizada de documentação ODT em projetos de código aberto.

* Fluxos de trabalho ETL multiplataforma que geram ODT para governos ou ONGs.

* Criação de ODT com base em gatilhos em pipelines de localização e tradução.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}