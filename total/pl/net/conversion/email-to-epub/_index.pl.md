---
title: C# API do eksportu EMAIL do EPUB
description: Konwertuj EMAIL na EPUB bez używania Microsoft Word lub Outlook na .NET
url_ignore: /pl/net/conversion/email-to-epub/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: EPUB
otherformats: DOTM PNG PS SVG TIFF JPEG ODT DOT DOCM PCL OTT EPUB WORDML DOTX RTF MD PDF GIF FLATOPC EMF TEXT XPS DOCX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Eksportuj EMAIL do EPUB przez .NET" h2="Interfejs API .NET do renderowania poczty e-mail do EPUB w systemach Windows, macOS i Linux bez korzystania z programu Word lub Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jeśli jesteś programistą .NET i chcesz dodać funkcje konwersji EMAIL do EPUB w swoich aplikacjach, najlepszym rozwiązaniem są interfejsy API [Aspose.Total for .NET](https://products.aspose.com/total/net/) Naprzód. Używając [Aspose.Email for .NET](https://products.aspose.com/email/net/), możesz przekonwertować format pliku EMAIL na HTML. Następnie, używając [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz renderować HTML do EPUB.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API do konwersji EMAIL na EPUB" %}}
1. Otwórz plik EMAIL za pomocą klasy [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Konwertuj EMAIL na HTML za pomocą metody [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Załaduj HTML za pomocą klasy [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Zapisz dokument w formacie EPUB za pomocą metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) i ustaw Epub jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.msg");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.epub", SaveFormat.Epub); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Przeanalizuj plik EMAIL przez .NET" %}}
Przed konwersją EMAIL na EPUB, jeśli chcesz się upewnić, że konwertujesz poprawny e-mail, możesz załadować dokument EMAIL, przeanalizować go i spojrzeć na żądaną właściwość. Korzystając z klasy [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, możesz uzyskać informacje o nadawcy i odbiorcy. Na przykład możesz sprawdzić konkretny adres e-mail nadawcy dla konwersji za pomocą właściwości [NazwaNadawcy](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ogranicz edycję dokumentów EPUB przez .NET" %}}
Podczas zapisywania dokumentu z EMAIL do EPUB może być konieczne zabezpieczenie dokumentu wyjściowego. Czasami może zajść potrzeba ograniczenia możliwości edycji dokumentu i zezwolenia tylko na określone czynności. Może to być przydatne, aby uniemożliwić innym osobom edytowanie poufnych i poufnych informacji w Twoim dokumencie. Interfejs API [Aspose.Words for .NET](https://products.aspose.com/words/net/) umożliwia kontrolowanie sposobu ograniczania treści za pomocą [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr wyliczenia. Możesz ustawić dokument jako tylko do odczytu, używając następujących wierszy kodu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.epub", SaveFormat.Epub);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku EMAIL w EPUB programowo: przypadki użycia" %}}
Pliki email są używane do przechowywania wiadomości tekstowych, czyniąc je idealnymi dla tworzenia indywidualnych komunikatów i newsletterów. Jednak gdy mamy do czynienia z multimedią, formaty EPUB (Electronic Publication) stają się niezbędne dla digital publishing oraz dystrybucji książek.

Przekształcenie plików email w formaty EPUB jest konieczne, aby wykorzystać pełną możliwość Twoich umiejętności publikowania cyfrowego. To przekształcenie pozwala Ci:

**Użycia:**

*   **Personalizowane E-Newsletters**: Przekształć pliki email do tworzenia zaangażujących e-newsletterów, personalizowanych z imionami czyliami i zainteresowaniami odbiorców.
*   **Digital Magazine Publishing**: Wykorzystać format EPUB do publikowania magazynów, gazet i czasopism w formacie łatwo czytelnym na różnych urządzeniach.
*   **E-Book Publishing**: Przekształć pliki email do tworzenia interaktywnych książek elektronicznych z linkami, zdjęciami i zawartością multimediową.
*   **Corporate Communications**: Wykorzystać format EPUB do rozłożenia raportów firmy, polityk i procedur w sposób dostępny dla pracowników i interesentów.
*   **Digital Content Distribution**: Przekształć pliki email do publikowania zawartości cyfrowej, takiej jak artykuły, blogi czy filmy, na różnych platformach.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}