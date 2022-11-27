---
title: Atualizar arquivos do Excel usando .NET 

description: Edite documentos XLSX, XLS, CSV do Microsoft Excel sem instalar o Microsoft Office com aplicativos baseados em C# .NET.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Atualizar documentos do Excel via .NET" h2="Modifique os arquivos XLSX e XLS do Microsoft Excel em aplicativos baseados em .NET sem instalar o Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
É comum que a organização atualize seus dados, armazenados em arquivos Excel, como dados de alunos, registros de pacientes e lista de itens de depósito, etc., por meio do software da empresa. A API [Aspose.Total for .NET](https://products.aspose.com/total/net/) fornece a funcionalidade de modificar as planilhas usando o software. Os programadores podem aprimorar o software com os recursos de modificação apenas escrevendo algumas linhas de código API. A API [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) que faz parte do pacote [Aspose.Total for .NET](https://products.aspose.com/total/net/) facilita esse processo de modificação. Abaixo está o processo de atualização do documento Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Atualizar documentos do Excel usando .NET" %}}

A API [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) fornece a classe Workbook que lida com o carregamento de planilhas do Excel. O processo é simples. Crie o objeto [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook/) fornecendo o arquivo de origem como parâmetro. Acesse a planilha relevante fornecendo seu índice usando o método [Worksheets[0].Cells[column]](https://reference.aspose.com/cells/net/aspose.cells/worksheet/cells/). Use o método [PutValue(data)](https://reference.aspose.com/cells/net/aspose.cells/cell/putvalue/) para modificar o conteúdo na célula acessada e finalmente chame o método save() para salvar o documento.

{{% blocks/products/pf/feature-page-code h3="Código .NET - Atualizar documentos do Excel" %}}

{{< gist "aspose-com-gists" "800f8b626c3129d4682bc58338b93ecc" "update-excel-file-using-net.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Atualizar">}}