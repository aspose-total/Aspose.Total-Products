---
title: Converteer PPS naar JSON-formaat via Java
description: Converteer PPS naar JSON-formaat via Java zonder Microsoft Excel of PowerPoint te gebruiken
url_ignore: /nl/java/conversion/pps-to-json/
family: total
platformtag: net
feature: conversion
informat: PPS
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converteer PPS naar JSON-formaat via Java" h2="On Premise Java API om PPS naar JSON te exporteren zonder Microsoft<sup>&reg;</sup> Excel of PowerPoint te gebruiken" >}}
{{% blocks/products/pf/feature-page-summary %}}
Het converteren van PPS naar JSON-formaat via [Aspose.Total for Java](https://products.aspose.com/total/java/) is een eenvoudig proces in twee stappen. In de eerste stap kunt u PPS naar HTML exporteren met [Aspose.Slides for Java](https://products.aspose.com/slides/java/). Ten tweede kunt u met [Aspose.Cells for Java](https://products.aspose.com/cells/java/) HTML naar JSON converteren.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converteer PPS naar JSON-formaat via Java" %}}
1. Open het PPS-bestand met de klasse [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Converteer PPS naar HTML met behulp van [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) methode
3. Laad HTML-document met behulp van [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) klasse
4. Sla het document op in JSON-indeling met [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) methode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total voor Java gemakkelijk rechtstreeks vanuit een op [Maven](https://releases.aspose.com/total/java/) gebaseerd project gebruiken en neem bibliotheken op in uw po.xml.

U kunt ook een ZIP-bestand krijgen van [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Conversievereisten" %}}
Met behulp van de API kunt u ook het met een wachtwoord beveiligde document openen. Als uw invoer-PPS-document met een wachtwoord is beveiligd, kunt u het niet converteren naar JSON-indeling zonder het wachtwoord te gebruiken. Met de API kunt u het gecodeerde document openen door het juiste wachtwoord in een LoadOptions-object door te geven.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converteer beveiligde PPS naar JSON-indeling via Java" %}}
Terwijl u PPS naar JSON converteert, kunt u het bereik ook instellen op uw output-JSON-formaat. Om het bereik in te stellen, kunt u de geconverteerde HTML openen met behulp van de Workbook-klasse, een gegevensbereik maken dat moet worden geëxporteerd met behulp van de Cells.createRange-methode, de JsonUtility.exportRangeToJson-methode aanroepen met verwijzingen naar Range & ExportRangeToJsonOptions en string-JSON-gegevens naar het bestand schrijven via BufferedWriter.write-methode. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}