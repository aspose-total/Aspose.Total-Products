---
title: Exportar XLSM para WORD no Android
description: API do Android para converter XLSM para WORD sem usar o Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: XLSM
outformat: DOC
otherformats: PPTX DOCX DOC POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderize XLSM para WORD no Android via Java" h2="Transforme XLSM em WORD em seus aplicativos Android sem usar o Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) é um pacote de poderosas APIs de automação de arquivos. Ao usar duas de suas APIs, você pode integrar o recurso de conversão de XLSM para WORD dentro de seus aplicativos Android. Na primeira etapa, você pode exportar XLSM para PDF usando [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). Depois disso, usando [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/), você pode converter PDF para WORD. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API do Android para exportar XLSM para WORD" %}}
1. Abra o arquivo XLSM usando a classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Converta XLSM para PDF e defina SaveFormat para AUTO
3. Carregue o arquivo PDF convertido usando a classe [Wordument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument)
4. Salve o wordumento no formato WORD usando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument#save-java.lang.String-com.aspose.pdf.SaveOptions -) método
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total for Android via Java diretamente do [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e instale [Aspose.PDF for Android via Java](https://words.aspose.com/pdf/androidjava/installation/) e [Aspose.Cells for Android via Java](https://words.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) em seus aplicativos.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSM file using Workbook class
Workbook book = new Workbook("input.xlsm");
// save XLSM as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Wordument class
Wordument wordument = new Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.save("output.word", com.aspose.pdf.SaveFormat.Word);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Remover propriedades personalizadas do arquivo XLSM no Android via Java" %}}
Além da conversão de wordumentos, o [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) também oferece vários outros recursos. Antes do processo de conversão, você pode remover as propriedades personalizadas do wordumento XLSM. Para remover propriedades personalizadas, chame o método [WordumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/wordumentpropertycollection#remove(java.lang.String)) e passe o nome de a propriedade do wordumento a ser removida.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSM file using Workbook class
Workbook book = new Workbook("input.xlsm");
// retrieve a list of all custom wordument properties of the Excel file
WordumentPropertyCollection customProperties = workbook.getWorksheets().getCustomWordumentProperties();
// remove a custom wordument property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/xlsm-to-pptx/" name="XLSM Para PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/xlsm-to-wordx/" name="XLSM Para WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/xlsm-to-word/" name="XLSM Para WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/xlsm-to-powerpoint/" name="XLSM Para POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}