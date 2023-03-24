---
title: Converter XSLFO para XLSM via API C#
description: API C# para converter arquivo XSLFO em XLSM sem usar o Microsoft Excel ou Adobe Reader
url_ignore: /pt/net/conversion/xslfo-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: XLSM
otherformats: XLT FODS XLAM SXC XLTX MD ODS XLTM TXT EXCEL DIF XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API C# para renderizar XSLFO para XLSM" h2="Exporte o arquivo XSLFO para XLSM via C# sem usar o Microsoft<sup>&reg;</sup> Excel ou Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total for .NET](https://products.aspose.com/total/net/) você pode facilmente converter arquivos XSLFO para XLSM em qualquer aplicativo .NET, C#, ASP.NET e VB.NET. Em primeiro lugar, usando [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/), você pode exportar XSLFO para XLSX. Depois disso, usando [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, você pode converter XLSX para XLSM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para converter XSLFO em XLSM" %}}
1. Abra o arquivo XSLFO usando a classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Converta XSLFO para XLSX usando o método [Salvar](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Carregue o documento XLSX usando a classe [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Salve o documento no formato XLSM usando o método [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) e defina `Xlsm` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Converter XSLFO Protegido para XLSM via C#" %}}
Se o seu documento XSLFO estiver protegido por senha, você não poderá convertê-lo em XLSM sem a senha. Usando a API, você pode primeiro abrir o documento protegido usando uma senha válida e convertê-lo depois. Para abrir o arquivo criptografado, você pode inicializar uma nova instância da classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) e passar o nome do arquivo e a senha como argumentos.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}C#

{{% blocks/products/pf/feature-page-section  h2="Converter arquivo XSLFO para XLSM com marca d'água via C#" %}}
Ao converter o arquivo XSLFO para XLSM, você também pode adicionar marca d'água ao formato de arquivo XLSM de saída. Para adicionar uma marca d'água, você pode criar um novo objeto Workbook e abrir o documento XLSX convertido, selecionar Worksheet através de seu índice, criar uma Shape e usar sua função AddTextEffect. Depois disso, você pode salvar seu documento XLSX como XLSM com marca d'água. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}