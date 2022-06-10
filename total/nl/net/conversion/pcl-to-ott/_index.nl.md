---
title: C# API om PCL naar OTT te exporteren
description: Converteer PCL naar OTT zonder Microsoft Word te gebruiken
url_ignore: /nl/net/conversion/pcl-to-ott/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: OTT
otherformats: DOTM XAMLFLOW DOTX MARKDOWN OTT ODT WORDML DOT PS RTF FLATOPC MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Render PCL naar OTT via .NET" h2=".NET API om PCL naar OTT te exporteren op Windows, macOS en Linux zonder Microsoft Word te gebruiken" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total voor .NET](https://products.aspose.com/total/net/) is een krachtige API om documentmanipulatie- en conversiefuncties toe te voegen aan uw .NET-toepassing. Door gebruik te maken van de geavanceerde PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), kunt u het PCL-bestandsformaat converteren naar DOC. Daarna kunt u met behulp van de krachtige API voor documentverwerking [Aspose.Words for .NET](https://products.aspose.com/words/net/) DOC naar OTT weergeven.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API om PCL naar OTT te converteren" %}}
1. Open het PCL-bestand met de klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Converteer PCL naar Doc met behulp van de methode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Laad het Doc-bestand met de klasse [Document](https://reference.aspose.com/words/net/aspose.words/document) van Aspose.Words
4. Sla het document op in OTT-indeling met de methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) en stel Ott in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.pcl");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.ott", SaveFormat.Ott);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Decodeer het PCL-bestand met het eigenaarswachtwoord via .NET" %}}
Voordat u PCL naar OTT converteert, kunt u uw document ontsleutelen met behulp van de API. Om het PDF-bestand te decoderen, moet u eerst een [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)-object maken en de PCL openen met het wachtwoord van de eigenaar. Daarna moet u de methode [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) van het Document-object aanroepen. Sla ten slotte het bijgewerkte bestand op met de Save-methode van het Document-object.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.pcl", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Maak alleen-lezen OTT-bestand via .NET" %}}
Om uw OTT te beschermen tegen bewerking en om te voorkomen dat andere mensen gevoelige en vertrouwelijke informatie in uw document bewerken, kunt u de bescherming van het document ook instellen met behulp van de API. U kunt de mogelijkheid om een document te bewerken beperken en er alleen bepaalde acties mee toestaan. Dit kan worden gedaan met behulp van de API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Hiermee kunt u bepalen hoe u de inhoud beperkt met behulp van de opsommingsparameter [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). U kunt uw document op alleen-lezen instellen door de volgende coderegels te gebruiken. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.ott", SaveFormat.Ott);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere conversie-opties" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/pcl-to-ott/" name="PCL Tot OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/pcl-to-mhtml/" name="PCL Tot MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/pcl-to-wordml/" name="PCL Tot WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/pcl-to-dot/" name="PCL Tot DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/pcl-to-odt/" name="PCL Tot ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/pcl-to-rtf/" name="PCL Tot RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/pcl-to-ps/" name="PCL Tot PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/pcl-to-flatopc/" name="PCL Tot FLATotPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/pcl-to-pcl/" name="PCL Tot PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/pcl-to-markdown/" name="PCL Tot MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/pcl-to-xamlflow/" name="PCL Tot XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/pcl-to-dotx/" name="PCL Tot DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}