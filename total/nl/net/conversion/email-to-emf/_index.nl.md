---
title: C# API om EMAIL naar EMF te exporteren
description: Converteer EMAIL naar EMF zonder Microsoft Word of Outlook te gebruiken op .NET
url_ignore: /nl/net/conversion/email-to-emf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: EMF
otherformats: XPS OTT DOTM EPUB GIF TEXT PCL DOT PS PDF DOTX ODT RTF DOCX DOCM PNG WORDML EMF JPEG SVG TIFF DOC FLATOPC MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporteer EMAIL naar EMF via .NET" h2=".NET API om EMAIL naar EMF te renderen op Windows, macOS en Linux zonder Word of Outlook te gebruiken" >}}

{{% blocks/products/pf/feature-page-summary %}}
Als u een .NET-ontwikkelaar bent die EMAIL-naar-EMF-conversiefuncties in uw toepassingen wilt toevoegen, zijn [Aspose.Total for .NET](https://products.aspose.com/total/net/) bestandsformaatmanipulatie-API's de juiste keuze vooruit. Door [Aspose.Email for .NET](https://products.aspose.com/email/net/) te gebruiken, kunt u het EMAIL-bestandsformaat converteren naar HTML. Daarna kunt u met [Aspose.Words for .NET](https://products.aspose.com/words/net/) HTML naar EMF renderen.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API om EMAIL naar EMF te converteren" %}}
1. Open het EMAIL-bestand met de klasse [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Converteer EMAIL naar HTML met behulp van de [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) methode
3. Laad HTML met behulp van [Document](https://reference.aspose.com/words/net/aspose.words/document) klasse
4. Sla het document op in EMF-indeling met de methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) en stel Emf in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.msg");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.emf", SaveFormat.Emf); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="E-MAIL-bestand ontleden via .NET" %}}
Voordat u EMAIL naar EMF converteert, kunt u, als u er zeker van wilt zijn dat u de juiste e-mail converteert, het EMAIL-document laden, het ontleden en uw gewenste eigenschap bekijken. Door gebruik te maken van [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) klasse van [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, kunt u informatie over afzender en ontvanger krijgen. U kunt bijvoorbeeld controleren op een specifiek e-mailadres van de afzender voor de conversie door de eigenschap [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) te gebruiken.  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Beperk het bewerken van EMF-documenten via .NET" %}}
Terwijl u het document opslaat van EMAIL naar EMF, moet u mogelijk uw uitvoerdocument beveiligen. Soms moet u de mogelijkheid om een document te bewerken beperken en er alleen bepaalde acties mee toestaan. Dit kan handig zijn om te voorkomen dat andere mensen gevoelige en vertrouwelijke informatie in uw document bewerken. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, stelt u in staat om te bepalen hoe u de inhoud beperkt met behulp van het [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) opsommingsparameter. U kunt uw document op alleen-lezen instellen door de volgende coderegels te gebruiken. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.emf", SaveFormat.Emf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EMAIL-bestand programmatisch naar EMF transformeren: gebruiksscenario's" %}}
E-mails worden gebruikt om tekstgebaseerd informatie te bewaren, waardoor ze ideaal zijn voor het verzenden en ontvangen van berichten. Maar wanneer werken we met afbeeldingen, worden formats zoals EMF essentieel voor grafische rendering en druktechnologie.

Het omzetten van E-mails naar EMF-formaten is nodig om de volledige capaciteit van uw grafische rendering en druktechnologie te onthullen. Dit proces maakt het mogelijk om:

**Gebruiksdoelen:**

*   **Marketing Materialen**: Omzetten van E-mail-bestanden naar EMF-formaten om printbare marketing materialen, brochures en flyers te creëren.
*   **Handleidingen**: Gebruik van EMF voor het genereren van gedrukte handleidingen, manuals en stapsgidsen voor technische processen.
*   **Technische Tekeningen**: Omzetten van E-mails naar precieze technische tekeningen, blauwdrukken en diagrammen voor architectuur-, ingenieur- en bouwprojecten.
*   **Graphische Ontwerpen**: Gebruik van EMF om hoogwaardige graphische ontwerpen, logotippen, iconen en afbeeldingen te produceren voor digitale displays, reclame en publicaties.
*   **Onderwijsmateriaal**: Omzetten van E-mail-bestanden naar interactieve en aantrekkelijke onderwijscontent, zoals presentatie-slideshows, quizzes en virtuele simulaties.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}