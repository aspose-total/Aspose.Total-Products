---
title: C# API om MSG naar RTF te exporteren
description: Converteer MSG naar RTF zonder Microsoft Word of Outlook te gebruiken op .NET
url_ignore: /nl/net/conversion/msg-to-rtf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: RTF
otherformats: DOCX SVG DOTM WORDML JPEG GIF PS XPS DOT DOTX MD RTF DOC PCL OTT TIFF EMF EPUB PNG FLATOPC DOCM PDF ODT TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporteer MSG naar RTF via .NET" h2=".NET API om MSG naar RTF te renderen op Windows, macOS en Linux zonder Word of Outlook te gebruiken" >}}

{{% blocks/products/pf/feature-page-summary %}}
Als u een .NET-ontwikkelaar bent die MSG-naar-RTF-conversiefuncties in uw toepassingen wilt toevoegen, zijn [Aspose.Total for .NET](https://products.aspose.com/total/net/) bestandsformaatmanipulatie-API's de juiste keuze vooruit. Door [Aspose.Email for .NET](https://products.aspose.com/email/net/) te gebruiken, kunt u het MSG-bestandsformaat converteren naar HTML. Daarna kunt u met [Aspose.Words for .NET](https://products.aspose.com/words/net/) HTML naar RTF renderen.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API om MSG naar RTF te converteren" %}}
1. Open het MSG-bestand met de klasse [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage)
2. Converteer MSG naar HTML met behulp van de [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3) methode
3. Laad HTML met behulp van [Document](https://reference.aspose.com/words/net/aspose.words/document) klasse
4. Sla het document op in RTF-indeling met de methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) en stel Rtf in als SaveFormat
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
Voordat u MSG naar RTF converteert, kunt u, als u er zeker van wilt zijn dat u de juiste e-mail converteert, het MSG-document laden, het ontleden en uw gewenste eigenschap bekijken. Door gebruik te maken van [MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) klasse van [Aspose.Email for .NET](https://products.aspose.com/msg /net/) API, kunt u informatie over afzender en ontvanger krijgen. U kunt bijvoorbeeld controleren op een specifiek e-mailadres van de afzender voor de conversie door de eigenschap [SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername) te gebruiken.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Beperk het bewerken van RTF-documenten via .NET" %}}
Terwijl u het document opslaat van MSG naar RTF, moet u mogelijk uw uitvoerdocument beveiligen. Soms moet u de mogelijkheid om een document te bewerken beperken en er alleen bepaalde acties mee toestaan. Dit kan handig zijn om te voorkomen dat andere mensen gevoelige en vertrouwelijke informatie in uw document bewerken. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, stelt u in staat om te bepalen hoe u de inhoud beperkt met behulp van het [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) opsommingsparameter. U kunt uw document op alleen-lezen instellen door de volgende coderegels te gebruiken. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.rtf", SaveFormat.Rtf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="MSG-bestand programmatisch naar RTF transformeren: gebruiksscenario's" %}}
De omzetting van MSG-bestanden naar RTF-formaten is nodig om volledige controle over uw documenten te hebben tijdens het bewerken. Deze conversie maakt het mogelijk:

**Gebruikscases:**

* **Documenten bewerken en reviewen**: Omgaan met MSG-bestanden om documenten efficiënter te reviewen, te bewerken en te beheersen in Microsoft Office-toepassingen.  
* **Optimale zakelijke communicatie**: Gebruiken van RTF voor het maken van professioneel uitzienende correspondentie, notities en rapporten die gemakkelijk kunnen worden gedeeld met medewerkers en klanten.  
* **Compatabiliteit met oude systemen**: Omgaan met MSG-bestanden om oude systemen te ondersteunen, waardoor u toegang hebt tot en kunt werken met historische documenten zonder problemen.  
* **Talenvertaling en lokale aanpassing**: Gebruiken van RTF voor het vertalen en lokaal aanpassen van documenten voor een internationale audience, zodat de inhoud cultureel gevoelig en accuraat kan worden gedistribueerd.  
* **Archivering en bewaring**: Omgaan met MSG-bestanden door ze te archiveren in RTF-formaten, waardoor belangrijke zakelijke documenten langdurig kunnen worden bewaard en gevaar van dataverlies wordt geminimaliseerd.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}