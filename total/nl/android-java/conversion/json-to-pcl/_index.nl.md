---
title: Converteer JSON-indeling naar PCL in Android Apps
description: JSON ontleden naar PCL in Java zonder Microsoft Word te gebruiken

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: PCL
otherformats: DOCM OTT ODT WORD WORDML DOT DOC MOBI PS DOTX EPUB CHM RTF FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converteer JSON-indeling naar PCL in Android-applicaties" h2="Parseer JSON naar PCL binnen Android-applicaties zonder Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
U kunt JSON naar PCL converteren in uw Android-applicaties in een proces van twee stappen. Ten eerste kunt u met behulp van de krachtige API voor spreadsheetverwerking [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) JSON naar PDF ontleden. In de tweede stap kunt u PDF naar PCL converteren met behulp van de Word Processing API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Beide API's vallen onder de productfamilie [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converteer JSON-indeling naar PCL in Android Apps" %}}
1. Maak een nieuw [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) object en lees geldige JSON-gegevens uit het bestand
2. Importeer het JSON-bestand naar het werkblad met de klasse [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) en [Save](https://reference.aspose.com/cellen/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) als PDF
3. Laad het PDF-document met behulp van de [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) klasse
4. Sla het document op in PCL-formaat met [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) methode
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total for Android eenvoudig via Java rechtstreeks vanuit [Maven](https://releases.aspose.com/total/java/) en installeer bibliotheken in uw app.

U kunt ook een ZIP-bestand krijgen van [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Stel lay-out in en converteer JSON-indeling naar PCL in Android Apps" %}}
Bovendien kunt u met de API lay-outopties instellen voor uw JSON-indeling terwijl u JSON naar PCL parseert met behulp van [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Het stelt je in staat om Array als een tabel te verwerken, nulls te negeren, arraytitel te negeren, objecttitel te negeren, string naar getal of datum te converteren, datum- en getalnotatie in te stellen en titelstijl in te stellen. Met al deze opties kunt u uw gegevens presenteren volgens uw behoeften. Het volgende codefragment laat zien hoe u de lay-outopties instelt.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converteer JSON-indeling naar PCL met watermerk in Android Apps" %}}
Met behulp van de API kunt u JSON ook converteren naar PCL met watermerk. Om een watermerk aan uw PCL-document toe te voegen, kunt u eerst het JSON-bestand naar PDF ontleden en er een watermerk aan toevoegen. Om een watermerk toe te voegen, laadt u het nieuw gemaakte PDF-bestand met de klasse [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), maakt u een instantie van TextWatermarkOptions en stelt u zijn eigenschappen, Bel de methode Watermark.setText en geef de watermerktekst en het object van TextWatermarkOptions door. Nadat u het watermerk hebt toegevoegd, kunt u het document opslaan in PCL.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}