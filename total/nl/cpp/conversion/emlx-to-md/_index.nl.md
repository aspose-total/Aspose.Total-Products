---
title: Export EMLX naar MD via C++
description: C++ API om EMLX naar MD te converteren zonder Microsoft Word of Outlook te gebruiken

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: MD
otherformats: DOT XPS EPUB DOCX WORDML JPEG DOCM BMP PNG DOTX PS FLATOPC GIF OTT TIFF EMF PCL ODT SVG DOTM RTF DOC PDF TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API om EMLX naar MD te exporteren" h2="Transformeer EMLX naar MD binnen de C++-toepassing zonder dat Microsoft Word of Outlook nodig is" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bent u een C++-ontwikkelaar en wilt u e-mailconversiefuncties toevoegen aan uw applicaties? Met [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/) kunt u het EMLX-bestandsformaat converteren naar HTML. Daarna kunt u met behulp van de [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API HTML naar MD exporteren. Beide API's vallen onder het pakket [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API om EMLX naar MD te converteren" %}}
1. Open het EMLX-bestand met behulp van [MailMessage](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message) klassereferentie
2. Converteer EMLX naar HTML met behulp van [Save](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) lidfunctie
3. Laad HTML met behulp van [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class
4. Sla het document op in MD-formaat met de methode [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) en stel Md in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total.Cpp``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total.Cpp```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMLX file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.emlx");
// save EMLX as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Md as save format
doc->Save(u"convertedFile.Md");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="E-MAIL-bestand ontleden via C++" %}}
U kunt niet alleen uw EMLX naar MD converteren, maar u kunt ook het EMLX-document lezen, manipuleren en ontleden. U kunt informatie over onderwerp, adres, hoofdtekst en ontvangers van de e-mail verkrijgen door de MapiMessage-klasse van [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/) API te gebruiken. U kunt bijvoorbeeld controleren op een specifiek e-mailadres van de afzender voor de conversie door de eigenschap get_SenderEmlxAddress() te gebruiken.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.emlx");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmlxAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ API om het bewerken van MD-bestandsindelingen te beperken" %}}
U kunt ook functies voor documentbeveiliging in uw app toevoegen terwijl u het document van EMLX naar MD exporteert. Beveiliging toevoegen aan uw document is een eenvoudig proces, aangezien u alleen de beveiligingsmethode op uw document hoeft toe te passen. U kunt het beveiligingstype instellen op Alleen-lezen om de gebruiker te beperken om het document te bewerken.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Md");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/emlx-to-dot/" name="EMLX Tot DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/emlx-to-xps/" name="EMLX Tot XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/emlx-to-epub/" name="EMLX Tot EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/emlx-to-docx/" name="EMLX Tot DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/emlx-to-wordml/" name="EMLX Tot WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/emlx-to-jpeg/" name="EMLX Tot JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/emlx-to-docm/" name="EMLX Tot DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/emlx-to-md/" name="EMLX Tot MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/emlx-to-png/" name="EMLX Tot PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/emlx-to-dotx/" name="EMLX Tot DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/emlx-to-ps/" name="EMLX Tot PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/emlx-to-flatopc/" name="EMLX Tot FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/emlx-to-gif/" name="EMLX Tot GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/emlx-to-ott/" name="EMLX Tot OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/emlx-to-tiff/" name="EMLX Tot TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/emlx-to-emf/" name="EMLX Tot EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/emlx-to-pcl/" name="EMLX Tot PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/emlx-to-odt/" name="EMLX Tot ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/emlx-to-svg/" name="EMLX Tot SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/emlx-to-dotm/" name="EMLX Tot DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/emlx-to-rtf/" name="EMLX Tot RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/emlx-to-doc/" name="EMLX Tot DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/emlx-to-pdf/" name="EMLX Tot PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/emlx-to-text/" name="EMLX Tot TEXT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}