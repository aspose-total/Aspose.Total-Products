---
title: C# API do eksportu EML do IMAGE
description: Konwertuj EML na IMAGE bez używania Microsoft Word lub Outlook na .NET
url_ignore: /pl/net/conversion/eml-to-image/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: PNG
otherformats: EMF WORDML PDF ODT MD TEXT DOTM DOC DOCX DOT DOCM IMAGE SVG EPUB JPEG RTF PNG XPS GIF PCL PS TIFF DOTX OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Eksportuj EML do IMAGE przez .NET" h2="Interfejs API .NET do renderowania poczty e-mail do IMAGE w systemach Windows, macOS i Linux bez korzystania z programu Word lub Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jeśli jesteś programistą .NET i chcesz dodać funkcje konwersji EML do IMAGE w swoich aplikacjach, najlepszym rozwiązaniem są interfejsy API [Aspose.Total for .NET](https://products.aspose.com/total/net/) Naprzód. Używając [Aspose.Email for .NET](https://products.aspose.com/email/net/), możesz przekonwertować format pliku EML na HTML. Następnie, używając [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz renderować HTML do IMAGE.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API do konwersji EML na IMAGE" %}}
1. Otwórz plik EML za pomocą klasy [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Konwertuj EML na HTML za pomocą metody [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
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

{{% blocks/products/pf/feature-page-section  h2="Przeanalizuj plik EML przez .NET" %}}
Przed konwersją EML na IMAGE, jeśli chcesz się upewnić, że konwertujesz poprawny e-mail, możesz załadować dokument EML, przeanalizować go i spojrzeć na żądaną właściwość. Korzystając z klasy [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, możesz uzyskać informacje o nadawcy i odbiorcy. Na przykład możesz sprawdzić konkretny adres e-mail nadawcy dla konwersji za pomocą właściwości [NazwaNadawcy](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ogranicz edycję dokumentów IMAGE przez .NET" %}}
Podczas zapisywania dokumentu z EML do IMAGE może być konieczne zabezpieczenie dokumentu wyjściowego. Czasami może zajść potrzeba ograniczenia możliwości edycji dokumentu i zezwolenia tylko na określone czynności. Może to być przydatne, aby uniemożliwić innym osobom edytowanie poufnych i poufnych informacji w Twoim dokumencie. Interfejs API [Aspose.Words for .NET](https://products.aspose.com/words/net/) umożliwia kontrolowanie sposobu ograniczania treści za pomocą [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr wyliczenia. Możesz ustawić dokument jako tylko do odczytu, używając następujących wierszy kodu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Png
document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku EML w IMAGE programowo: przypadki użycia" %}}
Pliki EML (Electronic Mail) są używane do przechowania treści elektronicznych wiadomości, czyniąc je idealnymi dla tworzenia statycznej zawartości wysyłanych przez pocztę. Jednak gdy pracujemy z dynamicznymi zdjęciami i grafikami, formaty takie jak JPEG lub PNG stają się niezbędne dla efektywnego przekazywania informacji wizualnej.

Przekształcenie plików EML na formaty obrazkowe jest koniecznym krokiem, aby wykorzystać pełną potęgę swoich umiejętności komunikacyjnych. To przekształcenie pozwala Ci:

**Użycia:**

*   **Tworzenie zawartości dla platformy social media**: Przekształć pliki EML na zdjęcia i grafiki, które będą chwalić się na platformach społecznościowych.
*   **Wystawa produktów w handlu elektronicznym**: Wykorzystać formaty obrazkowe do pokazania informacji o produkcie, jego cechach i zaletściach w sposób atrakcyjny.
*   **Kampanie marketingowe cyfrowe**: Tworzyć przepiękne kampanie email oraz materiały promocyjne i strony sprzedaży.
*   **Ilustracje dla blogów i artykułów**: Dodawać względne ilustracje do skomplikowanych blogów, artykułów i raportów.
*   **Dokumentacja techniczna**: Tworzyć przepięknie dokumenty techniczne, instrukcje użytkownika oraz przewodniki.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}