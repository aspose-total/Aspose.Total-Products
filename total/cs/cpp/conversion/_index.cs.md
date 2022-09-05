---
title: Konverze dokumentů přes C++ 
url: /cs/cpp/conversion/
description: Převádějte různé formáty dokumentů, jako je Word, Excel, PowerPoint, PDF, JSON, obrázky a další, pomocí C++ API. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konverze dokumentů pomocí C++" h2="Převeďte Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, obrázky a různé další formáty pomocí knihovny C++." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total C++ Library](https://products.aspose.com/total/cpp/) řeší problém konverze dokumentů a vývojáři mohou snadno automatizovat řešení pro správu a manipulaci s dokumenty integrací API do nově vyvinutých aplikací nebo do stávajících aplikací. Programátoři C++ mohou v rámci svého řešení přidávat funkce, jako je vytváření, úprava nebo převod dokumentů různých formátů, aniž by se spoléhali na jakýkoli software. Několik obecných případů, jako je txt do PDF, SVG do PNG, XLSX do CSV, JSON do CSV, Word do PDF, HTML do PDF, lze snadno převést. Kromě toho je níže uvedeno několik případů, které API řeší, a několik odkazů uvedených pro relevantní případy konverze. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Převést Microsoft Word do Excelu" %}}
Total C++ API podporuje převod Microsoft Word DOC/DOCX na Excel.  Postup je, načtěte soubor Word DOC / DOCX pomocí odkazu na třídu [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) a vyvolejte [Uložit](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) členskou funkci, kterou nejprve převedete do HTML. Poté načtěte dokument HTML pomocí odkazu na třídu [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) a vyvolejte [Uložit](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) členská funkce pro uložení dokumentu do formátu Excel. 

{{% blocks/products/pf/feature-page-code h3="C++ - převod Word do Excelu" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="Převod PDF do Wordu" %}}
Knihovna pro převod C++ také podporuje převod PDF do wordu DOC, DOCX a dalších formátů. Pokud vezmeme v úvahu případ vykreslování PDF do RTF, jedná se o dvoukrokový proces, nejprve převést PDF do formátu Word DOC/DOCX a poté jej vykreslit do RTF. Zahrnuty kroky, načtení souboru PDF pomocí odkazu na třídu [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) a vyvolání [Uložit](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) členská funkce pro převod PDF do Wordu. Nyní znovu načtěte soubor Word DOC / DOCX pomocí odkazu třídy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) API Aspose.Words a uložte jej do formátu RTF pomocí členské funkce [Uložit](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat).

{{% blocks/products/pf/feature-page-code h3="C++ - Převod PDF do Wordu" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="Převést JSON do Wordu" %}}
Pro převod JSON podporuje C++ API různé kombinace, jako je JSON do Wordu, Json do PowerPointu, Word do JSON atd. Pokud vezmeme v úvahu případ převodu Word, Process je, číst platná data JSON ze souboru pomocí nového objektu [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) a poté vyvolat Metoda [Uložit](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) k uložení JSON jako souboru PDF. Nyní tedy načtěte uložený soubor pomocí třídy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) a uložte jej do formátu dokumentu aplikace Word pomocí [Uložit](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat).
{{% blocks/products/pf/feature-page-code h3="C++ - převod JSON do Wordu" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}