---
title: C# API do eksportu EMAIL do DOC
description: Konwertuj EMAIL na DOC bez używania Microsoft Word lub Outlook na .NET
url_ignore: /pl/net/conversion/email-to-doc/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: DOC
otherformats: TEXT RTF DOC JPEG EMF EPUB DOT GIF PCL WORDML ODT TIFF SVG DOCM MD DOTX PS DOTM DOCX OTT PDF XPS FLATOPC PNG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Eksportuj EMAIL do DOC przez .NET" h2="Interfejs API .NET do renderowania poczty e-mail do DOC w systemach Windows, macOS i Linux bez korzystania z programu Word lub Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jeśli jesteś programistą .NET i chcesz dodać funkcje konwersji EMAIL do DOC w swoich aplikacjach, najlepszym rozwiązaniem są interfejsy API [Aspose.Total for .NET](https://products.aspose.com/total/net/) Naprzód. Używając [Aspose.Email for .NET](https://products.aspose.com/email/net/), możesz przekonwertować format pliku EMAIL na HTML. Następnie, używając [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz renderować HTML do DOC.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API do konwersji EMAIL na DOC" %}}
1. Otwórz plik EMAIL za pomocą klasy [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Konwertuj EMAIL na HTML za pomocą metody [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Załaduj HTML za pomocą klasy [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Zapisz dokument w formacie DOC za pomocą metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) i ustaw Doc jako SaveFormat
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
Przed konwersją EMAIL na DOC, jeśli chcesz się upewnić, że konwertujesz poprawny e-mail, możesz załadować dokument EMAIL, przeanalizować go i spojrzeć na żądaną właściwość. Korzystając z klasy [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, możesz uzyskać informacje o nadawcy i odbiorcy. Na przykład możesz sprawdzić konkretny adres e-mail nadawcy dla konwersji za pomocą właściwości [NazwaNadawcy](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ogranicz edycję dokumentów DOC przez .NET" %}}
Podczas zapisywania dokumentu z EMAIL do DOC może być konieczne zabezpieczenie dokumentu wyjściowego. Czasami może zajść potrzeba ograniczenia możliwości edycji dokumentu i zezwolenia tylko na określone czynności. Może to być przydatne, aby uniemożliwić innym osobom edytowanie poufnych i poufnych informacji w Twoim dokumencie. Interfejs API [Aspose.Words for .NET](https://products.aspose.com/words/net/) umożliwia kontrolowanie sposobu ograniczania treści za pomocą [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr wyliczenia. Możesz ustawić dokument jako tylko do odczytu, używając następujących wierszy kodu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.doc", SaveFormat.Doc);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku EMAIL w DOC programowo: przypadki użycia" %}}
Przekształcenie plików email na format Microsoft Office Documents (DOC)

Pliki email są często używane do komunikacji, ale gdy chodzi o udostępnianie i analizę danych, formaty Microsoft Office dokumentów stają się nieocenionymi. Przekształcenie plików email na format DOC pozwala wykorzystać pełną funkcjonalność Twoich możliwości tworzenia i analizy dokumentów.

Przekształcenie plików email na formaty DOC jest konieczne, aby wykorzystać pełną funkcjonalność Twoich możliwości tworzenia i analizy dokumentów. Ten przekształcenie umożliwia:

**Użycia przypadków:**

*   **Wysyłanie projektu wniosku na spotkanie**: Przekształć pliki email na profesjonalne dokumenty projektu wniosku, pokazujące kluczowe szczegóły i terminy.
*   **Dokumentowanie minut spotkani**: Użyć formatu DOC do organizacji minut spotkani, punktów akcji oraz decyzji podjętych podczas spotkania.
*   **Przeglądanie i analiza umowy**: Przekształć pliki email na dokumenty, aby przeglądać i analizować umowę, zapewneć, że wszystkie warunki są wyrażone jasno przez obie strony.
*   **Wysyłanie CV i listu motywacyjnego**: Tworzyć profesjonalne CV i listy motywacyjne za pomocą szablonów DOC, dostosowując materiały aplikacyjne do konkretnych ofert pracy.
*   **Generowanie raportów z konferencji**: Użyć formatu DOC do tworzenia raportów z konferencji, podsumowujących kluczowe prezentacje, dyskusje i wyniki.

Przekształcenie plików email na format DOC pozwala wyjątkowo skutecznie zarzązić i analizować potrzeby tworzenia dokumentów.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}