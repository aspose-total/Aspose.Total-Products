---
title: Exportar XLSX para POWERPOINT no Android
description: API do Android para converter XLSX para POWERPOINT sem usar o Microsoft Word
url: /pt/android-java/conversion/xlsx-to-powerpoint/
family: total
platformtag: cpp
feature: conversion
informat: XLSX
outformat: PPTX
otherformats: DOC WORD PPTX DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderize XLSX para POWERPOINT no Android via Java" h2="Transforme XLSX em POWERPOINT em seus aplicativos Android sem usar o Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total para Android via Java](https://products.aspose.com/total/android-java/) é um pacote de poderosas APIs de automação de arquivos. Ao usar duas de suas APIs, você pode integrar o recurso de conversão de XLSX para POWERPOINT dentro de seus aplicativos Android. Na primeira etapa, você pode exportar XLSX para PDF usando [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). Depois disso, usando [Aspose.PDF para Android via Java](https://products.aspose.com/pdf/android-java/), você pode converter PDF para POWERPOINT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API do Android para exportar XLSX para POWERPOINT" %}}
1. Abra o arquivo XLSX usando a classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Converta XLSX para PDF e defina SaveFormat para AUTO
3. Carregue o arquivo PDF convertido usando a classe [Powerpointument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument)
4. Salve o powerpointumento no formato POWERPOINT usando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument#save-java.lang.String-com.aspose.pdf.SaveOptions -) método
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Android via Java diretamente do [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e instale [Aspose.PDF para Android via Java](https://powerpoints.aspose.com/pdf/androidjava/installation/) e [Aspose.Cells para Android via Java](https://powerpoints.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) em seus aplicativos.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSX file using Workbook class
Workbook book = new Workbook("input.xlsx");
// save XLSX as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Powerpointument class
Powerpointument powerpointument = new Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Remover propriedades personalizadas do arquivo XLSX no Android via Java" %}}
Além da conversão de powerpointumentos, o [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) também oferece vários outros recursos. Antes do processo de conversão, você pode remover as propriedades personalizadas do powerpointumento XLSX. Para remover propriedades personalizadas, chame o método [PowerpointumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/powerpointumentpropertycollection#remove(java.lang.String)) e passe o nome de a propriedade do powerpointumento a ser removida.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSX file using Workbook class
Workbook book = new Workbook("input.xlsx");
// retrieve a list of all custom powerpointument properties of the Excel file
PowerpointumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPowerpointumentProperties();
// remove a custom powerpointument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/xlsx-to-powerpoint/" name="XLSX Para POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/xlsx-to-word/" name="XLSX Para WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/xlsx-to-pptx/" name="XLSX Para PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/xlsx-to-powerpointx/" name="XLSX Para POWERPOINTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}