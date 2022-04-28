---
title: Convertir XSLFO en PPSM via l'API Java
description: API Java pour convertir XSLFO en PPSM sans utiliser Microsoft Word
url: /fr/java/conversion/xslfo-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: PPSM
otherformats: POWERPOINT POT PPSM OTP PPT PPTM POTX PPS POTM XAML PPSX SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java pour exporter XSLFO vers PPSM" h2="Exportez XSLFO vers PPSM via l'API Java sur site sans utiliser Microsoft<sup>&reg;</sup> PowerPoint ou Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total pour Java](https://products.aspose.com/total/java/), vous pouvez facilement convertir XSLFO en PPSM dans n'importe quelle application Java J2SE, J2EE, J2ME. Tout d'abord, en utilisant [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), vous pouvez exporter XSLFO vers PPTX. Après cela, en utilisant l'API de traitement PowerPoint [Aspose.Slides for Java](https://products.aspose.com/slides/java/), vous pouvez convertir PPTX en PPSM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java pour convertir XSLFO en PPSM" %}}
1. Ouvrez le fichier XSLFO à l'aide de la classe [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez XSLFO en PPTX en utilisant la méthode [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Chargez le document PPTX en utilisant la classe [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Enregistrez le document au format PPSM à l'aide de la méthode [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) et définissez ` Ppsm` comme format de sauvegarde
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et inclure [Aspose.PDF pour Java](https://docs.aspose.com/pdf/java/installation/) et [Aspose.Slides pour Java](https://docs.aspose.com/slides/java/ installation/) dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XSLFO file with an instance of Document class
Document document = new Document("template.xslfo");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppsm format
presentation.save("output.ppsm", SaveFormat.Ppsm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}Document#Document-java.lang.String-java.lang.String-
Lors du chargement du format de fichier XSLFO, votre document peut être protégé par un mot de passe. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) vous permet également d'ouvrir des documents cryptés. Afin d'ouvrir le fichier crypté, vous pouvez initialiser une nouvelle instance du [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) classe et transmettez le nom de fichier et le mot de passe comme arguments.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open XSLFO document
Document doc = new Document("input.xslfo", "Your@Password");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ouvrir le fichier XSLFO crypté via Java" %}}
Après avoir converti XSLFO en PPSM, vous pouvez également ajouter un type de vue prédéfini pour votre présentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) fournit une fonction permettant de définir le type d'affichage de la présentation générée lorsqu'elle est ouverte dans PowerPoint via [ViewProperties](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties). La propriété [setLastView](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) est utilisée pour définir le type de vue à l'aide de [ViewType](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewType) énumérateur. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppsm format
presentation.save("output.ppsm", SaveFormat.Ppsm);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres options de conversion" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xslfo-to-pps/" name="XSLFO Pour PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xslfo-to-swf/" name="XSLFO Pour SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xslfo-to-potx/" name="XSLFO Pour POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xslfo-to-ppsx/" name="XSLFO Pour PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xslfo-to-potm/" name="XSLFO Pour POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xslfo-to-ppt/" name="XSLFO Pour PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xslfo-to-ppsm/" name="XSLFO Pour PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xslfo-to-xaml/" name="XSLFO Pour XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xslfo-to-otp/" name="XSLFO Pour OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xslfo-to-pptm/" name="XSLFO Pour PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xslfo-to-pot/" name="XSLFO Pour POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/xslfo-to-powerpoint/" name="XSLFO Pour POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}