---
title: Eksportuj OFT do PS przez C++
description: C++ API do konwersji OFT na PS bez użycia Microsoft Word lub Outlook
url: /pl/cpp/conversion/oft-to-ps/
family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: PS
otherformats: RTF DOTM TIFF FLATOPC WORDML MD PDF BMP PNG XPS GIF PCL EMF SVG DOC DOCX OTT TEXT DOT ODT DOTX DOCM JPEG EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API do eksportu OFT do PS" h2="Przekształć OFT w PS w aplikacji C++ bez konieczności korzystania z Microsoft Word lub Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Czy jesteś programistą C++ i chcesz dodać funkcje konwersji wiadomości e-mail do swoich aplikacji? Używając [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/) możesz przekonwertować format pliku OFT na HTML. Następnie za pomocą API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) możesz wyeksportować HTML do PS. Oba interfejsy API są objęte pakietem [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API do konwersji OFT na PS" %}}
1. Otwórz plik OFT przy użyciu odwołania do klasy [MailMessage](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message)
2. Konwertuj OFT na HTML za pomocą funkcji członka [Save](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Załaduj HTML za pomocą klasy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Zapisz dokument w formacie PS za pomocą metody [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) i ustaw Ps jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the OFT file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.oft");
// save OFT as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Ps as save format
doc->Save(u"convertedFile.Ps");
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Przeanalizuj plik OFT za pomocą C++" %}}
Nie tylko możesz przekonwertować swój OFT na PS, ale możesz czytać, manipulować i analizować dokument OFT. Możesz uzyskać temat, adres, treść, informacje o odbiorcach wiadomości e-mail za pomocą klasy MapiMessage interfejsu API [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/). Na przykład możesz sprawdzić konkretny adres e-mail nadawcy dla konwersji za pomocą właściwości get_SenderOftAddress().
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

{{% blocks/products/pf/feature-page-section  h2="C++ API do ograniczania edycji formatu plików PS" %}}
Możesz także dodać funkcje ochrony dokumentów w swojej aplikacji podczas eksportowania dokumentu z OFT do PS. Dodanie ochrony do dokumentu jest prostym procesem, ponieważ wszystko, co musisz zrobić, to zastosować metodę ochrony do swojego dokumentu. Możesz ustawić typ ochrony na Tylko do odczytu, aby ograniczyć użytkownikowi możliwość edytowania dokumentu.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Ps");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/oft-to-rtf/" name="OFT Do RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/oft-to-dotm/" name="OFT Do DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/oft-to-tiff/" name="OFT Do TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/oft-to-flatopc/" name="OFT Do FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/oft-to-wordml/" name="OFT Do WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/oft-to-md/" name="OFT Do MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/oft-to-pdf/" name="OFT Do PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/oft-to-ps/" name="OFT Do PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/oft-to-png/" name="OFT Do PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/oft-to-xps/" name="OFT Do XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/oft-to-gif/" name="OFT Do GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/oft-to-pcl/" name="OFT Do PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/oft-to-emf/" name="OFT Do EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/oft-to-svg/" name="OFT Do SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/oft-to-doc/" name="OFT Do DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/oft-to-docx/" name="OFT Do DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/oft-to-ott/" name="OFT Do OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/oft-to-text/" name="OFT Do TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/oft-to-dot/" name="OFT Do DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/oft-to-odt/" name="OFT Do ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/oft-to-dotx/" name="OFT Do DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/oft-to-docm/" name="OFT Do DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/oft-to-jpeg/" name="OFT Do JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/oft-to-epub/" name="OFT Do EPUB" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}