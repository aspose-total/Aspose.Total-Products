---
title: Exportujte EMLX do PNG přes C++
description: C++ API pro převod EMLX do PNG bez použití Microsoft Word nebo Outlook

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: PNG
otherformats: DOTM FLATOPC DOC BMP PCL EMF RTF TEXT DOCM PS DOTX DOCX PDF GIF SVG EPUB DOT TIFF WORDML OTT XPS ODT JPEG MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API pro export EMLX do PNG" h2="Transformujte EMLX na PNG v rámci aplikace C++ bez nutnosti aplikace Microsoft Word nebo Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jste vývojář C++ a chcete do svých aplikací přidat funkce pro převod e-mailů? Pomocí [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/) můžete převést formát souboru EMLX do HTML. Poté můžete pomocí [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API exportovat HTML do PNG. Obě rozhraní API jsou součástí balíčku [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro převod EMLX na PNG" %}}
1. Otevřete soubor EMLX pomocí odkazu třídy [MailMessage](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message)
2. Převeďte EMLX na HTML pomocí členské funkce [Save](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Načtěte HTML pomocí třídy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Uložte dokument do formátu PNG pomocí metody [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) a nastavte Png jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo přes konzolu Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si můžete stáhnout offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMLX file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.emlx");
// save EMLX as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Png as save format
doc->Save(u"convertedFile.Png");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analyzujte soubor EMLX přes C++" %}}
Nejen, že můžete převést svůj EMLX na PNG, ale můžete číst, manipulovat a analyzovat EMLX dokument. Informace o předmětu, adrese, těle a příjemcích e-mailu můžete získat pomocí třídy MapiMessage rozhraní API [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/). Můžete například zkontrolovat e-mail konkrétního odesílatele pro konverzi pomocí vlastnosti get_SenderEmlxAddress().
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

{{% blocks/products/pf/feature-page-section  h2="C++ API pro omezení úprav formátu souborů PNG" %}}
Při exportu dokumentu z EMLX do PNG můžete do aplikace přidat také funkce ochrany dokumentů. Přidání ochrany do vašeho dokumentu je jednoduchý proces, protože vše, co musíte udělat, je použít metodu ochrany vašeho dokumentu. Můžete nastavit typ ochrany na ReadOnly a omezit uživatele na úpravy dokumentu.
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
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/emlx-to-dotm/" name="EMLX Na DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/emlx-to-flatopc/" name="EMLX Na FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/emlx-to-doc/" name="EMLX Na DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/emlx-to-png/" name="EMLX Na PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/emlx-to-pcl/" name="EMLX Na PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/emlx-to-emf/" name="EMLX Na EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/emlx-to-rtf/" name="EMLX Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/emlx-to-text/" name="EMLX Na TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/emlx-to-docm/" name="EMLX Na DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/emlx-to-ps/" name="EMLX Na PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/emlx-to-dotx/" name="EMLX Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/emlx-to-docx/" name="EMLX Na DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/emlx-to-pdf/" name="EMLX Na PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/emlx-to-gif/" name="EMLX Na GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/emlx-to-svg/" name="EMLX Na SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/emlx-to-epub/" name="EMLX Na EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/emlx-to-dot/" name="EMLX Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/emlx-to-tiff/" name="EMLX Na TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/emlx-to-wordml/" name="EMLX Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/emlx-to-ott/" name="EMLX Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/emlx-to-xps/" name="EMLX Na XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/emlx-to-odt/" name="EMLX Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/emlx-to-jpeg/" name="EMLX Na JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/emlx-to-md/" name="EMLX Na MD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}