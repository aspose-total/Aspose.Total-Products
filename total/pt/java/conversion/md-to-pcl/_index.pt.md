---
title: API Java para exportar MD para PCL
description: Converter MD para PCL usando a API Java local
url_ignore: /pt/java/conversion/md-to-pcl/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: PCL
otherformats: PCL ODT OTT MHTML DOTM MARKDOWN RTF FLATOPC WORDML DOT PS XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Transforme MD em PCL via Java" h2="On Premise Java API para renderizar MD para PCL sem usar nenhum aplicativo de terceiros" >}}
{{% blocks/products/pf/feature-page-summary %}}
Você pode converter MD para PCL usando duas etapas simples. Primeiro você precisa renderizar o arquivo MD para DOC usando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Depois disso, usando a poderosa API de processamento de documentos [Aspose.Words for Java](https://products.aspose.com/words/java/), você pode converter DOC para PCL. Ambas as APIs estão no pacote [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java para converter MD em PCL" %}}
1. Abra o arquivo MD usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converta MD para DOC usando [salvar](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) método
3. Carregue o arquivo DOC usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Salve o documento no formato PCL usando o método [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) e defina o PCL como SalvarFormato
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://releases.aspose.com/total/java/) e inclua [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-pcl.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversão" %}}
Ao converter MD para PCL, mesmo que seu documento esteja protegido por senha, você ainda pode abri-lo usando a API de manipulação de PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Para abrir o arquivo criptografado, você precisa criar um objeto [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) e abrir o MD usando a senha do proprietário.  
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
Ao salvar seu documento de entrada no formato de arquivo PCL, você também pode salvar seu documento no banco de dados em vez de em um sistema de arquivos. Pode ser necessário implementar o armazenamento e a recuperação de objetos Document de e para um banco de dados. Isso seria necessário se você estivesse implementando qualquer tipo de sistema de gerenciamento de conteúdo. Para salvar seu PCL no banco de dados, muitas vezes é necessário serializar o documento para obter uma matriz de bytes. Isso pode ser feito usando a API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Depois de obter sua matriz de bytes, você pode armazená-la no banco de dados usando a instrução SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.PCL);
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



A conversão de Markdown (MD) para PCL (Linguagem de Comando de Impressora) gera arquivos prontos para impressão compatíveis com impressoras a laser e jato de tinta. A conversão para PCL é adequada para produzir documentos técnicos, relatórios e automação de fluxo de trabalho em ambientes de impressão empresarial.



{{% blocks/products/pf/agp/feature-section-col title="Principais Casos de Uso" %}}



* Impressão de relatórios baseados em Markdown em impressoras compatíveis com PCL.

* Geração de saída PCL para distribuição em lote de documentos.

* Conversão de documentação Markdown em formatos prontos para impressão.

* Preparação de instruções técnicas para fluxos de trabalho de impressão de escritório ou manufatura.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Cenários de Automação" %}}



* Conversão em lote agendada de arquivos Markdown para PCL para impressão empresarial.

* Integração com servidores de impressão para gerar automaticamente PCL a partir de documentação Markdown.

* Pipelines de impressão automatizados convertendo Markdown para PCL.

* Produção de documentos com base em gatilhos para impressoras PCL de alto volume.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}