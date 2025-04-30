---
title: PS exporteren naar PPT via C# API
description: .NET API om PS naar PPT te converteren zonder Microsoft Word te gebruiken
url_ignore: /nl/net/conversion/ps-to-ppt/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: PPT
otherformats: PPT POTX XAML PPS SWF POTM POWERPOINT PPSX PPTM PPSM POT OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Render PS naar PPT via .NET" h2=".NET API om PS naar PPT te exporteren op Windows, macOS en Linux zonder Microsoft<sup>&reg;</sup> PowerPoint te gebruiken" >}}

{{% blocks/products/pf/feature-page-summary %}}
Met behulp van een pakket krachtige API's voor bestandsindelingsautomatisering [Aspose.Total for .NET](https://products.aspose.com/total/net/) kunt u PS eenvoudig in twee eenvoudige stappen naar PPT renderen. Door PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) te gebruiken, kunt u het PS-bestandsformaat omzetten naar PPTX. Daarna kunt u met behulp van de Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), PPTX naar PPT converteren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API om PS naar PPT te converteren" %}}
1. Open het PS-bestand met de klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Converteer PS naar PPTX met behulp van de [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) methode
3. Laad het PPTX-bestand met behulp van de [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class
4. Sla het document op in PPT-indeling met de methode [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) en stel `Ppt` in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Verkrijg XMP-metadata van PS-bestand via .NET" %}}
Tijdens het converteren van PS naar PPT heeft u mogelijk extra XMP-metadata-informatie nodig om prioriteit te geven aan uw batchconversieproces. U kunt bijvoorbeeld uw conversiedocumenten ophalen en sorteren op aanmaakdatum en de documenten dienovereenkomstig verwerken. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) geeft u toegang tot de XMP-metadata van een PS-bestand. Om de metadata van een PS-bestand te krijgen, kunt u een [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)-object maken en het invoer-PS-bestand openen. Daarna kunt u de metadata van het bestand verkrijgen met behulp van de eigenschap [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Maak een alleen-lezen PPT-bestand via .NET" %}}
Door de API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) te gebruiken, kunt u de functies van uw conversietoepassing verder verbeteren. Een van de functies kan zijn om uw uitvoerbestand alleen-lezen te maken om de beveiliging te vergroten. Met de API kunt u uw PPT-bestand instellen op Alleen-lezen, wat betekent dat gebruikers (nadat ze de presentatie hebben geopend) de aanbeveling Alleen-lezen zien. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.ppt", SaveFormat.Ppt);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PS-bestand programmatisch naar PPT transformeren: gebruiksscenario's" %}}
PS (Portable Document Format)-bestanden worden gebruikt om lay-outinformatie op te slaan, waardoor ze ideaal zijn voor het maken van statische documenten zoals presentaties, rapporten en folders. Tijdens het werken met dynamisch multimediaal inhoud wordt PowerPoint ongeveerlijk voor het visualiseren en interactief maken van presentaties.

De omzetting van PS-bestanden naar PowerPoint-formaten is nodig om volledige mogelijkheden te benutten bij het maken van presentaties. Deze omzetting maakt het mogelijk om:

**Gebruikscases:**

* **Presentatieontwerp en ontwikkeling**: Omzetten van PS-bestanden naar interactieve en aantrekkelijke presentaties met tekst, afbeeldingen, video's en animaties.
* **Dijsluiting en optimalisering van de dijk**: Gebruik van PowerPoint om slides te scheren, lay-outs aan te passen en visuele elementen te optimaliseren voor een gepolijste presentatie-ervaring.
* **Beheersing en bijwerken van inhoud**: Omzetten van PS-bestanden naar gemakkelijk beheersbare en bij te werende inhoud across meerdere apparaten en platforms, waardoor consistentie en precisie worden gewaarborgd.
* **Interactief verhaal vertellen**: Gebruik van PowerPoint om immersieve presentaties te maken die tekst, afbeeldingen, geluid en video's combineren om complexe informatie op een aantrekkelijke manier te presenteren.
* **Samenwerken en commentaren**: Omzetten van PS-bestanden naar gemakkelijk delen en commentarijen tussen teamleden of belanghebenden door real-time samenwerking en feedback.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}