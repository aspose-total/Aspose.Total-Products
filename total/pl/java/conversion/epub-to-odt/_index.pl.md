---
title: Java API do eksportu EPUB do ODT
description: Konwertuj EPUB na ODT za pomocą lokalnego interfejsu Java API
url_ignore: /pl/java/conversion/epub-to-odt/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: ODT
otherformats: DOT DOTM PS XAMLFLOW MHTML RTF DOTX PCL FLATOPC MARKDOWN WORDML OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Przekształć EPUB w ODT za pomocą Javy" h2="On Premise Java API do renderowania EPUB do ODT bez korzystania z aplikacji innych firm" >}}
{{% blocks/products/pf/feature-page-summary %}}
Możesz przekonwertować EPUB na ODT, wykonując dwa proste kroki. Najpierw musisz wyrenderować plik EPUB do DOC za pomocą [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Następnie, korzystając z potężnego interfejsu API przetwarzania dokumentów [Aspose.Words for Java](https://products.aspose.com/words/java/), możesz przekonwertować DOC na ODT. Oba interfejsy API są objęte pakietem [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API do konwersji EPUB na ODT" %}}
1. Otwórz plik EPUB za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Przekonwertuj EPUB na DOC, używając [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metoda
3. Załaduj plik DOC za pomocą klasy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words
4. Zapisz dokument w formacie ODT za pomocą metody [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) i ustaw ODT jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://releases.aspose.com/total/java/) i dołącz [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) i [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) w pliku pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-odt.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Podczas konwersji EPUB na ODT, nawet jeśli dokument jest chroniony hasłem, nadal możesz go otworzyć za pomocą interfejsu API manipulacji PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Aby otworzyć zaszyfrowany plik, musisz utworzyć obiekt [Dokument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) i otworzyć EPUB przy użyciu hasła właściciela.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-password-proteted-epub-file.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Otwórz dokument EPUB chroniony hasłem przez Java" %}}
Podczas zapisywania dokumentu wejściowego w formacie pliku ODT możesz również zapisać dokument w bazie danych zamiast w systemie plików. Może być konieczne zaimplementowanie przechowywania i pobierania obiektów Document do iz bazy danych. Byłoby to konieczne, gdybyś wdrażał dowolny system zarządzania treścią. W celu zapisania ODT w bazie danych często konieczne jest wykonanie serializacji dokumentu w celu uzyskania tablicy bajtów. Można to zrobić za pomocą interfejsu API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Po uzyskaniu tablicy bajtów możesz przechowywać ją w bazie danych za pomocą instrukcji SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.ODT);
    // get the byte array from output steam
    // the byte array now contains the document
    byte[] buffer = aout.toByteArray();
    // get the filename from the document.
    String fileName = doc.getOriginalFileName();
    String filePath = fileName.replace("\\", "\\\\");
    // create the SQL command.
    String commandString = "INSERT INTO Documents (FileName, FileContent) VALUES('" + filePath + "', '" + buffer + "')";
    Statement statement = mConnection.createStatement();
    statement.executeUpdate(commandString);
}  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/agp/feature-section >}}  
Konwertowanie **EPUB na ODT (OpenDocument Text)** jest niezbędne do generowania **otwartych standardowych dokumentów tekstowych** z e-booków i publikacji cyfrowych. Pliki ODT zapewniają kompatybilność między platformami, edytowalne treści oraz zgodność z otwartymi standardami. Przekształcając EPUB na ODT, edukatorzy, badacze, wydawcy i przedsiębiorstwa mogą zoptymalizować proces pisania akademickiego, dystrybucji treści oraz efektywnie zarządzać pracami archiwalnymi.  

{{% blocks/products/pf/agp/feature-section-col title="Główne Przypadki Użycia" %}}  
- **Pisanie akademickie** – Konwertuj e-booki na edytowalne dokumenty tekstowe do celów badawczych i zadań.  
- **Publikowanie o otwartym kodzie źródłowym** – Udostępniaj publikacje cyfrowe w uniwersalnie obsługiwanych otwartych formatach.  
- **Archiwizacja biblioteczna** – Zachowaj treści tekstowe w standaryzowanym, dostępnym formacie.  
- **Dystrybucja treści edukacyjnych** – Dostarczaj lekcje i materiały kursowe w edytowalnych plikach ODT.  
- **Dokumentacja biznesowa** – Zintegruj treści e-booków w dokumenty zawodowe i operacyjne.  
{{% /blocks/products/pf/agp/feature-section-col %}}  

{{% blocks/products/pf/agp/feature-section-col title="Scenariusze Automatyzacji" %}}  
- **Potoki EPUB-do-ODT** – Zautomatyzuj konwersję e-booków na dokumenty tekstowe ODT.  
- **Automatyczna konwersja dokumentów tekstowych** – Zoptymalizuj procesy publikacyjne dla wielu plików.  
- **Publikowanie metadanych w postaci tekstu** – Wyodrębnij strukturalne dane e-booków do formatu ODT w celach raportowania i badań.  
- **Automatyzacja dokumentów ODT na poziomie przedsiębiorstwa** – Standaryzuj konwersję i dystrybucję tekstów na dużą skalę.  
{{% /blocks/products/pf/agp/feature-section-col %}}  

{{< /blocks/products/pf/agp/feature-section >}}  
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}