---
title: C# API do eksportu EMLX do PDF
description: Konwertuj EMLX na PDF bez używania Microsoft Word lub Outlook na .NET
url_ignore: /pl/net/conversion/emlx-to-pdf/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: PDF
otherformats: MD XPS SVG TEXT WORDML DOT DOTX FLATOPC TIFF DOCX EMF OTT ODT DOC EPUB DOTM JPEG PS PNG GIF DOCM PCL PDF RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Eksportuj EMLX do PDF przez .NET" h2="Interfejs API .NET do renderowania poczty e-mail do PDF w systemach Windows, macOS i Linux bez korzystania z programu Word lub Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jeśli jesteś programistą .NET i chcesz dodać funkcje konwersji EMLX do PDF w swoich aplikacjach, najlepszym rozwiązaniem są interfejsy API [Aspose.Total for .NET](https://products.aspose.com/total/net/) Naprzód. Używając [Aspose.Email for .NET](https://products.aspose.com/email/net/), możesz przekonwertować format pliku EMLX na HTML. Następnie, używając [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz renderować HTML do PDF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API do konwersji EMLX na PDF" %}}
1. Otwórz plik EMLX za pomocą klasy [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Konwertuj EMLX na HTML za pomocą metody [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
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

{{% blocks/products/pf/feature-page-section  h2="Przeanalizuj plik EMLX przez .NET" %}}
Przed konwersją EMLX na PDF, jeśli chcesz się upewnić, że konwertujesz poprawny e-mail, możesz załadować dokument EMLX, przeanalizować go i spojrzeć na żądaną właściwość. Korzystając z klasy [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, możesz uzyskać informacje o nadawcy i odbiorcy. Na przykład możesz sprawdzić konkretny adres e-mail nadawcy dla konwersji za pomocą właściwości [NazwaNadawcy](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ogranicz edycję dokumentów PDF przez .NET" %}}
Podczas zapisywania dokumentu z EMLX do PDF może być konieczne zabezpieczenie dokumentu wyjściowego. Czasami może zajść potrzeba ograniczenia możliwości edycji dokumentu i zezwolenia tylko na określone czynności. Może to być przydatne, aby uniemożliwić innym osobom edytowanie poufnych i poufnych informacji w Twoim dokumencie. Interfejs API [Aspose.Words for .NET](https://products.aspose.com/words/net/) umożliwia kontrolowanie sposobu ograniczania treści za pomocą [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr wyliczenia. Możesz ustawić dokument jako tylko do odczytu, używając następujących wierszy kodu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pdf", SaveFormat.Pdf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku EMLX w PDF programowo: przypadki użycia" %}}
Plik EMLX (Eudora Mail Exchange) jest przeznaczony do przechowania informacji opartych na tekście elektronicznych wiadomości, czyniąc go idealnym dla tworzenia cyfrowych archiwów przeszłych komunikatów. Jednak przy pracy z zawartością wizualną, pliki PDF stają się niezbędni do udostępniania i przechowaniu dokumentów.

Przekonwertowanie plików EMLX na formaty PDF jest niezbędne, aby rozwinąć pełną potęgę swoich możliwości archiwowania cyfrowego. To pozwala:

**Przykłady użycia:**

- **Archiwowanie cyfrowe:** Przekonwertowanie plików EMLX tworzy trwałą rejestrację przeszłych komunikatów, w tym wiadomości, załączków i informacji o nadatcach.
  
- **Zachowanie dokumentów:** Wykorzystujmy pliki PDF do zachowania kluczowych dokumentów, takich jak umowy, porozumienia i protokóły spotkań, w celu ich wykorzystania na przyszłość i z uwagi na potrzeby prawnicze.

- **Śledzenie zamówleń w handlu elektronicznym:** Przekonwertowanie plików EMLX pozwala śledzić szczegóły zamówlenia, takie jak informacje o wysyłce, rekordy płatności i komunikaty z klientów.

- **Dokumentacja techniczna:** Wykorzystujmy pliki PDF do tworzenia poradników technicznych, przewodników i zasobów pomocy dla zespołów obsługi.

- **Sprawdzanie zgody:** Przekonwertowanie plików EMLX pozwala tworzyć raporty sprawdzające, takie jak śledzenie audytów, logi incydentów i przepaści bezpieczeństwa.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}