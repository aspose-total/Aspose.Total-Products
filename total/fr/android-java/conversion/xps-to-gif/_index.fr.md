---
title: API Android pour rendre XPS en GIF
description: Transformez XPS en GIF via Android via l'API Java
url: /fr/android-java/conversion/xps-to-gif/
family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: GIF
otherformats: MHTML DOTX WORDML MARKDOWN OTT FLATOPC DOT XAMLFLOW PCL DOCM ODT DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendre XPS en GIF sur Android via Java" h2="Convertissez XPS en GIF dans des applications mobiles sans installer de logiciel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Vous pouvez intégrer la fonction de conversion XPS vers GIF dans vos applications mobiles en utilisant deux API du package [Aspose.Total pour Android Java](https://products.aspose.com/total/android-java/). Vous devez d'abord convertir le fichier XPS en DOC en utilisant [Aspose.PDF pour Android via Java](https://products.aspose.com/pdf/android-java/). Deuxièmement, en utilisant l'API de traitement de texte [Aspose.Words pour Android Java](https://products.aspose.com/words/android-java/), vous pouvez rendre DOC en GIF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir XPS en GIF sur Android via Java" %}}
1. Ouvrez le fichier XPS à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez XPS en DOC en utilisant [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) méthode
3. Chargez le fichier DOC en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Enregistrez le document au format GIF à l'aide de la méthode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) et définissez GIF en tant que format de sauvegarde
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Android via Java directement depuis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et installez [Aspose.PDF pour Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) et [Aspose.Words pour Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) dans vos applications.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.GIF
outputDocument.save("output.gif", SaveFormat.GIF);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenir des informations sur les fichiers XPS sur Android via Java" %}}
Avant de convertir XPS en GIF, vous aurez peut-être besoin d'informations sur le document, notamment l'auteur, la date de création, les mots-clés, la date de modification, le sujet et le titre. Ces informations sont utiles pour la prise de décision concernant le processus de conversion. En utilisant la puissante API [Aspose.PDF pour Android via Java](https://docs.aspose.com/pdf/androidjava/), vous pouvez tout obtenir. Pour obtenir des informations spécifiques à un fichier sur un fichier XPS, obtenez d'abord l'objet [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) en utilisant [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--). Une fois l'objet DocumentInfo récupéré, vous pouvez obtenir les valeurs des propriétés individuelles.
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

{{% blocks/products/pf/feature-page-section  h2="Insérer des notes de fin dans un document GIF sous Android via Java" %}}
Outre la conversion de documents, vous pouvez également ajouter de nombreuses autres fonctionnalités dans vos applications Android à l'aide de l'API [Aspose.Words pour Android via Java](https://products.aspose.com/words/androidjava/). L'une de ces fonctionnalités consiste à insérer des notes de fin et une numérotation dans le document GIF. Si vous souhaitez insérer une note de bas de page ou une note de fin dans un document GIF, veuillez utiliser la méthode DocumentBuilder.InsertFootnote. Cette méthode insère une note de bas de page ou une note de fin dans le document. Les classes EndnoteOptions et FootnoteOptions représentent les options de numérotation pour les notes de bas de page et les notes de fin.
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
doc.save("output.gif", SaveFormat.GIF);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xps-to-mhtml/" name="XPS À MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xps-to-dotx/" name="XPS À DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xps-to-wordml/" name="XPS À WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xps-to-markdown/" name="XPS À MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xps-to-ott/" name="XPS À OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xps-to-flatopc/" name="XPS À FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xps-to-dot/" name="XPS À DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xps-to-xamlflow/" name="XPS À XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xps-to-pcl/" name="XPS À PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xps-to-gif/" name="XPS À GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xps-to-odt/" name="XPS À ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/xps-to-dotm/" name="XPS À DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}