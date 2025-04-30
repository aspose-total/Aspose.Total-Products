---
title: C# API om CGM naar PCL te exporteren
description: Converteer CGM naar PCL zonder Microsoft Word te gebruiken
url_ignore: /nl/net/conversion/cgm-to-pcl/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PCL
otherformats: RTF ODT PS MHTML DOTX OTT FLATOPC WORDML DOT PCL MARKDOWN DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Render CGM naar PCL via .NET" h2=".NET API om CGM naar PCL te exporteren op Windows, macOS en Linux zonder Microsoft Word te gebruiken" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total voor .NET](https://products.aspose.com/total/net/) is een krachtige API om documentmanipulatie- en conversiefuncties toe te voegen aan uw .NET-toepassing. Door gebruik te maken van de geavanceerde PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), kunt u het CGM-bestandsformaat converteren naar DOC. Daarna kunt u met behulp van de krachtige API voor documentverwerking [Aspose.Words for .NET](https://products.aspose.com/words/net/) DOC naar PCL weergeven.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API om CGM naar PCL te converteren" %}}
1. Open het CGM-bestand met de klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Converteer CGM naar Doc met behulp van de methode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Laad het Doc-bestand met de klasse [Document](https://reference.aspose.com/words/net/aspose.words/document) van Aspose.Words
4. Sla het document op in PCL-indeling met de methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) en stel Pcl in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.cgm");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.pcl", SaveFormat.Pcl);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Decodeer het CGM-bestand met het eigenaarswachtwoord via .NET" %}}
Voordat u CGM naar PCL converteert, kunt u uw document ontsleutelen met behulp van de API. Om het PDF-bestand te decoderen, moet u eerst een [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)-object maken en de CGM openen met het wachtwoord van de eigenaar. Daarna moet u de methode [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) van het Document-object aanroepen. Sla ten slotte het bijgewerkte bestand op met de Save-methode van het Document-object.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.cgm", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Maak alleen-lezen PCL-bestand via .NET" %}}
Om uw PCL te beschermen tegen bewerking en om te voorkomen dat andere mensen gevoelige en vertrouwelijke informatie in uw document bewerken, kunt u de bescherming van het document ook instellen met behulp van de API. U kunt de mogelijkheid om een document te bewerken beperken en er alleen bepaalde acties mee toestaan. Dit kan worden gedaan met behulp van de API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Hiermee kunt u bepalen hoe u de inhoud beperkt met behulp van de opsommingsparameter [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). U kunt uw document op alleen-lezen instellen door de volgende coderegels te gebruiken. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pcl", SaveFormat.Pcl);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="CGM-bestand programmatisch naar PCL transformeren: gebruiksscenario's" %}}
CGM (Computer Graphics Metafile)-bestanden worden gebruikt om vectorgrafiekgegevens op te slagen, waardoor ze ideaal zijn voor het maken van statische grafieken en illustraties. Tijdens het werken met dynamische gegevens wordt Excel een essentieel hulpmiddel voor gegevensvisualisatie en analyse.

De omzetting van CGM-bestanden naar PCL-formats is nodig om volledige gebruikskwaliteit van je gegevensvisualisatie- en analysecapaciteiten te bereiken. Deze omzetting maakt het mogelijk om:

**Toepassingsgebieden:**

* **Optimisatie van productfabrikage**: Om optimale productontwerpen te creëren, simuleren van fabrikageprocessen en validatie van productieworkflows.
* **Ontwerp voor fabrikage (DFM)**: Gebruik van PCL-formats om ontwerpparameters te analyseren en optimaliseren, waardoor producten aan prestaties, kosten en fabrikageigenschappen worden voldaan.
* **3D-printen en additieve fabricage**: Om complexe 3D-modellen te creëren, simuleren van drukprocessen en validatie van materiaaleigenschappen voor additieve fabricageprocesse.
* **CNC-maakwerk en freeswerk**: Gebruik van PCL-formats om CNC-maakwerkefficiency en precisie te optimaliseren in productieworkflows.
* **Gegevensanalyse en kwaliteitscontrole**: Om gedetailleerde rapporten en visualisaties van fabrikagegegevens te maken, waardoor real-time kwaliteitscontrole en optimalisatie worden mogelijk.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}