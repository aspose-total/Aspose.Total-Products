---
title: Converter XLTX para DOC usando Java
description: API Java para exportar XLTX para DOC usando Excel ou Word
url_ignore: /pt/java/conversion/xltx-to-doc/
family: total
platformtag: net
feature: conversion
informat: XLTX
outformat: DOC
otherformats: DOCX PPTX POWERPOINT WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java para exportar XLTX para DOC" h2="On Premise Java API para exportar XLTX para DOC sem depender do Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
A renderização de XLTX para DOC é um processo de duas etapas. Você primeiro usará a API [Aspose.Cells for Java](https://products.aspose.com/cells/java) para converter o documento XLTX fornecido em PDF e, em seguida, usará [Aspose.Pdf for Java](https://products.aspose.com/pdf/java), você pode facilmente converter seu documento PDF em DOC. Ambas as APIs fazem parte da coleção de bibliotecas de automação de formato de arquivo [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Como converter XLTX para DOC via API Java" %}}
1. Abra o arquivo XLTX usando a classe [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Converta XLTX para PDF e defina SaveFormat para AUTO
3. Carregue o arquivo PDF convertido usando a classe [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Salve o documento no formato DOC usando [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) e defina Doc como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você precisa usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e inclua bibliotecas em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLTX file using Workbook class
Workbook book = new Workbook("input.xltx");
// save XLTX as PDF
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xltx-to-docx/" name="XLTX Para DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xltx-to-pptx/" name="XLTX Para PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xltx-to-powerpoint/" name="XLTX Para POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/xltx-to-word/" name="XLTX Para WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}