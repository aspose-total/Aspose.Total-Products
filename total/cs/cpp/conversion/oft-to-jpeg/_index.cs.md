---
title: Exportujte OFT do JPEG přes C++
description: C++ API pro převod OFT do JPEG bez použití Microsoft Word nebo Outlook
url: /cs/cpp/conversion/oft-to-jpeg/
family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: JPEG
otherformats: BMP DOCX WORDML DOTM TEXT XPS DOC SVG GIF RTF DOT TIFF EMF OTT DOTX DOCM PNG FLATOPC MD PDF ODT PS EPUB PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API pro export OFT do JPEG" h2="Transformujte OFT na JPEG v rámci aplikace C++ bez nutnosti aplikace Microsoft Word nebo Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jste vývojář C++ a chcete do svých aplikací přidat funkce pro převod e-mailů? Pomocí [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/) můžete převést formát souboru OFT do HTML. Poté můžete pomocí [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API exportovat HTML do JPEG. Obě rozhraní API jsou součástí balíčku [Aspose.Total pro C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro převod OFT na JPEG" %}}
1. Otevřete soubor OFT pomocí odkazu třídy [MailMessage](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message)
2. Převeďte OFT na HTML pomocí členské funkce [Uložit](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Načtěte HTML pomocí třídy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Uložte dokument do formátu JPEG pomocí metody [Uložit](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) a nastavte Jpeg jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo přes konzolu Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si můžete stáhnout offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/cpp).
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

{{% blocks/products/pf/feature-page-section  h2="Analyzujte soubor OFT přes C++" %}}
Nejen, že můžete převést svůj OFT na JPEG, ale můžete číst, manipulovat a analyzovat OFT dokument. Informace o předmětu, adrese, těle a příjemcích e-mailu můžete získat pomocí třídy MapiMessage rozhraní API [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/). Můžete například zkontrolovat e-mail konkrétního odesílatele pro konverzi pomocí vlastnosti get_SenderOftAddress().
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

{{% blocks/products/pf/feature-page-section  h2="C++ API pro omezení úprav formátu souborů JPEG" %}}
Při exportu dokumentu z OFT do JPEG můžete do aplikace přidat také funkce ochrany dokumentů. Přidání ochrany do vašeho dokumentu je jednoduchý proces, protože vše, co musíte udělat, je použít metodu ochrany vašeho dokumentu. Můžete nastavit typ ochrany na ReadOnly a omezit uživatele na úpravy dokumentu.
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
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/oft-to-jpeg/" name="OFT Na JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/oft-to-docx/" name="OFT Na DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/oft-to-wordml/" name="OFT Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/oft-to-dotm/" name="OFT Na DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/oft-to-text/" name="OFT Na TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/oft-to-xps/" name="OFT Na XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/oft-to-doc/" name="OFT Na DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/oft-to-svg/" name="OFT Na SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/oft-to-gif/" name="OFT Na GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/oft-to-rtf/" name="OFT Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/oft-to-dot/" name="OFT Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/oft-to-tiff/" name="OFT Na TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/oft-to-emf/" name="OFT Na EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/oft-to-ott/" name="OFT Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/oft-to-dotx/" name="OFT Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/oft-to-docm/" name="OFT Na DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/oft-to-png/" name="OFT Na PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/oft-to-flatopc/" name="OFT Na FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/oft-to-md/" name="OFT Na MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/oft-to-pdf/" name="OFT Na PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/oft-to-odt/" name="OFT Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/oft-to-ps/" name="OFT Na PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/oft-to-epub/" name="OFT Na EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/oft-to-pcl/" name="OFT Na PCL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}