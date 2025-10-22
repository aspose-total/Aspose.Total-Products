---
title: Java API om PS naar OTT te exporteren
description: Converteer PS naar OTT met behulp van on-premise Java API
url_ignore: /nl/java/conversion/ps-to-ott/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: OTT
otherformats: MHTML RTF FLATOPC MARKDOWN OTT WORDML ODT DOTX DOTM XAMLFLOW DOT PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Transformeer PS naar OTT via Java" h2="On Premise Java API om PS naar OTT te renderen zonder een applicatie van derden te gebruiken" >}}
{{% blocks/products/pf/feature-page-summary %}}
U kunt PS naar OTT converteren met behulp van twee eenvoudige stappen. Eerst moet u het PS-bestand naar DOC renderen met [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Daarna kunt u met behulp van de krachtige API voor documentverwerking [Aspose.Words for Java](https://products.aspose.com/words/java/) DOC naar OTT converteren. Beide API's vallen onder het pakket [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API om PS naar OTT te converteren" %}}
1. Open het PS-bestand met de klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converteer PS naar DOC met behulp van [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) methode:
3. Laad het DOC-bestand met behulp van de [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) klasse van Aspose.Words
4. Sla het document op in OTT-formaat met behulp van [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) methode en stel OTT in als OpslaanFormaat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total voor Java gemakkelijk rechtstreeks vanuit een op [Maven](https://releases.aspose.com/total/java/) gebaseerd project gebruiken en bevatten [Aspose.PDF voor Java](https://docs.aspose.com/pdf/java/installation/) en [Aspose.Words voor Java](https://docs.aspose.com/words/java/installation/) in uw po.xml.

U kunt ook een ZIP-bestand krijgen van [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "f5707d58ebee8d2889c8dbe5aa739d87" "convert-ps-to-ott.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Conversievereisten" %}}
Tijdens het converteren van PS naar OTT kunt u, zelfs als uw document met een wachtwoord is beveiligd, het nog steeds openen met de PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Om het versleutelde bestand te openen, moet u een [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)-object maken en de PS openen met het wachtwoord van de eigenaar.  
{{% blocks/products/pf/feature-page-code %}}
```cs
// open encrypted document
Document document = new Document("input.ps", "password");
// save PS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Open met een wachtwoord beveiligd PS-document via Java" %}}
Terwijl u uw invoerdocument opslaat in OTT-bestandsindeling, kunt u uw document ook opslaan in een database in plaats van in een bestandssysteem. Mogelijk moet u het opslaan en ophalen van documentobjecten van en naar een database implementeren. Dit zou nodig zijn als u een inhoudsbeheersysteem zou implementeren. Om uw OTT in de database op te slaan, is het vaak nodig om het document te serialiseren om een bytearray te verkrijgen. Dit kan worden gedaan met behulp van [Aspose.Words for Java](https://products.aspose.com/words/Java/) API. Nadat u uw byte-array hebt ontvangen, kunt u deze in de database opslaan met behulp van een SQL-instructie. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.OTT);
    // get the byte array from output steam
    // the byte array now contains the document
    byte[] buffer = aout.toByteArray();
    // get the filename from the document.
    String fileName = doc.getOriginalFileName();
    String filePath = fileName.replace("\\", "\\\\");
    // create the SQL command.
    String commandString = "INSERT INTO Documents (FileName, FileContent) VALUES('" + filePath + "', '" + buffer + "')";
    Statement statement = mConnection.createStatement();
    statement.executeUpdate(commandString);
}  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}

Het omzetten van PS (PostScript)-bestanden naar OTT (OpenDocument Tekstsjabloon) stelt teams in staat om gestandaardiseerde, herbruikbare tekstsjablonen voor documenten te maken. OTT-sjablonen zijn ideaal voor terugkerende rapporten, brieven of formulieren, waarbij gebruik wordt gemaakt van PostScript-indelingen voor consistente opmaak.

{{% blocks/products/pf/agp/feature-section-col title="Belangrijkste Gebruiksscenario's" %}}

* Het creëren van herbruikbare tekstsjablonen van op PS gebaseerde rapporten en documenten.
* Standaardiseren van brieven, formulieren en interne rapporten binnen teams.
* Het omzetten van PS gegenereerde handleidingen naar bewerkbare OTT-sjablonen.
* Voorbereiden van PostScript-indelingen voor terugkerende documentatie in open-source omgevingen.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Automatiseringsscenario's" %}}

* Batch PS-naar-OTT conversie voor sjabloonbibliotheken in zakelijke omgevingen.
* Integratie in documentbeheersystemen voor implementatie van herbruikbare sjablonen.
* Geautomatiseerde workflow voor het omzetten van PostScript-bestanden naar OTT voor herhaald gebruik.
* AI-gestuurde extractie en opmaak van PS-indelingen naar tekstsjablonen.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}