---
title: Konwersja MHTML do RTF online lub opracowanie aplikacji opartej na Javie do konwersji plików MHTML
description: Darmowa aplikacja online do konwersji plików MHTML na RTF. Kod biblioteki konwersji Java dla dokumentów MHTML. 

family: total
platformtag: Java
feature: conversion
informat: MHTML
outformat: RTF
otherformats: WORDML ODT XAMLFLOW DOTX OTT PS DOTM MARKDOWN FLATOPC DOT RTF PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aplikacja do konwersji plików MHTML do RTF online i kod Java do konwersji plików MHTML" h2="Opracuj wydajną aplikację do konwersji i eksportu MHTML opartą na Javie. Konwertuj pojedyncze lub wiele plików MHTML do formatu RTF i innych formatów za pomocą interfejsu API automatyzacji Java. Bezpłatna konwersja plików MHTML online za pomocą aplikacji z natychmiastowym pobraniem." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="Darmowa aplikacja do konwersji MHTML na RTF online" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=rtf&from=mhtml" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj pliki MHTML do RTF online za pomocą aplikacji" %}}

1. Prześlij pliki MHTML do konwersji
1. Poczekaj kilka sekund lub dłużej, w zależności od rozmiaru MHTML
1. Zwróć uwagę na pasek stanu przesyłania
1. Kliknij przycisk „Konwertuj”
1. MHTML zostanie przekonwertowany na dokument RTF
1. Pobierz przekonwertowany plik RTF

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konwertuj MHTML na RTF za pomocą Java Automation API" %}}


1. Otwórz plik MHTML za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Przekonwertuj MHTML na DOC, używając [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metoda
3. Załaduj plik DOC za pomocą klasy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) Aspose.Words
4. Zapisz dokument w formacie RTF za pomocą metody [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) i ustaw RTF jako SaveFormat



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "89f68c1b3e3c772c46b1f2adbaf240e5" "convert-mhtml-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

Jeszcze kilka przypadków zapisania MHTML w RTF przy użyciu innych funkcji, takich jak Wymagania dotyczące konwersji, Otwórz dokument MHTML chroniony hasłem przez Java.

{{% blocks/products/pf/feature-page-code %}}


```cs
// open encrypted document
Document document = new Document("input.mhtml", "password");
// save MHTML as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.RTF);
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


{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>Opracuj aplikację konwersji plików MHTML przy użyciu języka Java</h2>

Musisz stworzyć aplikację opartą na Javie, która umożliwi łatwe zapisywanie i eksportowanie plików MHTML do dokumentu RTF? Dzięki [Aspose.Total for Java](https://products.aspose.com/total/pl/java/) każdy programista Java może zintegrować powyższy kod API, aby zaprogramować aplikację konwersji w różnych formatach, w tym Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, plikach e-mail, obrazach (JPG, PNG, BMP, GIF) i innych formatach. Potężna biblioteka Java do konwersji dokumentów, obsługuje wiele popularnych formatów, w tym format MHTML. Eksportując i renderując dokumenty do innych formatów, programiści mogą korzystać z podrzędnych interfejsów API Aspose.Total for Java, w tym [Aspose.Words for Java](https://products.aspose.com/words/pl/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/pl/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/pl/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/pl/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/pl/java/) i innych.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MHTML Biblioteka konwersji dla Java" %}}

Istnieją alternatywne opcje integracji Aspose.Total for Java z Twoim systemem. Wybierz ten, który odpowiada Twoim potrzebom i postępuj zgodnie z instrukcją krok po kroku:<br /><br />

- Użyj Aspose.Total for Java bezpośrednio z projektu opartego na Maven i uwzględnij odpowiedni podrzędny interfejs API w pom.xml.
- Można też pobrać plik ZIP z [pobieranie](https://releases.aspose.com/total/java).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Zapisywanie MHTML do wymagań aplikacji RTF" %}}

Aspose.Total for Java może zostać uruchomiony na dowolnym systemie operacyjnym, który obsługuje środowisko Java Runtime Environment (JRE). Poniżej wymieniono większość, ale nie wszystkie, wspierane systemy operacyjne. <br /><br />
- Microsoft Windows
- Linux: Ubuntu, OpenSUSE, CentOS i inne
- macOS: 10.9 (Mavericks) i nowsze
- Mobilny: Android, iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}