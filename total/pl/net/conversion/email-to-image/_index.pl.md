---
title: C# API do eksportu EMAIL do IMAGE
description: Konwertuj EMAIL na IMAGE bez używania Microsoft Word lub Outlook na .NET
url_ignore: /pl/net/conversion/email-to-image/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PNG
otherformats: WORDML FLATOPC DOCM DOTX TIFF SVG TEXT PS DOT GIF EPUB RTF DOTM JPEG DOCX ODT PDF IMAGE XPS PNG EMF PCL DOC OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Eksportuj EMAIL do IMAGE przez .NET" h2="Interfejs API .NET do renderowania poczty e-mail do IMAGE w systemach Windows, macOS i Linux bez korzystania z programu Word lub Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jeśli jesteś programistą .NET i chcesz dodać funkcje konwersji EMAIL do IMAGE w swoich aplikacjach, najlepszym rozwiązaniem są interfejsy API [Aspose.Total for .NET](https://products.aspose.com/total/net/) Naprzód. Używając [Aspose.Email for .NET](https://products.aspose.com/email/net/), możesz przekonwertować format pliku EMAIL na HTML. Następnie, używając [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz renderować HTML do IMAGE.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API do konwersji EMAIL na IMAGE" %}}
1. Otwórz plik EMAIL za pomocą klasy [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Konwertuj EMAIL na HTML za pomocą metody [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Załaduj HTML za pomocą klasy [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Zapisz dokument w formacie IMAGE za pomocą metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) i ustaw Image jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Przeanalizuj plik EMAIL przez .NET" %}}
Przed konwersją EMAIL na IMAGE, jeśli chcesz się upewnić, że konwertujesz poprawny e-mail, możesz załadować dokument EMAIL, przeanalizować go i spojrzeć na żądaną właściwość. Korzystając z klasy [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, możesz uzyskać informacje o nadawcy i odbiorcy. Na przykład możesz sprawdzić konkretny adres e-mail nadawcy dla konwersji za pomocą właściwości [NazwaNadawcy](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ogranicz edycję dokumentów IMAGE przez .NET" %}}
Podczas zapisywania dokumentu z EMAIL do IMAGE może być konieczne zabezpieczenie dokumentu wyjściowego. Czasami może zajść potrzeba ograniczenia możliwości edycji dokumentu i zezwolenia tylko na określone czynności. Może to być przydatne, aby uniemożliwić innym osobom edytowanie poufnych i poufnych informacji w Twoim dokumencie. Interfejs API [Aspose.Words for .NET](https://products.aspose.com/words/net/) umożliwia kontrolowanie sposobu ograniczania treści za pomocą [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr wyliczenia. Możesz ustawić dokument jako tylko do odczytu, używając następujących wierszy kodu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Png
document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku EMAIL w IMAGE programowo: przypadki użycia" %}}
Przekształcenie wiadomości w formę obrazu: rozwój narracji wizualnej

Emaili są skutecznym narzędziem do przekazywania informacji, ale brakują im wizualnego przystropu w porównaniu z innymi formatami takimi jak obrazy. Konieczne jest przeobrażenie wiadomości w formę obrazu aby rozwiązać problem narracji wizualnej oraz zapisać zawartość na przyszłość.

Przekształcenie plików emaili w formę obrazu jest istotne dla:

**Użycia przypadków:**

*   **Zachowanie treści**: Przekształć emaili w obrazy aby zapisać zawartość takie jak notatki spotkania, umowy sprzedaży lub plany projektu dla przyszłej referencji.
*   **Ochrona marki**: Wykorzystać przeobrażenie do zachowania wzoru firmy, logotypu oraz innych wizualnych elementów z emaili aby upewnić się w jednorodności komunikacji.
*   **Tworzenie archiwu cyfrowego**: Przekształcić emaili w obrazy aby stworzyć cyfrowy archiw historyczny firmy obejmujący ważne wydarzenia, przełomy i procesy decyzjijnych.
*   **Dostępność i równości**: Przekształcić emaili w obrazy aby ułatwić dostęp do treści dla osób ze schorzeniami wzrokowymi lub inwalidami poprzez dodanie opisów tekstowych.
*   **Bezpieczeństwo i przepisy**: Wykorzystać przeobrażenie aby chronić wykryte informacje przed nieuprawnionym dostępem i spełnić wymiary przepisów dotyczących ochrony danych.

Przekształcenie plików emaili w formę obrazu pozwala organizacjom rozwiązać problem narracji wizualnej zapisać zawartość oraz upewnić się w przepisach.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}