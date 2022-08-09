---
title: Exportar TSV para DOCX no Android
description: API do Android para converter TSV para DOCX sem usar o Microsoft Word
url: /pt/android-java/conversion/tsv-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: TSV
outformat: DOCX
otherformats: WORD DOC POWERPOINT PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderize TSV para DOCX no Android via Java" h2="Transforme TSV em DOCX em seus aplicativos Android sem usar o Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total para Android via Java](https://products.aspose.com/total/android-java/) é um pacote de poderosas APIs de automação de arquivos. Ao usar duas de suas APIs, você pode integrar o recurso de conversão de TSV para DOCX dentro de seus aplicativos Android. Na primeira etapa, você pode exportar TSV para PDF usando [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). Depois disso, usando [Aspose.PDF para Android via Java](https://products.aspose.com/pdf/android-java/), você pode converter PDF para DOCX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API do Android para exportar TSV para DOCX" %}}
1. Abra o arquivo TSV usando a classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Converta TSV para PDF e defina SaveFormat para AUTO
3. Carregue o arquivo PDF convertido usando a classe [Docxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument)
4. Salve o docxumento no formato DOCX usando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument#save-java.lang.String-com.aspose.pdf.SaveOptions -) método
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Android via Java diretamente do [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e instale [Aspose.PDF para Android via Java](https://docxs.aspose.com/pdf/androidjava/installation/) e [Aspose.Cells para Android via Java](https://docxs.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) em seus aplicativos.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the TSV file using Workbook class
Workbook book = new Workbook("input.tsv");
// save TSV as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Docxument class
Docxument docxument = new Docxument("pdfOutput.pdf");
// save docxument in DOCX format
docxument.save("output.docx", com.aspose.pdf.SaveFormat.DocxX);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Remover propriedades personalizadas do arquivo TSV no Android via Java" %}}
Além da conversão de docxumentos, o [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) também oferece vários outros recursos. Antes do processo de conversão, você pode remover as propriedades personalizadas do docxumento TSV. Para remover propriedades personalizadas, chame o método [DocxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/docxumentpropertycollection#remove(java.lang.String)) e passe o nome de a propriedade do docxumento a ser removida.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the TSV file using Workbook class
Workbook book = new Workbook("input.tsv");
// retrieve a list of all custom docxument properties of the Excel file
DocxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocxumentProperties();
// remove a custom docxument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/tsv-to-word/" name="TSV Para WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/tsv-to-docx/" name="TSV Para DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/tsv-to-powerpoint/" name="TSV Para POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/tsv-to-pptx/" name="TSV Para PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}