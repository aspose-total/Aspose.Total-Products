---
title: C# API om EML naar ODT te exporteren
description: Converteer EML naar ODT zonder Microsoft Word of Outlook te gebruiken op .NET
url_ignore: /nl/net/conversion/eml-to-odt/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: ODT
otherformats: DOCX TEXT PNG WORDML DOC ODT FLATOPC EMF DOCM DOTM PDF XPS RTF PCL MD JPEG DOT TIFF SVG OTT GIF DOTX PS EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporteer EML naar ODT via .NET" h2=".NET API om EML naar ODT te renderen op Windows, macOS en Linux zonder Word of Outlook te gebruiken" >}}

{{% blocks/products/pf/feature-page-summary %}}
Als u een .NET-ontwikkelaar bent die EML-naar-ODT-conversiefuncties in uw toepassingen wilt toevoegen, zijn [Aspose.Total for .NET](https://products.aspose.com/total/net/) bestandsformaatmanipulatie-API's de juiste keuze vooruit. Door [Aspose.Email for .NET](https://products.aspose.com/email/net/) te gebruiken, kunt u het EML-bestandsformaat converteren naar HTML. Daarna kunt u met [Aspose.Words for .NET](https://products.aspose.com/words/net/) HTML naar ODT renderen.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API om EML naar ODT te converteren" %}}
1. Open het EML-bestand met de klasse [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Converteer EML naar HTML met behulp van de [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) methode
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
Voordat u EML naar ODT converteert, kunt u, als u er zeker van wilt zijn dat u de juiste e-mail converteert, het EML-document laden, het ontleden en uw gewenste eigenschap bekijken. Door gebruik te maken van [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) klasse van [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, kunt u informatie over afzender en ontvanger krijgen. U kunt bijvoorbeeld controleren op een specifiek e-mailadres van de afzender voor de conversie door de eigenschap [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) te gebruiken.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Beperk het bewerken van ODT-documenten via .NET" %}}
Terwijl u het document opslaat van EML naar ODT, moet u mogelijk uw uitvoerdocument beveiligen. Soms moet u de mogelijkheid om een document te bewerken beperken en er alleen bepaalde acties mee toestaan. Dit kan handig zijn om te voorkomen dat andere mensen gevoelige en vertrouwelijke informatie in uw document bewerken. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, stelt u in staat om te bepalen hoe u de inhoud beperkt met behulp van het [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) opsommingsparameter. U kunt uw document op alleen-lezen instellen door de volgende coderegels te gebruiken. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.odt", SaveFormat.Odt);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EML-bestand programmatisch naar ODT transformeren: gebruiksscenario's" %}}
Bestanden EML (Elektronische Post) worden gebruikt om tekstgebaseerd email- inhoud te bewaren, waardoor ze ideaal zijn voor het maken van eenvoudige, platte teksten. Tijdens het werken met meer geavanceerde documentfuncties worden echter OpenDocument Text-formats (.odt) essentieel voor het bewerken en opmaken.

De omzetting van EML-bestanden naar ODT-formats is nodig om volledige documentbewerkingscapaciteiten te ontsluiten. Dit maakt het mogelijk om:

**Gebruikscases:**

* **Inhoud bewerken**: Om EML-bestanden te converten voor het bewerken van inhoud, het opmaken van tekst en het toevoegen van multimediale elementen.
* **Samenwerken**: Gebruiken van ODT-formats om met anderen in real-time samen te werken, documenten te delen en wijzigingen door te sporen.
* **Sjablonen maken**: Om EML-bestanden te converten voor het maken van hergebrukbare sjablonen voor consistent branding en messaging.
* **Toegankelijkheid verbeteren**: Gebruiken van ODT-formats om documenten toegankelijker te maken, bijv. door lettergrootte aan te passen en contrastmodi's toe te voegen.
* **Integratie met andere tools**: Om EML-bestanden te converten voor integratie met andere kantoorsoftware, zoals Google Docs of Microsoft Word, voor een vloeiende workflow.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}