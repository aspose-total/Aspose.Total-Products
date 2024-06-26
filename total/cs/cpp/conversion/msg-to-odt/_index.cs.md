---
title: Exportujte MSG do ODT přes C++
description: C++ API pro převod MSG do ODT bez použití Microsoft Word nebo Outlook

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: ODT
otherformats: PDF RTF EPUB DOTX OTT EMF GIF PCL DOT TIFF TEXT SVG DOC FLATOPC MD WORDML DOCM JPEG XPS BMP DOCX DOTM PNG PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API pro export MSG do ODT" h2="Transformujte MSG na ODT v rámci aplikace C++ bez nutnosti aplikace Microsoft Word nebo Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jste vývojář C++ a chcete do svých aplikací přidat funkce pro převod e-mailů? Pomocí [Aspose.Msg for C++](https://products.aspose.com/msg/cpp/) můžete převést formát souboru MSG do HTML. Poté můžete pomocí [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API exportovat HTML do ODT. Obě rozhraní API jsou součástí balíčku [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro převod MSG na ODT" %}}
1. Otevřete soubor MSG pomocí odkazu třídy [MailMessage](https://reference.aspose.com/msg/cpp/class/aspose.msg.mail_message)
2. Převeďte MSG na HTML pomocí členské funkce [Save](https://reference.aspose.com/msg/cpp/class/aspose.msg.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Načtěte HTML pomocí třídy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Uložte dokument do formátu ODT pomocí metody [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) a nastavte Odt jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo přes konzolu Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si můžete stáhnout offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.comtotal/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the MSG file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.msg");
// save MSG as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Odt as save format
doc->Save(u"convertedFile.Odt");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analyzujte soubor MSG přes C++" %}}
Nejen, že můžete převést svůj MSG na ODT, ale můžete číst, manipulovat a analyzovat MSG dokument. Informace o předmětu, adrese, těle a příjemcích e-mailu můžete získat pomocí třídy MapiMessage rozhraní API [Aspose.Msg for C++](https://products.aspose.com/msg/cpp/). Můžete například zkontrolovat e-mail konkrétního odesílatele pro konverzi pomocí vlastnosti get_SenderMsgAddress().
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.msg");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderMsgAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ API pro omezení úprav formátu souborů ODT" %}}
Při exportu dokumentu z MSG do ODT můžete do aplikace přidat také funkce ochrany dokumentů. Přidání ochrany do vašeho dokumentu je jednoduchý proces, protože vše, co musíte udělat, je použít metodu ochrany vašeho dokumentu. Můžete nastavit typ ochrany na ReadOnly a omezit uživatele na úpravy dokumentu.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Odt");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}