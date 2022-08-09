---
title: API do Android para renderizar MHTML para XAMLFLOW
description: Transforme MHTML em XAMLFLOW via Android via API Java
url: /pt/android-java/conversion/mhtml-to-xamlflow/
family: total
platformtag: cpp
feature: conversion
informat: MHTML
outformat: XAML_FLOW
otherformats: DOCM OTT PS DOT FLATOPC DOTX RTF WORDML DOTM MARKDOWN ODT PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderize MHTML para XAMLFLOW no Android via Java" h2="Converta MHTML para XAMLFLOW em aplicativos móveis sem instalar nenhum software" >}}

{{% blocks/products/pf/feature-page-summary %}}
Você pode integrar o recurso de conversão MHTML para XAMLFLOW em seus aplicativos móveis usando duas APIs do pacote [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). Primeiro você precisa converter o arquivo MHTML para DOC usando [Aspose.PDF para Android via Java](https://products.aspose.com/pdf/android-java/). Em segundo lugar, usando a API de processamento de texto [Aspose.Words for Android Java](https://products.aspose.com/words/android-java/), você pode renderizar DOC para XAMLFLOW. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter MHTML para XAMLFLOW no Android via Java" %}}
1. Abra o arquivo MHTML usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converta MHTML para DOC usando [salvar](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) método
3. Carregue o arquivo DOC usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Salve o documento no formato XAMLFLOW usando o método [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) e defina o XAMLFLOW como SalvarFormato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Android via Java diretamente do [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e instale [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) e [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) em seus aplicativos.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MHTML file with an instance of Document class
Document document = new Document("template.mhtml");
// save MHTML as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.XAML_FLOW
outputDocument.save("output.xaml_flow", SaveFormat.XAML_FLOW);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obter informações do arquivo MHTML no Android via Java" %}}
Antes de converter MHTML para XAMLFLOW, você pode precisar de informações sobre o documento, incluindo autor, data de criação, palavras-chave, data de modificação, assunto e título. Esta informação é útil para a tomada de decisão para o processo de conversão. Usando a poderosa API [Aspose.PDF para Android via Java](https://docs.aspose.com/pdf/androidjava/), você pode obter tudo isso. Para obter informações específicas sobre um arquivo MHTML, primeiro obtenha o objeto [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) usando [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--). Depois que o objeto DocumentInfo for recuperado, você poderá obter os valores das propriedades individuais.
{{% blocks/products/pf/feature-page-code %}}

```java
// load MHTML document
Document doc = new Document("template.mhtml");
// get document information
DocumentInfo docInfo = doc.getInfo();
// show document information
System.out.println("Author: " + docInfo.getAuthor());
System.out.println("Creation Date: " + docInfo.getCreationDate());
System.out.println("Keywords: " + docInfo.getKeywords());
System.out.println("Modify Date: " + docInfo.getModDate());
System.out.println("Subject: " + docInfo.getSubject());
System.out.println("Title: " + docInfo.getTitle());
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Inserir notas de fim no documento XAMLFLOW no Android via Java" %}}
Além da conversão de documentos, você também pode adicionar vários outros recursos dentro de seus aplicativos Android usando a API [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/). Um desses recursos é inserir notas de fim e numeração no documento XAMLFLOW. Se você deseja inserir uma nota de rodapé ou uma nota de fim em um documento XAMLFLOW, use o método DocumentBuilder.InsertFootnote. Este método insere uma nota de rodapé ou nota de fim no documento. As classes EndnoteOptions e FootnoteOptions representam opções de numeração para nota de rodapé e nota de fim.
{{% blocks/products/pf/feature-page-code %}}

```java
// load document
Document doc = new Document("input.DOC");
// initialize document builder
DocumentBuilder builder = new DocumentBuilder(doc);
// add text in it
builder.write("Some text");
// insert footnote
builder.insertFootnote(FootnoteType.ENDNOTE, "Endnote text.");
// initialize endnote options
EndnoteOptions option = doc.getEndnoteOptions();
// set restart rule
option.setRestartRule(FootnoteNumberingRule.RESTART_PAGE);
// set position
option.setPosition(EndnotePosition.END_OF_SECTION);
// save the document to disk.
doc.save("output.xaml_flow", SaveFormat.XAML_FLOW);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/mhtml-to-xamlflow/" name="MHTML Para XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/mhtml-to-ott/" name="MHTML Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/mhtml-to-ps/" name="MHTML Para PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/mhtml-to-dot/" name="MHTML Para DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/mhtml-to-flatopc/" name="MHTML Para FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/mhtml-to-dotx/" name="MHTML Para DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/mhtml-to-rtf/" name="MHTML Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/mhtml-to-wordml/" name="MHTML Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/mhtml-to-dotm/" name="MHTML Para DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/mhtml-to-markdown/" name="MHTML Para MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/mhtml-to-odt/" name="MHTML Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/mhtml-to-pcl/" name="MHTML Para PCL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}