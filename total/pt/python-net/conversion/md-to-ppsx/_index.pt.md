---
title: Converter MD para PPSX em Python
description: Conversão de MD para PPSX em seus aplicativos Python sem usar o Microsoft Word ou PowerPoint 
url: /pt/python-net/conversion/md-to-ppsx/
family: total
platformtag: Python
feature: conversion
informat: MD
outformat: PPSX
otherformats: PowerPoint PPSX PPTX PPT POT POTX POTM PPTM PPSM PPS ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converter MD para PPSX usando Python" h2="Conversão de MD para PPSX em seus aplicativos Python sem instalar o Microsoft Word<sup>&reg;</sup> ou PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Para um desenvolvedor Python, quem está tentando adicionar um recurso de conversão MD para PPSX no aplicativo? A API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) pode ajudar a automatizar o processo de conversão. É um pacote completo de várias APIs que lidam com diferentes formatos. Então **Como converter MD para PPSX em Python?**

É principalmente em duas etapas. Em primeiro lugar, use a API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) para converter o arquivo MD em PDF. Depois disso, usando [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) da API Python do PowerPoint, salve o PDF criado na Apresentação como um formato PPSX. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter MD para PPSX em Python" %}}
- **Passo 1** Abra o arquivo MD de origem usando a classe [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Salve o arquivo MD em PDF usando o método [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) fornecendo o nome do arquivo e o caminho do diretório desejado.
-  **Passo 2** Carregar arquivo PDF com uma instância da classe [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)
-  Chame o método `save` enquanto especifica o caminho do arquivo de saída e SaveFormat.PPSX como parâmetros. Portanto, seu arquivo MD é convertido em PPSX no caminho especificado.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}

- Para conversão de MD para PPSX, é necessário o Python 3.5 ou posterior
- APIs de referência dentro do projeto diretamente do PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) e [Aspose.Words](https://pypi.org/project/aspose-words/)) ou
- Use os seguintes comandos pip ```pip install aspose.slides``` e ```pip install aspose.words```. Além disso,
- SO baseado em Microsoft Windows ou Linux (veja mais para [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) e [Words](https://docs.aspose.com/words/python-net/system-requirements/)) e para Linux verifique os requisitos adicionais para gcc e libpython e siga as instruções passo a passo [INSTALL](https://docs.aspose.com/words/python-net/installation/).
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Salvar MD em PDF em Python - Etapa 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-microsoft-word-documents-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Salvar PDF para PPSX em Python - Etapa 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-pdf-files-to-powerpoint-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}