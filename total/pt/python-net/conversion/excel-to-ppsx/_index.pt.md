---
title: Converter EXCEL para PPSX usando Python
description: Conversão de EXCEL para PPSX em seus aplicativos Python sem usar o Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: EXCEL
outformat: PPSX
otherformats: PowerPoint PPT PPTX PPS POT PPSX PPTM PPSM POTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converter EXCEL para PPSX via Python" h2="Conversão de EXCEL para PPSX em seus aplicativos Python sem instalar o Microsoft Excel<sup>&reg;</sup> ou PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Para um desenvolvedor Python, que está tentando adicionar um recurso de conversão de EXCEL para PPSX no aplicativo, A API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) pode ajudar a automatizar o processo de conversão. É um pacote completo de várias APIs que lidam com diferentes formatos, incluindo arquivos EXCEL e PPSX.

É principalmente em duas etapas. Em primeiro lugar, use a API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) para converter o arquivo EXCEL em PDF. Depois disso, usando o PowerPoint Python API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/), salve o PDF criado no formato desejado do Microsoft PowerPoint. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Como converter EXCEL para PPSX em Python" %}}
- **Passo 1** Use a instância da classe Workbook para abrir o arquivo EXCEL de origem 
- Salve o arquivo EXCEL em PDF usando o método save, fornecendo o nome do arquivo e o caminho do diretório desejado
-  **Passo 2** Carregar arquivo PDF usando a classe [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)
-  Chame o método [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) ao especificar o caminho do arquivo PPSX de saída. Portanto, seu arquivo EXCEL é convertido em PPSX no caminho especificado

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}

- Para conversão de EXCEL para PPSX, Python 3.5 ou posterior é necessário
- APIs de referência dentro do projeto diretamente do PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) e [Aspose.Slides](https://pypi.org/project/Aspose.Slides/))
-  Ou use os seguintes comandos pip ```pip install aspose-cells-python``` e ```pip install aspose.slides```
-  Além disso, SO baseado em Microsoft Windows ou Linux (veja mais sobre [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) e [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Salvar EXCEL em PDF em Python - Etapa 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "convert-microsoft-excel-file-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Salvar PDF em PPSX em Python - Etapa 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "pdf-documents-to-powerpoint-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}