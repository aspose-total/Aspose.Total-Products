---
title: Atualizar arquivos do Excel usando C++ 

description: Edite documentos XLSX, XLS, CSV do Microsoft Excel sem instalar o Microsoft Office com aplicativos baseados em C++.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Atualizar documentos do Excel via C++" h2="Modifique os arquivos XLSX e XLS do Microsoft Excel em aplicativos baseados em C++ sem instalar o Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
É comum que a organização atualize seus dados, armazenados em arquivos Excel, como dados de alunos, registros de pacientes e lista de itens de depósito, etc., por meio do software da empresa. A API [Aspose.Total for C++](https://products.aspose.com/total/cpp/) fornece a funcionalidade de modificar as planilhas usando o software. Os programadores podem aprimorar o software com os recursos de modificação apenas escrevendo algumas linhas de código API. A API [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) que faz parte do pacote [Aspose.Total for C++](https://products.aspose.com/total/cpp/) facilita esse processo de modificação. Abaixo está o processo de atualização do documento Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Atualizar documentos do Excel usando C++" %}}

Usando a API [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), carregue o documento de origem usando [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8). Acesse o [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) usando GetIWorksheets()->GetObjectByIndex(0) e a célula necessária usando GetICells()->GetObjectByIndex. Utilizando o método PutValue, modifique o conteúdo da célula acessada. Por último, invoque o método save() para salvar o documento.

{{% blocks/products/pf/feature-page-code h3="Código C++ - Atualizar documentos do Excel" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Atualizar">}}