---
title: C# API do eksportu MSG do PDF
description: Konwertuj MSG na PDF bez używania Microsoft Word lub Outlook na .NET
url_ignore: /pl/net/conversion/msg-to-pdf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PDF
otherformats: DOT ODT WORDML JPEG PCL EMF TEXT RTF EPUB FLATOPC PDF SVG GIF OTT PS DOCX MD TIFF DOTM PNG DOCM XPS DOC DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Eksportuj MSG do PDF przez .NET" h2="Interfejs API .NET do renderowania poczty e-mail do PDF w systemach Windows, macOS i Linux bez korzystania z programu Word lub Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jeśli jesteś programistą .NET i chcesz dodać funkcje konwersji MSG do PDF w swoich aplikacjach, najlepszym rozwiązaniem są interfejsy API [Aspose.Total for .NET](https://products.aspose.com/total/net/) Naprzód. Używając [Aspose.Email for .NET](https://products.aspose.com/email/net/), możesz przekonwertować format pliku MSG na HTML. Następnie, używając [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz renderować HTML do PDF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API do konwersji MSG na PDF" %}}
1. Otwórz plik MSG za pomocą klasy [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage)
2. Konwertuj MSG na HTML za pomocą metody [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3)
3. Załaduj HTML za pomocą klasy [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Zapisz dokument w formacie PDF za pomocą metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) i ustaw Pdf jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-pdf.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Przeanalizuj plik MSG przez .NET" %}}
Przed konwersją MSG na PDF, jeśli chcesz się upewnić, że konwertujesz poprawny e-mail, możesz załadować dokument MSG, przeanalizować go i spojrzeć na żądaną właściwość. Korzystając z klasy [MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) [Aspose.Email for .NET](https://products.aspose.com/msg /net/) API, możesz uzyskać informacje o nadawcy i odbiorcy. Na przykład możesz sprawdzić konkretny adres e-mail nadawcy dla konwersji za pomocą właściwości [NazwaNadawcy](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ogranicz edycję dokumentów PDF przez .NET" %}}
Podczas zapisywania dokumentu z MSG do PDF może być konieczne zabezpieczenie dokumentu wyjściowego. Czasami może zajść potrzeba ograniczenia możliwości edycji dokumentu i zezwolenia tylko na określone czynności. Może to być przydatne, aby uniemożliwić innym osobom edytowanie poufnych i poufnych informacji w Twoim dokumencie. Interfejs API [Aspose.Words for .NET](https://products.aspose.com/words/net/) umożliwia kontrolowanie sposobu ograniczania treści za pomocą [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr wyliczenia. Możesz ustawić dokument jako tylko do odczytu, używając następujących wierszy kodu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pdf", SaveFormat.Pdf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku MSG w PDF programowo: przypadki użycia" %}}
Przekonwertowanie plików MSG na format PDF pozwala wykorzystać pełną funkcjonalność dokumentów do ich udostępniania i analizy. Dzięki tej konwersji możesz:

**Użycia przypadków:**

*   **Zgodność z przepisami**: Przekonwertuj plik MSG na format PDF dla potrzeb zgodności z przepisami, zapewniając, że wszystkie wymagane dokumenty są dostarczone dokładnie i w czasie.
*   **Zapisywania historii**: Wykorzystaj konwersję do PDF dla zapisywania historii wiadomości i rekordów, czyniąc je dostępne do przyszłej referencji lub analizy.
*   **Weryfikacja wyborów**: Przekonwertuj plik MSG na format PDF dla potrzeb weryfikacji wyborów, zapewniając integralność danych głosowania i wyników wyborczych.
*   **Ochrona własności intelektualnej**: Wykorzystaj konwersję do PDF dla ochrony poufnych danych firmy przez przeprowadzenie dokumentów na format niezmiennej wersji.
*   **Zarządzanie archiwem danych**: Przekonwertuj plik MSG na format PDF dla archiwowania i przechowania historii danych, czyniąc je łatwo dostępne do przyszłej analizy lub raportowania.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}