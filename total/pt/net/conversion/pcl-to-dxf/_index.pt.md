---
title: Converter PCL para DXF via API C#
description: Exporte PCL para DXF em seus aplicativos .NET sem usar nenhum aplicativo de terceiros
url: /pt/net/conversion/pcl-to-dxf/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: DXF
otherformats: DXF JPEG2000 WMF PSD WMZ IMAGE EMZ  SVGZ TGA DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converter arquivo PCL para DXF via C#" h2="Exporte PCL para DXF em aplicativos .NET sem usar o Adobe<sup>&reg;</sup> Acrobat Reader ou qualquer outro aplicativo de terceiros" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total for .NET](https://products.aspose.com/total/net/) você pode exportar facilmente PCL para imagem DXF em qualquer aplicativo .NET em duas etapas simples. Em primeiro lugar, usando [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), você pode exportar PCL para JPEG. Depois disso, usando [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) API de processamento de imagem, você pode converter JPEG para DXF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter arquivo PCL para DXF via .NET" %}}
1. Abra o arquivo PCL usando a classe [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Inicialize o objeto de classe [JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) e renderize PCL para JPEG usando [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) método
3. Carregue o arquivo JPEG usando a classe [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
4. Salve o documento no formato DXF usando o método [Salvar](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Converter arquivo PCL para DXF em um único arquivo via C#" %}}
Usando a API, você também pode converter o arquivo PCL para DXF em um único arquivo de imagem. Para converter todas as páginas, você pode primeiro renderizar seu documento PCL para um arquivo TIFF e depois exportar o arquivo TIFF para DXF. Você pode abrir o arquivo de entrada usando a classe [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) e criar objetos de dispositivo Resolution, TiffSettings e TIFF. Você pode obter uma única imagem TIFF usando o método [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) de [TiffDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Finalmente, você pode carregar o arquivo TIFF usando a classe [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
e salve-o no formato DXF usando o método [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converta e gire o arquivo PCL para DXF via C#" %}}
Usando a API, você também pode girar a imagem DXF de saída conforme suas necessidades. O método Image.RotateFlip pode ser usado para girar a imagem em 90/180/270 graus e virar a imagem horizontalmente ou verticalmente. Você pode especificar o tipo de rotação e inversão para aplicar à imagem. Para girar e inverter a imagem, você pode carregar a imagem JPEG convertida usando o método de fábrica exposto pela classe [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) e chamar a classe Image .RotateFlip enquanto especifica o [RotateFlipType](https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) apropriado. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras opções de conversão" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pcl-to-emz/" name="PCL Para EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pcl-to-tga/" name="PCL Para TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pcl-to-jpeg2000/" name="PCL Para JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pcl-to-image/" name="PCL Para IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pcl-to-psd/" name="PCL Para PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pcl-to-wmz/" name="PCL Para WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pcl-to-svgz/" name="PCL Para SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pcl-to/" name="PCL Para" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pcl-to-wmf/" name="PCL Para WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pcl-to-dxf/" name="PCL Para DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/pcl-to-dicom/" name="PCL Para DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}