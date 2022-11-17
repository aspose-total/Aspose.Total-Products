---
title: Conversão de formato de arquivo via C# 

description: Converta Microsoft Word, Excel, PowerPoint, Outlook, PDF, HTML, imagens 3D, diagramas, formatos de vídeo e muitos outros arquivos populares com apenas algumas linhas de código C#.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Conversão de formato de arquivo via C# .NET" h2="Converta arquivos do Microsoft<sup>&reg;</sup> Office, PDF, Imagens, HTML e outros formatos sem usar nenhum outro software." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Biblioteca Total .NET](https://products.aspose.com/total/net/) acelera o desenvolvimento de soluções de gerenciamento de documentos do zero ou aprimora os aplicativos existentes para lidar com a manipulação de documentos com facilidade. A API não apenas gerencia documentos do Microsoft Office, mas também lida com PDF, HTML, Imagens TIFF, JPG, PNG, BMP e SVG, arquivos de e-mail, formatos de vídeo, formatos de dados GIS e muito mais. É um conjunto completo de APIs de solução de gerenciamento e manipulação de documentos sem nenhuma dependência de software. Os programadores podem facilmente criar, atualizar, renderizar, imprimir e converter entre os formatos mais populares em qualquer aplicativo baseado em .NET.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Converter Word para PDF" %}}
A API Total suporta não apenas a conversão entre os formatos do Microsoft Word, mas também a conversão do Word para PDF, HTML, Imagens, EPUB, Markdown e XPS. O processo de conversão é simples. Carregue o Document via classe Document e apenas chame o método Save com o formato de destino. É tão simples. Os desenvolvedores podem verificar o [resultado da conversão](https://products.aspose.com/words/net/conversion/word-to-pdf/) antes da integração do código do **Word to PDF**


{{% blocks/products/pf/feature-page-code h3="C# - Conversão de Word para PDF" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-word-to-pdf.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-excel word-to-json word-to-ods" >}}


{{% blocks/products/pf/feature-page-section  h2="Converter PDF em Imagens" %}}
A API suporta a conversão de PDF para Imagens, Powerpoint, Excel e outros formatos. Para conversão de PDF para imagem, vamos considerar a imagem JPG como arquivo de destino. O processo é carregar o arquivo PDF usando a classe Document e inicializar o objeto [JpegDevice class](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) e renderizar PDF para JPEG via [Process](https ://apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) método
Carregue o arquivo JPEG usando a classe [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) e, finalmente, chame o método Save.

{{% blocks/products/pf/feature-page-code h3="C# - Conversão de PDF para Imagem" %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt" >}}

{{% blocks/products/pf/feature-page-section  h2="Converter Excel para Word e PowerPoint" %}}

Para converter formatos do Microsoft Excel para diferentes arquivos, incluindo Word e PowerPoint, sub APIs relevantes envolvidas da principal Aspose.Total for .NET API. Processo de conversão de arquivos do Excel para documento do Word, carregue o arquivo EXCEL usando a classe [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) e converta o EXCEL para PDF primeiro e defina SaveFormat para Auto. Em seguida, carregue o arquivo PDF convertido usando a classe Document e chame o método Save e defina Doc, Docx como SaveFormat. Código também listado para conversão do Microsoft **Excel para Powerpoint**.

{{% blocks/products/pf/feature-page-code h3="C# - Conversão de JSON para Excel" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-word.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# - Conversão de Excel para JSON" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="excel-to-doc excel-to-docx excel-to-pptx" >}}