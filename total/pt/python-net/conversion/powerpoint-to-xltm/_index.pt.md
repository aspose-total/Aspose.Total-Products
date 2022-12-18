---
title: Converter POWERPOINT para XLTM usando Python
description: Conversão de POWERPOINT para XLTM em seus aplicativos Python sem usar o Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: POWERPOINT
outformat: XLTM
otherformats: Excel XLS XLSX XLSB XLTX XLTM XLSM CSV TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converter POWERPOINT para XLTM via Python" h2="Conversão de POWERPOINT para XLTM em seus aplicativos Python sem instalar o Microsoft PowerPoint<sup>&reg;</sup> ou Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

Para um desenvolvedor Python, que está tentando adicionar um recurso de conversão de POWERPOINT para XLTM no aplicativo. A API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) pode ajudar a automatizar o processo de conversão. É um pacote completo de várias APIs que lidam com diferentes formatos, incluindo arquivos POWERPOINT e XLTM.

É principalmente em duas etapas. Em primeiro lugar, use a API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) para converter o arquivo POWERPOINT em HTML. Depois disso, usando o Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), salve o HTML criado no formato desejado do Microsoft Excel. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Como converter POWERPOINT para XLTM em Python" %}}
- **Passo 1** Use a instância da classe [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) para abrir o arquivo POWERPOINT de origem 
- Salve o arquivo POWERPOINT em HTML usando o método [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/), fornecendo o nome do arquivo e o caminho do diretório desejado
-  **Passo 2** Carregar arquivo HTML com uma instância da classe Workbook
-  Chame o método `save` ao especificar o caminho do arquivo XLTM de saída. Portanto, seu arquivo POWERPOINT é convertido em XLTM no caminho especificado

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}

- Para conversão de POWERPOINT para XLTM, Python 3.5 ou posterior é necessário
- APIs de referência dentro do projeto diretamente do PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) e [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Ou use os seguintes comandos pip ```pip install aspose.slides``` e ```pip install aspose-cells-python```
-  Além disso, SO baseado em Microsoft Windows ou Linux (veja mais sobre [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) e [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Salvar POWERPOINT em HTML em Python - Etapa 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "convert-microsoft-powerpoint-presentations-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Salvar HTML em XLTM em Python - Etapa 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "html-documents-to-excel-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}