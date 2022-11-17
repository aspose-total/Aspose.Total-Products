---
title: Eksportuj EMLX do SVG przez C++
description: C++ API do konwersji EMLX na SVG bez użycia Microsoft Word lub Outlook

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: SVG
otherformats: DOCM EMF PDF XPS PCL FLATOPC DOC GIF WORDML EPUB DOTX RTF MD TEXT ODT PS DOCX TIFF JPEG DOTM PNG DOT OTT BMP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API do eksportu EMLX do SVG" h2="Przekształć EMLX w SVG w aplikacji C++ bez konieczności korzystania z Microsoft Word lub Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Czy jesteś programistą C++ i chcesz dodać funkcje konwersji wiadomości e-mail do swoich aplikacji? Używając [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/) możesz przekonwertować format pliku EMLX na HTML. Następnie za pomocą API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) możesz wyeksportować HTML do SVG. Oba interfejsy API są objęte pakietem [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API do konwersji EMLX na SVG" %}}
1. Otwórz plik EMLX przy użyciu odwołania do klasy [MailMessage](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message)
2. Konwertuj EMLX na HTML za pomocą funkcji członka [Save](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Załaduj HTML za pomocą klasy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Zapisz dokument w formacie SVG za pomocą metody [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) i ustaw Svg jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMLX file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.emlx");
// save EMLX as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Svg as save format
doc->Save(u"convertedFile.Svg");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Przeanalizuj plik EMLX za pomocą C++" %}}
Nie tylko możesz przekonwertować swój EMLX na SVG, ale możesz czytać, manipulować i analizować dokument EMLX. Możesz uzyskać temat, adres, treść, informacje o odbiorcach wiadomości e-mail za pomocą klasy MapiMessage interfejsu API [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/). Na przykład możesz sprawdzić konkretny adres e-mail nadawcy dla konwersji za pomocą właściwości get_SenderEmlxAddress().
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

{{% blocks/products/pf/feature-page-section  h2="C++ API do ograniczania edycji formatu plików SVG" %}}
Możesz także dodać funkcje ochrony dokumentów w swojej aplikacji podczas eksportowania dokumentu z EMLX do SVG. Dodanie ochrony do dokumentu jest prostym procesem, ponieważ wszystko, co musisz zrobić, to zastosować metodę ochrony do swojego dokumentu. Możesz ustawić typ ochrony na Tylko do odczytu, aby ograniczyć użytkownikowi możliwość edytowania dokumentu.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Svg");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/emlx-to-docm/" name="EMLX Do DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/emlx-to-emf/" name="EMLX Do EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/emlx-to-pdf/" name="EMLX Do PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/emlx-to-xps/" name="EMLX Do XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/emlx-to-pcl/" name="EMLX Do PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/emlx-to-flatopc/" name="EMLX Do FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/emlx-to-doc/" name="EMLX Do DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/emlx-to-gif/" name="EMLX Do GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/emlx-to-wordml/" name="EMLX Do WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/emlx-to-epub/" name="EMLX Do EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/emlx-to-dotx/" name="EMLX Do DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/emlx-to-rtf/" name="EMLX Do RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/emlx-to-md/" name="EMLX Do MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/emlx-to-text/" name="EMLX Do TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/emlx-to-odt/" name="EMLX Do ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/emlx-to-ps/" name="EMLX Do PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/emlx-to-docx/" name="EMLX Do DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/emlx-to-tiff/" name="EMLX Do TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/emlx-to-jpeg/" name="EMLX Do JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/emlx-to-dotm/" name="EMLX Do DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/emlx-to-png/" name="EMLX Do PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/emlx-to-dot/" name="EMLX Do DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/emlx-to-ott/" name="EMLX Do OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/emlx-to-svg/" name="EMLX Do SVG" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}