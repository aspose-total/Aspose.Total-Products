---
title: C# API do eksportu MSG do ODT
description: Konwertuj MSG na ODT bez używania Microsoft Word lub Outlook na .NET
url_ignore: /pl/net/conversion/msg-to-odt/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: ODT
otherformats: EPUB DOTX PS WORDML RTF JPEG PNG SVG PCL TEXT DOTM PDF FLATOPC DOCX DOCM GIF MD OTT ODT DOC EMF DOT TIFF XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Eksportuj MSG do ODT przez .NET" h2="Interfejs API .NET do renderowania poczty e-mail do ODT w systemach Windows, macOS i Linux bez korzystania z programu Word lub Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jeśli jesteś programistą .NET i chcesz dodać funkcje konwersji MSG do ODT w swoich aplikacjach, najlepszym rozwiązaniem są interfejsy API [Aspose.Total for .NET](https://products.aspose.com/total/net/) Naprzód. Używając [Aspose.Email for .NET](https://products.aspose.com/email/net/), możesz przekonwertować format pliku MSG na HTML. Następnie, używając [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz renderować HTML do ODT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API do konwersji MSG na ODT" %}}
1. Otwórz plik MSG za pomocą klasy [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage)
2. Konwertuj MSG na HTML za pomocą metody [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3)
3. Załaduj HTML za pomocą klasy [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Zapisz dokument w formacie ODT za pomocą metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) i ustaw Odt jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Przeanalizuj plik MSG przez .NET" %}}
Przed konwersją MSG na ODT, jeśli chcesz się upewnić, że konwertujesz poprawny e-mail, możesz załadować dokument MSG, przeanalizować go i spojrzeć na żądaną właściwość. Korzystając z klasy [MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) [Aspose.Email for .NET](https://products.aspose.com/msg /net/) API, możesz uzyskać informacje o nadawcy i odbiorcy. Na przykład możesz sprawdzić konkretny adres e-mail nadawcy dla konwersji za pomocą właściwości [NazwaNadawcy](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ogranicz edycję dokumentów ODT przez .NET" %}}
Podczas zapisywania dokumentu z MSG do ODT może być konieczne zabezpieczenie dokumentu wyjściowego. Czasami może zajść potrzeba ograniczenia możliwości edycji dokumentu i zezwolenia tylko na określone czynności. Może to być przydatne, aby uniemożliwić innym osobom edytowanie poufnych i poufnych informacji w Twoim dokumencie. Interfejs API [Aspose.Words for .NET](https://products.aspose.com/words/net/) umożliwia kontrolowanie sposobu ograniczania treści za pomocą [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr wyliczenia. Możesz ustawić dokument jako tylko do odczytu, używając następujących wierszy kodu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.odt", SaveFormat.Odt);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku MSG w ODT programowo: przypadki użycia" %}}
Pliki MSG są używane do przechowania informacji opartych na tekście, co czyni je idealnymi dla tworzenia prostych szablonów email i wersji pocztkowych. Jednak gdy pracujemy z bardziej skomplikowanymi ułożeniami dokumentu, pliki OpenDocument Text (ODT) stają się niezbędne dla bogatego redakowania tekstu oraz dostosowania układu.

Przekształcenie plików MSG na formaty ODT jest konieczne, aby wykorzystać pełną możliwość funkcji edycji dokumentów. To przekształcenie pozwala na:

**Użycia przypadków:**

*   **Tworzenie szablonów email**: Przekształć pliki MSG na format ODT, aby tworzyć zawodowe szabłony email, oszczędzając czas i wysiłek na formowanie powtarzającej się treści.
*   **Edycja i układ dokumentu**: Wykorzystać ODT do edycji i dostosowania skomplikowanych dokumentów z łatwością, w tym bogatego tekstu, zdjęć, tabel i więcej.
*   **Współpraca i udostępnianie**: Przekształć pliki MSG na format ODT, aby udostępnić i współpracować na dokumentach z innymi, zapewne że każdy będzie miał dostęp do najnowszej wersji.
*   **Import i eksport danych**: Wykorzystać ODT do importu danych z zewnętrznych źródłów, takich jak bazy danych lub arkusze Excel, oraz do eksportu danych dla dalszego analizowania lub raportowania.
*   **Systemy Zarządzania Treścią (CMS)**: Przekształć pliki MSG na format ODT, aby zapewnić integrację z platformami CMS, ułatwiając tworzenie, edycję i publikację treści.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}