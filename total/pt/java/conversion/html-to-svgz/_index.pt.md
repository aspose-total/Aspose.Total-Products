---
title: Converter HTML para SVGZ via Java
description: Exporte o arquivo HTML para SVGZ em seus aplicativos Java sem usar nenhum aplicativo de terceiros
url_ignore: /pt/java/conversion/html-to-svgz/
family: total
platformtag: net
feature: conversion
informat: HTML
outformat: SVGZ
otherformats: EMZ JPEG2000 PSD WMF TGA IMAGE WMZ DXF SVGZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converter HTML para SVGZ via Java" h2="Exporte o arquivo HTML para SVGZ em qualquer aplicativo Java J2SE, J2EE, J2ME sem usar o Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Você pode converter o arquivo html em imagem SVGZ em Java em duas etapas simples. Em primeiro lugar, usando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), você pode exportar HTML para JPEG. Depois disso, usando [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) API de processamento de imagem, você pode renderizar JPEG para SVGZ. Ambas as APIs estão no pacote [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Exportar HTML para SVGZ via Java" %}}
1. Abra o arquivo HTML usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Inicialize o objeto de classe e renderize HTML para JPEG usando [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-)
3. Carregue o arquivo JPEG usando a classe [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Salve o documento no formato SVGZ usando [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e inclua bibliotecas em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Converter HTML para SVGZ em um único arquivo via Java" %}}
A API também permite exportar o arquivo HTML para SVGZ para um único arquivo. Para converter todas as páginas, você pode primeiro renderizar seu documento HTML em um arquivo TIFF e depois exportar o arquivo TIFF para SVGZ. Você pode abrir o arquivo de entrada usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) e criar objetos de dispositivo Resolution, TiffSettings e TIFF. Você pode obter uma única imagem TIFF usando [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) da classe [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Por fim, você pode carregar o arquivo TIFF usando a classe [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) e salvá-lo no formato SVGZ usando [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converter HTML para SVGZ com marca d'água via Java" %}}
Usando a API, você também pode exportar o arquivo HTML para SVGZ com marca d'água em seu documento SVGZ. Para adicionar uma marca d'água, você pode primeiro converter HTML para JPEG e adicionar uma marca d'água nele. Para adicionar marca d'água, carregue um arquivo de imagem usando a classe [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), crie um objeto da classe [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) e inicialize-a com o objeto Image, crie uma nova [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) e defina a tradução e a transformação para o ângulo desejado e adicione marca d'água usando [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Depois de adicionar a marca d'água em sua imagem, você pode salvar o JPEG como formato SVGZ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converter e girar HTML para arquivo SVGZ via Java" %}}
Usando a API, você também pode girar a imagem SVGZ de saída conforme suas necessidades. O método Image.rotateFlip pode ser usado para girar a imagem em 90/180/270 graus e virar a imagem horizontalmente ou verticalmente. A biblioteca fornece métodos simples para realizar operações complexas enquanto encapsula todos os detalhes feios. Você pode especificar o tipo de rotação e inversão para aplicar à imagem. Para girar e inverter a imagem, você pode carregar a imagem JPEG convertida usando a classe [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) e chamar a classe Image. girarFlip enquanto especifica o [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType) apropriado. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras opções de conversão" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/html-to-emz/" name="HTML Para EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/html-to-tga/" name="HTML Para TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/html-to-jpeg2000/" name="HTML Para JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/html-to-image/" name="HTML Para IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/html-to-psd/" name="HTML Para PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/html-to-wmz/" name="HTML Para WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/html-to-svgz/" name="HTML Para SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/html-to/" name="HTML Para" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/html-to-wmf/" name="HTML Para WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/html-to-dxf/" name="HTML Para DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/html-to-dicom/" name="HTML Para DICOM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}