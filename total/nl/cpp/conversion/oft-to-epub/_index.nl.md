---
title: Export OFT naar EPUB via C++
description: C++ API om OFT naar EPUB te converteren zonder Microsoft Word of Outlook te gebruiken

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: EPUB
otherformats: RTF PS DOCX DOTM PCL DOT MD BMP PNG XPS TIFF JPEG PDF ODT DOC WORDML EMF DOTX GIF SVG FLATOPC TEXT DOCM OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API om OFT naar EPUB te exporteren" h2="Transformeer OFT naar EPUB binnen de C++-toepassing zonder dat Microsoft Word of Outlook nodig is" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bent u een C++-ontwikkelaar en wilt u e-mailconversiefuncties toevoegen aan uw applicaties? Met [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/) kunt u het OFT-bestandsformaat converteren naar HTML. Daarna kunt u met behulp van de [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API HTML naar EPUB exporteren. Beide API's vallen onder het pakket [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API om OFT naar EPUB te converteren" %}}
1. Open het OFT-bestand met behulp van [MailMessage](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message) klassereferentie
2. Converteer OFT naar HTML met behulp van [Save](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) lidfunctie
3. Laad HTML met behulp van [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class
4. Sla het document op in EPUB-formaat met de methode [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) en stel Epub in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total.Cpp``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total.Cpp```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the OFT file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.oft");
// save OFT as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Epub as save format
doc->Save(u"convertedFile.Epub");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="E-MAIL-bestand ontleden via C++" %}}
U kunt niet alleen uw OFT naar EPUB converteren, maar u kunt ook het OFT-document lezen, manipuleren en ontleden. U kunt informatie over onderwerp, adres, hoofdtekst en ontvangers van de e-mail verkrijgen door de MapiMessage-klasse van [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/) API te gebruiken. U kunt bijvoorbeeld controleren op een specifiek e-mailadres van de afzender voor de conversie door de eigenschap get_SenderOftAddress() te gebruiken.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.oft");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderOftAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ API om het bewerken van EPUB-bestandsindelingen te beperken" %}}
U kunt ook functies voor documentbeveiliging in uw app toevoegen terwijl u het document van OFT naar EPUB exporteert. Beveiliging toevoegen aan uw document is een eenvoudig proces, aangezien u alleen de beveiligingsmethode op uw document hoeft toe te passen. U kunt het beveiligingstype instellen op Alleen-lezen om de gebruiker te beperken om het document te bewerken.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Epub");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/oft-to-rtf/" name="OFT Tot RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/oft-to-ps/" name="OFT Tot PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/oft-to-docx/" name="OFT Tot DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/oft-to-dotm/" name="OFT Tot DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/oft-to-pcl/" name="OFT Tot PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/oft-to-dot/" name="OFT Tot DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/oft-to-md/" name="OFT Tot MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/oft-to-epub/" name="OFT Tot EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/oft-to-png/" name="OFT Tot PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/oft-to-xps/" name="OFT Tot XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/oft-to-tiff/" name="OFT Tot TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/oft-to-jpeg/" name="OFT Tot JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/oft-to-pdf/" name="OFT Tot PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/oft-to-odt/" name="OFT Tot ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/oft-to-doc/" name="OFT Tot DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/oft-to-wordml/" name="OFT Tot WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/oft-to-emf/" name="OFT Tot EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/oft-to-dotx/" name="OFT Tot DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/oft-to-gif/" name="OFT Tot GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/oft-to-svg/" name="OFT Tot SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/oft-to-flatopc/" name="OFT Tot FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/oft-to-text/" name="OFT Tot TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/oft-to-docm/" name="OFT Tot DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/oft-to-ott/" name="OFT Tot OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}