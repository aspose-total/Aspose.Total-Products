---
title: Converter o formato JSON para PSD via Java
description: Analise JSON para PSD em Java sem usar o Microsoft PowerPoint
url_ignore: /pt/java/conversion/json-to-psd/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PSD
otherformats: SVGZ WMF DICOM DXF IMAGE TGA EMZ PSD WMZ JPEG2000
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converter o formato JSON para PSD via Java" h2="API Java para analisar o formato JSON para PSD em qualquer aplicativo Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total for Java](https://products.aspose.com/total/java/), você pode converter o formato JSON para PSD em qualquer aplicativo Java em duas etapas simples. Em primeiro lugar, usando [Aspose.Cells for Java](https://products.aspose.com/cells/java/), você pode analisar JSON para JPEG. Depois disso, usando [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/), você pode converter JPEG em PSD.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter o formato JSON para PSD via Java" %}}
1. Crie um novo objeto [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) e abra o arquivo JSON
2. Salve JSON como JPEG usando [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) método
3. Carregue o documento JPEG usando a classe [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Salve o documento no formato PSD usando [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e inclua bibliotecas em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversão" %}}
Além disso, a API permite analisar JSON para PSD com opções de layout especificadas. Para especificar as opções de layout, você pode usar a classe [JsonLayoutOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonlayouttoptions). Ele permite que você processe uma matriz como uma tabela, ignore nulos, ignore o título da matriz, ignore o título do objeto, converta string em número ou data, defina data e formato de número e defina estilo de título. Todas essas opções permitem que você apresente seus dados conforme suas necessidades. O trecho de código a seguir mostra como definir as opções de layout.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Defina o layout e converta o formato JSON para PSD via Java" %}}
Usando a API, você também pode converter JSON em PSD com marca d'água em seu documento PSD. Para adicionar uma marca d'água, você pode primeiro converter JSON para JPEG e adicionar uma marca d'água nele. Para adicionar marca d'água, carregue um arquivo de imagem usando a classe [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image), crie um objeto da classe [Graphics](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) e inicialize-a com o objeto Image, crie uma nova [Matrix](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Matrix) e defina a tradução e a transformação para o ângulo desejado e adicione marca d'água usando [Graphics.drawString](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Depois de adicionar a marca d'água em sua imagem, você pode salvar o JPEG como formato PSD. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras opções de conversão" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/json-to-jpeg2000/" name="JSON Para JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/json-to-emz/" name="JSON Para EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/json-to-psd/" name="JSON Para PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/json-to-wmf/" name="JSON Para WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/json-to-wmz/" name="JSON Para WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/json-to-dxf/" name="JSON Para DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/json-to-image/" name="JSON Para IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/json-to-svgz/" name="JSON Para SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/json-to-dicom/" name="JSON Para DICOM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/json-to-tga/" name="JSON Para TGA" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}