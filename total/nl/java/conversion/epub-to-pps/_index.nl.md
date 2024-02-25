---
title: Converteer EPUB naar PPS via Java API
description: Java API om EPUB naar PPS te converteren zonder Microsoft Word te gebruiken
url_ignore: /nl/java/conversion/epub-to-pps/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PPS
otherformats: PPS POTX POTM POT PPSX XAML PPTM PPSM SWF OTP PPT POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API om EPUB naar PPS te exporteren" h2="Exporteer EPUB naar PPS via lokale Java API zonder Microsoft<sup>&reg;</sup> PowerPoint of Adobe<sup>&reg;</sup> Acrobat Reader te gebruiken" >}}
{{% blocks/products/pf/feature-page-summary %}}
Met [Aspose.Total for Java](https://products.aspose.com/total/java/) kunt u EPUB gemakkelijk converteren naar PPS binnen elke Java J2SE, J2EE, J2ME-toepassing. Ten eerste, door [Aspose.PDF voor Java](https://products.aspose.com/pdf/java/) te gebruiken, kunt u EPUB naar PPTX exporteren. Daarna kunt u met behulp van [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API PPTX naar PPS converteren.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API om EPUB naar PPS te converteren" %}}
1. Open het EPUB-bestand met de klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converteer EPUB naar PPTX met behulp van de [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) methode
3. Laad PPTX-document met behulp van [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class
4. Sla het document op in PPS-indeling met de methode [opslaan](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) en stel ` Pps` als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total voor Java gemakkelijk rechtstreeks vanuit een op [Maven](https://releases.aspose.com/total/java/) gebaseerd project gebruiken en bevatten [Aspose.PDF voor Java](https://docs.aspose.com/pdf/java/installation/) en [Aspose.Slides voor Java](https://docs.aspose.com/slides/java/installation/) in uw po.xml.

U kunt ook een ZIP-bestand krijgen van [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load EPUB file with an instance of Document class
Document document = new Document("template.epub");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pps format
presentation.save("output.pps", SaveFormat.Pps);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Conversievereisten" %}}
Tijdens het laden van de EPUB-bestandsindeling is uw document mogelijk beveiligd met een wachtwoord. Met [Aspose.PDF voor Java](https://products.aspose.com/pdf/java/) kunt u ook versleutelde documenten openen. Om het versleutelde bestand te openen, kunt u een nieuwe instantie van het [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java) initialiseren .lang.String-) class en geef bestandsnaam en wachtwoord door als argumenten.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open EPUB document
Document doc = new Document("input.epub", "Your@Password");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}https://reference.aspose.com/slides/java/com.aspose.slides/ViewType
{{% blocks/products/pf/feature-page-section  h2="Open gecodeerd EPUB-bestand via Java" %}}
Na het converteren van EPUB naar PPS, kunt u ook een vooraf gedefinieerd weergavetype voor uw presentatie toevoegen. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) biedt een mogelijkheid om het weergavetype in te stellen voor de gegenereerde presentatie wanneer deze wordt geopend in PowerPoint via de [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) klasse. De eigenschap [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) wordt gebruikt om het weergavetype in te stellen met behulp van de [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Pps format
presentation.save("output.pps", SaveFormat.Pps);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}