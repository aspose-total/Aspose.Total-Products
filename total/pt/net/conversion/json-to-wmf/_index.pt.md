---
title: Converter o formato JSON para WMF via .NET
description: Analise JSON para WMF em C# sem usar dependências de terceiros
url_ignore: /pt/net/conversion/json-to-wmf/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: WMF
otherformats: DICOM WMF IMAGE WMZ DXF TGA PSD JPEG2000 SVGZ EMZ
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converter o formato JSON para WMF via C#" h2="API C# para analisar JSON para WMF sem usar dependências de terceiros" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total for .NET](https://products.aspose.com/total/net/) você pode analisar JSON para WMF dentro de qualquer aplicativo .NET, C#, ASP.NET e VB.NET em duas simples degraus. Em primeiro lugar, usando [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), você pode exportar JSON para JPEG. Depois disso, usando [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/), você pode converter JPEG em WMF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter o formato JSON para WMF via C#" %}}
1. Crie um novo objeto [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) e leia os dados JSON do arquivo
2. Converta JSON para JPEG usando o método [Salvar](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
3. Carregue o documento JPEG usando a classe [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Salve o documento no formato WMF usando o método [Salvar](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "parse-json-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
C#
{{% blocks/products/pf/feature-page-section  h2="Defina o layout e converta o formato JSON para WMF via C#" %}}
Ao analisar JSON para WMF, você também pode definir opções de layout para seu JSON usando [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayouttoptions). Ele permite que você processe Array como uma tabela, ignore nulos, ignore título de array, ignore título de objeto, converta string em número ou data, defina data e formato de número e defina estilo de título. Todas essas opções permitem que você apresente seus dados conforme suas necessidades. O trecho de código a seguir mostra como definir as opções de layout.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "set-layout-and-parse-json-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Analisar o formato JSON para WMF com marca d'água" %}}
Usando a API, você também pode converter JSON em WMF com marca d'água em seu documento WMF. Para adicionar uma marca d'água, você pode primeiro renderizar seu documento JSON para JPEG e adicionar uma marca d'água nele. Para demonstrar a operação, você pode carregar sua imagem JPEG convertida, adicionar transformações usando um objeto da classe Matrix e desenhar uma string como marca d'água na superfície da imagem usando o [Graphics](https://reference.aspose.com/imaging/ net/aspose.imaging/graphics) método [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring). Depois de adicionar a marca d'água, você pode salvar o JPEG como formato WMF. Abaixo está um exemplo de código que demonstra como adicionar uma marca d'água diagonal ao seu documento. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "convert-json-to-image-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}