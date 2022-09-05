---
title: Documentconversie via C++ 
url: /nl/cpp/conversion/
description: Converteer verschillende documentformaten zoals Word, Excel, PowerPoint, PDF, JSON, afbeeldingen en meer met behulp van C++ API. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Documentconversie met C++" h2="Converteer Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, afbeeldingen en verschillende andere formaten met behulp van de C++-bibliotheek." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total C++ Library](https://products.aspose.com/total/cpp/) lost het probleem van documentconversie op en ontwikkelaars kunnen de oplossing voor documentbeheer en -manipulatie eenvoudig automatiseren door API te integreren in nieuw ontwikkelde applicaties of in bestaande applicaties. C++-programmeurs kunnen functionaliteiten toevoegen, zoals het maken, bewerken of converteren van documenten in verschillende formaten binnen hun oplossing zonder afhankelijk te zijn van software. Weinig generieke gevallen zoals txt naar PDF, SVG naar PNG, XLSX naar CSV, JSON naar CSV, Word naar PDF, HTML naar PDF, kan men gemakkelijk converteren. Bovendien zijn er weinig gevallen die API hieronder vermeldt en weinig links gegeven voor de relevante conversiegevallen. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Converteer Microsoft Word naar Excel" %}}
Total C++ API ondersteunt Microsoft Word DOC/DOCX naar Excel conversie.  Proces is, Laad Word DOC / DOCX-bestand met behulp van [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) klassereferentie en roep [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) lidfunctie om eerst naar HTML te converteren. Laad vervolgens het HTML-document met behulp van [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) class reference en roep [Save](https://reference.aspose.com/ op) cellen/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) lidfunctie om het document in Excel-indeling op te slaan. 

{{% blocks/products/pf/feature-page-code h3="C++ - Word naar Excel conversie" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="PDF naar Word-conversie" %}}
De C++-conversiebibliotheek ondersteunt ook de conversie van PDF naar DOC, DOCX en andere formaten. Gezien het geval van het renderen van PDF naar RTF, is het een proces in twee stappen: converteer eerst PDF naar Word DOC/DOCX-formaat en render dat vervolgens naar RTF. Inbegrepen stappen hiervoor, het laden van een PDF-bestand met behulp van [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) klasseverwijzing en het aanroepen van [Opslaan](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) lidfunctie om PDF naar Word te converteren. Laad nu opnieuw Word DOC / DOCX-bestand met behulp van [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) klasseverwijzing van Aspose.Words API en sla het op in RTF-indeling met [Opslaan](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) lidfunctie.

{{% blocks/products/pf/feature-page-code h3="C++ - PDF naar Word-conversie" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="Converteer JSON naar Word" %}}
Voor JSON-conversie ondersteunt C++ API verschillende combinaties zoals JSON naar Word, Json naar PowerPoint, Word naar JSON enz. Gezien het geval van Word-conversie, is Proces: lees geldige JSON-gegevens uit het bestand met behulp van een nieuw [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) object en roep vervolgens [Opslaan](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) methode om JSON op te slaan als PDF-bestand. Dus laad nu het opgeslagen bestand met behulp van [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class en sla het op in Word-documentformaat met [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) methode.
{{% blocks/products/pf/feature-page-code h3="C++ - JSON naar Word-conversie" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}