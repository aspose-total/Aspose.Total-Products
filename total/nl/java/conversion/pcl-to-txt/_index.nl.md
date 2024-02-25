---
title: Java API om PCL naar TXT te renderen
description: Exporteer PCL naar TXT via Java API zonder Microsoft Excel of Adobe Reader te gebruiken
url_ignore: /nl/java/conversion/pcl-to-txt/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: TXT
otherformats: TXT DIF MD XLSB FODS XLSM XLT SXC ODS XLAM TSV XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="PCL exporteren naar TXT via Java" h2="Converteer PCL-bestand naar TXT met behulp van on-premise Java API binnen alle Java J2SE-, J2EE-, J2ME-applicaties" >}}
{{% blocks/products/pf/feature-page-summary %}}
Door [Aspose.Total for Java](https://products.aspose.com/total/java/) te gebruiken, kunt u de conversiefunctie van PCL naar TXT in uw Java-toepassingen integreren in een proces van twee stappen. Ten eerste, door [Aspose.PDF voor Java](https://products.aspose.com/pdf/java/) te gebruiken, kunt u PCL naar XLSX renderen. In de tweede stap kunt u XLSX naar TXT converteren met behulp van de Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converteer PCL-bestand naar TXT via Java" %}}
1. Open het PCL-bestand met de klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converteer PCL naar XLSX met behulp van [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) methode:
3. Laad XLSX-document met behulp van de klasse [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Sla het document op in TXT-indeling met [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) methode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total voor Java gemakkelijk rechtstreeks vanuit een op [Maven](https://releases.aspose.com/total/java/) gebaseerd project gebruiken en bevatten [Aspose.PDF voor Java](https://docs.aspose.com/pdf/java/installation/) en [Aspose.Cells voor Java](https://docs.aspose.com/cells/java/installation/) in uw po.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Conversievereisten" %}}
Als uw PCL-document met een wachtwoord is beveiligd, kunt u het niet converteren naar TXT zonder het wachtwoord. Met behulp van de API kunt u eerst het beveiligde document openen met een geldig wachtwoord en het daarna converteren. Om het versleutelde bestand te openen, kunt u een nieuwe instantie van het [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class en geef bestandsnaam en wachtwoord door als argumenten.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converteer beveiligde PCL naar TXT via Java" %}}
Tijdens het converteren van het PCL-bestand naar TXT, kunt u ook een watermerk toevoegen aan uw uitvoer-TXT-bestandsformaat. Om een watermerk toe te voegen, maakt u een nieuwe werkmap om het geconverteerde XLSX-bestand te openen. Selecteer werkblad via de index, maak een vorm en gebruik de functie addTextEffect, stel kleuren, transparantie en meer in. Daarna kunt u uw XLSX-document opslaan als TXT met Watermark. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}