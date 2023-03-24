---
title: Converteer JSON-formaat naar DOTX via Java
description: JSON ontleden naar DOTX in Java zonder Microsoft Word te gebruiken
url_ignore: /nl/java/conversion/json-to-dotx/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DOTX
otherformats: DOCM PS OTT WORD PCL RTF DOT FLATOPC EPUB ODT DOTX DOC WORDML MOBI
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converteer JSON-formaat naar DOTX via Java" h2="On-premise Java API om JSON naar DOTX te parseren zonder Microsoft<sup>&reg;</sup> Word te gebruiken" >}}
{{% blocks/products/pf/feature-page-summary %}}
Door [Aspose.Total for Java](https://products.aspose.com/total/java/) te gebruiken, kunt u JSON naar DOTX converteren in uw Java-applicaties in een proces van twee stappen. Ten eerste, door [Aspose.Cells for Java](https://products.aspose.com/cells/java/) te gebruiken, kunt u JSON naar PDF ontleden. In de tweede stap kunt u PDF naar DOTX converteren met behulp van de Word Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converteer JSON-formaat naar DOTX via Java" %}}
1. Maak een nieuw [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) object en lees geldige JSON-gegevens uit het bestand
2. Importeer het JSON-bestand naar het werkblad met de klasse [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) en [Save](https://reference.aspose.com/ cellen/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) het als PDF
3. Laad het PDF-document met behulp van de [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class
4. Sla het document op in DOTX-formaat met [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) methode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total voor Java gemakkelijk rechtstreeks vanuit een op [Maven](https://releases.aspose.com/total/java/) gebaseerd project gebruiken en neem bibliotheken op in uw po.xml.

U kunt ook een ZIP-bestand krijgen van [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Conversievereisten" %}}
Bovendien kunt u met de API lay-outopties voor uw JSON instellen terwijl u JSON naar DOTX parseert met behulp van [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Het stelt je in staat om Array als een tabel te verwerken, nulls te negeren, arraytitel te negeren, objecttitel te negeren, string naar getal of datum te converteren, datum- en getalnotatie in te stellen en titelstijl in te stellen. Met al deze opties kunt u uw gegevens presenteren volgens uw behoeften. Het volgende codefragment laat zien hoe u de lay-outopties instelt.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Stel lay-out in en converteer JSON-indeling naar DOTX via Java" %}}
Met behulp van de API kunt u JSON ook ontleden naar DOTX met watermerk. Om een watermerk aan uw DOTX-document toe te voegen, kunt u eerst het JSON-bestand naar PDF converteren en er een watermerk aan toevoegen. Om een watermerk toe te voegen, laadt u het nieuw gemaakte PDF-bestand met de klasse [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), maakt u een instantie van TextWatermarkOptions en stelt u zijn eigenschappen, Bel de methode Watermark.setText en geef de watermerktekst en het object van TextWatermarkOptions door. Nadat u het watermerk hebt toegevoegd, kunt u het document opslaan in DOTX. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}