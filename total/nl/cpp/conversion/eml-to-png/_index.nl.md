---
title: Export EML naar PNG via C++
description: C++ API om EML naar PNG te converteren zonder Microsoft Word of Outlook te gebruiken

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: PNG
otherformats: DOTM XPS PS FLATOPC PCL SVG DOT TIFF BMP PDF EPUB OTT DOCM MD GIF EMF RTF DOC WORDML TEXT DOTX DOCX JPEG ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API om EML naar PNG te exporteren" h2="Transformeer EML naar PNG binnen de C++-toepassing zonder dat Microsoft Word of Outlook nodig is" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bent u een C++-ontwikkelaar en wilt u e-mailconversiefuncties toevoegen aan uw applicaties? Met [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) kunt u het EML-bestandsformaat converteren naar HTML. Daarna kunt u met behulp van de [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API HTML naar PNG exporteren. Beide API's vallen onder het pakket [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API om EML naar PNG te converteren" %}}
1. Open het EML-bestand met behulp van [MailMessage](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message) klassereferentie
2. Converteer EML naar HTML met behulp van [Save](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) lidfunctie
3. Laad HTML met behulp van [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class
4. Sla het document op in PNG-formaat met de methode [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) en stel Png in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total.Cpp``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total.Cpp```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EML file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.eml");
// save EML as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Png as save format
doc->Save(u"convertedFile.Png");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="E-MAIL-bestand ontleden via C++" %}}
U kunt niet alleen uw EML naar PNG converteren, maar u kunt ook het EML-document lezen, manipuleren en ontleden. U kunt informatie over onderwerp, adres, hoofdtekst en ontvangers van de e-mail verkrijgen door de MapiMessage-klasse van [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) API te gebruiken. U kunt bijvoorbeeld controleren op een specifiek e-mailadres van de afzender voor de conversie door de eigenschap get_SenderEmlAddress() te gebruiken.
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

{{% blocks/products/pf/feature-page-section  h2="C++ API om het bewerken van PNG-bestandsindelingen te beperken" %}}
U kunt ook functies voor documentbeveiliging in uw app toevoegen terwijl u het document van EML naar PNG exporteert. Beveiliging toevoegen aan uw document is een eenvoudig proces, aangezien u alleen de beveiligingsmethode op uw document hoeft toe te passen. U kunt het beveiligingstype instellen op Alleen-lezen om de gebruiker te beperken om het document te bewerken.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Png");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}