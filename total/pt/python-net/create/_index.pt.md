---
title: Criar arquivo usando Python 

description: Crie texto e documentos do Microsoft Word sem instalar o Microsoft Office 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Criar documentos usando Python" h2="Crie arquivos de texto e Microsoft Word DOCX, DOC dentro de aplicativos Python sem instalar o Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Armazenar dados é o básico de qualquer aplicativo de software, dependendo da natureza do aplicativo. O local de armazenamento pode ser o banco de dados, XML, JSON, arquivos de texto, relatórios do Excel ou documentos do Microsoft Word. A E/S de arquivo é parte de qualquer linguagem e principalmente linguagens, incluindo Python, suportam a gravação de dados em arquivos de texto. Vamos considerar a linguagem Python. Escrevendo arquivos de texto existentes usando Python, ele fornece o método open, write e close para essas tarefas. Em primeiro lugar, abra o arquivo com o caminho de arquivo relevante e acrescente ou escreva o recurso como argumentos. Em seguida, escreva o texto necessário no arquivo e, por último, feche o arquivo usando o método close(). 

Para criar documentos do Microsoft Word usando Python, usamos o pacote [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) APIs que possui a API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) como parte de seu pacote. Esta API fornece solução completa de automação de documentos para faturas, relatórios e artigos técnicos. Procedimento de criação de documento do Word listado abaixo.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Como criar um arquivo de texto usando Python" %}}

Criar e gravar em arquivos de texto é simples. Python fornece o método open() com três parâmetros e tem que usar um dos parâmetros junto com o caminho do arquivo. Três parâmetros são "x", "a" e "w". Ao fornecer "x", um novo arquivo será criado, mas gera erro caso o arquivo já exista. Ao fornecer "a", será criado um novo arquivo de texto caso não exista e caso exista, o conteúdo será anexado ao final. E, por último, fornecendo "w", um novo documento de texto será criado e substituído pelo novo conteúdo, caso já exista.

{{% blocks/products/pf/feature-page-code h3="Python - Criar arquivo de texto" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-text-file-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Criar documentos do Microsoft Word" %}}

Total Python Word API tem vários recursos, incluindo a criação de arquivos do Microsoft Word, inserção de imagens e texto em documentos, adicionar tabelas e listas dentro dos arquivos, bem como modificar documentos existentes com facilidade. Para criar o processo de documento do Microsoft Word, crie o objeto das classes [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) e [DocumentBuilder](https://reference.aspose.com/words/python-net/aspose.words/documentbuilder/). Adicione o texto, parágrafo, listas e tabelas necessários dentro do documento e, finalmente, salve-o.

{{% blocks/products/pf/feature-page-code h3="Python - Criar documentos do Microsoft Word" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-word-files-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Crio">}}