---
title: Atualizar arquivo XLS usando Python
description: Modifique o documento XLS em aplicativos Python sem usar o Microsoft Excel. 

family: total
platformtag: Python
feature: update
informat: XLS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Atualizar arquivo XLS via Python" h2="Modifique planilhas XLS por meio de seus aplicativos Python sem instalar o Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Para um desenvolvedor, quem está tentando atualizar arquivos XLS por meio do aplicativo Python? A API [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) pode ajudar a automatizar o processo de atualização. É um pacote completo de várias APIs que lidam com diferentes formatos, incluindo arquivos do Microsoft Excel. A API ASPOSE.CELL que faz parte do pacote [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) facilita esse processo de modificação. Abaixo está o processo de atualização do documento XLS.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Como atualizar o arquivo XLS em Python" %}}

- Crie um novo objeto de classe [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) tendo o arquivo XLS de origem como parâmetro
- Acesso da planilha relevante usando o método [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets)
- Insira novos dados na célula acessada usando o método [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)
- Salve o arquivo como arquivo .xls usando o método save() passando o arquivo com caminho como parâmetro

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de modificação" %}}

- Para modificação de XLS, faça referência a APIs dentro do projeto diretamente do PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Ou use o seguinte comando pip ```pip install aspose.cells``` 
- Além disso, baixe o pacote de API da seção [Transferências](https://releases.aspose.com/cells/python-java)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código - Atualizar arquivo XLS em Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}