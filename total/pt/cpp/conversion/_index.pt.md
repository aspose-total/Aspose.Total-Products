---
title: Conversão de documentos via C++ 
url: /pt/cpp/conversion/
description: Converta vários formatos de documentos, como Word, Excel, PowerPoint, PDF, JSON, Imagens e muito mais usando a API C++. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Conversão de documentos usando C++" h2="Converta Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, Imagens e vários outros formatos usando a biblioteca C++." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total C++ Library](https://products.aspose.com/total/cpp/) resolve o problema de conversão de documentos e os desenvolvedores podem automatizar a solução de gerenciamento e manipulação de documentos facilmente integrando a API em novos aplicativos desenvolvidos ou em aplicativos existentes. Os programadores de C++ podem adicionar funcionalidades como criar, editar ou converter vários documentos de formato dentro de sua solução sem depender de nenhum software. Alguns casos genéricos como txt para PDF, SVG para PNG, XLSX para CSV, JSON para CSV, Word para PDF, HTML para PDF, podem ser facilmente convertidos. Além disso, poucos casos que a API trata listados abaixo e alguns links fornecidos para os casos de conversão relevantes. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Converter Microsoft Word para Excel" %}}
Total C++ API suporta conversão Microsoft Word DOC/DOCX para Excel.  O processo é carregar o arquivo Word DOC / DOCX usando a referência de classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) e invocar [Save](https://reference. aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) para converter em HTML primeiro. Em seguida, carregue o documento HTML usando a referência de classe [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) e invoque [Save](https://reference.aspose.com/ cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) para salvar o documento no formato Excel. 

{{% blocks/products/pf/feature-page-code h3="C++ - Conversão de Word para Excel" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc  doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="Conversão de PDF para Word" %}}
A biblioteca de conversão C++ também suporta PDF para Word DOC, DOCX e outros formatos de conversão. Considerando o caso de renderização de PDF para RTF, é um processo de duas etapas, primeiro converter PDF para formato Word DOC/DOCX e depois renderizá-lo para RTF. Etapas incluídas para isso, carregar o arquivo PDF usando a referência de classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) e invocar [Save](https://reference.aspose .com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) para converter PDF em Word. Agora carregue novamente o arquivo Word DOC / DOCX usando [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) referência de classe da API Aspose.Words e salve-o no formato RTF usando [Salvar](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) função de membro.

{{% blocks/products/pf/feature-page-code h3="C++ - Conversão de PDF para Word" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="Converter JSON para Word" %}}
Para conversão JSON, a API C++ suporta várias combinações, como JSON para Word, Json para PowerPoint, Word para JSON etc. Considerando o caso da conversão do Word, Process é ler dados JSON válidos do arquivo usando um novo objeto [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) e, em seguida, invocar [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) para salvar JSON como arquivo PDF. Então agora carregue o arquivo salvo usando a classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) e salve-o no formato de documento do Word usando [Save](https://reference .aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat).
{{% blocks/products/pf/feature-page-code h3="C++ - Conversão de JSON para Word" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}