---
title: Converter PDF para WMZ via API C#
description: Exporte PDF para WMZ em seus aplicativos .NET sem usar nenhum aplicativo de terceiros
url: /pt/net/conversion/pdf-to-wmz/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: WMZ
otherformats: TGA WMF SVGZ WMZ  DXF PSD JPEG2000 IMAGE EMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converter arquivo PDF para WMZ via C#" h2="Exporte PDF para WMZ em aplicativos .NET sem usar o Adobe<sup>&reg;</sup> Acrobat Reader ou qualquer outro aplicativo de terceiros" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total for .NET](https://products.aspose.com/total/net/) você pode exportar facilmente PDF para imagem WMZ em qualquer aplicativo .NET em duas etapas simples. Em primeiro lugar, usando [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), você pode exportar PDF para JPEG. Depois disso, usando [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) API de processamento de imagem, você pode converter JPEG para WMZ.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter arquivo PDF para WMZ via .NET" %}}
1. Abra o arquivo PDF usando a classe [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Inicialize o objeto de classe [JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) e renderize PDF para JPEG usando [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) método
3. Carregue o arquivo JPEG usando a classe [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
4. Salve o documento no formato WMZ usando o método [Salvar](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Converter arquivo PDF para WMZ em um único arquivo via C#" %}}
Usando a API, você também pode converter o arquivo PDF para WMZ em um único arquivo de imagem. Para converter todas as páginas, você pode primeiro renderizar seu documento PDF para um arquivo TIFF e depois exportar o arquivo TIFF para WMZ. Você pode abrir o arquivo de entrada usando a classe [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) e criar objetos de dispositivo Resolution, TiffSettings e TIFF. Você pode obter uma única imagem TIFF usando o método [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) de [TiffDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Finalmente, você pode carregar o arquivo TIFF usando a classe [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
e salve-o no formato WMZ usando o método [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converta e gire o arquivo PDF para WMZ via C#" %}}
Usando a API, você também pode girar a imagem WMZ de saída conforme suas necessidades. O método Image.RotateFlip pode ser usado para girar a imagem em 90/180/270 graus e virar a imagem horizontalmente ou verticalmente. Você pode especificar o tipo de rotação e inversão para aplicar à imagem. Para girar e inverter a imagem, você pode carregar a imagem JPEG convertida usando o método de fábrica exposto pela classe [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) e chamar a classe Image .RotateFlip enquanto especifica o [RotateFlipType](https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) apropriado. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras opções de conversão" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-emz/" name="PDF Para EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-tga/" name="PDF Para TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-jpeg2000/" name="PDF Para JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-image/" name="PDF Para IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-psd/" name="PDF Para PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-wmz/" name="PDF Para WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-svgz/" name="PDF Para SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to/" name="PDF Para" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-wmf/" name="PDF Para WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-dxf/" name="PDF Para DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pdf-to-dicom/" name="PDF Para DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}