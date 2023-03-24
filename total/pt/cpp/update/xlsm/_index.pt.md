---
title: Atualize o arquivo XLSM usando C++
description: Modifique o documento XLSM em aplicativos C++ sem usar o Microsoft Excel.
family: total
platformtag: C++
feature: update
informat: XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Atualize o arquivo XLSM via C++" h2="Modifique planilhas XLSM por meio de aplicativos baseados em C++ sem instalar o Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Para um programador que está tentando atualizar arquivos XLSM no aplicativo C++, A API [Aspose.Total for C++](https://products.aspose.com/total/cpp/) pode ajudar a automatizar o processo de atualização. É um pacote completo de diferentes bibliotecas C++ que lidam com vários formatos, incluindo documentos do Microsoft Excel. A API [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) que faz parte do pacote [Aspose.Total for C++](https://products.aspose.com/total/cpp/) facilita esse processo de modificação. O processo de atualização do documento XLSM é simples, primeiro acessando a planilha e depois atualizando o valor da célula no Excel usando C++.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Como atualizar o arquivo XLSM em C++" %}}

- Carregue o arquivo XLSM usando [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8)
- Acesso de [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) relevante usando GetIWorksheets()->GetObjectByIndex(0) e célula relevante usando GetICells()->GetObjectByIndex
- Inserir novos dados na célula acessada usando o método PutValue
- Salve o arquivo como arquivo .xlsm usando o método Save passando o arquivo com caminho como parâmetro

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de Modificação" %}}

- Para modificação XLSM, seguindo [requisitos de sistema](https://docs.aspose.com/cells/cpp/system-requirements/) para sistemas Windows e Linux 
- Instale a partir da linha de comando como ```nuget install Aspose.Total.Cpp```
- Ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```
- Como alternativa, obtenha o instalador MSI offline ou DLLs em um arquivo ZIP do [Transferências](https://releases.aspose.com/cells/cpp)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código - Atualizar arquivo XLSM em C++" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}