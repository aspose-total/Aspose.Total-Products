---
title: C# API om CGM naar DOT te exporteren
description: Converteer CGM naar DOT zonder Microsoft Word te gebruiken
url_ignore: /nl/net/conversion/cgm-to-dot/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DOT
otherformats: PCL FLATOPC OTT WORDML ODT DOT RTF MARKDOWN XAMLFLOW DOTX PS MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Render CGM naar DOT via .NET" h2=".NET API om CGM naar DOT te exporteren op Windows, macOS en Linux zonder Microsoft Word te gebruiken" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total voor .NET](https://products.aspose.com/total/net/) is een krachtige API om documentmanipulatie- en conversiefuncties toe te voegen aan uw .NET-toepassing. Door gebruik te maken van de geavanceerde PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), kunt u het CGM-bestandsformaat converteren naar DOC. Daarna kunt u met behulp van de krachtige API voor documentverwerking [Aspose.Words for .NET](https://products.aspose.com/words/net/) DOC naar DOT weergeven.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API om CGM naar DOT te converteren" %}}
1. Open het CGM-bestand met de klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Converteer CGM naar Doc met behulp van de methode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Laad het Doc-bestand met de klasse [Document](https://reference.aspose.com/words/net/aspose.words/document) van Aspose.Words
4. Sla het document op in DOT-indeling met de methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) en stel Dot in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Decodeer het CGM-bestand met het eigenaarswachtwoord via .NET" %}}
Voordat u CGM naar DOT converteert, kunt u uw document ontsleutelen met behulp van de API. Om het PDF-bestand te decoderen, moet u eerst een [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)-object maken en de CGM openen met het wachtwoord van de eigenaar. Daarna moet u de methode [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) van het Document-object aanroepen. Sla ten slotte het bijgewerkte bestand op met de Save-methode van het Document-object.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Maak alleen-lezen DOT-bestand via .NET" %}}
Om uw DOT te beschermen tegen bewerking en om te voorkomen dat andere mensen gevoelige en vertrouwelijke informatie in uw document bewerken, kunt u de bescherming van het document ook instellen met behulp van de API. U kunt de mogelijkheid om een document te bewerken beperken en er alleen bepaalde acties mee toestaan. Dit kan worden gedaan met behulp van de API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Hiermee kunt u bepalen hoe u de inhoud beperkt met behulp van de opsommingsparameter [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). U kunt uw document op alleen-lezen instellen door de volgende coderegels te gebruiken. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dot", SaveFormat.Dot);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="CGM-bestand programmatisch naar DOT transformeren: gebruiksscenario's" %}}
De omzetting van CGM-bestanden naar DOT-formaten is nodig om de volledige potentie van uw grafische visualisatie- en opmaakmogelijkheden te onvermijdelijke. Deze omzetting maakt het mogelijk om:

**Toepassingsgebieden:**

* **Graphische Visualisatie**: Omzetten van CGM-bestanden naar DOT-formaten voor het maken van diagrammen, stroomdiagrammen en processkaarten met behulp van DOT-formaat, waardoor complexe relaties tussen gegevenspunten kunnen worden weergeven.  
* **Optimale Opmaak**: Gebruik van DOT-formaten om de opzet van knopen en randen in uw grafische elementen te optimaliseren, zodat ze maximaal leesbaar en efficiënt zijn.  
* **Bedrijfsproceskaarten**: Omzetten van CGM-bestanden naar DOT-formaten voor het maken van gedetailleerde bedrijfsproceskaarten, waarbij workflows, taken en beslissingen worden benadrukt.  
* **Technische Diagrammen**: Gebruik van DOT-formaten om technische diagrammen te genereren, zoals UML-classdiagrammen, dataflow-diagrammen en ER-modellen.  
* **Graphische Hiërarchie en Structuur**: Omzetten van CGM-bestanden naar DOT-formaten om duidelijke hiërarchieën en structuren in uw grafische elementen te vestigen, waardoor ze gemakkelijk te navigeren en te begrijpen zijn.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}