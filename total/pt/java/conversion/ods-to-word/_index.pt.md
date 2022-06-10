---
title: Converter ODS para WORD usando Java
description: API Java para exportar ODS para WORD usando Excel ou Word
url_ignore: /pt/java/conversion/ods-to-word/
family: total
platformtag: net
feature: conversion
informat: ODS
outformat: WORD
otherformats: WORDX WORD PPTX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java para exportar ODS para WORD" h2="On Premise Java API para exportar ODS para WORD sem depender do Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
A renderização de ODS para WORD é um processo de duas etapas. Você primeiro usará a API [Aspose.Cells for Java](https://products.aspose.com/cells/java) para converter o documento ODS fornecido em PDF e, em seguida, usará [Aspose.Pdf for Java](https://products.aspose.com/pdf/java), você pode facilmente converter seu documento PDF em WORD. Ambas as APIs fazem parte da coleção de bibliotecas de automação de formato de arquivo [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Como converter ODS para WORD via API Java" %}}
1. Abra o arquivo ODS usando a classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Converta ODS para PDF e defina SaveFormat para AUTO
3. Carregue o arquivo PDF convertido usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Salve o documento no formato WORD usando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) e defina Word como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você precisa usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e inclua bibliotecas em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the ODS file using Workbook class
Workbook book = new Workbook("input.ods");
// save ODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in WORD format
document.save("output.word", com.aspose.pdf.SaveFormat.Word);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras opções de conversão" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/ods-to-wordx/" name="ODS Para WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/ods-to-pptx/" name="ODS Para PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/ods-to-powerpoint/" name="ODS Para POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/ods-to-word/" name="ODS Para WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}