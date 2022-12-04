---
title: Converter OTT para XLS usando Python
description: Conversão de OTT para XLS em seus aplicativos Python sem usar o Microsoft Word ou Excel 

family: total
platformtag: Python
feature: conversion
informat: OTT
outformat: XLS
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converter OTT para XLS via Python" h2="Conversão de OTT para XLS em seus aplicativos Python sem instalar o Microsoft Word<sup>&reg;</sup> ou Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

Para um desenvolvedor Python, que está tentando adicionar um recurso de conversão de OTT para XLS no aplicativo. A API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) pode ajudar a automatizar o processo de conversão. É um pacote completo de várias APIs que lidam com formatos diferentes.

É principalmente em duas etapas. Em primeiro lugar, use a API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) para converter o arquivo OTT em HTML. Depois disso, usando o Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), salve o HTML criado no formato desejado do Microsoft Excel. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Como converter OTT para XLS em Python" %}}
- **Etapa 1** Abra o arquivo OTT de origem usando a classe [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Salve o arquivo OTT em HTML usando o método [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/), fornecendo o nome do arquivo e o caminho do diretório desejado
-  **Etapa 2** Carregar arquivo HTML com uma instância da classe Workbook com arquivo e LoadOptions como parâmetros
-  Chame o método `save` ao especificar o caminho do arquivo XLS de saída. Portanto, seu arquivo OTT é convertido em XLS no caminho especificado

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}

- Para conversão de OTT para XLS, Python 3.5 ou posterior é necessário
- APIs de referência dentro do projeto diretamente do PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) e [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Ou use os seguintes comandos pip ```pip install aspose.words``` e ```pip install aspose-cells-python``` 
-  Além disso, o sistema operacional baseado em Microsoft Windows ou Linux (consulte mais para [Words](https://docs.aspose.com/words/python-net/system-requirements/) e [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation)) e para Linux verifique os requisitos adicionais para gcc e libpython e siga [instruções passo a passo](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Salvar OTT em HTML em Python - Etapa 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Salvar HTML em XLS em Python - Etapa 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}