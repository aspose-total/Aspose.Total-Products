---
title: Konwersja formatu pliku przez Java 
url: /pl/java/conversion/
description: Konwertuj Microsoft Office Word, Excel, PowerPoint, Outlook, PDF, HTML, obrazy 3D, diagramy, formaty wideo i różne inne formaty za pomocą zaledwie kilku linii kodu Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwersja formatu pliku przez Java" h2="Konwertuj dokumenty Microsoft<sup>&reg;</sup> Office, PDF, obrazy, HTML i wiele innych plików bez użycia innego oprogramowania." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Java Total Library](https://products.aspose.com/total/java/) przyspiesza opracowywanie od podstaw rozwiązań do manipulacji dokumentami lub ulepsza istniejące aplikacje w celu łatwego zarządzania dokumentami. API nie tylko tworzy, edytuje i konwertuje dokumenty Microsoft Office, ale także obsługuje pliki PDF, HTML, obrazy TIFF, JPG, PNG, BMP i SVG, pliki e-mail, formaty wideo, 3D, CAD i wiele innych. Jest to zbiór interfejsów API rozwiązań do zarządzania i manipulacji dokumentami bez żadnych zależności programowych w ramach jakichkolwiek aplikacji Java J2SE, J2EE, J2ME. Programiści mogą łatwo tworzyć, aktualizować, renderować, drukować i konwertować między najpopularniejszymi formatami w dowolnych aplikacjach opartych na Javie.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Konwersja Worda do Excela" %}}
Total API obsługuje nie tylko konwersję między formatami Microsoft Word, ale także konwersję Worda do Excela, PDF, HTML, obrazów, EPUB, Markdown i XPS. Proces konwersji jest prosty. Rozważmy przypadek konwersji **Word do Excel**. Załaduj plik Microsoft Word za pomocą klasy [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) i przekonwertuj **WORD na HTML** za pomocą [metody Save](https: //apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)). Następnie otwórz przekonwertowany dokument HTML za pomocą klasy [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) i zapisz dokument w formacie XLSX za pomocą [Save](https:/ /apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).
 Programiści mogą również konwertować [Word na PDF](https://products.aspose.com/words/java/conversion/word-to-pdf/).


{{% blocks/products/pf/feature-page-code h3="Java Konwersja Worda do Excela" %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-json word-to-powerpoint" >}}


{{% blocks/products/pf/feature-page-section  h2="Konwertuj PDF na obrazy" %}}
API obsługuje konwersję plików PDF na obrazy takie jak JPEG2000, EMZ, WMZ, TGA, PSD, DXF, WMF, SVGZ, APNG, DICOM, Powerpoint, Excel i inne formaty. W przypadku konwersji PDF na obraz rozważmy obraz JPG jako plik docelowy. Proces polega na załadowaniu pliku PDF przy użyciu klasy Document i zainicjowaniu obiektu [klasy JpegDevice](https://apireference.aspose.com/pdf/java/aspose.pdf.devices/jpegdevice) i wyrenderowaniu pliku PDF do JPEG przez [Process](https ://apireference.aspose.com/pdf/java/aspose.pdf.devices.pagedevice/process/methods/1)
Załaduj plik JPEG przy użyciu klasy [Image](https://apireference.aspose.com/imaging/java/aspose.imaging/image) i na koniec wywołaj metodę Save.

{{% blocks/products/pf/feature-page-code h3="Java PDF to Image Conversion" %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-csv pdf-to-txt pdf-to-markdown" >}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj PowerPoint do plików Excel" %}}

Do konwersji plików Microsoft PowerPoint na różne pliki, w tym Excel Word, MHTML, odpowiednie podrzędne interfejsy API związane z głównym interfejsem Aspose.Total dla Java API. Proces konwersji plików PowerPoint do dokumentu Excel, Załaduj plik PowerPoint za pomocą klasy [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) i skonwertuj **PowerPoint do HTML** przez za pomocą metody [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-). Następnie załaduj przekonwertowany dokument HTML za pomocą klasy [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) i zapisz dokument w formacie EXCEL za pomocą [save](https:/ /apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)). Na liście znajduje się również kod konwersji **PowerPoint do Word**.

{{% blocks/products/pf/feature-page-code h3="Konwersja Java PowerPoint do Excela" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Konwersja Java PowerPoint do Word" %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="powerpoint-to-doc powerpoint-to-docx powerpoint-to-xlsx" >}}