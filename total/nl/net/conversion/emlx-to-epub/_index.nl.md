---
title: C# API om EMLX naar EPUB te exporteren
description: Converteer EMLX naar EPUB zonder Microsoft Word of Outlook te gebruiken op .NET
url_ignore: /nl/net/conversion/emlx-to-epub/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: EPUB
otherformats: GIF OTT PCL PS EMF RTF DOCM TEXT XPS PNG DOCX DOT EPUB ODT MD FLATOPC DOTM DOTX DOC JPEG WORDML PDF SVG TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporteer EMLX naar EPUB via .NET" h2=".NET API om EMLX naar EPUB te renderen op Windows, macOS en Linux zonder Word of Outlook te gebruiken" >}}

{{% blocks/products/pf/feature-page-summary %}}
Als u een .NET-ontwikkelaar bent die EMLX-naar-EPUB-conversiefuncties in uw toepassingen wilt toevoegen, zijn [Aspose.Total for .NET](https://products.aspose.com/total/net/) bestandsformaatmanipulatie-API's de juiste keuze vooruit. Door [Aspose.Email for .NET](https://products.aspose.com/email/net/) te gebruiken, kunt u het EMLX-bestandsformaat converteren naar HTML. Daarna kunt u met [Aspose.Words for .NET](https://products.aspose.com/words/net/) HTML naar EPUB renderen.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API om EMLX naar EPUB te converteren" %}}
1. Open het EMLX-bestand met de klasse [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Converteer EMLX naar HTML met behulp van de [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) methode
3. Laad HTML met behulp van [Document](https://reference.aspose.com/words/net/aspose.words/document) klasse
4. Sla het document op in EPUB-indeling met de methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) en stel Epub in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.emlx");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.epub", SaveFormat.Epub); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="E-MAIL-bestand ontleden via .NET" %}}
Voordat u EMLX naar EPUB converteert, kunt u, als u er zeker van wilt zijn dat u de juiste e-mail converteert, het EMLX-document laden, het ontleden en uw gewenste eigenschap bekijken. Door gebruik te maken van [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) klasse van [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, kunt u informatie over afzender en ontvanger krijgen. U kunt bijvoorbeeld controleren op een specifiek e-mailadres van de afzender voor de conversie door de eigenschap [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) te gebruiken.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EMLX file from disk
var outlookMessageFile = MapiMessage.FromFile("message.emlx");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Beperk het bewerken van EPUB-documenten via .NET" %}}
Terwijl u het document opslaat van EMLX naar EPUB, moet u mogelijk uw uitvoerdocument beveiligen. Soms moet u de mogelijkheid om een document te bewerken beperken en er alleen bepaalde acties mee toestaan. Dit kan handig zijn om te voorkomen dat andere mensen gevoelige en vertrouwelijke informatie in uw document bewerken. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, stelt u in staat om te bepalen hoe u de inhoud beperkt met behulp van het [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) opsommingsparameter. U kunt uw document op alleen-lezen instellen door de volgende coderegels te gebruiken. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.epub", SaveFormat.Epub);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EMLX-bestand programmatisch naar EPUB transformeren: gebruiksscenario's" %}}
EMLX (Electronic Mail with X-Based Headers)-bestanden worden gebruiken om e-mailinformatie op te slaan, waardoor ze ideaal zijn voor het maken van statische e-mails en berichtenarchieven. Tijdens het werken met dynamisch inhoud wordt de ePUB-formaat noodzakelijk voor digitale publicatie en online contentdistributie.

Het omzetten van EMLX-bestanden naar ePUB-formaten is nodig om de volledige potentie van uw digitale publicatiemogelijkheden en online contentdistributiemiddelen te ontsluiten. Dit omzetten maakt het mogelijk om:

**Gebruikscases:**

*   **Digitale Publicatie**: Omzetten van EMLX-bestanden naar interactieve digitale tijdschriften, kranten en boeken maken ze toegankelijk op meerdere apparaten.  
*   **E-learning Content Distribution**: Gebruiken van ePUB voor het publiceren van online cursussen, handleidingen en beroepsopleidingen, wat de leerervaring van studenten en professionals verbetert.  
*   **Online Artikel Publicatie**: Omzetten van EMLX-bestanden naar zichtbaarere artikelen, verhalen en blogposts, waardoor online betrokkenheid en lezersvrijheid worden vergroot.  
*   **Digitale Comics en Romans**: Gebruiken van ePUB om digitale strips, romans en andere vormen van interactieve vertellingen te bewaren en te distribueren, waardoor lezers een unieke leeservaring krijgen.  
*   **Website Content Syndication**: Omzetten van EMLX-bestanden naar dynamisch webcontent, zoals artikelen, productbeschrijvingen en klantgetuigenissen, wat de gebruikersbetrokkenheid en omzetsnelheid van uw website verbetert.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}