---
title: Converter CGM para SVGZ via API C#
description: Exporte CGM para SVGZ em seus aplicativos .NET sem usar nenhum aplicativo de terceiros
url_ignore: /pt/net/conversion/cgm-to-svgz/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: SVGZ
otherformats: TGA JPEG2000 IMAGE SVGZ WMF  WMZ PSD EMZ DXF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converter arquivo CGM para SVGZ via C#" h2="Exporte CGM para SVGZ em aplicativos .NET sem usar o Adobe<sup>&reg;</sup> Acrobat Reader ou qualquer outro aplicativo de terceiros" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total for .NET](https://products.aspose.com/total/net/) você pode exportar facilmente CGM para imagem SVGZ em qualquer aplicativo .NET em duas etapas simples. Em primeiro lugar, usando [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), você pode exportar CGM para JPEG. Depois disso, usando [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) API de processamento de imagem, você pode converter JPEG para SVGZ.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter arquivo CGM para SVGZ via .NET" %}}
1. Abra o arquivo CGM usando a classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Inicialize o objeto de classe [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) e renderize CGM para JPEG usando [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) método
3. Carregue o arquivo JPEG usando a classe [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Salve o documento no formato SVGZ usando o método [Salvar](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Converter arquivo CGM para SVGZ em um único arquivo via C#" %}}
Usando a API, você também pode converter o arquivo CGM para SVGZ em um único arquivo de imagem. Para converter todas as páginas, você pode primeiro renderizar seu documento CGM para um arquivo TIFF e depois exportar o arquivo TIFF para SVGZ. Você pode abrir o arquivo de entrada usando a classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) e criar objetos de dispositivo Resolution, TiffSettings e TIFF. Você pode obter uma única imagem TIFF usando o método [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) de [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Finalmente, você pode carregar o arquivo TIFF usando a classe [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
e salve-o no formato SVGZ usando o método [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converta e gire o arquivo CGM para SVGZ via C#" %}}
Usando a API, você também pode girar a imagem SVGZ de saída conforme suas necessidades. O método Image.RotateFlip pode ser usado para girar a imagem em 90/180/270 graus e virar a imagem horizontalmente ou verticalmente. Você pode especificar o tipo de rotação e inversão para aplicar à imagem. Para girar e inverter a imagem, você pode carregar a imagem JPEG convertida usando o método de fábrica exposto pela classe [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) e chamar a classe Image .RotateFlip enquanto especifica o [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) apropriado. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos CGM a SVGZ mediante programación: casos de uso" %}}
Arquivos CGM (Metafile de Gráficos de Computador) são usados para armazenar informações de gráficos vetoriais, tornando-os ideais para criar gráficos estáticos e ilustrações.

No entanto, ao trabalhar com dados dinâmicos, planilhas como o Excel se tornam essenciais para a visualização e análise de dados.

A conversão de arquivos CGM para formatos SVGZ é necessária para desbloquear o potencial completo das suas capacidades de gráficos vetoriais e ilustrações. Essa conversão permite:

**Uso Caso:**

*   **Criação de Gráficos Estáticos**: Converter arquivos CGM para criar gráficos estáticos de alta qualidade, ilustrações e logos ideais para uso impresso ou web.
*   **Design de Identidade de Marca**: Usar SVGZ para projetar identidades de marca, ícones e gráficos que são escaláveis e mantêm sua qualidade ao serem resízidos.
*   **Projeto de Embalagem e Rotulagem**: Converter arquivos CGM para criar design de embalagem e rotulagem visualmente atraentes que se destacam em bancas de lojas.
*   **Gestão de Ativos Digitais**: Armazenar arquivos CGM em formatos SVGZ para gestão eficiente de ativos digitais, permitindo acesso fácil e compartilhamento rápido de gráficos vetoriais entre equipes.
*   **Otimização de Gráficos para Web e Móveis**: Usar SVGZ para otimizar arquivos CGM para dispositivos web e móveis, garantindo tempo de carregamento rápido e visualizações de alta qualidade.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}