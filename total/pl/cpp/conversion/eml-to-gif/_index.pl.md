---
title: Eksportuj EML do GIF przez C++
description: C++ API do konwersji EML na GIF bez użycia Microsoft Word lub Outlook

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: GIF
otherformats: DOTM EPUB TIFF DOCM TEXT DOCX PS SVG DOTX PNG ODT DOC WORDML PCL RTF BMP XPS PDF MD FLATOPC OTT DOT EMF JPEG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API do eksportu EML do GIF" h2="Przekształć EML w GIF w aplikacji C++ bez konieczności korzystania z Microsoft Word lub Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Czy jesteś programistą C++ i chcesz dodać funkcje konwersji wiadomości e-mail do swoich aplikacji? Używając [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) możesz przekonwertować format pliku EML na HTML. Następnie za pomocą API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) możesz wyeksportować HTML do GIF. Oba interfejsy API są objęte pakietem [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API do konwersji EML na GIF" %}}
1. Otwórz plik EML przy użyciu odwołania do klasy [MailMessage](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message)
2. Konwertuj EML na HTML za pomocą funkcji członka [Save](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Załaduj HTML za pomocą klasy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Zapisz dokument w formacie GIF za pomocą metody [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) i ustaw Gif jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EML file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.eml");
// save EML as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Gif as save format
doc->Save(u"convertedFile.Gif");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Przeanalizuj plik EML za pomocą C++" %}}
Nie tylko możesz przekonwertować swój EML na GIF, ale możesz czytać, manipulować i analizować dokument EML. Możesz uzyskać temat, adres, treść, informacje o odbiorcach wiadomości e-mail za pomocą klasy MapiMessage interfejsu API [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/). Na przykład możesz sprawdzić konkretny adres e-mail nadawcy dla konwersji za pomocą właściwości get_SenderEmlAddress().
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

{{% blocks/products/pf/feature-page-section  h2="C++ API do ograniczania edycji formatu plików GIF" %}}
Możesz także dodać funkcje ochrony dokumentów w swojej aplikacji podczas eksportowania dokumentu z EML do GIF. Dodanie ochrony do dokumentu jest prostym procesem, ponieważ wszystko, co musisz zrobić, to zastosować metodę ochrony do swojego dokumentu. Możesz ustawić typ ochrony na Tylko do odczytu, aby ograniczyć użytkownikowi możliwość edytowania dokumentu.
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
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/eml-to-dotm/" name="EML Do DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/eml-to-epub/" name="EML Do EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/eml-to-tiff/" name="EML Do TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/eml-to-docm/" name="EML Do DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/eml-to-text/" name="EML Do TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/eml-to-docx/" name="EML Do DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/eml-to-ps/" name="EML Do PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/eml-to-svg/" name="EML Do SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/eml-to-dotx/" name="EML Do DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/eml-to-png/" name="EML Do PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/eml-to-odt/" name="EML Do ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/eml-to-doc/" name="EML Do DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/eml-to-wordml/" name="EML Do WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/eml-to-pcl/" name="EML Do PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/eml-to-rtf/" name="EML Do RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/eml-to-gif/" name="EML Do GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/eml-to-xps/" name="EML Do XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/eml-to-pdf/" name="EML Do PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/eml-to-md/" name="EML Do MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/eml-to-flatopc/" name="EML Do FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/eml-to-ott/" name="EML Do OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/eml-to-dot/" name="EML Do DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/eml-to-emf/" name="EML Do EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/eml-to-jpeg/" name="EML Do JPEG" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}