---
title: Converter DOTX para formato JSON via .NET
description: Converter DOTX para JSON em C# sem usar o Microsoft Excel ou Adobe Reader
url_ignore: /pt/net/conversion/dotx-to-json/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: JSON
otherformats: XLT EXCEL ODS XLTM TSV XLAM SXC DIF XLS XLSB XLTX XLSX CSV FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converter DOTX para formato JSON via C#" h2="Analise DOTX para JSON via C# sem usar o Microsoft<sup>&reg;</sup> Word ou Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total for .NET](https://products.aspose.com/total/net/) você pode converter DOTX para JSON em qualquer aplicativo .NET, C#, ASP.NET e VB.NET em dois passos simples. Em primeiro lugar, usando [Aspose.Words for .NET](https://products.aspose.com/words/net/), você pode exportar DOTX para HTML. Depois disso, usando a API de programação de planilha [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), você pode converter HTML em JSON.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter DOTX para formato JSON via C#" %}}
1. Abra o arquivo DOTX usando a classe [Document](https://reference.aspose.com/words/net/aspose.words/Document)
2. Converta DOTX para HTML usando o método [Salvar](https://reference.aspose.com/words/net/aspose.words.Document/save/methods/4)
3. Carregue o Documento HTML usando a classe [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Salve o Documento no formato JSON usando o método [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Converter DOTX protegido para formato JSON via C#" %}}
Usando a API, você também pode abrir o Documento protegido por senha. Se o Documento DOTX de entrada estiver protegido por senha, você não poderá convertê-lo para o formato JSON sem usar a senha. A API permite que você abra o Documento criptografado passando a senha correta em um objeto LoadOptions. O exemplo de código a seguir mostra como tentar abrir um Documento criptografado com uma senha:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}C#

{{% blocks/products/pf/feature-page-section  h2="Converter DOTX para JSON no intervalo via C#" %}}
Ao converter DOTX para JSON, você também pode definir o intervalo para o formato JSON de saída. Para definir o intervalo, você pode abrir o HTML convertido usando a classe Workbook, obter CellsCollection da planilha que contém os dados, criar um intervalo de CellsCollection especificando índices de linha e coluna e chamar o método ExportRangeToJson com referências aos objetos Range & ExportRangeToJsonOptions. Por fim, você pode salvar os dados JSON em um arquivo por meio do método File.WriteAllText. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}