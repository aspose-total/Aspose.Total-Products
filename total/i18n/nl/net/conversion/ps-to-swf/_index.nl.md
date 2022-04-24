---
title: PS exporteren naar SWF via C# API
description: .NET API om PS naar SWF te converteren zonder Microsoft Word te gebruiken
url: /nl/net/conversion/ps-to-swf/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: SWF
otherformats: PPSM POTM OTP POWERPOINT PPS PPTM POT POTX XAML SWF PPSX PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Render PS naar SWF via .NET" h2=".NET API om PS naar SWF te exporteren op Windows, macOS en Linux zonder Microsoft<sup>&reg;</sup> PowerPoint te gebruiken" >}}

{{% blocks/products/pf/feature-page-summary %}}
Met behulp van een pakket krachtige API's voor bestandsindelingsautomatisering [Aspose.Total for .NET](https://products.aspose.com/total/net/) kunt u PS eenvoudig in twee eenvoudige stappen naar SWF renderen. Door PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) te gebruiken, kunt u het PS-bestandsformaat omzetten naar PPTX. Daarna kunt u met behulp van de Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), PPTX naar SWF converteren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API om PS naar SWF te converteren" %}}
1. Open het PS-bestand met de klasse [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Converteer PS naar PPTX met behulp van de [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) methode
3. Laad het PPTX-bestand met behulp van de [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation) class
4. Sla het document op in SWF-indeling met de methode [Save](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) en stel `Swf` in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("input.ps");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.swf", SaveFormat.Swf);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Verkrijg XMP-metadata van PS-bestand via .NET" %}}
Tijdens het converteren van PS naar SWF heeft u mogelijk extra XMP-metadata-informatie nodig om prioriteit te geven aan uw batchconversieproces. U kunt bijvoorbeeld uw conversiedocumenten ophalen en sorteren op aanmaakdatum en de documenten dienovereenkomstig verwerken. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) geeft u toegang tot de XMP-metadata van een PS-bestand. Om de metadata van een PS-bestand te krijgen, kunt u een [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)-object maken en het invoer-PS-bestand openen. Daarna kunt u de metadata van het bestand verkrijgen met behulp van de eigenschap [Metadata](https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
```cs

Document doc = new Document("input.ps");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Maak een alleen-lezen SWF-bestand via .NET" %}}
Door de API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) te gebruiken, kunt u de functies van uw conversietoepassing verder verbeteren. Een van de functies kan zijn om uw uitvoerbestand alleen-lezen te maken om de beveiliging te vergroten. Met de API kunt u uw SWF-bestand instellen op Alleen-lezen, wat betekent dat gebruikers (nadat ze de presentatie hebben geopend) de aanbeveling Alleen-lezen zien. 
```cs
```cs
Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.swf", SaveFormat.Swf);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere conversie-opties" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/ps-to-pot/" name="PS Tot POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/ps-to-ppsx/" name="PS Tot PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/ps-to-swf/" name="PS Tot SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/ps-to-powerpoint/" name="PS Tot POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/ps-to-otp/" name="PS Tot OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/ps-to-potm/" name="PS Tot POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/ps-to-ppt/" name="PS Tot PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/ps-to-pps/" name="PS Tot PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/ps-to-potx/" name="PS Tot POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/ps-to-xaml/" name="PS Tot XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/ps-to-ppsm/" name="PS Tot PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/ps-to-pptm/" name="PS Tot PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}