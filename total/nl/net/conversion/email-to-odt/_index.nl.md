---
title: C# API om EMAIL naar ODT te exporteren
description: Converteer EMAIL naar ODT zonder Microsoft Word of Outlook te gebruiken op .NET
url_ignore: /nl/net/conversion/email-to-odt/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: ODT
otherformats: OTT JPEG MD DOCM PCL EMF PS DOT DOCX TEXT PNG ODT DOC DOTM FLATOPC SVG PDF RTF TIFF EPUB DOTX XPS GIF WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporteer EMAIL naar ODT via .NET" h2=".NET API om EMAIL naar ODT te renderen op Windows, macOS en Linux zonder Word of Outlook te gebruiken" >}}

{{% blocks/products/pf/feature-page-summary %}}
Als u een .NET-ontwikkelaar bent die EMAIL-naar-ODT-conversiefuncties in uw toepassingen wilt toevoegen, zijn [Aspose.Total for .NET](https://products.aspose.com/total/net/) bestandsformaatmanipulatie-API's de juiste keuze vooruit. Door [Aspose.Email for .NET](https://products.aspose.com/email/net/) te gebruiken, kunt u het EMAIL-bestandsformaat converteren naar HTML. Daarna kunt u met [Aspose.Words for .NET](https://products.aspose.com/words/net/) HTML naar ODT renderen.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API om EMAIL naar ODT te converteren" %}}
1. Open het EMAIL-bestand met de klasse [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Converteer EMAIL naar HTML met behulp van de [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) methode
3. Laad HTML met behulp van [Document](https://reference.aspose.com/words/net/aspose.words/document) klasse
4. Sla het document op in ODT-indeling met de methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) en stel Odt in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="E-MAIL-bestand ontleden via .NET" %}}
Voordat u EMAIL naar ODT converteert, kunt u, als u er zeker van wilt zijn dat u de juiste e-mail converteert, het EMAIL-document laden, het ontleden en uw gewenste eigenschap bekijken. Door gebruik te maken van [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) klasse van [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, kunt u informatie over afzender en ontvanger krijgen. U kunt bijvoorbeeld controleren op een specifiek e-mailadres van de afzender voor de conversie door de eigenschap [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) te gebruiken.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Beperk het bewerken van ODT-documenten via .NET" %}}
Terwijl u het document opslaat van EMAIL naar ODT, moet u mogelijk uw uitvoerdocument beveiligen. Soms moet u de mogelijkheid om een document te bewerken beperken en er alleen bepaalde acties mee toestaan. Dit kan handig zijn om te voorkomen dat andere mensen gevoelige en vertrouwelijke informatie in uw document bewerken. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, stelt u in staat om te bepalen hoe u de inhoud beperkt met behulp van het [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) opsommingsparameter. U kunt uw document op alleen-lezen instellen door de volgende coderegels te gebruiken. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.odt", SaveFormat.Odt);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EMAIL-bestand programmatisch naar ODT transformeren: gebruiksscenario's" %}}
Het omzetten van E-mails naar ODT-bestanden wordt gebruikt om schriftelijke inhoud op te slaan, waardoor dit ideaal is voor het maken van formele documenten en presentaties. Tijdens het werken met multimedia-gegevens worden OpenDocument Text-bestanden essentieel voor het visualiseren en analyseren van de documenten.

Het omzetten van E-mailbestanden naar ODT-formaten is nodig om de volledige potentie van je documentbewerking en presentatietalenten te ontplozen. Deze conversie maakt het mogelijk om:

**Gebruiksdoelen:**

*   **Formele Documenten Creëren**: E-mails omzetten naar formele rapporten, voorstellen en presentaties, waardoor dit ideaal is voor professioneel gebruik.
*   **Bedrijfscommunicatie Optimaliseren**: ODT-bestanden gebruiken om bedrijfsberichten, persmedeelingen en marketingmateriaal te visualiseren, waardoor interne en externe communicatie wordt geoptimaliseerd.
*   **Academisch Onderzoek en Samenwerken**: E-mails omzetten naar wetenschappelijke publicaties, essays en dissertaties, waardoor samenwerking onderzoeksers en academici wordt bevorderd.
*   **Digitale Publicatie en E-Learning**: ODT-bestanden gebruiken om educatieve inhoud te formaten, online cursussen en digitale publicaties te maken, waardoor het leren meer aantrekkelijk en toegankelijk wordt.
*   **Gegevensgestuurde Documentanalyse**: E-mails omzetten naar geschreven gegevens, waardoor inzichten kunnen worden getrokken, trends geïdentificeerd en wijzigingen in bedrijfscommunicatie kunnen worden gemonitorde.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}