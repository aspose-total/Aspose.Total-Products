---
title: C# API do eksportu EML do XPS
description: Konwertuj EML na XPS bez używania Microsoft Word lub Outlook na .NET
url_ignore: /pl/net/conversion/eml-to-xps/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: XPS
otherformats: DOC PS WORDML DOCX PNG DOTM SVG EMF ODT MD DOTX OTT XPS EPUB GIF DOT JPEG DOCM RTF PCL TIFF PDF FLATOPC TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Eksportuj EML do XPS przez .NET" h2="Interfejs API .NET do renderowania poczty e-mail do XPS w systemach Windows, macOS i Linux bez korzystania z programu Word lub Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jeśli jesteś programistą .NET i chcesz dodać funkcje konwersji EML do XPS w swoich aplikacjach, najlepszym rozwiązaniem są interfejsy API [Aspose.Total for .NET](https://products.aspose.com/total/net/) Naprzód. Używając [Aspose.Email for .NET](https://products.aspose.com/email/net/), możesz przekonwertować format pliku EML na HTML. Następnie, używając [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz renderować HTML do XPS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API do konwersji EML na XPS" %}}
1. Otwórz plik EML za pomocą klasy [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Konwertuj EML na HTML za pomocą metody [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Załaduj HTML za pomocą klasy [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Zapisz dokument w formacie XPS za pomocą metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) i ustaw Xps jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Przeanalizuj plik EML przez .NET" %}}
Przed konwersją EML na XPS, jeśli chcesz się upewnić, że konwertujesz poprawny e-mail, możesz załadować dokument EML, przeanalizować go i spojrzeć na żądaną właściwość. Korzystając z klasy [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, możesz uzyskać informacje o nadawcy i odbiorcy. Na przykład możesz sprawdzić konkretny adres e-mail nadawcy dla konwersji za pomocą właściwości [NazwaNadawcy](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ogranicz edycję dokumentów XPS przez .NET" %}}
Podczas zapisywania dokumentu z EML do XPS może być konieczne zabezpieczenie dokumentu wyjściowego. Czasami może zajść potrzeba ograniczenia możliwości edycji dokumentu i zezwolenia tylko na określone czynności. Może to być przydatne, aby uniemożliwić innym osobom edytowanie poufnych i poufnych informacji w Twoim dokumencie. Interfejs API [Aspose.Words for .NET](https://products.aspose.com/words/net/) umożliwia kontrolowanie sposobu ograniczania treści za pomocą [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr wyliczenia. Możesz ustawić dokument jako tylko do odczytu, używając następujących wierszy kodu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.xps", SaveFormat.Xps);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku EML w XPS programowo: przypadki użycia" %}}
Pliki EML (Electronic Mail) są używani do przechowania tekstowych wiadomości elektronicznych, czyniąc ich idealnymi do tworzenia statycznych dokumentów i komunikatów. Jednak gdy pracujemy z dynamicznymi multimediowymi danymi, pliki XPS (specyfikacja XML na papier) stają się niezbędne do zachowania formatowania i układu zawartości.

Przekształcenie plików EML na formaty XPS pozwala wykorzystać pełną możliwość przesłania i prezentacji dokumentów. To przekształcenie umożliwia:

**Użytki:**

* **Zachowanie historii dokumentów**: Przekształć pliki EML aby zachować historyczne wiadomości, dokumenty i komunikaty w formacie, który zachowuje ich oryginalny układ i formatowanie.
* **Publikacja w formie e-booku**: Wykorzystać XPS do tworzenia interaktywnych e-booków, gdzie formatowanie i typografia tekstu są zachowane dla optymalnej doświadczeniu czytelności.
* **Weryfikacja cyfrowego podpisu**: Przekształć pliki EML aby weryfikować cyfrowe podpisy i zapewnić autentykację wiadomości i dokumentów.
* **Zgodność z WCAG**: Wykorzystać XPS do tworzenia dostępnych dokumentów, które są zgodne ze standardami WCAG, zapewniając kompatybilność z technologiami pomagającymi osobom z niepełnosprawnością.
* **Analiza forenzowa**: Przekształć pliki EML aby przeprowadzić analizę zawartości wiadomości na potrzeby forenzyjnych celów, takie jak śledzenie lokalizacji nadatców lub identyfikacja szkodów komputerowych.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}