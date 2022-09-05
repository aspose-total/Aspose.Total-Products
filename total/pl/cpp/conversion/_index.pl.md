---
title: Konwersja dokumentów za pomocą C++ 
url: /pl/cpp/conversion/
description: Konwertuj różne formaty dokumentów, takie jak Word, Excel, PowerPoint, PDF, JSON, obrazy i inne, korzystając z interfejsu API C++. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwersja dokumentów przy użyciu C++" h2="Konwertuj Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, obrazy i różne inne formaty przy użyciu biblioteki C++." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total C++ Library](https://products.aspose.com/total/cpp/) rozwiązuje problem konwersji dokumentów, a programiści mogą łatwo zautomatyzować rozwiązanie do zarządzania i manipulacji dokumentami, integrując interfejs API z nowo opracowanymi lub istniejącymi aplikacjami. Programiści C++ mogą dodawać funkcje, takie jak tworzenie, edytowanie lub konwertowanie dokumentów w różnych formatach w ramach swojego rozwiązania bez polegania na jakimkolwiek oprogramowaniu. Niewiele ogólnych przypadków, takich jak txt do PDF, SVG do PNG, XLSX do CSV, JSON do CSV, Word do PDF, HTML do PDF, można łatwo przekonwertować. Co więcej, kilka przypadków, w których API zajmuje się wymienionymi poniżej, i kilka linków podanych dla odpowiednich przypadków konwersji. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj Microsoft Word na Excel" %}}
Total C++ API obsługuje konwersję Microsoft Word DOC/DOCX do Excela.  Proces polega na załadowaniu pliku Word DOC / DOCX przy użyciu odwołania do klasy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) i wywołaniu [Save](https://reference. aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) elementu członkowskiego, aby najpierw przekonwertować na kod HTML. Następnie załaduj dokument HTML, używając odwołania do klasy [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) i wywołaj [Save](https://reference.aspose.com/ cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) funkcja elementu członkowskiego, aby zapisać dokument w formacie programu Excel. 

{{% blocks/products/pf/feature-page-code h3="C++ - Konwersja Worda do Excela" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc  doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="Konwersja PDF do Word" %}}
Biblioteka konwersji C++ obsługuje również konwersję plików PDF do Word DOC, DOCX i innych formatów. Biorąc pod uwagę przypadek renderowania PDF do RTF, jest to proces dwuetapowy, najpierw przekonwertuj plik PDF na format Word DOC/DOCX, a następnie wyrenderuj go do RTF. Kroki zawarte w tym celu: Ładowanie pliku PDF przy użyciu odwołania do klasy [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) i wywołanie [Save](https://reference.aspose .com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) funkcja elementu członkowskiego do konwersji pliku PDF na program Word. Teraz załaduj ponownie plik Word DOC / DOCX, używając referencji klasy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) Aspose.Words API i zapisz go w formacie RTF, używając Funkcja członkowska [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat).

{{% blocks/products/pf/feature-page-code h3="C++ - Konwersja PDF do Word" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj JSON na Word" %}}
W przypadku konwersji JSON C++ API obsługuje różne kombinacje, takie jak JSON na Word, Json na PowerPoint, Word na JSON itp. Biorąc pod uwagę przypadek konwersji Worda, proces polega na odczytaniu prawidłowych danych JSON z pliku przy użyciu nowego obiektu [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook), a następnie wywołaniu [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) metoda zapisu JSON jako plik PDF. Więc teraz załaduj zapisany plik za pomocą klasy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) i zapisz go w formacie dokumentu Word za pomocą [Save](https://reference .aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat).
{{% blocks/products/pf/feature-page-code h3="C++ - Konwersja JSON na Word" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}