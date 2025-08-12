---
title: Java API do eksportu CGM do MHTML
description: Konwertuj CGM na MHTML za pomocą lokalnego interfejsu Java API
url_ignore: /pl/java/conversion/cgm-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: MHTML
otherformats: XAMLFLOW DOTX WORDML OTT FLATOPC DOTM PCL ODT PS MHTML MARKDOWN DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Przekształć CGM w MHTML za pomocą Javy" h2="On Premise Java API do renderowania CGM do MHTML bez korzystania z aplikacji innych firm" >}}
{{% blocks/products/pf/feature-page-summary %}}
Możesz przekonwertować CGM na MHTML, wykonując dwa proste kroki. Najpierw musisz wyrenderować plik CGM do DOC za pomocą [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Następnie, korzystając z potężnego interfejsu API przetwarzania dokumentów [Aspose.Words for Java](https://products.aspose.com/words/java/), możesz przekonwertować DOC na MHTML. Oba interfejsy API są objęte pakietem [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API do konwersji CGM na MHTML" %}}
1. Otwórz plik CGM za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Przekonwertuj CGM na DOC, używając [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metoda
3. Załaduj plik DOC za pomocą klasy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words
4. Zapisz dokument w formacie MHTML za pomocą metody [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) i ustaw MHTML jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://releases.aspose.com/total/java/) i dołącz [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) i [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) w pliku pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-mhtml.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Podczas konwersji CGM na MHTML, nawet jeśli dokument jest chroniony hasłem, nadal możesz go otworzyć za pomocą interfejsu API manipulacji PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Aby otworzyć zaszyfrowany plik, musisz utworzyć obiekt [Dokument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) i otworzyć CGM przy użyciu hasła właściciela.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "open-password-protected-cgm.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Otwórz dokument CGM chroniony hasłem przez Java" %}}
Podczas zapisywania dokumentu wejściowego w formacie pliku MHTML możesz również zapisać dokument w bazie danych zamiast w systemie plików. Może być konieczne zaimplementowanie przechowywania i pobierania obiektów Document do iz bazy danych. Byłoby to konieczne, gdybyś wdrażał dowolny system zarządzania treścią. W celu zapisania MHTML w bazie danych często konieczne jest wykonanie serializacji dokumentu w celu uzyskania tablicy bajtów. Można to zrobić za pomocą interfejsu API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Po uzyskaniu tablicy bajtów możesz przechowywać ją w bazie danych za pomocą instrukcji SQL. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "save-cgm-to-database.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Konwertowanie plików **Computer Graphics Metafile (CGM)** na format **MHTML (MIME HTML)** jest niezbędne do zachowania złożonych dokumentów inżynieryjnych i technicznych z osadzonymi grafikami w jednym, samodzielnym pliku. W **systemach archiwizacji internetowej opartych na Java**, ta konwersja pozwala organizacjom przechowywać kompletne dokumenty—w tym wizualizacje CGM, style i zasoby—w przenośnym archiwum odpowiednim do offline'owego przeglądania i wdrażania w intranecie. MHTML zapewnia, że specyfikacje projektowe, raporty i rysunki pozostaną nietknięte dla długoterminowego dostępu i dystrybucji.

---

## ✅ Kluczowe przypadki użycia

- **Pakowanie dokumentów inżynieryjnych z osadzonymi grafikami**  
  Spakuj diagramy CGM i powiązane treści do MHTML dla spójnych, samodzielnych technicznych rejestrów.

- **Offline'owe przeglądanie w portalach intranetowych**  
  Udostępnij dokumenty wzbogacone o CGM w formacie MHTML dla bezproblemowego offline'owego dostępu w sieciach korporacyjnych.

- **Archiwizacja specyfikacji projektowych**  
  Przechowuj wersje MHTML specyfikacji opartych na CGM dla zgodności, odniesienia i dokumentacji projektowej.

---

## ⚙️ Scenariusze automatyzacji

- **Biblioteki Java z obsługą MHTML**  
  Użyj interfejsów API takich jak **Aspose.Words dla Java** lub niestandardowych eksporterów Java do generowania plików MHTML z dokumentów opartych na CGM.

- **Narzędzia eksportu oparte na sieci**  
  Zintegruj konwersję CGM na MHTML do aplikacji internetowych zasilanych przez Javę dla natychmiastowego pakowania plików.

- **Przepływy pracy oparte na serwletach**  
  Wdroż serwlety Javy, które przetwarzają dane wejściowe CGM i generują archiwa MHTML do bezpiecznej dystrybucji.

- **Zautomatyzowane potoki archiwizacyjne**  
  Dodaj kroki konwersji CGM na MHTML do systemów zarządzania dokumentami lub ETL opartych na Javie dla zaplanowanej archiwizacji.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}