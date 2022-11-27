---
title: Atualizar arquivos do Excel usando Java 

description: Edite documentos XLSX, XLS, CSV do Microsoft Excel sem instalar o Microsoft Office em aplicativos baseados em Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Atualizar documentos do Excel via Java" h2="Modifique os arquivos XLSX e XLS do Microsoft Excel em aplicativos baseados em Java sem instalar o Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
É comum que a organização atualize seus dados, armazenados em arquivos Excel, como dados de alunos, registros de pacientes e lista de itens de depósito, etc., por meio do software da empresa. A API [Aspose.Total for Java](https://products.aspose.com/total/java/) fornece a funcionalidade de modificar as planilhas usando seu próprio software. Os programadores podem aprimorar o software com os recursos de modificação apenas escrevendo algumas linhas de código API. A API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) que faz parte do pacote [Aspose.Total for Java](https://products.aspose.com/total/java/) facilita esse processo de modificação. Abaixo está o processo de atualização do documento Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Atualizar documentos do Excel usando Java" %}}

A API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) fornece a classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) que lida com o carregamento de planilhas do Excel. O processo é simples. Crie o objeto de classe Workbook fornecendo o arquivo de origem como parâmetro. Acesse a planilha relevante e a célula relevante usando o método [getWorksheets().get(index).getCells().get(column)](https://reference.aspose.com/cells/java/com.aspose.cells/cells#Item%20(int)). Use o método [getCells().get(indexValue).setValue(data)](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) para modificar o conteúdo na célula acessada e finalmente chame o método save() para salvar o documento.

{{% blocks/products/pf/feature-page-code h3="Código Java - Atualizar documentos do Excel" %}}

{{< gist "aspose-com-gists" "a9643fb7de748fcd7904675f4f1b2144" "update-excel-file-via-java.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Atualizar">}}