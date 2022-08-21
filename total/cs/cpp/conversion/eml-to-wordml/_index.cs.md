---
title: Exportujte EML do WORDML přes C++
description: C++ API pro převod EML do WORDML bez použití Microsoft Word nebo Outlook
url: /cs/cpp/conversion/eml-to-wordml/
family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: WORDML
otherformats: PS ODT TEXT OTT DOCX DOT DOC FLATOPC RTF EPUB PCL DOCM GIF XPS DOTX PNG TIFF PDF MD DOTM EMF SVG BMP JPEG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API pro export EML do WORDML" h2="Transformujte EML na WORDML v rámci aplikace C++ bez nutnosti aplikace Microsoft Word nebo Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jste vývojář C++ a chcete do svých aplikací přidat funkce pro převod e-mailů? Pomocí [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) můžete převést formát souboru EML do HTML. Poté můžete pomocí [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API exportovat HTML do WORDML. Obě rozhraní API jsou součástí balíčku [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro převod EML na WORDML" %}}
1. Otevřete soubor EML pomocí odkazu třídy [MailMessage](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message)
2. Převeďte EML na HTML pomocí členské funkce [Save](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Načtěte HTML pomocí třídy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Uložte dokument do formátu WORDML pomocí metody [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) a nastavte Wordml jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo přes konzolu Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si můžete stáhnout offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EML file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.eml");
// save EML as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing WordML as save format
doc->Save(u"convertedFile.WordML");
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analyzujte soubor EML přes C++" %}}
Nejen, že můžete převést svůj EML na WORDML, ale můžete číst, manipulovat a analyzovat EML dokument. Informace o předmětu, adrese, těle a příjemcích e-mailu můžete získat pomocí třídy MapiMessage rozhraní API [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/). Můžete například zkontrolovat e-mail konkrétního odesílatele pro konverzi pomocí vlastnosti get_SenderEmlAddress().
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

{{% blocks/products/pf/feature-page-section  h2="C++ API pro omezení úprav formátu souborů WORDML" %}}
Při exportu dokumentu z EML do WORDML můžete do aplikace přidat také funkce ochrany dokumentů. Přidání ochrany do vašeho dokumentu je jednoduchý proces, protože vše, co musíte udělat, je použít metodu ochrany vašeho dokumentu. Můžete nastavit typ ochrany na ReadOnly a omezit uživatele na úpravy dokumentu.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.WordML");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/eml-to-ps/" name="EML Na PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/eml-to-odt/" name="EML Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/eml-to-text/" name="EML Na TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/eml-to-ott/" name="EML Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/eml-to-docx/" name="EML Na DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/eml-to-dot/" name="EML Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/eml-to-doc/" name="EML Na DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/eml-to-flatopc/" name="EML Na FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/eml-to-rtf/" name="EML Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/eml-to-epub/" name="EML Na EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/eml-to-pcl/" name="EML Na PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/eml-to-docm/" name="EML Na DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/eml-to-gif/" name="EML Na GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/eml-to-xps/" name="EML Na XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/eml-to-dotx/" name="EML Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/eml-to-png/" name="EML Na PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/eml-to-tiff/" name="EML Na TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/eml-to-pdf/" name="EML Na PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/eml-to-md/" name="EML Na MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/eml-to-dotm/" name="EML Na DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/eml-to-emf/" name="EML Na EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/eml-to-svg/" name="EML Na SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/eml-to-wordml/" name="EML Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/eml-to-jpeg/" name="EML Na JPEG" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}