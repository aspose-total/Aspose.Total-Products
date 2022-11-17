---
title: Dokumentenkonvertierung über C++ 

description: Konvertieren Sie mithilfe der C++-API verschiedene Dokumentformate wie Word, Excel, PowerPoint, PDF, JSON, Bilder und mehr. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Dokumentenkonvertierung mit C++" h2="Konvertieren Sie Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, Bilder und verschiedene andere Formate mithilfe der C++-Bibliothek." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total C++ Library](https://products.aspose.com/total/cpp/) löst das Problem der Dokumentenkonvertierung und Entwickler können die Dokumentenverwaltungs- und -bearbeitungslösung einfach automatisieren, indem sie die API in neu entwickelte Anwendungen oder in bestehende Anwendungen integrieren. C++-Programmierer können Funktionen wie das Erstellen, Bearbeiten oder Konvertieren von Dokumenten in verschiedenen Formaten innerhalb ihrer Lösung hinzufügen, ohne sich auf eine Software verlassen zu müssen. Einige generische Fälle wie txt zu PDF, SVG zu PNG, XLSX zu CSV, JSON zu CSV, Word zu PDF, HTML zu PDF können einfach konvertiert werden. Darüber hinaus sind unten einige Fälle aufgeführt, die von der API behandelt werden, sowie einige Links für die relevanten Konvertierungsfälle. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie Microsoft Word in Excel" %}}
Die Total C++ API unterstützt die Konvertierung von Microsoft Word DOC/DOCX in Excel.  Prozess ist, Word DOC/DOCX-Datei mit [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) Klassenreferenz zu laden und [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) Member-Funktion, um sie zuerst in HTML zu konvertieren. Laden Sie dann das HTML-Dokument mithilfe der Klassenreferenz [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) und rufen Sie [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) Member-Funktion, um das Dokument im Excel-Format zu speichern. 

{{% blocks/products/pf/feature-page-code h3="C++ - Word-zu-Excel-Konvertierung" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="PDF-zu-Word-Konvertierung" %}}
Die C++-Konvertierungsbibliothek unterstützt auch die Konvertierung von PDF in Word DOC, DOCX und andere Formate. Betrachtet man den Fall des Renderns von PDF in RTF, so handelt es sich um einen zweistufigen Prozess. Konvertieren Sie zuerst PDF in das Word DOC/DOCX-Format und rendern Sie es dann in RTF. Dazu gehörende Schritte, Laden der PDF-Datei mit der Klassenreferenz [Dokument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) und Aufrufen von [Speichern](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) Member-Funktion zum Konvertieren von PDF in Word. Laden Sie nun die Word-DOC-/DOCX-Datei erneut, indem Sie die [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) Klassenreferenz der Aspose.Words-API verwenden, und speichern Sie sie mit im RTF-Format Member-Funktion [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat).

{{% blocks/products/pf/feature-page-code h3="C++ - PDF-zu-Word-Konvertierung" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie JSON in Word" %}}
Für die JSON-Konvertierung unterstützt die C++-API verschiedene Kombinationen wie JSON zu Word, Json zu PowerPoint, Word zu JSON usw. Betrachtet man den Fall der Word-Konvertierung, so liest Process gültige JSON-Daten aus der Datei, indem ein neues [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)-Objekt verwendet und dann aufgerufen wird [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) Methode zum Speichern von JSON als PDF-Datei. Laden Sie nun die gespeicherte Datei mit der Klasse [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) und speichern Sie sie mit [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)-Methode.
{{% blocks/products/pf/feature-page-code h3="C++ - Konvertierung von JSON in Word" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}