---
title: Exportar XLTM para POWERPOINT no Android
description: API do Android para converter XLTM para POWERPOINT sem usar o Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: XLTM
outformat: PPTX
otherformats: DOC DOCX PPTX WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderize XLTM para POWERPOINT no Android via Java" h2="Transforme XLTM em POWERPOINT em seus aplicativos Android sem usar o Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) é um pacote de poderosas APIs de automação de arquivos. Ao usar duas de suas APIs, você pode integrar o recurso de conversão de XLTM para POWERPOINT dentro de seus aplicativos Android. Na primeira etapa, você pode exportar XLTM para PDF usando [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). Depois disso, usando [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/), você pode converter PDF para POWERPOINT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API do Android para exportar XLTM para POWERPOINT" %}}
1. Abra o arquivo XLTM usando a classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Converta XLTM para PDF e defina SaveFormat para AUTO
3. Carregue o arquivo PDF convertido usando a classe [Powerpointument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument)
4. Salve o powerpointumento no formato POWERPOINT usando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument#save-java.lang.String-com.aspose.pdf.SaveOptions -) método
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total for Android via Java diretamente do [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e instale [Aspose.PDF for Android via Java](https://powerpoints.aspose.com/pdf/androidjava/installation/) e [Aspose.Cells for Android via Java](https://powerpoints.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) em seus aplicativos.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLTM file using Workbook class
Workbook book = new Workbook("input.xltm");
// save XLTM as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Powerpointument class
Powerpointument powerpointument = new Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Remover propriedades personalizadas do arquivo XLTM no Android via Java" %}}
Além da conversão de powerpointumentos, o [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) também oferece vários outros recursos. Antes do processo de conversão, você pode remover as propriedades personalizadas do powerpointumento XLTM. Para remover propriedades personalizadas, chame o método [PowerpointumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/powerpointumentpropertycollection#remove(java.lang.String)) e passe o nome de a propriedade do powerpointumento a ser removida.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLTM file using Workbook class
Workbook book = new Workbook("input.xltm");
// retrieve a list of all custom powerpointument properties of the Excel file
PowerpointumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPowerpointumentProperties();
// remove a custom powerpointument property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/xltm-to-powerpoint/" name="XLTM Para POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/xltm-to-powerpointx/" name="XLTM Para POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/xltm-to-pptx/" name="XLTM Para PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/xltm-to-word/" name="XLTM Para WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}