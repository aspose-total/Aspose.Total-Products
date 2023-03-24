---
title: Converter XLSM para DOC usando Java ou com o conversor online grátis
description: API Java para exportar XLSM para DOC ou online usando Excel ou Word ou on-line. Teste o conversor online gratuito de CSV para DOC rapidamente antes de integrar o código.
url_ignore: /pt/java/conversion/xlsm-to-doc/
family: total
platformtag: net
feature: conversion
informat: XLSM
outformat: DOC
otherformats: DOCX POWERPOINT PPTX WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java para exportar XLSM para DOC ou online" h2="On Premise Java API para exportar XLSM para DOC sem depender do Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
A renderização de XLSM para DOC é um processo de duas etapas. Você primeiro usará a API [Aspose.Cells for Java](https://products.aspose.com/cells/java) para converter o documento XLSM fornecido em PDF e, em seguida, usará [Aspose.Pdf for Java](https://products.aspose.com/pdf/java), você pode facilmente converter seu documento PDF em DOC. Ambas as APIs fazem parte da coleção de bibliotecas de automação de formato de arquivo [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Como converter XLSM para DOC via API Java" %}}
1. Abra o arquivo XLSM usando a classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Converta XLSM para PDF e defina SaveFormat para AUTO
3. Carregue o arquivo PDF convertido usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Salve o documento no formato DOC usando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) e defina Doc como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você precisa usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://releases.aspose.com/total/java/) e inclua bibliotecas em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSM file using Workbook class
Workbook book = new Workbook("input.xlsm");
// save XLSM as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in DOC format
document.save("output.doc", com.aspose.pdf.SaveFormat.Doc);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class="demobox tc col-md-12 padding-0" align="center">
<div class="demobox tc col-md-12 padding-0">

<h3>Conversor Online de XLSM para DOC</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=doc&from=xlsm" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/xlsm-to-doc/">Experimente nosso aplicativo gratuito para conversão de XLSM para DOC</a></p>
</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}