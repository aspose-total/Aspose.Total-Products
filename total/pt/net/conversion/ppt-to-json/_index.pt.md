---
title: Converter formato PPT para JSON via .NET
description: Converter PPT para JSON em C# sem usar o Microsoft Excel ou Powerpoint
url_ignore: /pt/net/conversion/ppt-to-json/
family: total
platformtag: net
feature: conversion
informat: PPT
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converter PPT para formato JSON via C#" h2="Exporte PPT para JSON via C# sem usar o Microsoft<sup>&reg;</sup> Excel ou PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total for .NET](https://products.aspose.com/total/net/) você pode converter PPT para formato JSON em qualquer aplicativo .NET, C#, ASP.NET e VB.NET em dois passos simples. Em primeiro lugar, usando [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), você pode exportar PPT para HTML. Depois disso, usando a API de programação de planilha [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), você pode converter HTML em JSON.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter PPT para formato JSON via C#" %}}
1. Abra o arquivo PPT usando a classe [Apresentação](https://reference.aspose.com/slides/net/aspose.slides/presentation)
2. Converta PPT para HTML usando o método [Salvar](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
3. Carregue o documento HTML usando a classe [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Salve o documento no formato JSON usando o método [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Converter PPT Protegido para o Formato JSON via C#" %}}
Usando a API, você também pode abrir o documento protegido por senha. Se o documento PPT de entrada estiver protegido por senha, você não poderá convertê-lo para o formato JSON sem usar a senha. A API permite que você abra o documento criptografado passando a senha correta em um objeto LoadOptions. O exemplo de código a seguir mostra como abrir um documento criptografado com uma senha.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-protected-powerpoint-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}C#

{{% blocks/products/pf/feature-page-section  h2="Converter PPT para JSON no intervalo via C#" %}}
Ao converter PPT para JSON, você também pode definir o intervalo para o formato JSON de saída. Para definir o intervalo, você pode abrir o HTML convertido usando a classe Workbook, obter CellsCollection da planilha que contém os dados, criar um intervalo de CellsCollection especificando índices de linha e coluna e chamar o método ExportRangeToJson com referências aos objetos Range & ExportRangeToJsonOptions. Por fim, você pode salvar os dados JSON em um arquivo por meio do método File.WriteAllText. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}