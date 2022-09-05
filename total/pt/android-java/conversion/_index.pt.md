---
title: Conversão de documentos via API Android 
url: /pt/android-java/conversion/
description: Converta os formatos Word, Excel, PowerPoint, HTML, PDF e Imagem usando a API de conversão do Android. Android converte Office docx, xlsx, pptx para PDF. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Conversão de documentos usando a API do Android" h2="Converta Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, Imagens e vários outros formatos usando Aspose.Total para Android via Java." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Android API](https://products.aspose.com/total/android-java/) fornece a solução de conversão e gerenciamento de documentos para aplicativos Android sem depender de nenhum outro software. Os programadores podem automatizar a solução de gerenciamento e manipulação de documentos facilmente integrando a API em novos aplicativos desenvolvidos ou em aplicativos existentes. Ao integrar a API, o Programmer pode adicionar facilmente funcionalidades para criar, editar ou converter vários documentos de formato dentro do aplicativo. A API PDF Converter no Android lida com casos de conversão como Office DOCX, XLSX, PPTX para PDF ou vice-versa. Além disso, poucos casos que a API trata listados abaixo e alguns links fornecidos para os casos de conversão relevantes. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Converter PDF para CSV" %}}
Total Android API suporta conversão de PDF para Excel XLSX e CSV. É um processo de duas etapas. Duas APIs totais [Aspose.PDF para Android via Java](https://products.aspose.com/pdf/android-java/) e Aspose.Cells para Android via Java](https://products.aspose.com/ células/android-java/) envolvidas. O processo é que você pode converter PDF para Excel no formato XLSX primeiro e depois XLSX para CSV. Em mais detalhes, carregue o arquivo PDF por meio da classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) e renderize para XLSX por meio de [save](https://reference. aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-). Em seguida, carregue o documento XLSX renderizado usando a classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) e invoque [save](https://reference.aspose.com /cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).

{{% blocks/products/pf/feature-page-code h3="Android - Conversão de PDF para Excel" %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint potm-to-rtf powerpoint-to-docx ppt-to-docx pptx-to-odt potm-to-docx email-to-docx email-to-word eml-to-pdf emlx-to-bmp emlx-to-image msg-to-pdf oft-to-word" >}}


{{% blocks/products/pf/feature-page-section  h2="Conversão de Excel para Word" %}}
A API do Android também lida com a conversão do Excel. O processo é carregar o arquivo EXCEL XLSX usando a classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) e converter EXCEL para PDF definindo SaveFormat para AUTO primeiro. Em seguida, carregue o arquivo PDF salvo usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) e invoque [save](https://reference.aspose.com/ pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) para salvar o documento no formato Word DOC/DOCX.

{{% blocks/products/pf/feature-page-code h3="Android - Conversão de Excel para Word" %}}

{{< gist "aspose-com-gists" "10fdb88fb4d39618cdc2dfd0d0bd86c1" "excel-to-word-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mhtml-to-docm pdf-to-rtf svg-to-docm xps-to-dotx pdf-to-powerpoint tex-to-ppsx xps-to-potx csv-to-doc excel-to-word xls-to-word xlsx-to-powerpoint xltx-to-word word-to-excel" >}}

{{% blocks/products/pf/feature-page-section  h2="Converter POWERPOINT para HTML e MHTML" %}}
A Android Total API lida com vários formatos, incluindo arquivos do PowerPoint, para que possa converter apresentações em HTML e MHTML. O processo é carregar o arquivo POWERPOINT PPT/ PPTX usando a classe [Apresentação](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) e invocar [save](https://reference.aspose .com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) para converter POWERPOINT em HTML. Além disso, agora carregue o documento HTML convertido usando a classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) e chame [save](https://reference.aspose .com/cells/java/com.aspose.cells/) para conversão MHTML. 
{{% blocks/products/pf/feature-page-code h3="Android - Slides do PowerPoint para conversão de HTML e MHTML" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="rtf-to-excel docx-to-csv json-to-word json-to-powerpoint word-to-json powerpoint-to-json potm-to-excel pptx-to-excel ppsx-to-mhtml" >}}