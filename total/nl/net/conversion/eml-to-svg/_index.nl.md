---
title: C# API om EML naar SVG te exporteren
description: Converteer EML naar SVG zonder Microsoft Word of Outlook te gebruiken op .NET
url_ignore: /nl/net/conversion/eml-to-svg/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: SVG
otherformats: DOCX OTT PS DOTX WORDML GIF PNG SVG ODT RTF DOC PCL XPS MD DOT JPEG TIFF EMF TEXT PDF FLATOPC EPUB DOCM DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporteer EML naar SVG via .NET" h2=".NET API om EML naar SVG te renderen op Windows, macOS en Linux zonder Word of Outlook te gebruiken" >}}

{{% blocks/products/pf/feature-page-summary %}}
Als u een .NET-ontwikkelaar bent die EML-naar-SVG-conversiefuncties in uw toepassingen wilt toevoegen, zijn [Aspose.Total for .NET](https://products.aspose.com/total/net/) bestandsformaatmanipulatie-API's de juiste keuze vooruit. Door [Aspose.Email for .NET](https://products.aspose.com/email/net/) te gebruiken, kunt u het EML-bestandsformaat converteren naar HTML. Daarna kunt u met [Aspose.Words for .NET](https://products.aspose.com/words/net/) HTML naar SVG renderen.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API om EML naar SVG te converteren" %}}
1. Open het EML-bestand met de klasse [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Converteer EML naar HTML met behulp van de [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) methode
3. Laad HTML met behulp van [Document](https://reference.aspose.com/words/net/aspose.words/document) klasse
4. Sla het document op in SVG-indeling met de methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) en stel Svg in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.eml");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.svg", SaveFormat.Svg); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="E-MAIL-bestand ontleden via .NET" %}}
Voordat u EML naar SVG converteert, kunt u, als u er zeker van wilt zijn dat u de juiste e-mail converteert, het EML-document laden, het ontleden en uw gewenste eigenschap bekijken. Door gebruik te maken van [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) klasse van [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, kunt u informatie over afzender en ontvanger krijgen. U kunt bijvoorbeeld controleren op een specifiek e-mailadres van de afzender voor de conversie door de eigenschap [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) te gebruiken.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EML file from disk
var outlookMessageFile = MapiMessage.FromFile("message.eml");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Beperk het bewerken van SVG-documenten via .NET" %}}
Terwijl u het document opslaat van EML naar SVG, moet u mogelijk uw uitvoerdocument beveiligen. Soms moet u de mogelijkheid om een document te bewerken beperken en er alleen bepaalde acties mee toestaan. Dit kan handig zijn om te voorkomen dat andere mensen gevoelige en vertrouwelijke informatie in uw document bewerken. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, stelt u in staat om te bepalen hoe u de inhoud beperkt met behulp van het [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) opsommingsparameter. U kunt uw document op alleen-lezen instellen door de volgende coderegels te gebruiken. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.svg", SaveFormat.Svg);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EML-bestand programmatisch naar SVG transformeren: gebruiksscenario's" %}}
**Bestand EML (Electronic Mail)** wordt gebruikt om tekstgebaseerde berichten op te slaan, waardoor het ideaal is voor het verzenden en ontvangen van e-mails. Maar wanneer werken we met grafische gegevens, worden SVG-bestanden (Scalable Vector Graphics) essentieel voor het maken van schaalbare en resoluatie-onafhankelijke graphics.

De omzetting van EML-bestanden naar SVG-formaten is nodig om de volledige potentie van je grafische gegevensvisualisatie en analyse te ontsluiten. Deze omzetting maakt het mogelijk om:

**Toepassingen:**

* **Webdesign voor Grafische Ontwerpen**: Omzetten van EML-bestanden naar vectorgebaseerde webgraphics, logotipen en icoontjes die schalen met verschillende schermresoluties.
* **Desktop Publishing**: Gebruik van SVG voor het visualiseren van complexe grafische gegevens, zoals diagrammen, grafiek en infografieken, in publicaties en presentaties.
* **Ontwikkeling van Mobiele Apps**: Omzetten van EML-bestanden naar schaalbare graphics en illustraties voor mobiele apps, waardoor een consistent gebruikerservaring ontstaat across devices.
* **Creatie van Leercontent voor Electronische Lesmaterialen**: Gebruik van SVG voor het maken van interactieve en aantrekkelijke visualisaties voor elektronisch lesmateriaal, zoals animatie-leringen en simulaties.
* **Data Visualisatie en Rapportage**: Omzetten van EML-bestanden naar interactieve dashboards, rapporten en visualisaties voor stakeholders, waardoor betere beslissingen worden mogelijk gemaakt.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}