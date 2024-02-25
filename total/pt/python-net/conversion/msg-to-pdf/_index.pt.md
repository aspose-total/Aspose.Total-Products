---
title: Converter MSG para PDF em Python
description: Salve MSG para PDF em seus aplicativos Python sem usar o Microsoft Outlook ou Word 

family: total
platformtag: Python
feature: conversion
informat: MSG
outformat: PDF
otherformats: DOC DOCM DOCX DOT DOTM DOTX EMF EPUB FLATOPC MD ODT OTT PCL PDF PS RTF TEXT WORD WORDML BMP GIF IMAGE JPEG TIFF PNG SVG XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converter MSG para PDF usando Python" h2="Conversão de MSG para PDF em seus aplicativos Python sem instalar o Microsoft Word<sup>&reg;</sup> ou Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}

Para um desenvolvedor Python, quem está tentando adicionar um recurso de conversão MSG para PDF no aplicativo? A API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) pode ajudar a automatizar o processo de conversão. É um pacote completo de várias APIs que lidam com diferentes formatos, incluindo e-mail, imagens e formatos do Microsoft Word. As APIs [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) e [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) que fazem parte do pacote [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) facilitam essa conversão usando Python. É um processo de duas etapas, primeiro carregue o e-mail e o renderize em HTML via [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/). Em segundo lugar, carregue o HTML convertido usando [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) e salve-o no formato PDF.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Como converter MSG para PDF em Python" %}}

- Abra o arquivo MSG de origem usando a classe MailMessage.load
- Chame o método `save` enquanto especifica o caminho do arquivo HTML de saída e as opções relevantes de Salvar HTML como parâmetro. Portanto, seu arquivo MSG é convertido em HTML no caminho especificado
- Agora carregue o arquivo HTML salvo usando [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Chame o método save com o caminho de arquivo relevante. Então, finalmente, o MSG é convertido

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}

- Para conversão de MSG para PDF, é necessário o Python 3.5 ou posterior
- APIs de referência dentro do projeto diretamente do PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) e [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Ou use o seguinte comando pip ```pip install aspose.words``` e ```pip install Aspose.Email-for-Python-via-NET``` 
- Além disso, o sistema operacional baseado em Microsoft Windows ou Linux (veja mais para [Words](https://docs.aspose.com/words/python-net/system-requirements/) e [Email](https://docs.aspose.com/email/python-net/system-requirements/)) e para Linux verifique os requisitos adicionais para gcc e libpython e siga as instruções passo a passo [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Salvar MSG para PDF em Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-email-to-word-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}