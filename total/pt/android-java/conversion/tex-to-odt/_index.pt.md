---
title: API do Android para renderizar TEX para ODT
description: Transforme TEX em ODT via Android via API Java

family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: ODT
otherformats: DOT MHTML RTF MARKDOWN PCL FLATOPC XAMLFLOW OTT PS DOTX WORDML DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderize TEX para ODT no Android via Java" h2="Converta TEX para ODT em aplicativos móveis sem instalar nenhum software" >}}

{{% blocks/products/pf/feature-page-summary %}}
Você pode integrar o recurso de conversão TEX para ODT em seus aplicativos móveis usando duas APIs do pacote [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). Primeiro você precisa converter o arquivo TEX para DOC usando [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Em segundo lugar, usando a API de processamento de texto [Aspose.Words for Android Java](https://products.aspose.com/words/android-java/), você pode renderizar DOC para ODT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter TEX para ODT no Android via Java" %}}
1. Abra o arquivo TEX usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converta TEX para DOC usando [salvar](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) método
3. Carregue o arquivo DOC usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Salve o documento no formato ODT usando o método [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) e defina o ODT como SalvarFormato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total for Android via Java diretamente do [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e instale [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) e [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) em seus aplicativos.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load TEX file with an instance of Document class
Document document = new Document("template.tex");
// save TEX as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.ODT
outputDocument.save("output.odt", SaveFormat.ODT);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obter informações do arquivo TEX no Android via Java" %}}
Antes de converter TEX para ODT, você pode precisar de informações sobre o documento, incluindo autor, data de criação, palavras-chave, data de modificação, assunto e título. Esta informação é útil para a tomada de decisão para o processo de conversão. Usando a poderosa API [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/), você pode obter tudo isso. Para obter informações específicas sobre um arquivo TEX, primeiro obtenha o objeto [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) usando [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--). Depois que o objeto DocumentInfo for recuperado, você poderá obter os valores das propriedades individuais.
{{% blocks/products/pf/feature-page-code %}}

```java
// load TEX document
Document doc = new Document("template.tex");
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

{{% blocks/products/pf/feature-page-section  h2="Inserir notas de fim no documento ODT no Android via Java" %}}
Além da conversão de documentos, você também pode adicionar vários outros recursos dentro de seus aplicativos Android usando a API [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/). Um desses recursos é inserir notas de fim e numeração no documento ODT. Se você deseja inserir uma nota de rodapé ou uma nota de fim em um documento ODT, use o método DocumentBuilder.InsertFootnote. Este método insere uma nota de rodapé ou nota de fim no documento. As classes EndnoteOptions e FootnoteOptions representam opções de numeração para nota de rodapé e nota de fim.
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
doc.save("output.odt", SaveFormat.ODT);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/tex-to-dot/" name="TEX Para DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/tex-to-mhtml/" name="TEX Para MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/tex-to-rtf/" name="TEX Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/tex-to-markdown/" name="TEX Para MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/tex-to-pcl/" name="TEX Para PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/tex-to-flatopc/" name="TEX Para FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/tex-to-xamlflow/" name="TEX Para XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/tex-to-ott/" name="TEX Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/tex-to-ps/" name="TEX Para PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/tex-to-dotx/" name="TEX Para DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/tex-to-wordml/" name="TEX Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/tex-to-dotm/" name="TEX Para DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}