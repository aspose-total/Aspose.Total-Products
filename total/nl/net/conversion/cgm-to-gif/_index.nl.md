---
title: C# API om CGM naar GIF te exporteren
description: Converteer CGM naar GIF zonder Microsoft Word te gebruiken
url_ignore: /nl/net/conversion/cgm-to-gif/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: GIF
otherformats: XAMLFLOW DOT MHTML PCL MARKDOWN RTF PS GIF OTT WORDML ODT DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Render CGM naar GIF via .NET" h2=".NET API om CGM naar GIF te exporteren op Windows, macOS en Linux zonder Microsoft Word te gebruiken" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total voor .NET](https://products.aspose.com/total/net/) is een krachtige API om documentmanipulatie- en conversiefuncties toe te voegen aan uw .NET-toepassing. Door gebruik te maken van de geavanceerde PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), kunt u het CGM-bestandsformaat converteren naar DOC. Daarna kunt u met behulp van de krachtige API voor documentverwerking [Aspose.Words for .NET](https://products.aspose.com/words/net/) DOC naar GIF weergeven.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API om CGM naar GIF te converteren" %}}
1. Open het CGM-bestand met de klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Converteer CGM naar Doc met behulp van de methode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Laad het Doc-bestand met de klasse [Document](https://reference.aspose.com/words/net/aspose.words/document) van Aspose.Words
4. Sla het document op in GIF-indeling met de methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) en stel Gif in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Decodeer het CGM-bestand met het eigenaarswachtwoord via .NET" %}}
Voordat u CGM naar GIF converteert, kunt u uw document ontsleutelen met behulp van de API. Om het PDF-bestand te decoderen, moet u eerst een [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)-object maken en de CGM openen met het wachtwoord van de eigenaar. Daarna moet u de methode [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) van het Document-object aanroepen. Sla ten slotte het bijgewerkte bestand op met de Save-methode van het Document-object.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Maak alleen-lezen GIF-bestand via .NET" %}}
Om uw GIF te beschermen tegen bewerking en om te voorkomen dat andere mensen gevoelige en vertrouwelijke informatie in uw document bewerken, kunt u de bescherming van het document ook instellen met behulp van de API. U kunt de mogelijkheid om een document te bewerken beperken en er alleen bepaalde acties mee toestaan. Dit kan worden gedaan met behulp van de API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Hiermee kunt u bepalen hoe u de inhoud beperkt met behulp van de opsommingsparameter [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). U kunt uw document op alleen-lezen instellen door de volgende coderegels te gebruiken. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.gif", SaveFormat.Gif);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="CGM-bestand programmatisch naar GIF transformeren: gebruiksscenario's" %}}
Het volledige potentie van je visueel content ontsluiten door het omzetten van CGM (Computer Graphics Metafile) bestanden naar GIF (Graphics Interchange Format) bestanden, draagt bij aan een hogere mate van mediasnelheid en dynamisch effect. Hiermee kun je:

**Gebruikscases:**

* **Bijdragen aan sociale media-uitingen**: CGM-bestanden omzetten naar GIFs voor deling op sociale media zoals Instagram of Twitter, wat de engagementrates en de zichtbaarheid van je merk verhoogt.  

* **Websitewerkingen**: GIFs gebruiken voor interactieve website-ervaringen, zoals hover-effecten, animaties en laadingsindicatoren.  

* **Marktonderzoeken**: CGM-bestanden omzetten naar GIFs voor het visualiseren van marketingcampagnes, het bijhouden van prestaties en het optimaliseren van strategieën.  

* **Onderwijsmateriaal**: GIFs gebruiken om complexe concepten visueel te illustreren, waardoor leerlingen gemakkelijk en met plezier kunnen leren, ideaal voor tutorials en onderwijsmateriaal.  

* **Verbeteringen van de e-commerce**: CGM-bestanden omzetten naar GIFs voor het maken van interactieve productdemonstraties, het benadrukken van klantvoordelen en een betere winkelervaring creëren.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}