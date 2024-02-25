---
title: Exportera OFT till PNG via C++
description: C++ API för att konvertera OFT till PNG utan att använda Microsoft Word eller Outlook

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: PNG
otherformats: DOTX DOT DOCM PDF MD DOTM DOCX SVG XPS PCL GIF EPUB TIFF RTF JPEG DOC WORDML OTT PS TEXT ODT EMF BMP FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API för att exportera OFT till PNG" h2="Förvandla OFT till PNG i C++-applikationen utan att behöva Microsoft Word eller Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Är du en C++-utvecklare som vill lägga till funktioner för e-postkonvertering i dina applikationer? Genom att använda [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/) kan du konvertera OFT-filformat till HTML. Efter det, genom att använda [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API, kan du exportera HTML till PNG. Båda API:erna kommer under paketet [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API för att konvertera OFT till PNG" %}}
1. Öppna OFT-filen med [MailMessage](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message) klassreferens
2. Konvertera OFT till HTML genom att använda medlemsfunktionen [Save](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Ladda HTML genom att använda klassen [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Spara dokumentet i PNG-format med metoden [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) och ställ in Png som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total.Cpp``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total.Cpp```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.comtotal/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the OFT file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.oft");
// save OFT as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Png as save format
doc->Save(u"convertedFile.Png");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analysera OFT-fil via C++" %}}
Du kan inte bara konvertera din OFT till PNG, utan du kan läsa, manipulera och analysera OFT-dokument. Du kan få ämne, adress, text, mottagares information för e-postmeddelandet genom att använda MapiMessage-klassen av [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/) API. Du kan till exempel söka efter en specifik avsändar-e-post för konverteringen genom att använda egenskapen get_SenderOftAddress().
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

{{% blocks/products/pf/feature-page-section  h2="C++ API för att begränsa redigering av PNG-filformat" %}}
Du kan också lägga till dokumentskyddsfunktioner i din app medan du exporterar dokumentet från OFT till PNG. Att lägga till skydd till ditt dokument är en enkel process, eftersom allt du behöver göra är att tillämpa skyddsmetoden på ditt dokument. Du kan ställa in skyddstypen på Skrivskyddad för att begränsa användaren att redigera dokumentet.
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