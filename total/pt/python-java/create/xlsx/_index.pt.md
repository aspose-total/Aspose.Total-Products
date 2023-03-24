---
title: Criar XLSX em Python
description: Gere o arquivo XLSX usando aplicativos Python sem usar o Microsoft Office. 

family: total
platformtag: Python
feature: create
informat: XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Criar XLSX usando Python" h2="Gere XLSX por meio de seus aplicativos Python sem instalar o Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Para um desenvolvedor, quem está tentando criar arquivos XLSX via aplicativo Python? A API [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) pode ajudar a automatizar o processo de criação. É um pacote completo de várias APIs que lidam com diferentes formatos, incluindo arquivos e imagens do Microsoft Office. A API [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) que faz parte do pacote [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) facilita esse processo de geração. Abaixo está o processo de criação. Além disso, os desenvolvedores podem facilmente aprimorar o aplicativo para modificação do arquivo XLSX. Para atualizar o arquivo XLSX usando o processo Python é o mesmo, exceto que requer um arquivo existente como parâmetro ao criar o objeto Workbook.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Como criar um arquivo XLSX em Python" %}}

- Crie um novo objeto de classe [Workbook](https://reference.aspose.com/cells/python/asposecells.api/Workbook) tendo ArquivoFormatType como parâmetro
- Obtenha o acesso do [Worksheet](https://reference.aspose.com/cells/python/asposecells.api/Worksheet) necessário usando o método [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets)
- Insira dados na célula acessada usando o método [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)
- Salve o documento como arquivo .xlsx usando [save()](https://reference.aspose.com/cells/python/asposecells.api/workbook#save(java.lang.String)) passando o arquivo com caminho como parâmetro

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de criação" %}}

- Para geração de XLSX, faça referência a APIs dentro do projeto diretamente do PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Ou use o seguinte comando pip ```pip install aspose.cells``` 
- Além disso, baixe o pacote de API da seção [downloads](https://releases.aspose.com/cells/python-java) 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Criar XLSX em Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}