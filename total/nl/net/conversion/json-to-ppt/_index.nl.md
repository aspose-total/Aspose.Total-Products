---
title: Converteer JSON-indeling naar PPT via .NET
description: JSON ontleden naar PPT in C# zonder Microsoft PowerPoint te gebruiken
url_ignore: /nl/net/conversion/json-to-ppt/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPT
otherformats: PPSM POT POTM PPS OTP POWERPOINT PPTM PPT PPSX POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converteer JSON-formaat naar PPT via C#" h2="C# API om JSON naar PPT te ontleden zonder Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
U kunt in twee eenvoudige stappen JSON naar PPT converteren binnen elke .NET-, C#-, ASP.NET- en VB.NET-toepassing. Ten eerste, door [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) te gebruiken, kunt u JSON ontleden naar PPTX. Daarna kunt u met [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) PPTX naar PPT converteren. Beide API's vallen onder het pakket [Aspose.Total for .NET](https://products.aspose.com/total/net/).
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converteer JSON-formaat naar PPT via C#" %}}
1. Maak een nieuw [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) object en lees geldige JSON-gegevens uit het bestand
2. Importeer het JSON-bestand naar het werkblad met de klasse [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) en [Save](https://reference.aspose.com/ cellen/net/aspose.cells.workbook/save/methods/4) het als PPTX
3. Laad PPTX-document met behulp van [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class
4. Sla het document op in PPT-indeling met de methode [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
C#
{{% blocks/products/pf/feature-page-section  h2="Lay-out instellen en JSON-indeling converteren naar PPT via C#" %}}
Tijdens het ontleden van JSON naar PPT, kunt u ook lay-outopties voor uw JSON-indeling instellen met [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Het stelt u in staat om array als een tabel te verwerken, nulls te negeren, arraytitel te negeren, objecttitel te negeren, string naar getal of datum te converteren, datum- en getalnotatie in te stellen en titelstijl in te stellen. Met al deze opties kunt u uw gegevens presenteren volgens uw behoeften. Het volgende codefragment laat zien hoe u de lay-outopties instelt.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "set-layout-and-parse-json-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converteer JSON-indeling naar PPT met watermerk" %}}
Met behulp van de API kunt u JSON ook converteren naar PPT met watermerk. Om een watermerk aan uw PPT-document toe te voegen, kunt u eerst JSON naar PPTX ontleden en er een watermerk aan toevoegen. Om een watermerk toe te voegen, laadt u het nieuw gemaakte PPTX-bestand met behulp van de klasse [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation), selecteert u de hoofdpresentatie, voegt u vormtype toe met AddAutoShape en voeg watermerktekst toe met AddTextFrame. Nadat u het watermerk hebt toegevoegd, kunt u het document opslaan in PPT. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}