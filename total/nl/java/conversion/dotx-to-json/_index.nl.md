---
title: Converteer DOTX naar JSON-formaat via Java
description: Converteer DOTX naar JSON-formaat via Java zonder Microsoft Word of Microsoft Excel te gebruiken
url_ignore: /nl/java/conversion/dotx-to-json/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: JSON
otherformats: SXC XLSM XLSB TSV XLAM XLT DIF EXCEL XLTX CSV XLTM FODS ODS XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converteer DOTX naar JSON-formaat via Java" h2="On Premise Java API om DOTX naar JSON te converteren zonder Microsoft<sup>&reg;</sup> Word of Microsoft<sup>&reg;</sup> Excel te gebruiken" >}}
{{% blocks/products/pf/feature-page-summary %}}
Het converteren van DOTX naar JSON-formaat via [Aspose.Total for Java](https://products.aspose.com/total/java/) is een eenvoudig proces in twee stappen. Door gebruik te maken van de veelzijdige API voor Documentmanipulatie en conversie [Aspose.Words for Java](https://products.aspose.com/words/java/), kunt u DOTX naar HTML exporteren. Daarna kunt u met [Aspose.Cells for Java](https://products.aspose.com/cells/java/) HTML naar JSON converteren.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converteer DOTX naar JSON-formaat via Java" %}}
1. Open het DOTX-bestand met de klasse [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. Converteer DOTX naar HTML met behulp van [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) methode:
3. Laad HTML-Document met behulp van [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) klasse
4. Sla het Document op in JSON-indeling met [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) methode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total voor Java gemakkelijk rechtstreeks vanuit een op [Maven](https://releases.aspose.com/total/java/) gebaseerd project gebruiken en neem bibliotheken op in uw po.xml.

U kunt ook een ZIP-bestand krijgen van [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ConversievereistenDocument" %}}
Met behulp van de API kunt u ook het met een wachtwoord beveiligde Document openen. Als uw DOTX-invoerDocument met een wachtwoord is beveiligd, kunt u het niet converteren naar JSON-indeling zonder het wachtwoord te gebruiken. Met de API kunt u het gecodeerde Document openen door het juiste wachtwoord in een LoadOptions-object door te geven. Het volgende codevoorbeeld laat zien hoe u kunt proberen een versleuteld Document met een wachtwoord te openen:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converteer beveiligde DOTX naar JSON-indeling via Java" %}}
Terwijl u DOTX naar JSON converteert, kunt u het bereik ook instellen op uw JSON-uitvoerformaat. Om het bereik in te stellen, kunt u de geconverteerde HTML openen met behulp van de Workbook-klasse, een gegevensbereik maken dat moet worden geëxporteerd met behulp van de Cells.createRange-methode, de JsonUtility.exportRangeToJson-methode aanroepen met verwijzingen naar Range & ExportRangeToJsonOptions en string-JSON-gegevens naar het bestand schrijven via BufferedWriter.write-methode. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}