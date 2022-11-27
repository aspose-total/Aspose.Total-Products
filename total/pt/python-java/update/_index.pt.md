---
title: Atualizar arquivos do Excel usando Python 

description: Edite documentos XLSX, XLS, CSV do Microsoft Excel sem instalar o Microsoft Office em aplicativos Python
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Atualizar documentos do Excel via Python" h2="Modifique os arquivos XLSX e XLS do Microsoft Excel nos aplicativos Python sem instalar o Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
É comum que a organização atualize seus dados, armazenados em arquivos Excel, como dados de alunos, prontuários de pacientes, lista de itens de almoxarifado, etc., por meio de um software da empresa. A API [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) fornece a funcionalidade de modificar as planilhas por meio do software. Os programadores podem aprimorar o software com os recursos de modificação integrando a API e escrevendo algumas linhas de código. A API [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) que faz parte do pacote [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) facilita esse processo de modificação. Abaixo está o processo de atualização do documento Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Atualizar documentos do Excel usando Python" %}}

A API [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) fornece a classe Workbook que lida com o carregamento de planilhas do Excel. O processo é simples. Crie o objeto de classe [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) fornecendo o arquivo de origem como parâmetro. Use o método [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets) para acessar a planilha relevante fornecendo seu índice. chame o método [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells) para modificar o conteúdo na célula acessada e finalmente chame o método save() para salvar o documento.

{{% blocks/products/pf/feature-page-code h3="Python - Atualizar documentos do Excel" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Atualizar">}}