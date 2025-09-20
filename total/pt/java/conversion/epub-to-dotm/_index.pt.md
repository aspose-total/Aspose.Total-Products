---
title: API Java para exportar EPUB para DOTM
description: Converter EPUB para DOTM usando a API Java local
url_ignore: /pt/java/conversion/epub-to-dotm/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: DOTM
otherformats: FLATOPC ODT XAMLFLOW DOTX DOTM RTF OTT MARKDOWN PCL MHTML WORDML PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Transforme EPUB em DOTM via Java" h2="On Premise Java API para renderizar EPUB para DOTM sem usar nenhum aplicativo de terceiros" >}}
{{% blocks/products/pf/feature-page-summary %}}
Você pode converter EPUB para DOTM usando duas etapas simples. Primeiro você precisa renderizar o arquivo EPUB para DOC usando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Depois disso, usando a poderosa API de processamento de documentos [Aspose.Words for Java](https://products.aspose.com/words/java/), você pode converter DOC para DOTM. Ambas as APIs estão no pacote [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java para converter EPUB em DOTM" %}}
1. Abra o arquivo EPUB usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converta EPUB para DOC usando [salvar](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) método
3. Carregue o arquivo DOC usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Salve o documento no formato DOTM usando o método [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) e defina o DOTM como SalvarFormato
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://releases.aspose.com/total/java/) e inclua [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversão" %}}
Ao converter EPUB para DOTM, mesmo que seu documento esteja protegido por senha, você ainda pode abri-lo usando a API de manipulação de PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Para abrir o arquivo criptografado, você precisa criar um objeto [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) e abrir o EPUB usando a senha do proprietário.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-password-proteted-epub-file.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Abrir documento EPUB protegido por senha via Java" %}}
Ao salvar seu documento de entrada no formato de arquivo DOTM, você também pode salvar seu documento no banco de dados em vez de em um sistema de arquivos. Pode ser necessário implementar o armazenamento e a recuperação de objetos Document de e para um banco de dados. Isso seria necessário se você estivesse implementando qualquer tipo de sistema de gerenciamento de conteúdo. Para salvar seu DOTM no banco de dados, muitas vezes é necessário serializar o documento para obter uma matriz de bytes. Isso pode ser feito usando a API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Depois de obter sua matriz de bytes, você pode armazená-la no banco de dados usando a instrução SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.DOTM);
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
{{< blocks/products/pf/agp/feature-section >}}
Converter **EPUB para DOTM** é crucial para gerar **modelos de Word com macros ativadas** a partir de eBooks e publicações digitais. Arquivos DOTM permitem automação avançada por meio de macros incorporadas, possibilitando a editores, pesquisadores e empresas otimizar fluxos de trabalho, reduzir esforços manuais e padronizar a criação de conteúdo. Ao transformar EPUB em DOTM, organizações podem integrar funções dinâmicas em modelos reutilizáveis, garantindo eficiência e consistência em documentação acadêmica, empresarial e educacional.

{{% blocks/products/pf/agp/feature-section-col title="Principais Casos de Uso" %}}
- **Modelos de publicação automatizados** – Agilize conversões de eBook para modelos em grande escala.
- **Automação em pesquisa e acadêmica** – Crie estruturas padronizadas com macros para estudos.
- **Modelos de inteligência empresarial** – Automatize relatórios, integração de dados e conteúdo estruturado.
- **Estruturas de conteúdo educacional** – Construa modelos de curso e material de aprendizagem com macros ativadas.
- **Modelos orientados por fluxo de trabalho** – Integre macros para automatizar tarefas repetitivas de publicação.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Cenários de Automação" %}}
- **Pipelines de EPUB para DOTM** – Simplifique a geração em massa de modelos a partir de publicações digitais.
- **Distribuição de modelos com macros ativadas** – Implante modelos interativos e dinâmicos em equipes.
- **Conversão de metadados para modelos** – Converta metadados bibliográficos e de publicação em arquivos DOTM prontos para uso.
- **Automação de publicação empresarial** – Construa fluxos de trabalho completos que conectam fontes EPUB a modelos de Word com macros ativadas.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}