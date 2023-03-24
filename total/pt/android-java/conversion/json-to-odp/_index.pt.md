---
title: Converter o formato JSON para ODP no Android via Java
description: Analise JSON para ODP em aplicativos Android sem usar o Microsoft PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: ODP
otherformats: PPT POWERPOINT PPSX POTM POTX PPTM OTP PPSM POT PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converter o formato JSON para ODP no Android" h2="Analisar o formato JSON para ODP em aplicativos Android sem usar o Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Você pode converter o formato JSON para ODP em seus aplicativos Android em um processo de duas etapas. Em primeiro lugar, usando [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/), você pode analisar JSON para PPTX. Depois disso, usando [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), você pode converter PPTX para ODP. Ambas as APIs estão no pacote [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter o formato JSON para ODP no Android" %}}
1. Crie um novo objeto [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) e abra o arquivo JSON
2. Salve JSON como PPTX usando [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) método
3. Carregue o documento PPTX usando a classe [Apresentação](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Salve o documento no formato ODP usando o método [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total for Android via Java diretamente do [Maven](https://releases.aspose.com/total/java/) e instalar bibliotecas em seu aplicativo.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "convert-json-to-powerpoint.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Definir layout e converter o formato JSON para ODP em aplicativos Android" %}}
Além disso, a API permite analisar JSON para ODP com opções de layout especificadas. Para especificar as opções de layout, você pode usar a classe [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayouttoptions). Ele permite que você processe uma matriz como uma tabela, ignore nulos, ignore o título da matriz, ignore o título do objeto, converta string em número ou data, defina data e formato de número e defina estilo de título. Todas essas opções permitem que você apresente seus dados conforme suas necessidades. O trecho de código a seguir mostra como definir as opções de layout.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converter o formato JSON para ODP com marca d'água no Android via Java" %}}
Usando a API, você também pode converter JSON em ODP com marca d'água. Para adicionar uma marca d'água ao seu documento ODP, você pode primeiro analisar JSON para PPTX e adicionar uma marca d'água a ele. Para adicionar uma marca d'água, carregue o arquivo PPTX recém-criado usando a classe [Apresentação](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation), percorra todos os slides, adicione texto usando addTextFrame, defina todas as opções relevantes, como cor, fillType e muito mais, e salve o documento no ODP.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}