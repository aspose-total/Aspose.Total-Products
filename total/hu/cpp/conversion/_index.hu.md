---
title: Dokumentum konvertálás C++-on keresztül 
url: /hu/cpp/conversion/
description: Különféle dokumentumformátumok konvertálása, például Word, Excel, PowerPoint, PDF, JSON, Képek és egyebek a C++ API segítségével. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Dokumentum konvertálás C++ használatával" h2="Konvertálja a Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, Képek és számos egyéb formátumot a C++ könyvtár használatával." >}}

{{% blocks/products/pf/feature-page-summary %}}
A [Total C++ Library](https://products.aspose.com/total/cpp/) megoldja a dokumentumkonverzió problémáját, és a fejlesztők könnyedén automatizálhatják a dokumentumkezelési és -manipulációs megoldást az API új fejlesztésű alkalmazásokba vagy meglévő alkalmazásokba történő integrálásával. A C++ programozók olyan funkciókat adhatnak hozzá, mint például különféle formátumú dokumentumok létrehozása, szerkesztése vagy konvertálása megoldásukon belül, anélkül, hogy bármilyen szoftverre támaszkodnának. Néhány általános eset, például txt PDF-be, SVG-ből PNG-be, XLSX-ből CSV-be, JSON-ból CSV-be, Wordből PDF-be, HTML-ből PDF-be, könnyen konvertálható. Ezenkívül az alábbiakban felsorolt néhány API-val foglalkozó eset, és néhány hivatkozás található a releváns konverziós esetekhez. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="A Microsoft Word konvertálása Excelbe" %}}
A Total C++ API támogatja a Microsoft Word DOC/DOCX konvertálását Excelbe.  A folyamat a Word DOC/DOCX fájljának betöltése a [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) osztályhivatkozás használatával, majd a [Mentés](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) tagfüggvényt először HTML-be konvertálni. Ezután töltse be a HTML-dokumentumot az [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) osztályhivatkozás használatával, és hívja meg a [Save](https://reference.aspose.com/) parancsot. cell/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) tagfüggvény a dokumentum Excel formátumba mentéséhez. 

{{% blocks/products/pf/feature-page-code h3="C++ – Word-Excel konvertálás" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="PDF konvertálása Wordbe" %}}
A C++ konverziós könyvtár támogatja a PDF-ből Word DOC-ba, DOCX-be és más formátumok konvertálását is. Tekintettel a PDF RTF formátumba való renderelésére, ez egy kétlépéses folyamat, először konvertálja a PDF-et Word DOC/DOCX formátumba, majd rendereli azt RTF formátumba. Ennek lépései: PDF-fájl betöltése [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) osztályhivatkozás használatával és a [Mentés](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) tagfüggvény a PDF-ek Word-be konvertálásához. Most töltse be újra a Word DOC / DOCX fájlt az Aspose.Words API [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) osztályhivatkozásával, és mentse el RTF formátumba a használatával [Mentés](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) tagfüggvény.

{{% blocks/products/pf/feature-page-code h3="C++ - PDF konvertálása Wordbe" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a JSON-t Word-be" %}}
A JSON-konverzióhoz a C++ API különféle kombinációkat támogat, például a JSON-ból Word-be, a JSON-ból PowerPointba, a Wordből a JSON-ba stb. A Word-konverzió esetét figyelembe véve a Process az érvényes JSON-adatok beolvasását a fájlból egy új [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) objektum használatával, majd meghívja [Mentés](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) módszer a JSON PDF-fájlként való mentéséhez. Tehát most töltse be a mentett fájlt a [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) osztály használatával, és mentse el Word dokumentumformátumba a [Mentés](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) metódus.
{{% blocks/products/pf/feature-page-code h3="C++ – JSON konvertálása Wordbe" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}