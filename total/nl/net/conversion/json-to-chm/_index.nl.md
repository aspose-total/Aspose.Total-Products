---
title: Converteer JSON-indeling naar CHM via .NET
description: Parseer JSON naar CHM in C# zonder Microsoft Word te gebruiken
url_ignore: /nl/net/conversion/json-to-chm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: CHM
otherformats: OTT FLATOPC PS DOTX RTF WORDML ODT WORD EPUB DOC DOT PCL MOBI DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converteer JSON-formaat naar CHM via C#" h2="C# API om JSON naar CHM te ontleden zonder Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Door [Aspose.Total for .NET](https://products.aspose.com/total/net/) te gebruiken, kunt u JSON naar CHM ontleden binnen elke .NET-, C#-, ASP.NET- en VB.NET-toepassing in twee eenvoudige stappen. Ten eerste, door [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) te gebruiken, kunt u JSON naar PDF exporteren. Daarna kunt u met [Aspose.Words for .NET](https://products.aspose.com/words/net/) PDF naar CHM converteren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converteer JSON-formaat naar CHM via C#" %}}
1. Maak een nieuw [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) object en lees geldige JSON-gegevens uit het bestand
2. Importeer het JSON-bestand naar het werkblad met de klasse [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) en [Save](https://reference.aspose.com/ cellen/net/aspose.cells.workbook/save/methods/4) het als PDF
3. Laad het PDF-document met behulp van de [Document](https://reference.aspose.com/words/net/aspose.words/document) class
4. Sla het document op in CHM-formaat met de methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/3)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
C#
{{% blocks/products/pf/feature-page-section  h2="Stel lay-out in en converteer JSON-indeling naar CHM via C#" %}}
Tijdens het ontleden van JSON naar CHM, kunt u ook lay-outopties voor uw JSON instellen met [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Het stelt je in staat om Array als een tabel te verwerken, nulls te negeren, arraytitel te negeren, objecttitel te negeren, string naar getal of datum te converteren, datum- en getalnotatie in te stellen en titelstijl in te stellen. Met al deze opties kunt u uw gegevens presenteren volgens uw behoeften. Het volgende codefragment laat zien hoe u de lay-outopties instelt.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="JSON-indeling ontleden naar CHM met watermerk" %}}
Met behulp van de API kunt u JSON ook converteren naar CHM met watermerk. Om een watermerk aan uw CHM-document toe te voegen, kunt u eerst het JSON-bestand naar PDF ontleden en er een watermerk aan toevoegen. Om een watermerk toe te voegen, laadt u het nieuw gemaakte PDF-bestand met behulp van de klasse [Document](https://reference.aspose.com/words/net/aspose.words/document), maakt u een instantie van TextWatermarkOptions en stelt u de eigenschappen ervan in, Roep de Watermark.SetText-methode aan en geef de watermerktekst en het object van TextWatermarkOptions door. Nadat u het watermerk hebt toegevoegd, kunt u het document opslaan in CHM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}