---
title: API Android pour rendre XPS en DOTX
description: Transformez XPS en DOTX via Android via l'API Java

family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: DOTX
otherformats: MHTML PS WORDML DOCM RTF PCL FLATOPC DOT DOTM XAMLFLOW MARKDOWN ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendre XPS en DOTX sur Android via Java" h2="Convertissez XPS en DOTX dans des applications mobiles sans installer de logiciel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Vous pouvez intégrer la fonction de conversion XPS vers DOTX dans vos applications mobiles en utilisant deux API du package [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). Vous devez d'abord convertir le fichier XPS en DOC en utilisant [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Deuxièmement, en utilisant l'API de traitement de texte [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/), vous pouvez rendre DOC en DOTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir XPS en DOTX sur Android via Java" %}}
1. Ouvrez le fichier XPS à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez XPS en DOC en utilisant [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) méthode
3. Chargez le fichier DOC en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Enregistrez le document au format DOTX à l'aide de la méthode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) et définissez DOTX en tant que format de sauvegarde
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total for Android via Java directement depuis [Maven](https://releases.aspose.com/total/java/)cs.aspose.com/pdf/androidjava/installation/) et [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) dans vos applications.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOTX
outputDocument.save("output.dotx", SaveFormat.DOTX);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenir des informations sur les fichiers XPS sur Android via Java" %}}
Avant de convertir XPS en DOTX, vous aurez peut-être besoin d'informations sur le document, notamment l'auteur, la date de création, les mots-clés, la date de modification, le sujet et le titre. Ces informations sont utiles pour la prise de décision concernant le processus de conversion. En utilisant la puissante API [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/), vous pouvez tout obtenir. Pour obtenir des informations spécifiques à un fichier sur un fichier XPS, obtenez d'abord l'objet [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) en utilisant [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--). Une fois l'objet DocumentInfo récupéré, vous pouvez obtenir les valeurs des propriétés individuelles.
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS document
Document doc = new Document("template.xps");
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

{{% blocks/products/pf/feature-page-section  h2="Insérer des notes de fin dans un document DOTX sous Android via Java" %}}
Outre la conversion de documents, vous pouvez également ajouter de nombreuses autres fonctionnalités dans vos applications Android à l'aide de l'API [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/). L'une de ces fonctionnalités consiste à insérer des notes de fin et une numérotation dans le document DOTX. Si vous souhaitez insérer une note de bas de page ou une note de fin dans un document DOTX, veuillez utiliser la méthode DocumentBuilder.InsertFootnote. Cette méthode insère une note de bas de page ou une note de fin dans le document. Les classes EndnoteOptions et FootnoteOptions représentent les options de numérotation pour les notes de bas de page et les notes de fin.
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
doc.save("output.dotx", SaveFormat.DOTX);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}