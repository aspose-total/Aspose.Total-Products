---
title: Exportera OFT till JPEG via C++
description: C++ API för att konvertera OFT till JPEG utan att använda Microsoft Word eller Outlook
url: /sv/cpp/conversion/oft-to-jpeg/
family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: JPEG
otherformats: BMP DOCX WORDML DOTM TEXT XPS DOC SVG GIF RTF DOT TIFF EMF OTT DOTX DOCM PNG FLATOPC MD PDF ODT PS EPUB PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API för att exportera OFT till JPEG" h2="Förvandla OFT till JPEG i C++-applikationen utan att behöva Microsoft Word eller Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Är du en C++-utvecklare som vill lägga till funktioner för e-postkonvertering i dina applikationer? Genom att använda [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/) kan du konvertera OFT-filformat till HTML. Efter det, genom att använda [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API, kan du exportera HTML till JPEG. Båda API:erna kommer under paketet [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API för att konvertera OFT till JPEG" %}}
1. Öppna OFT-filen med [MailMessage](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message) klassreferens
2. Konvertera OFT till HTML genom att använda medlemsfunktionen [Save](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Ladda HTML genom att använda klassen [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Spara dokumentet i JPEG-format med metoden [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) och ställ in Jpeg som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total.Cpp``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total.Cpp```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the OFT file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.oft");
// save OFT as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Jpeg as save format
doc->Save(u"convertedFile.Jpeg");
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analysera OFT-fil via C++" %}}
Du kan inte bara konvertera din OFT till JPEG, utan du kan läsa, manipulera och analysera OFT-dokument. Du kan få ämne, adress, text, mottagares information för e-postmeddelandet genom att använda MapiMessage-klassen av [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/) API. Du kan till exempel söka efter en specifik avsändar-e-post för konverteringen genom att använda egenskapen get_SenderOftAddress().
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

{{% blocks/products/pf/feature-page-section  h2="C++ API för att begränsa redigering av JPEG-filformat" %}}
Du kan också lägga till dokumentskyddsfunktioner i din app medan du exporterar dokumentet från OFT till JPEG. Att lägga till skydd till ditt dokument är en enkel process, eftersom allt du behöver göra är att tillämpa skyddsmetoden på ditt dokument. Du kan ställa in skyddstypen på Skrivskyddad för att begränsa användaren att redigera dokumentet.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Jpeg");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/oft-to-jpeg/" name="OFT Till JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/oft-to-docx/" name="OFT Till DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/oft-to-wordml/" name="OFT Till WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/oft-to-dotm/" name="OFT Till DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/oft-to-text/" name="OFT Till TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/oft-to-xps/" name="OFT Till XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/oft-to-doc/" name="OFT Till DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/oft-to-svg/" name="OFT Till SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/oft-to-gif/" name="OFT Till GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/oft-to-rtf/" name="OFT Till RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/oft-to-dot/" name="OFT Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/oft-to-tiff/" name="OFT Till TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/oft-to-emf/" name="OFT Till EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/oft-to-ott/" name="OFT Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/oft-to-dotx/" name="OFT Till DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/oft-to-docm/" name="OFT Till DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/oft-to-png/" name="OFT Till PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/oft-to-flatopc/" name="OFT Till FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/oft-to-md/" name="OFT Till MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/oft-to-pdf/" name="OFT Till PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/oft-to-odt/" name="OFT Till ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/oft-to-ps/" name="OFT Till PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/oft-to-epub/" name="OFT Till EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/oft-to-pcl/" name="OFT Till PCL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}