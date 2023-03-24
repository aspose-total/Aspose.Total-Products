---
title: Eksportuj EML do PNG przez C++
description: C++ API do konwersji EML na PNG bez użycia Microsoft Word lub Outlook

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: PNG
otherformats: DOTM XPS PS FLATOPC PCL SVG DOT TIFF BMP PDF EPUB OTT DOCM MD GIF EMF RTF DOC WORDML TEXT DOTX DOCX JPEG ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API do eksportu EML do PNG" h2="Przekształć EML w PNG w aplikacji C++ bez konieczności korzystania z Microsoft Word lub Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Czy jesteś programistą C++ i chcesz dodać funkcje konwersji wiadomości e-mail do swoich aplikacji? Używając [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) możesz przekonwertować format pliku EML na HTML. Następnie za pomocą API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) możesz wyeksportować HTML do PNG. Oba interfejsy API są objęte pakietem [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API do konwersji EML na PNG" %}}
1. Otwórz plik EML przy użyciu odwołania do klasy [MailMessage](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message)
2. Konwertuj EML na HTML za pomocą funkcji członka [Save](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Załaduj HTML za pomocą klasy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Zapisz dokument w formacie PNG za pomocą metody [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) i ustaw Png jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EML file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.eml");
// save EML as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Png as save format
doc->Save(u"convertedFile.Png");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Przeanalizuj plik EML za pomocą C++" %}}
Nie tylko możesz przekonwertować swój EML na PNG, ale możesz czytać, manipulować i analizować dokument EML. Możesz uzyskać temat, adres, treść, informacje o odbiorcach wiadomości e-mail za pomocą klasy MapiMessage interfejsu API [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/). Na przykład możesz sprawdzić konkretny adres e-mail nadawcy dla konwersji za pomocą właściwości get_SenderEmlAddress().
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

{{% blocks/products/pf/feature-page-section  h2="C++ API do ograniczania edycji formatu plików PNG" %}}
Możesz także dodać funkcje ochrony dokumentów w swojej aplikacji podczas eksportowania dokumentu z EML do PNG. Dodanie ochrony do dokumentu jest prostym procesem, ponieważ wszystko, co musisz zrobić, to zastosować metodę ochrony do swojego dokumentu. Możesz ustawić typ ochrony na Tylko do odczytu, aby ograniczyć użytkownikowi możliwość edytowania dokumentu.
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
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}