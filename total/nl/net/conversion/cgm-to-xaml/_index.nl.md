---
title: CGM exporteren naar XAML via C# API
description: .NET API om CGM naar XAML te converteren zonder Microsoft Word te gebruiken
url_ignore: /nl/net/conversion/cgm-to-xaml/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: XAML
otherformats: SWF POT PPTM OTP PPT XAML PPSX PPSM POTX POTM POWERPOINT PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Render CGM naar XAML via .NET" h2=".NET API om CGM naar XAML te exporteren op Windows, macOS en Linux zonder Microsoft<sup>&reg;</sup> PowerPoint te gebruiken" >}}

{{% blocks/products/pf/feature-page-summary %}}
Met behulp van een pakket krachtige API's voor bestandsindelingsautomatisering [Aspose.Total for .NET](https://products.aspose.com/total/net/) kunt u CGM eenvoudig in twee eenvoudige stappen naar XAML renderen. Door PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) te gebruiken, kunt u het CGM-bestandsformaat omzetten naar PPTX. Daarna kunt u met behulp van de Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), PPTX naar XAML converteren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API om CGM naar XAML te converteren" %}}
1. Open het CGM-bestand met de klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Converteer CGM naar PPTX met behulp van de [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) methode
3. Laad het PPTX-bestand met behulp van de [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class
4. Sla het document op in XAML-indeling met de methode [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) en stel `Xaml` in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.cgm");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.xaml", SaveFormat.Xaml);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Verkrijg XMP-metadata van CGM-bestand via .NET" %}}
Tijdens het converteren van CGM naar XAML heeft u mogelijk extra XMP-metadata-informatie nodig om prioriteit te geven aan uw batchconversieproces. U kunt bijvoorbeeld uw conversiedocumenten ophalen en sorteren op aanmaakdatum en de documenten dienovereenkomstig verwerken. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) geeft u toegang tot de XMP-metadata van een CGM-bestand. Om de metadata van een CGM-bestand te krijgen, kunt u een [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)-object maken en het invoer-CGM-bestand openen. Daarna kunt u de metadata van het bestand verkrijgen met behulp van de eigenschap [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.cgm");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Maak een alleen-lezen XAML-bestand via .NET" %}}
Door de API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) te gebruiken, kunt u de functies van uw conversietoepassing verder verbeteren. Een van de functies kan zijn om uw uitvoerbestand alleen-lezen te maken om de beveiliging te vergroten. Met de API kunt u uw XAML-bestand instellen op Alleen-lezen, wat betekent dat gebruikers (nadat ze de presentatie hebben geopend) de aanbeveling Alleen-lezen zien. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.xaml", SaveFormat.Xaml);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="CGM-bestand programmatisch naar XAML transformeren: gebruiksscenario's" %}}
Het omzetten van CGM-bestanden naar XAML-formaten is essentieel voor het benutten van de volledige capaciteit van uw UI-designmogelijkheden.

Deze omzetting maakt mogelijk:

**Gebruikscases:**

* **Ontwikkeling van een UI-componentenbibliotheek**: Omzetten van CGM-bestanden naar XAML voor het creëren van een bibliotheek met hergebrukbare UI-componenten, wat ontwikkelingstijd vermindert en consistentiteit verbetert in de toepassingen.  
* **Implementatie van een Ontwerp systeem**: Gebruik van XAML om ontwerpsystemen te visualiseren en te implementeren, waardoor een cohérente gebruikerservaring wordt bereikt op meerdere platforms.  
* **Prototypen en bruikbaarheidstoetsing**: Omzetten van CGM-bestanden naar XAML voor het maken van interactieve prototypen en het uitvoeren van bruikbaarheidstoetsingen, waardoor ontwerpdoelen worden gevalideerd en de gebruikersbetrokkenheid verbeterd wordt.  
* **Optimisatie van toegankelijkheid**: Gebruik van XAML om UI-toegankelijkheid te analyseren en te optimaliseren, zodat alle gebruikers, ongeacht hun capaciteit, de applicatie kunnen gebruiken.  
* **Data-gerichte ontwerp**: Omzetten van CGM-bestanden naar XAML voor het maken van data-gerichte ontwerpen, waarbij analytika en gebruikersfeedback worden gebruikt om ontwerpdoelen te verbeteren en bedrijfsresultaten te optimaliseren.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}