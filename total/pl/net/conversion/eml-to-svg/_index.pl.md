---
title: C# API do eksportu EML do SVG
description: Konwertuj EML na SVG bez używania Microsoft Word lub Outlook na .NET
url_ignore: /pl/net/conversion/eml-to-svg/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: SVG
otherformats: DOCX OTT PS DOTX WORDML GIF PNG SVG ODT RTF DOC PCL XPS MD DOT JPEG TIFF EMF TEXT PDF FLATOPC EPUB DOCM DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Eksportuj EML do SVG przez .NET" h2="Interfejs API .NET do renderowania poczty e-mail do SVG w systemach Windows, macOS i Linux bez korzystania z programu Word lub Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jeśli jesteś programistą .NET i chcesz dodać funkcje konwersji EML do SVG w swoich aplikacjach, najlepszym rozwiązaniem są interfejsy API [Aspose.Total for .NET](https://products.aspose.com/total/net/) Naprzód. Używając [Aspose.Email for .NET](https://products.aspose.com/email/net/), możesz przekonwertować format pliku EML na HTML. Następnie, używając [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz renderować HTML do SVG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API do konwersji EML na SVG" %}}
1. Otwórz plik EML za pomocą klasy [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Konwertuj EML na HTML za pomocą metody [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Załaduj HTML za pomocą klasy [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Zapisz dokument w formacie SVG za pomocą metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) i ustaw Svg jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.eml");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.svg", SaveFormat.Svg); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Przeanalizuj plik EML przez .NET" %}}
Przed konwersją EML na SVG, jeśli chcesz się upewnić, że konwertujesz poprawny e-mail, możesz załadować dokument EML, przeanalizować go i spojrzeć na żądaną właściwość. Korzystając z klasy [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, możesz uzyskać informacje o nadawcy i odbiorcy. Na przykład możesz sprawdzić konkretny adres e-mail nadawcy dla konwersji za pomocą właściwości [NazwaNadawcy](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EML file from disk
var outlookMessageFile = MapiMessage.FromFile("message.eml");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ogranicz edycję dokumentów SVG przez .NET" %}}
Podczas zapisywania dokumentu z EML do SVG może być konieczne zabezpieczenie dokumentu wyjściowego. Czasami może zajść potrzeba ograniczenia możliwości edycji dokumentu i zezwolenia tylko na określone czynności. Może to być przydatne, aby uniemożliwić innym osobom edytowanie poufnych i poufnych informacji w Twoim dokumencie. Interfejs API [Aspose.Words for .NET](https://products.aspose.com/words/net/) umożliwia kontrolowanie sposobu ograniczania treści za pomocą [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr wyliczenia. Możesz ustawić dokument jako tylko do odczytu, używając następujących wierszy kodu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.svg", SaveFormat.Svg);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku EML w SVG programowo: przypadki użycia" %}}
Pliki EML (Electronic Mail) są używane do przechowania tekstowych wiadomości, czyniąc ich idealnymi dla wysyłki i odbioru maili. Jednak gdy mamy do czynienia z danymi w postaci graficznej, pliki SVG (Scalable Vector Graphics), czyli wektorowe grafiki skalowalne i niezależne od rozdzielczości, stają się niezbędne do tworzenia skalowalnych i wydajnych grafik.

Przekształcenie plików EML na format SVG jest konieczne, aby wykorzystać pełną możliwość wizualizacji i analizy danych opartych na grafikach. To przekształcenie pozwala na:

**Użycia:**  

*   **Projektowanie stron internetowych**: Przekształć pliki EML na wektorowe grafiki webowe, logi i ikony, które będą skalować się w różnych rozdzielczościach ekranu.  
*   **Dessktop Publishing**: Wykorzystać SVG do wizualizacji skomplikowanych danych, takich jak wykresy, diagramy i infografiki, w publikacjach i prezentacjach.  
*   **Rozwoju aplikacji mobilnych**: Przekształć pliki EML na skalowalne grafiki i ilustracje dla aplikacji mobilnych, zapewniając spójną doświadczenie użytkownika na różnych urządzeniach.  
*   **Tworzenie treści edukacyjnej**: Wykorzystać SVG do tworzenia interaktywnych i przyciągających względów vizualizacji dla treści edukacyjnej, takich jak animowane poradki i symulacje.  
*   **Wizualizacja danych i raportowanie**: Przekształć pliki EML na interaktywne dashbordy, raporty i wizualizacje dla interesujących stron, co umożliwi lepsze podejmowanie decyzji.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}