---
title: C# API do eksportu EMLX do TEXT
description: Konwertuj EMLX na TEXT bez używania Microsoft Word lub Outlook na .NET
url_ignore: /pl/net/conversion/emlx-to-text/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: TEXT
otherformats: DOCX DOC DOTM SVG PDF DOTX PNG RTF ODT FLATOPC DOT XPS GIF EPUB TIFF DOCM JPEG TEXT OTT EMF MD WORDML PCL PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Eksportuj EMLX do TEXT przez .NET" h2="Interfejs API .NET do renderowania poczty e-mail do TEXT w systemach Windows, macOS i Linux bez korzystania z programu Word lub Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jeśli jesteś programistą .NET i chcesz dodać funkcje konwersji EMLX do TEXT w swoich aplikacjach, najlepszym rozwiązaniem są interfejsy API [Aspose.Total for .NET](https://products.aspose.com/total/net/) Naprzód. Używając [Aspose.Email for .NET](https://products.aspose.com/email/net/), możesz przekonwertować format pliku EMLX na HTML. Następnie, używając [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz renderować HTML do TEXT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API do konwersji EMLX na TEXT" %}}
1. Otwórz plik EMLX za pomocą klasy [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Konwertuj EMLX na HTML za pomocą metody [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Załaduj HTML za pomocą klasy [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Zapisz dokument w formacie TEXT za pomocą metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) i ustaw Text jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Przeanalizuj plik EMLX przez .NET" %}}
Przed konwersją EMLX na TEXT, jeśli chcesz się upewnić, że konwertujesz poprawny e-mail, możesz załadować dokument EMLX, przeanalizować go i spojrzeć na żądaną właściwość. Korzystając z klasy [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, możesz uzyskać informacje o nadawcy i odbiorcy. Na przykład możesz sprawdzić konkretny adres e-mail nadawcy dla konwersji za pomocą właściwości [NazwaNadawcy](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ogranicz edycję dokumentów TEXT przez .NET" %}}
Podczas zapisywania dokumentu z EMLX do TEXT może być konieczne zabezpieczenie dokumentu wyjściowego. Czasami może zajść potrzeba ograniczenia możliwości edycji dokumentu i zezwolenia tylko na określone czynności. Może to być przydatne, aby uniemożliwić innym osobom edytowanie poufnych i poufnych informacji w Twoim dokumencie. Interfejs API [Aspose.Words for .NET](https://products.aspose.com/words/net/) umożliwia kontrolowanie sposobu ograniczania treści za pomocą [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr wyliczenia. Możesz ustawić dokument jako tylko do odczytu, używając następujących wierszy kodu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.text", SaveFormat.Text);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku EMLX w TEXT programowo: przypadki użycia" %}}
Pliki EMLX (Electronic Messaging for Learning) są używane do przechowania zawartości edukacyjnego, czyniąc ich idealnymi dla tworzenia kursów online i prezentacji multimedialnych. Jednak przy pracy z danymi w formacie płynym, dokumenty takie jak Pliki tekstowe stają się niezastąpionymi dla prostoty i wygodnej obsługi.

Przekształcenie plików EMLX na formaty tekstowe jest konieczne, aby rozwinąć pełną potęgę swojej zawartości edukacyjnej oraz możliwości komunikacji. To przekształcenie pozwala Ci:

**Użycia przypadków:**

*   **Edycja zawartości**: Przekształć pliki EMLX na format tekstowy, aby łatwie było poprawiać i aktualizować zawartość.
*   **Narzędzia współpracy**: Wykorzystać Pliki tekstowe do współpracy z innymi osobami przy prostej edycji tekstu.
*   **Rozbudowa bazy wiedzy**: Przekształć pliki EMLX na interaktywną bazę wiedzy i dokumentację dla celów naucznych.
*   **Integracja z platformami e-learning**: Wykorzystać formaty tekstowe do łatwej integracji zawartości edukacyjnej z platformami e-learning, poprawiając doświadczenie użytkownika.
*   **Publikacja i dystrybucja zawartości**: Przekształć pliki EMLX na format tekstowy dla publikacji i dystrybucji zawartości przez różne kanały.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}