---
title: API Java para exportar PS para DOT
description: Converter PS para DOT usando a API Java local
url_ignore: /pt/java/conversion/ps-to-dot/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: DOT
otherformats: OTT XAMLFLOW ODT DOT RTF MHTML MARKDOWN FLATOPC WORDML DOTM DOTX PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Transforme PS em DOT via Java" h2="On Premise Java API para renderizar PS para DOT sem usar nenhum aplicativo de terceiros" >}}
{{% blocks/products/pf/feature-page-summary %}}
Você pode converter PS para DOT usando duas etapas simples. Primeiro você precisa renderizar o arquivo PS para DOC usando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Depois disso, usando a poderosa API de processamento de documentos [Aspose.Words for Java](https://products.aspose.com/words/java/), você pode converter DOC para DOT. Ambas as APIs estão no pacote [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java para converter PS em DOT" %}}
1. Abra o arquivo PS usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converta PS para DOC usando [salvar](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) método
3. Carregue o arquivo DOC usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Salve o documento no formato DOT usando o método [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) e defina o DOT como SalvarFormato
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://releases.aspose.com/total/java/) e inclua [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "f5707d58ebee8d2889c8dbe5aa739d87" "convert-ps-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversão" %}}
Ao converter PS para DOT, mesmo que seu documento esteja protegido por senha, você ainda pode abri-lo usando a API de manipulação de PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Para abrir o arquivo criptografado, você precisa criar um objeto [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) e abrir o PS usando a senha do proprietário.  
{{% blocks/products/pf/feature-page-code %}}
```cs
// open encrypted document
Document document = new Document("input.ps", "password");
// save PS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Abrir documento PS protegido por senha via Java" %}}
Ao salvar seu documento de entrada no formato de arquivo DOT, você também pode salvar seu documento no banco de dados em vez de em um sistema de arquivos. Pode ser necessário implementar o armazenamento e a recuperação de objetos Document de e para um banco de dados. Isso seria necessário se você estivesse implementando qualquer tipo de sistema de gerenciamento de conteúdo. Para salvar seu DOT no banco de dados, muitas vezes é necessário serializar o documento para obter uma matriz de bytes. Isso pode ser feito usando a API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Depois de obter sua matriz de bytes, você pode armazená-la no banco de dados usando a instrução SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.DOT);
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

Converter arquivos PS (PostScript) para DOT (Modelo do Word) permite que as empresas padronizem a formatação e o layout de documentos. Os modelos DOT podem ser reutilizados para correspondência oficial, relatórios e documentos voltados para clientes sem a necessidade de recriar designs.

{{% blocks/products/pf/agp/feature-section-col title="Principais Casos de Uso" %}}

* Criar modelos de Word reutilizáveis a partir de relatórios baseados em PostScript.
* Padronizar cabeçalhos de cartas comerciais, formulários e documentos internos.
* Converter layouts visuais gerados em PS em modelos editáveis do Word.
* Manter consistência de design em vários documentos gerados pela equipe.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Cenários de Automação" %}}

* Conversão automatizada de PS para DOT para sistemas de gerenciamento de modelos.
* Integração com sistemas de gerenciamento de conteúdo para modelos de documentos reutilizáveis.
* Processamento em lote para gerar modelos específicos por departamento.
* Atualizações programadas de modelos do Word a partir de ativos de marca baseados em PostScript.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}