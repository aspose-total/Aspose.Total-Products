---
title: C# API do eksportu EMLX do JPEG
description: Konwertuj EMLX na JPEG bez używania Microsoft Word lub Outlook na .NET
url_ignore: /pl/net/conversion/emlx-to-jpeg/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: JPEG
otherformats: DOCM PDF OTT XPS MD PS ODT DOT DOTM EMF DOTX SVG DOC GIF TEXT PCL TIFF FLATOPC RTF JPEG PNG DOCX EPUB WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Eksportuj EMLX do JPEG przez .NET" h2="Interfejs API .NET do renderowania poczty e-mail do JPEG w systemach Windows, macOS i Linux bez korzystania z programu Word lub Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jeśli jesteś programistą .NET i chcesz dodać funkcje konwersji EMLX do JPEG w swoich aplikacjach, najlepszym rozwiązaniem są interfejsy API [Aspose.Total for .NET](https://products.aspose.com/total/net/) Naprzód. Używając [Aspose.Email for .NET](https://products.aspose.com/email/net/), możesz przekonwertować format pliku EMLX na HTML. Następnie, używając [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz renderować HTML do JPEG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API do konwersji EMLX na JPEG" %}}
1. Otwórz plik EMLX za pomocą klasy [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Konwertuj EMLX na HTML za pomocą metody [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Załaduj HTML za pomocą klasy [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Zapisz dokument w formacie JPEG za pomocą metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) i ustaw Jpeg jako SaveFormat
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
Przed konwersją EMLX na JPEG, jeśli chcesz się upewnić, że konwertujesz poprawny e-mail, możesz załadować dokument EMLX, przeanalizować go i spojrzeć na żądaną właściwość. Korzystając z klasy [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, możesz uzyskać informacje o nadawcy i odbiorcy. Na przykład możesz sprawdzić konkretny adres e-mail nadawcy dla konwersji za pomocą właściwości [NazwaNadawcy](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ogranicz edycję dokumentów JPEG przez .NET" %}}
Podczas zapisywania dokumentu z EMLX do JPEG może być konieczne zabezpieczenie dokumentu wyjściowego. Czasami może zajść potrzeba ograniczenia możliwości edycji dokumentu i zezwolenia tylko na określone czynności. Może to być przydatne, aby uniemożliwić innym osobom edytowanie poufnych i poufnych informacji w Twoim dokumencie. Interfejs API [Aspose.Words for .NET](https://products.aspose.com/words/net/) umożliwia kontrolowanie sposobu ograniczania treści za pomocą [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr wyliczenia. Możesz ustawić dokument jako tylko do odczytu, używając następujących wierszy kodu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.jpeg", SaveFormat.Jpeg);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku EMLX w JPEG programowo: przypadki użycia" %}}
Plik EMLX (Electronic Mail with X.400) jest używany do przechowywania informacji tekstowej, czyniąc go idealnym dla wysyłki email i wymiany wiadomości. Jednak przy pracy z statycznymi zawartościami wizualnymi, zdjęcia w formacie JPEG (Joint Photographic Experts Group) stają się niezbędne do ich udostępniania i wyświetlania.

Przekształcenie plików EMLX na formaty JPEG jest konieczne, aby rozwinąć pełną możliwość Twoich umiejętności dotyczących udostępniania zawartości wizualnej. To przekształcenie pozwala Ci:

**Użycia przypadków:**

* **Materiały marketingowe**: Przekształć pliki EMLX na wygląd atrakcyjnych materiałów marketingowych, takich jak broszury produktów, newslettery firmy lub promocji emaili.  
* ** Udostępnianie na platformach społecznościowych**: Wykorzystać zdjęcia w formacie JPEG do udostępniania ich na platformach społecznościowych, co poprawi engagement i zasięg.  
* **Treści strony internetowej**: Przekształć pliki EMLX na wysyłanie wyjątkowo wysokiej jakości zdjęć na stronie internetowej, poprawiając doznania użytkownika i podnosząc wiarygodność.  
* **Reklamę w formacie display**: Wykorzystać zdjęcia w formacie JPEG do tworzenia przypominających oksygenowych reklam, co zwiększy świadomość marki i pobudzi sprzedaż.  
* **Materiały wydarzeń**: Przekształć pliki EMLX na materiały drukowane, takie jak ulotki, posterowe i programy wydarzenia, które mogą być łatwo udostępniane uczestnikom.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}