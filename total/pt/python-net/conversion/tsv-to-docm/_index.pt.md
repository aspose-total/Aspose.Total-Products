---
title: Converter TSV para DOCM usando Python
description: Conversão de TSV para DOCM em seus aplicativos Python sem usar o Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: TSV
outformat: DOCM
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converter TSV para DOCM via Python" h2="Conversão de TSV para DOCM em seus aplicativos Python sem instalar o Microsoft Excel<sup>&reg;</sup> ou Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

Para um desenvolvedor Python, que está tentando adicionar um recurso de conversão de TSV para DOCM no aplicativo. A API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) pode ajudar a automatizar o processo de conversão. É um pacote completo de várias APIs que lidam com diferentes formatos, incluindo arquivos TSV e DOCM.

É principalmente em duas etapas. Em primeiro lugar, use a API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) para converter o arquivo TSV em HTML. Depois disso, usando o Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/), salve o HTML criado no formato Microsoft Word desejado. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Como converter TSV para DOCM em Python" %}}
- **Passo 1** Abra o arquivo TSV de origem usando a classe Workbook
- Salve o arquivo TSV em HTML usando o método save(file, SaveFormat.HTML), fornecendo o nome do arquivo e o caminho do diretório desejado
-  **Passo 2** Carregar arquivo HTML com uma instância da classe [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
-  Chame o método `save` ao especificar o caminho do arquivo DOCM de saída. Portanto, seu arquivo TSV é convertido em DOCM no caminho especificado

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}

- Para conversão de TSV para DOCM, Python 3.5 ou posterior é necessário
- APIs de referência dentro do projeto diretamente do PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) e [Aspose.Words](https://pypi.org/project/aspose-words/))
-  Ou use os seguintes comandos pip ```pip install aspose-cells-python``` e ```pip install aspose.words```
-  Além disso, o sistema operacional baseado em Microsoft Windows ou Linux (consulte mais para [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) e [Words](https://docs.aspose.com/words/python-net/system-requirements/)) e para Linux verifique os requisitos adicionais para gcc e libpython e siga [instruções passo a passo](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Salvar TSV em HTML em Python - Etapa 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Salvar HTML em DOCM em Python - Etapa 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}