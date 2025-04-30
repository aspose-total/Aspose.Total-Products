---
title: C# API om EML naar TIFF te exporteren
description: Converteer EML naar TIFF zonder Microsoft Word of Outlook te gebruiken op .NET
url_ignore: /nl/net/conversion/eml-to-tiff/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: TIFF
otherformats: TIFF GIF XPS DOTX SVG ODT PCL DOCM PDF DOC PS RTF MD EPUB PNG FLATOPC DOTM DOCX EMF WORDML JPEG OTT DOT TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporteer EML naar TIFF via .NET" h2=".NET API om EML naar TIFF te renderen op Windows, macOS en Linux zonder Word of Outlook te gebruiken" >}}

{{% blocks/products/pf/feature-page-summary %}}
Als u een .NET-ontwikkelaar bent die EML-naar-TIFF-conversiefuncties in uw toepassingen wilt toevoegen, zijn [Aspose.Total for .NET](https://products.aspose.com/total/net/) bestandsformaatmanipulatie-API's de juiste keuze vooruit. Door [Aspose.Email for .NET](https://products.aspose.com/email/net/) te gebruiken, kunt u het EML-bestandsformaat converteren naar HTML. Daarna kunt u met [Aspose.Words for .NET](https://products.aspose.com/words/net/) HTML naar TIFF renderen.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API om EML naar TIFF te converteren" %}}
1. Open het EML-bestand met de klasse [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Converteer EML naar HTML met behulp van de [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) methode
3. Laad HTML met behulp van [Document](https://reference.aspose.com/words/net/aspose.words/document) klasse
4. Sla het document op in TIFF-indeling met de methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) en stel Tiff in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="E-MAIL-bestand ontleden via .NET" %}}
Voordat u EML naar TIFF converteert, kunt u, als u er zeker van wilt zijn dat u de juiste e-mail converteert, het EML-document laden, het ontleden en uw gewenste eigenschap bekijken. Door gebruik te maken van [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) klasse van [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, kunt u informatie over afzender en ontvanger krijgen. U kunt bijvoorbeeld controleren op een specifiek e-mailadres van de afzender voor de conversie door de eigenschap [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) te gebruiken.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Beperk het bewerken van TIFF-documenten via .NET" %}}
Terwijl u het document opslaat van EML naar TIFF, moet u mogelijk uw uitvoerdocument beveiligen. Soms moet u de mogelijkheid om een document te bewerken beperken en er alleen bepaalde acties mee toestaan. Dit kan handig zijn om te voorkomen dat andere mensen gevoelige en vertrouwelijke informatie in uw document bewerken. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, stelt u in staat om te bepalen hoe u de inhoud beperkt met behulp van het [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) opsommingsparameter. U kunt uw document op alleen-lezen instellen door de volgende coderegels te gebruiken. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.tiff", SaveFormat.Tiff);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EML-bestand programmatisch naar TIFF transformeren: gebruiksscenario's" %}}
Bestand EML (Electronic Mail) wordt gebruikt om tekstgebaseerd berichten te bewaren, waardoor het ideaal is voor het verzenden en ontvangen van e-mails. echter, wanneer werken met afbeeldingen, worden formaten zoals TIFF (Tagged Image File Format) essentieel voor het behouden en manipuleren van hoogwaardige afbeeldingen.

De omzetting van EML-bestanden naar TIFF-formaten is nodig om de volledige capaciteiten van uw gegevens in beeld te ontkrachten. deze omzetting maakt het mogelijk om:

**Toepassingsgebieden:**

*   **Medische afbeeldingenanalyse**: Omzetten van EML-bestanden naar TIFF voor het analyseren van medische afbeeldingen, het bijhouden van de progressie van patiënten en het herkennen van patronen in de gegevens.
*   **Archivalering en behoud**: Gebruiken van TIFF om hoogwaardige afbeeldingen te bewaren voor archivarisering, waardoor digitale artifacten blijven stabiliseren over tijd.
*   **Afbeeldingen bewerken en verbeteren**: Omzetten van EML-bestanden naar TIFF voor het maken en bewerken van afbeeldingen, waarbij filters, aanpassingen en effecten worden toegepast om gewenste resultaten te bereiken.
*   **Wetenschappelijke afbeeldingenverwerking**: Gebruiken van TIFF voor het verwerken van wetenschappelijke afbeeldingen, het uitvoeren van beeldregistratie en het verbeteren van de kwaliteit van afbeeldingen voor verdere analyse.
*   **Digitale forensische onderzoek**: Omzetten van EML-bestanden naar TIFF voor het analyseren van digitale bewijzen, het bijhouden van online-activiteit en het herstellen van digitale gebeurtenissen.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}