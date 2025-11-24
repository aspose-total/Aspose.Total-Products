---
title: Converteer MD naar SWF via Java API
description: Java API om MD naar SWF te converteren zonder Microsoft Word te gebruiken
url_ignore: /nl/java/conversion/md-to-swf/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: SWF
otherformats: PPSX PPSM PPT POT POTM POWERPOINT OTP SWF XAML PPTM POTX PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API om MD naar SWF te exporteren" h2="Exporteer MD naar SWF via lokale Java API zonder Microsoft<sup>&reg;</sup> PowerPoint of Adobe<sup>&reg;</sup> Acrobat Reader te gebruiken" >}}
{{% blocks/products/pf/feature-page-summary %}}
Met [Aspose.Total for Java](https://products.aspose.com/total/java/) kunt u MD gemakkelijk converteren naar SWF binnen elke Java J2SE, J2EE, J2ME-toepassing. Ten eerste, door [Aspose.PDF voor Java](https://products.aspose.com/pdf/java/) te gebruiken, kunt u MD naar PPTX exporteren. Daarna kunt u met behulp van [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API PPTX naar SWF converteren.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API om MD naar SWF te converteren" %}}
1. Open het MD-bestand met de klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converteer MD naar PPTX met behulp van de [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) methode
3. Laad PPTX-document met behulp van [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class
4. Sla het document op in SWF-indeling met de methode [opslaan](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) en stel ` Swf` als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total voor Java gemakkelijk rechtstreeks vanuit een op [Maven](https://releases.aspose.com/total/java/) gebaseerd project gebruiken en bevatten [Aspose.PDF voor Java](https://docs.aspose.com/pdf/java/installation/) en [Aspose.Slides voor Java](https://docs.aspose.com/slides/java/installation/) in uw po.xml.

U kunt ook een ZIP-bestand krijgen van [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Conversievereisten" %}}
Tijdens het laden van de MD-bestandsindeling is uw document mogelijk beveiligd met een wachtwoord. Met [Aspose.PDF voor Java](https://products.aspose.com/pdf/java/) kunt u ook versleutelde documenten openen. Om het versleutelde bestand te openen, kunt u een nieuwe instantie van het [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java) initialiseren .lang.String-) class en geef bestandsnaam en wachtwoord door als argumenten.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open MD document
Document doc = new Document("input.md", "Your@Password");
// save MD as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}https://reference.aspose.com/slides/java/com.aspose.slides/ViewType
{{% blocks/products/pf/feature-page-section  h2="Open gecodeerd MD-bestand via Java" %}}
Na het converteren van MD naar SWF, kunt u ook een vooraf gedefinieerd weergavetype voor uw presentatie toevoegen. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) biedt een mogelijkheid om het weergavetype in te stellen voor de gegenereerde presentatie wanneer deze wordt geopend in PowerPoint via de [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) klasse. De eigenschap [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) wordt gebruikt om het weergavetype in te stellen met behulp van de [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Swf format
presentation.save("output.swf", SaveFormat.Swf);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



Het omzetten van Markdown (MD) naar SWF (Shockwave Flash) maakt het mogelijk om tekst, diagrammen en grafieken om te zetten in interactieve Flash-animaties. SWF is ideaal voor verouderde educatieve inhoud, tutorials en geanimeerde webpresentaties.



{{% blocks/products/pf/agp/feature-section-col title="Belangrijkste Gebruiksscenario's" %}}



* Het omzetten van Markdown tutorials naar interactieve SWF-inhoud.

* Geanimeerde diagrammen voor e-learning modules gegenereerd vanuit Markdown.

* Verouderde Flash-gebaseerde presentaties voor weblevering.

* Interactieve Markdown visuals insluiten in educatieve platforms.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Automatiseringsscenario's" %}}



* Geautomatiseerde Markdown-naar-SWF-pijplijn voor online trainingsmateriaal.

* Batchconversie van MD-inhoud naar interactieve Flash-bestanden.

* Geplande updates voor SWF-leermodules afgeleid van Markdown.

* Getriggerde generatie van SWF visuals voor op web gebaseerde verouderde platforms.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}