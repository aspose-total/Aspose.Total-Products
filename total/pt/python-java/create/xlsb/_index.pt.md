---
title: Criar XLSB em Python
description: Gere o arquivo XLSB usando aplicativos Python sem usar o Microsoft Office. 

family: total
platformtag: Python
feature: create
informat: XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Criar XLSB usando Python" h2="Gere XLSB por meio de seus aplicativos Python sem instalar o Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Para um desenvolvedor, quem está tentando criar arquivos XLSB via aplicativo Python? A API [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) pode ajudar a automatizar o processo de criação. É um pacote completo de várias APIs que lidam com diferentes formatos, incluindo arquivos e imagens do Microsoft Office. A API [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) que faz parte do pacote [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) facilita esse processo de geração. Abaixo está o processo de criação. Além disso, os desenvolvedores podem facilmente aprimorar o aplicativo para modificação do arquivo XLSB. Para atualizar o arquivo XLSB usando o processo Python é o mesmo, exceto que requer um arquivo existente como parâmetro ao criar o objeto Workbook.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Como criar um arquivo XLSB em Python" %}}

- Crie um novo objeto de classe [Workbook](https://reference.aspose.com/cells/python/asposecells.api/Workbook) tendo ArquivoFormatType como parâmetro
- Obtenha o acesso do [Worksheet](https://reference.aspose.com/cells/python/asposecells.api/Worksheet) necessário usando o método [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets)
- Insira dados na célula acessada usando o método [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)
- Salve o documento como arquivo .xlsb usando [save()](https://reference.aspose.com/cells/python/asposecells.api/workbook#save(java.lang.String) passando o arquivo com caminho como parâmetro

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de criação" %}}

- Para geração de XLSB, faça referência a APIs dentro do projeto diretamente do PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Ou use o seguinte comando pip ```pip install aspose.cells``` 
- Além disso, baixe o pacote de API da seção [downloads](https://releases.aspose.com/cells/python-java) 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Criar XLSB em Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras opções de criação" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/python-java/create/xls/" name="Gerar XLS Arquivo" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/python-java/create/xlsx/" name="Crio XLSX Arquivo" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/python-java/create/csv/" name="Crio CSV Arquivo" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/python-java/create/xlsb/" name="Crio XLSB Arquivo" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/python-java/create/xlsm/" name="Crio XLSM Arquivo" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/python-java/create/xlt/" name="Crio XLT Arquivo" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/python-java/create/xltx/" name="Crio XLTX Arquivo" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/python-java/create/xltm/" name="Crio XLTM Arquivo" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/python-java/create/ods/" name="Crio ODS Arquivo" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/python-java/create/tsv/" name="Crio TSV Arquivo" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}