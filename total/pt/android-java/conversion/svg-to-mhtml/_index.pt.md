---
title: API do Android para renderizar SVG para MHTML
description: Transforme SVG em MHTML via Android via API Java
url: /pt/android-java/conversion/svg-to-mhtml/
family: total
platformtag: cpp
feature: conversion
informat: SVG
outformat: MHTML
otherformats: DOT MARKDOWN ODT DOTM PCL WORDML PS OTT DOCM FLATOPC RTF XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderize SVG para MHTML no Android via Java" h2="Converta SVG para MHTML em aplicativos móveis sem instalar nenhum software" >}}

{{% blocks/products/pf/feature-page-summary %}}
Você pode integrar o recurso de conversão SVG para MHTML em seus aplicativos móveis usando duas APIs do pacote [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). Primeiro você precisa converter o arquivo SVG para DOC usando [Aspose.PDF para Android via Java](https://products.aspose.com/pdf/android-java/). Em segundo lugar, usando a API de processamento de texto [Aspose.Words for Android Java](https://products.aspose.com/words/android-java/), você pode renderizar DOC para MHTML. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter SVG para MHTML no Android via Java" %}}
1. Abra o arquivo SVG usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converta SVG para DOC usando [salvar](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) método
3. Carregue o arquivo DOC usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Salve o documento no formato MHTML usando o método [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) e defina o MHTML como SalvarFormato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Android via Java diretamente do [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e instale [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) e [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) em seus aplicativos.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load SVG file with an instance of Document class
Document document = new Document("template.svg");
// save SVG as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.MHTML
outputDocument.save("output.mhtml", SaveFormat.MHTML);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obter informações do arquivo SVG no Android via Java" %}}
Antes de converter SVG para MHTML, você pode precisar de informações sobre o documento, incluindo autor, data de criação, palavras-chave, data de modificação, assunto e título. Esta informação é útil para a tomada de decisão para o processo de conversão. Usando a poderosa API [Aspose.PDF para Android via Java](https://docs.aspose.com/pdf/androidjava/), você pode obter tudo isso. Para obter informações específicas sobre um arquivo SVG, primeiro obtenha o objeto [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) usando [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--). Depois que o objeto DocumentInfo for recuperado, você poderá obter os valores das propriedades individuais.
{{% blocks/products/pf/feature-page-code %}}

```java
// load SVG document
Document doc = new Document("template.svg");
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

{{% blocks/products/pf/feature-page-section  h2="Inserir notas de fim no documento MHTML no Android via Java" %}}
Além da conversão de documentos, você também pode adicionar vários outros recursos dentro de seus aplicativos Android usando a API [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/). Um desses recursos é inserir notas de fim e numeração no documento MHTML. Se você deseja inserir uma nota de rodapé ou uma nota de fim em um documento MHTML, use o método DocumentBuilder.InsertFootnote. Este método insere uma nota de rodapé ou nota de fim no documento. As classes EndnoteOptions e FootnoteOptions representam opções de numeração para nota de rodapé e nota de fim.
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
doc.save("output.mhtml", SaveFormat.MHTML);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/svg-to-dot/" name="SVG Para DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/svg-to-markdown/" name="SVG Para MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/svg-to-odt/" name="SVG Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/svg-to-dotm/" name="SVG Para DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/svg-to-pcl/" name="SVG Para PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/svg-to-wordml/" name="SVG Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/svg-to-ps/" name="SVG Para PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/svg-to-ott/" name="SVG Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/svg-to-mhtml/" name="SVG Para MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/svg-to-flatopc/" name="SVG Para FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/svg-to-rtf/" name="SVG Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/svg-to-xamlflow/" name="SVG Para XAMLFLOW" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}