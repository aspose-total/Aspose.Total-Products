---
title: Java API om MHTML naar CSV te renderen
description: Exporteer MHTML naar CSV via Java API zonder Microsoft Excel of Adobe Reader te gebruiken
url_ignore: /nl/java/conversion/mhtml-to-csv/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: CSV
otherformats: XLSM TXT ODS XLT FODS TSV XLTM XLTX SXC XLSB MD XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="MHTML exporteren naar CSV via Java" h2="Converteer MHTML-bestand naar CSV met behulp van on-premise Java API binnen alle Java J2SE-, J2EE-, J2ME-applicaties" >}}
{{% blocks/products/pf/feature-page-summary %}}
Door [Aspose.Total for Java](https://products.aspose.com/total/java/) te gebruiken, kunt u de conversiefunctie van MHTML naar CSV in uw Java-toepassingen integreren in een proces van twee stappen. Ten eerste, door [Aspose.PDF voor Java](https://products.aspose.com/pdf/java/) te gebruiken, kunt u MHTML naar XLSX renderen. In de tweede stap kunt u XLSX naar CSV converteren met behulp van de Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converteer MHTML-bestand naar CSV via Java" %}}
1. Open het MHTML-bestand met de klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converteer MHTML naar XLSX met behulp van [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) methode:
3. Laad XLSX-document met behulp van de klasse [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Sla het document op in CSV-indeling met [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) methode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total voor Java gemakkelijk rechtstreeks vanuit een op [Maven](https://releases.aspose.com/total/java/) gebaseerd project gebruiken en bevatten [Aspose.PDF voor Java](https://docs.aspose.com/pdf/java/installation/) en [Aspose.Cells voor Java](https://docs.aspose.com/cells/java/installation/) in uw po.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Conversievereisten" %}}
Als uw MHTML-document met een wachtwoord is beveiligd, kunt u het niet converteren naar CSV zonder het wachtwoord. Met behulp van de API kunt u eerst het beveiligde document openen met een geldig wachtwoord en het daarna converteren. Om het versleutelde bestand te openen, kunt u een nieuwe instantie van het [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class en geef bestandsnaam en wachtwoord door als argumenten.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converteer beveiligde MHTML naar CSV via Java" %}}
Tijdens het converteren van het MHTML-bestand naar CSV, kunt u ook een watermerk toevoegen aan uw uitvoer-CSV-bestandsformaat. Om een watermerk toe te voegen, maakt u een nieuwe werkmap om het geconverteerde XLSX-bestand te openen. Selecteer werkblad via de index, maak een vorm en gebruik de functie addTextEffect, stel kleuren, transparantie en meer in. Daarna kunt u uw XLSX-document opslaan als CSV met Watermark. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}