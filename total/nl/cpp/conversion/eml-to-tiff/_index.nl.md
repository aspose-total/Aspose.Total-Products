---
title: Export EML naar TIFF via C++
description: C++ API om EML naar TIFF te converteren zonder Microsoft Word of Outlook te gebruiken
url: /nl/cpp/conversion/eml-to-tiff/
family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: TIFF
otherformats: JPEG PS DOT DOCM DOCX RTF DOTM EPUB ODT BMP PNG DOC PDF EMF PCL GIF WORDML MD OTT TEXT FLATOPC DOTX SVG XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API om EML naar TIFF te exporteren" h2="Transformeer EML naar TIFF binnen de C++-toepassing zonder dat Microsoft Word of Outlook nodig is" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bent u een C++-ontwikkelaar en wilt u e-mailconversiefuncties toevoegen aan uw applicaties? Met [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) kunt u het EML-bestandsformaat converteren naar HTML. Daarna kunt u met behulp van de [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API HTML naar TIFF exporteren. Beide API's vallen onder het pakket [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API om EML naar TIFF te converteren" %}}
1. Open het EML-bestand met behulp van [MailMessage](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message) klassereferentie
2. Converteer EML naar HTML met behulp van [Save](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) lidfunctie
3. Laad HTML met behulp van [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class
4. Sla het document op in TIFF-formaat met de methode [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) en stel Tiff in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total.Cpp``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total.Cpp```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EML file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.eml");
// save EML as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Tiff as save format
doc->Save(u"convertedFile.Tiff");
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="E-MAIL-bestand ontleden via C++" %}}
U kunt niet alleen uw EML naar TIFF converteren, maar u kunt ook het EML-document lezen, manipuleren en ontleden. U kunt informatie over onderwerp, adres, hoofdtekst en ontvangers van de e-mail verkrijgen door de MapiMessage-klasse van [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) API te gebruiken. U kunt bijvoorbeeld controleren op een specifiek e-mailadres van de afzender voor de conversie door de eigenschap get_SenderEmlAddress() te gebruiken.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.eml");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmlAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ API om het bewerken van TIFF-bestandsindelingen te beperken" %}}
U kunt ook functies voor documentbeveiliging in uw app toevoegen terwijl u het document van EML naar TIFF exporteert. Beveiliging toevoegen aan uw document is een eenvoudig proces, aangezien u alleen de beveiligingsmethode op uw document hoeft toe te passen. U kunt het beveiligingstype instellen op Alleen-lezen om de gebruiker te beperken om het document te bewerken.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Tiff");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/eml-to-jpeg/" name="EML Tot JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/eml-to-ps/" name="EML Tot PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/eml-to-dot/" name="EML Tot DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/eml-to-docm/" name="EML Tot DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/eml-to-docx/" name="EML Tot DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/eml-to-rtf/" name="EML Tot RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/eml-to-dotm/" name="EML Tot DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/eml-to-epub/" name="EML Tot EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/eml-to-odt/" name="EML Tot ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/eml-to-tiff/" name="EML Tot TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/eml-to-png/" name="EML Tot PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/eml-to-doc/" name="EML Tot DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/eml-to-pdf/" name="EML Tot PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/eml-to-emf/" name="EML Tot EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/eml-to-pcl/" name="EML Tot PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/eml-to-gif/" name="EML Tot GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/eml-to-wordml/" name="EML Tot WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/eml-to-md/" name="EML Tot MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/eml-to-ott/" name="EML Tot OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/eml-to-text/" name="EML Tot TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/eml-to-flatopc/" name="EML Tot FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/eml-to-dotx/" name="EML Tot DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/eml-to-svg/" name="EML Tot SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/eml-to-xps/" name="EML Tot XPS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}