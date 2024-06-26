---
title: Exportera EML till MD via C++
description: C++ API för att konvertera EML till MD utan att använda Microsoft Word eller Outlook

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: MD
otherformats: EPUB FLATOPC PNG JPEG DOCM BMP PDF GIF RTF WORDML ODT PCL PS XPS TEXT OTT EMF DOTX DOT SVG DOCX DOTM TIFF DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API för att exportera EML till MD" h2="Förvandla EML till MD i C++-applikationen utan att behöva Microsoft Word eller Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Är du en C++-utvecklare som vill lägga till funktioner för e-postkonvertering i dina applikationer? Genom att använda [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) kan du konvertera EML-filformat till HTML. Efter det, genom att använda [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API, kan du exportera HTML till MD. Båda API:erna kommer under paketet [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API för att konvertera EML till MD" %}}
1. Öppna EML-filen med [MailMessage](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message) klassreferens
2. Konvertera EML till HTML genom att använda medlemsfunktionen [Save](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Ladda HTML genom att använda klassen [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Spara dokumentet i MD-format med metoden [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) och ställ in Md som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total.Cpp``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total.Cpp```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.comtotal/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EML file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.eml");
// save EML as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Md as save format
doc->Save(u"convertedFile.Md");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analysera EML-fil via C++" %}}
Du kan inte bara konvertera din EML till MD, utan du kan läsa, manipulera och analysera EML-dokument. Du kan få ämne, adress, text, mottagares information för e-postmeddelandet genom att använda MapiMessage-klassen av [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) API. Du kan till exempel söka efter en specifik avsändar-e-post för konverteringen genom att använda egenskapen get_SenderEmlAddress().
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

{{% blocks/products/pf/feature-page-section  h2="C++ API för att begränsa redigering av MD-filformat" %}}
Du kan också lägga till dokumentskyddsfunktioner i din app medan du exporterar dokumentet från EML till MD. Att lägga till skydd till ditt dokument är en enkel process, eftersom allt du behöver göra är att tillämpa skyddsmetoden på ditt dokument. Du kan ställa in skyddstypen på Skrivskyddad för att begränsa användaren att redigera dokumentet.
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
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}