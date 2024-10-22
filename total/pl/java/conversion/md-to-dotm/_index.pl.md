---
title: Java API do eksportu MD do DOTM
description: Konwertuj MD na DOTM za pomocą lokalnego interfejsu Java API
url_ignore: /pl/java/conversion/md-to-dotm/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: DOTM
otherformats: PS DOTM FLATOPC MHTML PCL MARKDOWN RTF DOT OTT ODT WORDML DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Przekształć MD w DOTM za pomocą Javy" h2="On Premise Java API do renderowania MD do DOTM bez korzystania z aplikacji innych firm" >}}
{{% blocks/products/pf/feature-page-summary %}}
Możesz przekonwertować MD na DOTM, wykonując dwa proste kroki. Najpierw musisz wyrenderować plik MD do DOC za pomocą [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Następnie, korzystając z potężnego interfejsu API przetwarzania dokumentów [Aspose.Words for Java](https://products.aspose.com/words/java/), możesz przekonwertować DOC na DOTM. Oba interfejsy API są objęte pakietem [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API do konwersji MD na DOTM" %}}
1. Otwórz plik MD za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Przekonwertuj MD na DOC, używając [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metoda
3. Załaduj plik DOC za pomocą klasy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words
4. Zapisz dokument w formacie DOTM za pomocą metody [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) i ustaw DOTM jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://releases.aspose.com/total/java/) i dołącz [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) i [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) w pliku pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Podczas konwersji MD na DOTM, nawet jeśli dokument jest chroniony hasłem, nadal możesz go otworzyć za pomocą interfejsu API manipulacji PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Aby otworzyć zaszyfrowany plik, musisz utworzyć obiekt [Dokument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) i otworzyć MD przy użyciu hasła właściciela.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.md", "password");
// save MD as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Otwórz dokument MD chroniony hasłem przez Java" %}}
Podczas zapisywania dokumentu wejściowego w formacie pliku DOTM możesz również zapisać dokument w bazie danych zamiast w systemie plików. Może być konieczne zaimplementowanie przechowywania i pobierania obiektów Document do iz bazy danych. Byłoby to konieczne, gdybyś wdrażał dowolny system zarządzania treścią. W celu zapisania DOTM w bazie danych często konieczne jest wykonanie serializacji dokumentu w celu uzyskania tablicy bajtów. Można to zrobić za pomocą interfejsu API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Po uzyskaniu tablicy bajtów możesz przechowywać ją w bazie danych za pomocą instrukcji SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.DOTM);
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
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}