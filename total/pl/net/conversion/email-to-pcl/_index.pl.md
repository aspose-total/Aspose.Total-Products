---
title: C# API do eksportu EMAIL do PCL
description: Konwertuj EMAIL na PCL bez używania Microsoft Word lub Outlook na .NET
url_ignore: /pl/net/conversion/email-to-pcl/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PCL
otherformats: DOTX EPUB ODT RTF GIF DOCX FLATOPC DOC TIFF JPEG EMF SVG PS PCL MD DOT PDF OTT PNG TEXT DOCM XPS WORDML DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Eksportuj EMAIL do PCL przez .NET" h2="Interfejs API .NET do renderowania poczty e-mail do PCL w systemach Windows, macOS i Linux bez korzystania z programu Word lub Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jeśli jesteś programistą .NET i chcesz dodać funkcje konwersji EMAIL do PCL w swoich aplikacjach, najlepszym rozwiązaniem są interfejsy API [Aspose.Total for .NET](https://products.aspose.com/total/net/) Naprzód. Używając [Aspose.Email for .NET](https://products.aspose.com/email/net/), możesz przekonwertować format pliku EMAIL na HTML. Następnie, używając [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz renderować HTML do PCL.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API do konwersji EMAIL na PCL" %}}
1. Otwórz plik EMAIL za pomocą klasy [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Konwertuj EMAIL na HTML za pomocą metody [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Załaduj HTML za pomocą klasy [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Zapisz dokument w formacie PCL za pomocą metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) i ustaw Pcl jako SaveFormat
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

document.Save("output.pcl", SaveFormat.Pcl); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Przeanalizuj plik EMAIL przez .NET" %}}
Przed konwersją EMAIL na PCL, jeśli chcesz się upewnić, że konwertujesz poprawny e-mail, możesz załadować dokument EMAIL, przeanalizować go i spojrzeć na żądaną właściwość. Korzystając z klasy [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, możesz uzyskać informacje o nadawcy i odbiorcy. Na przykład możesz sprawdzić konkretny adres e-mail nadawcy dla konwersji za pomocą właściwości [NazwaNadawcy](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ogranicz edycję dokumentów PCL przez .NET" %}}
Podczas zapisywania dokumentu z EMAIL do PCL może być konieczne zabezpieczenie dokumentu wyjściowego. Czasami może zajść potrzeba ograniczenia możliwości edycji dokumentu i zezwolenia tylko na określone czynności. Może to być przydatne, aby uniemożliwić innym osobom edytowanie poufnych i poufnych informacji w Twoim dokumencie. Interfejs API [Aspose.Words for .NET](https://products.aspose.com/words/net/) umożliwia kontrolowanie sposobu ograniczania treści za pomocą [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr wyliczenia. Możesz ustawić dokument jako tylko do odczytu, używając następujących wierszy kodu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pcl", SaveFormat.Pcl);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku EMAIL w PCL programowo: przypadki użycia" %}}
Przekształcanie plików email na formaty PCL jest niezbędne, aby wykorzystać pełną potęgę możliwości drukowania.

**Użycia:**

* **Automatyczne rozstawianie zadach drukowania**: Przekształć pliki email na format PCL, aby rozstawiać zadania drukowania automatycznie, zapewniając, że dokumenty będą drukowane w odpowiednim czasie i zmniejszając pracę rączną.  
* **Dobór ustawień drukowania osobniczych**: Wykorzystać formaty PCL do stosowania dostosowanych ustawień drukowania, takich jak wielkość papieru, orientacja i style fontów, aby poprawić doświadczenie drukowania.  
* **Monitorowanie w czasie rzeczywistym procesów drukowania**: Przekształć pliki email na systemy monitorowania drukowania w czasie rzeczywistym, umożliwiając śledzenie zadach drukowania w czasie rzeczywistym i optimalizację zasobów drukarskich.  
* **Bezpieczne drukowanie dokumentów**: Wykorzystać formaty PCL do wprowadzenia funkcji bezpieczeństwa, takich jak szyfrowanie i autentykacja, aby chronić wyrażenie poufności.  
* **Uproszczone przepływania zadach drukowania**: Przekształć pliki email na format PCL, aby uproszczyć przepływanie zadach drukowania, zmniejszając czas spędzany na przygotowanie zadach ręcznie i zwiększając wydajność.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}