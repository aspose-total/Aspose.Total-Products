---
title: C# API do eksportu EMLX do IMAGE
description: Konwertuj EMLX na IMAGE bez używania Microsoft Word lub Outlook na .NET
url_ignore: /pl/net/conversion/emlx-to-image/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: PNG
otherformats: DOCX EMF MD TEXT DOT DOTM TIFF WORDML PS DOTX XPS PDF SVG FLATOPC JPEG DOCM DOC PCL EPUB OTT IMAGE ODT RTF GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Eksportuj EMLX do IMAGE przez .NET" h2="Interfejs API .NET do renderowania poczty e-mail do IMAGE w systemach Windows, macOS i Linux bez korzystania z programu Word lub Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jeśli jesteś programistą .NET i chcesz dodać funkcje konwersji EMLX do IMAGE w swoich aplikacjach, najlepszym rozwiązaniem są interfejsy API [Aspose.Total for .NET](https://products.aspose.com/total/net/) Naprzód. Używając [Aspose.Email for .NET](https://products.aspose.com/email/net/), możesz przekonwertować format pliku EMLX na HTML. Następnie, używając [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz renderować HTML do IMAGE.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API do konwersji EMLX na IMAGE" %}}
1. Otwórz plik EMLX za pomocą klasy [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Konwertuj EMLX na HTML za pomocą metody [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
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

{{% blocks/products/pf/feature-page-section  h2="Przeanalizuj plik EMLX przez .NET" %}}
Przed konwersją EMLX na IMAGE, jeśli chcesz się upewnić, że konwertujesz poprawny e-mail, możesz załadować dokument EMLX, przeanalizować go i spojrzeć na żądaną właściwość. Korzystając z klasy [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, możesz uzyskać informacje o nadawcy i odbiorcy. Na przykład możesz sprawdzić konkretny adres e-mail nadawcy dla konwersji za pomocą właściwości [NazwaNadawcy](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ogranicz edycję dokumentów IMAGE przez .NET" %}}
Podczas zapisywania dokumentu z EMLX do IMAGE może być konieczne zabezpieczenie dokumentu wyjściowego. Czasami może zajść potrzeba ograniczenia możliwości edycji dokumentu i zezwolenia tylko na określone czynności. Może to być przydatne, aby uniemożliwić innym osobom edytowanie poufnych i poufnych informacji w Twoim dokumencie. Interfejs API [Aspose.Words for .NET](https://products.aspose.com/words/net/) umożliwia kontrolowanie sposobu ograniczania treści za pomocą [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr wyliczenia. Możesz ustawić dokument jako tylko do odczytu, używając następujących wierszy kodu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Png
document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku EMLX w IMAGE programowo: przypadki użycia" %}}
Pliki EMLX (Electronic Mail with X-Content) są używane do przechowania prostego tekstu email, czyniąc ich idealnymi dla tworzenia statycznych email i newsletterów. Jednak gdy mamy do czynienia z dynamiką zawartości, zdjęcia stają się nieoczekiwanymi elementami wizualności i zaangażowania.

Przekształcenie plików EMLX na formaty obrazkowe jest konieczne, aby wykorzystać pełną potęgę możliwości marketingu i projektowania email. To przekształcenie pozwala na:

**Użycia:**

*   **Kampanie email personalizowane**: Przekształć pliki EMLX na formaty obrazkowe, aby stworzyć osobiste email z dynamiką zawartości, taką jak imiona, adresy i doporučení produktów.  
*   **Projektowanie i rozwój newsletterów**: Wykorzystać formaty obrazkowe do wizualizacji newsletterów, optymalizacji układu i pomiaru metryków zaangażowania.  
*   **Tworzenie zawartości dla platform social media**: Przekształć pliki EMLX na zdjęcia, filmy i captiony, aby stworzyć przyciągające posty dla mediów społecznych.  
*   **Optymizację witryn e-commerce**: Wykorzystać formaty obrazkowe do wizualizacji informacji o produktach, simulacji doświadczeń użytkowników i walidacji koncepcji projektowania witrin.  
*   **Zgodność marki i konsystencja**: Przekształć pliki EMLX na formaty obrazkowe, aby stworzyć zgodną identyfikację marki w całej gamie kanałów marketingowych, w tym logotypy, schematy kolorów i typografię.

To przekształcenie pozwala wykorzystać pełną potęgę możliwości marketingu i projektowania email, tworząc wizualnie atrakcyjną i zaangażujące zawartość, która będzie rezonować z Twoją społczą branzą.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}