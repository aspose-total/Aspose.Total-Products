---
title: C# API do eksportu EMAIL do XPS
description: Konwertuj EMAIL na XPS bez używania Microsoft Word lub Outlook na .NET
url_ignore: /pl/net/conversion/email-to-xps/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: XPS
otherformats: ODT DOTM DOCX PDF JPEG TEXT DOCM WORDML RTF PS PNG TIFF DOTX EMF XPS GIF MD DOC OTT DOT SVG PCL EPUB FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Eksportuj EMAIL do XPS przez .NET" h2="Interfejs API .NET do renderowania poczty e-mail do XPS w systemach Windows, macOS i Linux bez korzystania z programu Word lub Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jeśli jesteś programistą .NET i chcesz dodać funkcje konwersji EMAIL do XPS w swoich aplikacjach, najlepszym rozwiązaniem są interfejsy API [Aspose.Total for .NET](https://products.aspose.com/total/net/) Naprzód. Używając [Aspose.Email for .NET](https://products.aspose.com/email/net/), możesz przekonwertować format pliku EMAIL na HTML. Następnie, używając [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz renderować HTML do XPS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API do konwersji EMAIL na XPS" %}}
1. Otwórz plik EMAIL za pomocą klasy [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Konwertuj EMAIL na HTML za pomocą metody [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
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

{{% blocks/products/pf/feature-page-section  h2="Przeanalizuj plik EMAIL przez .NET" %}}
Przed konwersją EMAIL na XPS, jeśli chcesz się upewnić, że konwertujesz poprawny e-mail, możesz załadować dokument EMAIL, przeanalizować go i spojrzeć na żądaną właściwość. Korzystając z klasy [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, możesz uzyskać informacje o nadawcy i odbiorcy. Na przykład możesz sprawdzić konkretny adres e-mail nadawcy dla konwersji za pomocą właściwości [NazwaNadawcy](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ogranicz edycję dokumentów XPS przez .NET" %}}
Podczas zapisywania dokumentu z EMAIL do XPS może być konieczne zabezpieczenie dokumentu wyjściowego. Czasami może zajść potrzeba ograniczenia możliwości edycji dokumentu i zezwolenia tylko na określone czynności. Może to być przydatne, aby uniemożliwić innym osobom edytowanie poufnych i poufnych informacji w Twoim dokumencie. Interfejs API [Aspose.Words for .NET](https://products.aspose.com/words/net/) umożliwia kontrolowanie sposobu ograniczania treści za pomocą [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr wyliczenia. Możesz ustawić dokument jako tylko do odczytu, używając następujących wierszy kodu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.xps", SaveFormat.Xps);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku EMAIL w XPS programowo: przypadki użycia" %}}
Przekształcanie Email na Pliki XPS: Odkrycie Potencjalu Wizualnych Treści

Emails są niezbędnym narzędziem komunikacji, ale gdy chodzi o zawartość wizualną, często przegradzają. Inne formaty jak PDF lub XPS lepiej zachowują oryginalną grafikę i układ, podczas gdy emaily mogą utracić jakość obrazów oraz formatowanie podczas przekazywania.

Wtedy wchodzi na scenę konwersja. Przekształcanie emailów na pliki XPS to prosty proces, który pozwala:

**Użycia:**

*   **Zachowanie Wizualnej Treści**: Przekształć email na plik XPS aby Twoje zawartość wizualna pozostała niezmączone przy ich przekazywaniu lub archiwowaniu.
*   **Wersja Do Druku**: Wykorzystać pliki XPS do tworzenia wersji do druku swoich emailów, idealnie pasujących na prezentacje, raporty oraz inne formale komunikaty.
*   **Bezpieczeństwo i Zgodność z Przepisami**: Przekształć emaily na pliki XPS aby spełnić wymiary prawne oraz zapewnić bezpieczeństwo swojej wizualnej zawartości.
*   **Archiwowanie i Zachowanie na Prawo**: Zapisać pliki XPS aby zachować załączki i obrazy do archiwowania lub spełnienia wymiarów prawnych.
*   **Dostępność dla Osób ze Slabym Okiem**: Przekształć emaily na pliki XPS aby poprawić dostępność dla osób ze słbym okiem.

Przekształcając swoje emaily na pliki XPS możesz wykorzystać pełny potencjał swojej zawartości wizualnej i być pewnym że ona pozostaje kolorową i całkowitą.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}