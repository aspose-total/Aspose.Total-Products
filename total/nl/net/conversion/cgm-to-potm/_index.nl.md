---
title: CGM exporteren naar POTM via C# API
description: .NET API om CGM naar POTM te converteren zonder Microsoft Word te gebruiken
url_ignore: /nl/net/conversion/cgm-to-potm/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: POTM
otherformats: POWERPOINT PPSX SWF POT POTX PPSM PPTM PPS PPT OTP XAML POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Render CGM naar POTM via .NET" h2=".NET API om CGM naar POTM te exporteren op Windows, macOS en Linux zonder Microsoft<sup>&reg;</sup> PowerPoint te gebruiken" >}}

{{% blocks/products/pf/feature-page-summary %}}
Met behulp van een pakket krachtige API's voor bestandsindelingsautomatisering [Aspose.Total for .NET](https://products.aspose.com/total/net/) kunt u CGM eenvoudig in twee eenvoudige stappen naar POTM renderen. Door PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) te gebruiken, kunt u het CGM-bestandsformaat omzetten naar PPTX. Daarna kunt u met behulp van de Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), PPTX naar POTM converteren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API om CGM naar POTM te converteren" %}}
1. Open het CGM-bestand met de klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Converteer CGM naar PPTX met behulp van de [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) methode
3. Laad het PPTX-bestand met behulp van de [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class
4. Sla het document op in POTM-indeling met de methode [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) en stel `Potm` in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Verkrijg XMP-metadata van CGM-bestand via .NET" %}}
Tijdens het converteren van CGM naar POTM heeft u mogelijk extra XMP-metadata-informatie nodig om prioriteit te geven aan uw batchconversieproces. U kunt bijvoorbeeld uw conversiedocumenten ophalen en sorteren op aanmaakdatum en de documenten dienovereenkomstig verwerken. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) geeft u toegang tot de XMP-metadata van een CGM-bestand. Om de metadata van een CGM-bestand te krijgen, kunt u een [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)-object maken en het invoer-CGM-bestand openen. Daarna kunt u de metadata van het bestand verkrijgen met behulp van de eigenschap [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Maak een alleen-lezen POTM-bestand via .NET" %}}
Door de API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) te gebruiken, kunt u de functies van uw conversietoepassing verder verbeteren. Een van de functies kan zijn om uw uitvoerbestand alleen-lezen te maken om de beveiliging te vergroten. Met de API kunt u uw POTM-bestand instellen op Alleen-lezen, wat betekent dat gebruikers (nadat ze de presentatie hebben geopend) de aanbeveling Alleen-lezen zien. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.potm", SaveFormat.Potm);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="CGM-bestand programmatisch naar POTM transformeren: gebruiksscenario's" %}}
De omzetting van CGM-bestanden naar POTM-formaten (Microsoft Office-sjablonen) is nodig om de volledige potentie van uw presentatiemontage en opmaakcapaciteiten te onthullen. Dit proces maakt het mogelijk om:

**Gebruikscases:**

* **Consistente merkidentiteit**: Om zorgen dat alle visuele elementen in presentaties overeenkomen met de organisatie's identiteit.  
* **Sjablonen ontwikkelen**: Gebruiken van POTM-sjablonen om herbruikbare en aanpassbare sjablonen te maken voor presentaties, waardoor het gemakkelijk wordt om consistent inhoud te produceren.  
* **Efficiënt ontwerp**: Om zorgen dat presentatieontwerpen efficiënter worden, waardoor u zich kunt richten op inhoudelijke creatie in plaats van vervelende formatietaken.  
* **Samenwerkingstools**: Gebruiken van POTM-formaten om tools te creëren die real-time feedback en mede-auteurdeelnemers faciliteren onder teamleden.  
* **Standardisering en conformiteit**: Om zorgen dat CGM-bestanden worden omgezet naar vormen die aan industriestandaarden en wet- en regelmatige eisen voldoen, waardoor alle presentaties aan specifieke richtlijnen blijven conform.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}