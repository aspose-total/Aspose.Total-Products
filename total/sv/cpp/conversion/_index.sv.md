---
title: Dokumentkonvertering via C++ 
url: /sv/cpp/conversion/
description: Konvertera olika dokumentformat som Word, Excel, PowerPoint, PDF, JSON, bilder och mer med C++ API. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Dokumentkonvertering med C++" h2="Konvertera Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, bilder och olika andra format med C++-biblioteket." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total C++ Library](https://products.aspose.com/total/cpp/) löser problemet med dokumentkonvertering och utvecklare kan enkelt automatisera dokumenthanterings- och manipuleringslösningen genom att integrera API i nyutvecklade applikationer eller i befintliga applikationer. C++-programmerare kan lägga till funktioner som att skapa, redigera eller konvertera dokument i olika format i sin lösning utan att förlita sig på någon programvara. Få generiska fall som txt till PDF, SVG till PNG, XLSX till CSV, JSON till CSV, Word till PDF, HTML till PDF, man kan enkelt konvertera. Dessutom, några få fall som API handlar listade nedan och få länkar för relevanta konverteringsfall. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera Microsoft Word till Excel" %}}
Total C++ API stöder konvertering från Microsoft Word DOC/DOCX till Excel.  Processen är att ladda Word DOC / DOCX-fil med [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) klassreferens och anropa [Spara](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) medlemsfunktion för att konvertera till HTML först. Ladda sedan HTML-dokument genom att använda klassreferensen [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) och anropa [Spara](https://reference.aspose.com/ cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) medlemsfunktion för att spara dokumentet i Excel-format. 

{{% blocks/products/pf/feature-page-code h3="C++ - Konvertering av Word till Excel" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertering av PDF till Word" %}}
C++ konverteringsbibliotek stöder även PDF till word DOC, DOCX och andra formatkonverteringar. Med tanke på fallet med att rendera PDF till RTF, är det en tvåstegsprocess, först konvertera PDF till Word DOC/DOCX-format och sedan rendera det till RTF. Inkluderade steg för detta, laddar PDF-fil med [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) klassreferens och anropar [Spara](https://reference.aspose. .com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) medlemsfunktion för att konvertera PDF till Word. Ladda nu Word DOC / DOCX-filen igen genom att använda [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) klassreferens för Aspose.Words API och spara den i RTF-format med hjälp av [Spara](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) medlemsfunktion.

{{% blocks/products/pf/feature-page-code h3="C++ - Konvertering av PDF till Word" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera JSON till Word" %}}
För JSON-konvertering stöder C++ API olika kombinationer som JSON till Word, Json till PowerPoint, Word till JSON etc. Med tanke på fallet med Word-konvertering, Process is, läs giltig JSON-data från filen genom att använda ett nytt [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) objekt och anropa sedan [Spara](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) metod för att spara JSON som PDF-fil. Så ladda nu sparad fil med klassen [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) och spara den i Word-dokumentformat med [Spara](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat).
{{% blocks/products/pf/feature-page-code h3="C++ - JSON till Word-konvertering" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}