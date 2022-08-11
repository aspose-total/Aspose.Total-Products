---
title: Exportera EMLX till GIF via C++
description: C++ API för att konvertera EMLX till GIF utan att använda Microsoft Word eller Outlook
url: /sv/cpp/conversion/emlx-to-gif/
family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: GIF
otherformats: DOT FLATOPC BMP DOTM OTT DOTX JPEG EPUB RTF MD TIFF PDF TEXT PS EMF SVG DOCM WORDML PNG ODT XPS DOCX PCL DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API för att exportera EMLX till GIF" h2="Förvandla EMLX till GIF i C++-applikationen utan att behöva Microsoft Word eller Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Är du en C++-utvecklare som vill lägga till funktioner för e-postkonvertering i dina applikationer? Genom att använda [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/) kan du konvertera EMLX-filformat till HTML. Efter det, genom att använda [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API, kan du exportera HTML till GIF. Båda API:erna kommer under paketet [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API för att konvertera EMLX till GIF" %}}
1. Öppna EMLX-filen med [MailMessage](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message) klassreferens
2. Konvertera EMLX till HTML genom att använda medlemsfunktionen [Spara](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Ladda HTML genom att använda klassen [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Spara dokumentet i GIF-format med metoden [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) och ställ in Gif som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total.Cpp``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total.Cpp```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMLX file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.emlx");
// save EMLX as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Gif as save format
doc->Save(u"convertedFile.Gif");
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analysera EMLX-fil via C++" %}}
Du kan inte bara konvertera din EMLX till GIF, utan du kan läsa, manipulera och analysera EMLX-dokument. Du kan få ämne, adress, text, mottagares information för e-postmeddelandet genom att använda MapiMessage-klassen av [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/) API. Du kan till exempel söka efter en specifik avsändar-e-post för konverteringen genom att använda egenskapen get_SenderEmlxAddress().
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

{{% blocks/products/pf/feature-page-section  h2="C++ API för att begränsa redigering av GIF-filformat" %}}
Du kan också lägga till dokumentskyddsfunktioner i din app medan du exporterar dokumentet från EMLX till GIF. Att lägga till skydd till ditt dokument är en enkel process, eftersom allt du behöver göra är att tillämpa skyddsmetoden på ditt dokument. Du kan ställa in skyddstypen på Skrivskyddad för att begränsa användaren att redigera dokumentet.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Gif");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/emlx-to-dot/" name="EMLX Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/emlx-to-flatopc/" name="EMLX Till FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/emlx-to-gif/" name="EMLX Till GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/emlx-to-dotm/" name="EMLX Till DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/emlx-to-ott/" name="EMLX Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/emlx-to-dotx/" name="EMLX Till DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/emlx-to-jpeg/" name="EMLX Till JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/emlx-to-epub/" name="EMLX Till EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/emlx-to-rtf/" name="EMLX Till RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/emlx-to-md/" name="EMLX Till MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/emlx-to-tiff/" name="EMLX Till TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/emlx-to-pdf/" name="EMLX Till PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/emlx-to-text/" name="EMLX Till TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/emlx-to-ps/" name="EMLX Till PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/emlx-to-emf/" name="EMLX Till EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/emlx-to-svg/" name="EMLX Till SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/emlx-to-docm/" name="EMLX Till DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/emlx-to-wordml/" name="EMLX Till WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/emlx-to-png/" name="EMLX Till PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/emlx-to-odt/" name="EMLX Till ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/emlx-to-xps/" name="EMLX Till XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/emlx-to-docx/" name="EMLX Till DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/emlx-to-pcl/" name="EMLX Till PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/emlx-to-doc/" name="EMLX Till DOC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}