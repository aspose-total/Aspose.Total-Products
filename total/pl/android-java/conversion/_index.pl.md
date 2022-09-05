---
title: Konwersja dokumentów przez Android API 
url: /pl/android-java/conversion/
description: Konwertuj formaty Word, Excel, PowerPoint, HTML, PDF i Image za pomocą interfejsu API konwersji systemu Android. Android konwertuje Office docx, xlsx, pptx na PDF. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwersja dokumentów za pomocą Android API" h2="Konwertuj Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, obrazy i różne inne formaty za pomocą Aspose.Total na Androida za pomocą Javy." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Android API](https://products.aspose.com/total/android-java/) zapewnia rozwiązanie do konwersji i zarządzania dokumentami dla aplikacji na Androida bez polegania na żadnym innym oprogramowaniu. Programiści mogą łatwo zautomatyzować rozwiązanie do zarządzania i manipulacji dokumentami, integrując API z nowo opracowanymi aplikacjami lub z istniejącymi aplikacjami. Integrując API, Programmer może łatwo dodawać funkcje do tworzenia, edytowania lub konwertowania dokumentów o różnych formatach w aplikacji. PDF Converter API w Androidzie obsługuje przypadki konwersji, takie jak Office DOCX, XLSX, PPTX do PDF i odwrotnie. Co więcej, kilka przypadków, w których API zajmuje się wymienionymi poniżej, i kilka linków podanych dla odpowiednich przypadków konwersji. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj PDF na CSV" %}}
Total Android API obsługuje konwersję plików PDF do Excel XLSX i CSV. To proces dwuetapowy. Dwa Total APIs [Aspose.PDF na Androida przez Javę](https://products.aspose.com/pdf/android-java/) i Aspose.Cells na Androida przez Javę](https://products.aspose.com/zaangażowane komórki/android-java/). Proces polega na tym, że możesz najpierw przekryć PDF do formatu Excel XLSX, a następnie XLSX do CSV. Bardziej szczegółowo, Załaduj plik PDF przez klasę [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) i wyrenderuj do XLSX przez [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-). Następnie załaduj wyrenderowany dokument XLSX za pomocą klasy [Skoroszyt](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) i wywołaj [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).

{{% blocks/products/pf/feature-page-code h3="Android — konwersja plików PDF na Excel" %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint potm-to-rtf powerpoint-to-docx ppt-to-docx pptx-to-odt potm-to-docx email-to-docx email-to-word eml-to-pdf emlx-to-bmp emlx-to-image msg-to-pdf oft-to-word" >}}


{{% blocks/products/pf/feature-page-section  h2="Konwersja Excela do Worda" %}}
Android API obsługuje również konwersję Excela. Proces polega na załadowaniu pliku EXCEL XLSX przy użyciu klasy [Skoroszyt](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) i przekonwertowaniu programu EXCEL na PDF, najpierw ustawiając SaveFormat na AUTO. Następnie załaduj zapisany plik PDF za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) i wywołaj [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metoda zapisu dokumentu w formacie Word DOC/DOCX.

{{% blocks/products/pf/feature-page-code h3="Android - Konwersja Excela do Worda" %}}

{{< gist "aspose-com-gists" "10fdb88fb4d39618cdc2dfd0d0bd86c1" "excel-to-word-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mhtml-to-docm pdf-to-rtf svg-to-docm xps-to-dotx pdf-to-powerpoint tex-to-ppsx xps-to-potx csv-to-doc excel-to-word xls-to-word xlsx-to-powerpoint xltx-to-word word-to-excel" >}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj POWERPOINT na HTML i MHTML" %}}
Android Total API obsługuje różne formaty, w tym pliki PowerPoint, dzięki czemu można konwertować prezentacje do HTML i MHTML. Proces polega na załadowaniu pliku POWERPOINT PPT/PPTX przy użyciu klasy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) i wywołaniu [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) do konwersji POWERPOINT na HTML. Co więcej, teraz załaduj przekonwertowany dokument HTML za pomocą klasy [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) i wywołaj [save](https://reference.aspose.com/cells/java/com.aspose.cells/) do konwersji MHTML. 
{{% blocks/products/pf/feature-page-code h3="Android — konwersja prezentacji PowerPoint do formatu HTML i MHTML" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="rtf-to-excel docx-to-csv json-to-word json-to-powerpoint word-to-json powerpoint-to-json potm-to-excel pptx-to-excel ppsx-to-mhtml" >}}