---
title: Converter TSV para DOC usando Java
description: API Java para exportar TSV para DOC usando Excel ou Word
url_ignore: /pt/java/conversion/tsv-to-doc/
family: total
platformtag: net
feature: conversion
informat: TSV
outformat: DOC
otherformats: PPTX WORD POWERPOINT DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java para exportar TSV para DOC" h2="On Premise Java API para exportar TSV para DOC sem depender do Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
A renderização de TSV para DOC é um processo de duas etapas. Você primeiro usará a API [Aspose.Cells for Java](https://products.aspose.com/cells/java) para converter o documento TSV fornecido em PDF e, em seguida, usará [Aspose.Pdf for Java](https://products.aspose.com/pdf/java), você pode facilmente converter seu documento PDF em DOC. Ambas as APIs fazem parte da coleção de bibliotecas de automação de formato de arquivo [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Como converter TSV para DOC via API Java" %}}
1. Abra o arquivo TSV usando a classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Converta TSV para PDF e defina SaveFormat para AUTO
3. Carregue o arquivo PDF convertido usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Salve o documento no formato DOC usando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) e defina Doc como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você precisa usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e inclua bibliotecas em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the TSV file using Workbook class
Workbook book = new Workbook("input.tsv");
// save TSV as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in DOC format
document.save("output.doc", com.aspose.pdf.SaveFormat.Doc);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras opções de conversão" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/tsv-to-docx/" name="TSV Para DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/tsv-to-pptx/" name="TSV Para PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/tsv-to-powerpoint/" name="TSV Para POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/tsv-to-word/" name="TSV Para WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}