---
title: Konvertera DOCM till JSON-format via Java
description: Konvertera DOCM till JSON-format via Java utan att använda Microsoft Word eller Microsoft Excel
url_ignore: /sv/java/conversion/docm-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: JSON
otherformats: XLT XLTM FODS SXC XLAM XLS EXCEL ODS XLSM DIF XLSB XLTX TSV CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertera DOCM till JSON-format via Java" h2="On Premise Java API för att konvertera DOCM till JSON utan att använda Microsoft<sup>&reg;</sup> Word eller Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Att konvertera DOCM till JSON-format via [Aspose.Total for Java](https://products.aspose.com/total/java/) är en enkel process i två steg. Genom att använda funktionsrika, dokumentmanipulerings- och konverterings-API [Aspose.Words for Java](https://products.aspose.com/words/java/), kan du exportera DOCM till HTML. Efter det, genom att använda [Aspose.Cells for Java](https://products.aspose.com/cells/java/), kan du konvertera HTML till JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera DOCM till JSON-format via Java" %}}
1. Öppna DOCM-filen med klassen [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. Konvertera DOCM till HTML genom att använda [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) metod
3. Ladda HTML-dokument genom att använda klassen [Arbetsbok](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Spara dokumentet i JSON-format med [Spara](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metod
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Java direkt från ett [Maven](https://releases.aspose.com/total/java/) baserat projekt och inkludera bibliotek i din pom.xml.

Alternativt kan du få en ZIP-fil från [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverteringskrav" %}}
Med hjälp av API:t kan du också öppna det lösenordsskyddade dokumentet. Om ditt inmatade DOCM-dokument är lösenordsskyddat kan du inte konvertera det till JSON-format utan att använda lösenordet. API:et låter dig öppna det krypterade dokumentet genom att skicka in rätt lösenord i ett LoadOptions-objekt. Följande kodexempel visar hur du försöker öppna ett krypterat dokument med ett lösenord:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertera skyddad DOCM till JSON-format via Java" %}}
Medan du konverterar DOCM till JSON kan du också ställa in intervallet för ditt utdata-JSON-format. För att ställa in intervallet kan du öppna den konverterade HTML-koden med Workbook-klassen, skapa ett dataområde som ska exporteras med metoden Cells.createRange, anropa metoden JsonUtility.exportRangeToJson med referenser till Range & ExportRangeToJsonOptions och skriva sträng JSON-data till fil via BufferedWriter.write-metoden. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
## ✅ Viktiga användningsfall  

- **Publicera dokumentdata till REST/GraphQL-API:er**  
  Servera extraherat DOCM-innehåll som JSON för direkt användning i webb- och mobilappar.  

- **Mata NoSQL-databaser och datalager**  
  Ladda DOCM-avledat strukturerat data in i MongoDB, Elasticsearch eller molnbaserade datalager.  

- **Driva instrumentpaneler med realtids-JSON-flöden**  
  Strömma dokumentbaserade KPI:er och mätetal till BI-instrumentpaneler och övervakningsverktyg.  

- **Validera inmatningar mot JSON-schema**  
  Se till att konsistens och integritet upprätthålls genom att anpassa DOCM-fältdata med JSON-schema-regler.  

- **Möjliggöra headless CMS eller mikrotjänstarkitekturer**  
  Integrera DOCM-innehåll i distribuerade system med API-först där JSON är lingua franca.  

## ⚙️ Automatiseringsscenario  

- **DOCM-till-JSON-extraktion med fältmappning**  
  Definiera mappningar för att omvandla tabeller, rubriker och fält till strukturerade JSON-objekt.  

- **Serverlösa funktioner som konverterar och sänder JSON-händelser**  
  Utlös konverteringar vid filuppladdning och sänd JSON-payloads till händelsestyrda system.  

- **ETL-jobb som normaliserar typer och nycklar**  
  Standardisera DOCM-exporter till konsekventa JSON-strukturer för efterföljande analys.  

- **Webhooks som skickar JSON till efterföljande system**  
  Automatisera DOCM-till-JSON-exporter som matar CRM-system, ERP-verktyg eller appar från tredje part.  

- **Styrningsregler som tar bort makron och PII innan JSON-export**  
  Tillämpa efterlevnadsregler för att säkerställa säkra, sanerade JSON-utdata från makroaktiverade filer.  
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}