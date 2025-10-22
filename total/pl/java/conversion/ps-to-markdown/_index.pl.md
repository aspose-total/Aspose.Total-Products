---
title: Java API do eksportu PS do MARKDOWN
description: Konwertuj PS na MARKDOWN za pomocą lokalnego interfejsu Java API
url_ignore: /pl/java/conversion/ps-to-markdown/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: MARKDOWN
otherformats: MARKDOWN RTF DOT OTT FLATOPC DOTM WORDML MHTML DOTX ODT XAMLFLOW PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Przekształć PS w MARKDOWN za pomocą Javy" h2="On Premise Java API do renderowania PS do MARKDOWN bez korzystania z aplikacji innych firm" >}}
{{% blocks/products/pf/feature-page-summary %}}
Możesz przekonwertować PS na MARKDOWN, wykonując dwa proste kroki. Najpierw musisz wyrenderować plik PS do DOC za pomocą [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Następnie, korzystając z potężnego interfejsu API przetwarzania dokumentów [Aspose.Words for Java](https://products.aspose.com/words/java/), możesz przekonwertować DOC na MARKDOWN. Oba interfejsy API są objęte pakietem [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API do konwersji PS na MARKDOWN" %}}
1. Otwórz plik PS za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Przekonwertuj PS na DOC, używając [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metoda
3. Załaduj plik DOC za pomocą klasy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words
4. Zapisz dokument w formacie MARKDOWN za pomocą metody [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) i ustaw MARKDOWN jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://releases.aspose.com/total/java/) i dołącz [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) i [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) w pliku pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "f5707d58ebee8d2889c8dbe5aa739d87" "convert-ps-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Podczas konwersji PS na MARKDOWN, nawet jeśli dokument jest chroniony hasłem, nadal możesz go otworzyć za pomocą interfejsu API manipulacji PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Aby otworzyć zaszyfrowany plik, musisz utworzyć obiekt [Dokument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) i otworzyć PS przy użyciu hasła właściciela.  
{{% blocks/products/pf/feature-page-code %}}
```cs
// open encrypted document
Document document = new Document("input.ps", "password");
// save PS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Otwórz dokument PS chroniony hasłem przez Java" %}}
Podczas zapisywania dokumentu wejściowego w formacie pliku MARKDOWN możesz również zapisać dokument w bazie danych zamiast w systemie plików. Może być konieczne zaimplementowanie przechowywania i pobierania obiektów Document do iz bazy danych. Byłoby to konieczne, gdybyś wdrażał dowolny system zarządzania treścią. W celu zapisania MARKDOWN w bazie danych często konieczne jest wykonanie serializacji dokumentu w celu uzyskania tablicy bajtów. Można to zrobić za pomocą interfejsu API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Po uzyskaniu tablicy bajtów możesz przechowywać ją w bazie danych za pomocą instrukcji SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.MARKDOWN);
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
```
{{< blocks/products/pf/agp/feature-section >}}

Konwertowanie plików PS (PostScript) na MARKDOWN (.md) umożliwia wykorzystanie treści tekstowej i graficznej PostScript w lekkich, przyjaznych dla sieci formatach. Markdown doskonale nadaje się do dokumentacji, baz wiedzy, blogów i repozytoriów projektów opartych na systemie Git.

{{% blocks/products/pf/agp/feature-section-col title="Główne przypadki użycia" %}}

* Przekształcanie podręczników i raportów PS w dokumenty Markdown gotowe do publikacji w sieci.
* Konwertowanie diagramów i tabel na formaty obsługiwane przez Markdown do celów dokumentacyjnych.
* Publikowanie technicznych treści opartych na PS na GitHubie lub w wewnętrznych wiki.
* Przygotowywanie samouczków, przewodników lub notatek akademickich z plików PS w formacie Markdown.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Scenariusze automatyzacji" %}}

* Automatyczna konwersja PS na Markdown w potokach dokumentacyjnych.
* Integracja z generatorami statycznych stron dla blogów technicznych i portali wiedzy.
* Przetwarzanie wsadowe do konwertowania archiwów PS na repozytoria Markdown.
* Wydobywanie treści wspomagane sztuczną inteligencją z plików PS dla gotowych do użycia w Markdown wyników.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}