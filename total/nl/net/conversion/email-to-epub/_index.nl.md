---
title: C# API om EMAIL naar EPUB te exporteren
description: Converteer EMAIL naar EPUB zonder Microsoft Word of Outlook te gebruiken op .NET
url_ignore: /nl/net/conversion/email-to-epub/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: EPUB
otherformats: DOTM PNG PS SVG TIFF JPEG ODT DOT DOCM PCL OTT EPUB WORDML DOTX RTF MD PDF GIF FLATOPC EMF TEXT XPS DOCX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporteer EMAIL naar EPUB via .NET" h2=".NET API om EMAIL naar EPUB te renderen op Windows, macOS en Linux zonder Word of Outlook te gebruiken" >}}

{{% blocks/products/pf/feature-page-summary %}}
Als u een .NET-ontwikkelaar bent die EMAIL-naar-EPUB-conversiefuncties in uw toepassingen wilt toevoegen, zijn [Aspose.Total for .NET](https://products.aspose.com/total/net/) bestandsformaatmanipulatie-API's de juiste keuze vooruit. Door [Aspose.Email for .NET](https://products.aspose.com/email/net/) te gebruiken, kunt u het EMAIL-bestandsformaat converteren naar HTML. Daarna kunt u met [Aspose.Words for .NET](https://products.aspose.com/words/net/) HTML naar EPUB renderen.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API om EMAIL naar EPUB te converteren" %}}
1. Open het EMAIL-bestand met de klasse [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Converteer EMAIL naar HTML met behulp van de [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) methode
3. Laad HTML met behulp van [Document](https://reference.aspose.com/words/net/aspose.words/document) klasse
4. Sla het document op in EPUB-indeling met de methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) en stel Epub in als SaveFormat
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

document.Save("output.epub", SaveFormat.Epub); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="E-MAIL-bestand ontleden via .NET" %}}
Voordat u EMAIL naar EPUB converteert, kunt u, als u er zeker van wilt zijn dat u de juiste e-mail converteert, het EMAIL-document laden, het ontleden en uw gewenste eigenschap bekijken. Door gebruik te maken van [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) klasse van [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, kunt u informatie over afzender en ontvanger krijgen. U kunt bijvoorbeeld controleren op een specifiek e-mailadres van de afzender voor de conversie door de eigenschap [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) te gebruiken.  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
.aspose.com
{{% blocks/products/pf/feature-page-section  h2="Beperk het bewerken van EPUB-documenten via .NET" %}}
Terwijl u het document opslaat van EMAIL naar EPUB, moet u mogelijk uw uitvoerdocument beveiligen. Soms moet u de mogelijkheid om een document te bewerken beperken en er alleen bepaalde acties mee toestaan. Dit kan handig zijn om te voorkomen dat andere mensen gevoelige en vertrouwelijke informatie in uw document bewerken. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, stelt u in staat om te bepalen hoe u de inhoud beperkt met behulp van het [ProtectionType](https://apireference.aspose. com/words/net/aspose.words/protectiontype) opsommingsparameter. U kunt uw document op alleen-lezen instellen door de volgende coderegels te gebruiken. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.epub", SaveFormat.Epub);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}