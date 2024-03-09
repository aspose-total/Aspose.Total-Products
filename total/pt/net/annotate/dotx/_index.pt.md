---
title: Remova a anotação DOTX online ou gerencie anotações via .NET
description: exclua comentários do arquivo DOTX por meio do aplicativo online gratuitamente.Código API .NET para gerenciar comentários de arquivos DOTX.

family: total
platformtag: net
feature: Annotate
informat: DOTX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Limpar comentários do documento DOTX online ou gerenciar via .NET" h2="Desenvolva um poderoso aplicativo utilitário de anotação de documentos DOTX baseado em .NET.Código listado para gerenciar comentários do arquivo DOTX através do .NET." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Remover anotações DOTX online" %}}

1. Importe o arquivo DOTX para excluir comentários enviando-o
1. Faça isso clicando dentro da área de soltar arrastando e soltando do aplicativo de anotação
1. Dependendo do tamanho do arquivo DOTX e da velocidade da internet, aguarde alguns segundos
1. Clique no botão 'Remover' para limpar os comentários
1. Baixe o arquivo instantaneamente

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Excluir comentários de documentos DOTX de autores específicos via .NET" %}}

1. Adicionar referência de biblioteca ao projeto .NET
1. Carregar documento por meio do objeto da classe Document
1. Obtenha comentários de todos os nós usando GetChildNodes com NodeType.Comment
1. Iterar todos os comentários e combinar o nome do autor
1. Chame o método Remove para excluir o comentário específico do autor

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Código C#: excluir comentários específicos do autor do arquivo DOTX" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "remove-comments-of-a-specific-author-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Adicione comentários via .NET" %}}

1. Criar objeto de classe Documento
1. Use a classe Comentário
1. Adicione o novo parágrafo usando Paragraphs.Add
1. Use FirstParagraph.Runs.Add e adicione o comentário
1. Ou a outra forma é usar as classes CommentRangeStart e CommentRangeEnd
1. Chame o método save para salvar o arquivo com comentários adicionados

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Extraia todos os comentários" %}}

1. Carregar documento por meio do objeto da classe Document
1. Crie um objeto ArrayList
1. Obtenha todos os GetChildNodes em NodeCollection
1. Iterar cada coleção e adicionar comentários em ArrayList

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Código .NET: Adicionar comentário do arquivo DOTX" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "add-comments-in-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C# Code: Extraia todos os comentários" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "extract-all-comments-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Desenvolva aplicativo de anotação de documentos DOTX via .NET</h2>

Precisa desenvolver um aplicativo ou utilitário de anotação DOTX para fornecer feedback, fazer sugestões ou colaborar com outras pessoas no documento?Com o [Aspose.Words for .NET](https://products.aspose.com/words/net/), uma API filha do [Aspose.Total for .NET](https://products.aspose.com/total/net/), qualquer desenvolvedor .NET pode integrar o código da API acima em seu aplicativo de anotação de documentos.A poderosa biblioteca .NET permite programar qualquer solução de anotação de documentos.Além disso, pode suportar muitos formatos populares, incluindo o formato DOTX.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Biblioteca .NET para anotar arquivos DOTX" %}}

Existem três opções alternativas para instalar “Aspose.Words for .NET” ou “Aspose.Total for .NET” em seu sistema.Escolha um que se adeque às suas necessidades e siga as instruções passo a passo:<br /><br />

- Instale um [Pacote NuGet](https://www.nuget.org/packages/Aspose.Words/). Veja [Documentação](https://docs.aspose.com/words/net/installation/#install-or-update-aspose-words-for-net-using-nuget)
- Instale a biblioteca usando [Console do gerenciador de pacotes](https://docs.aspose.com/words/net/installation/#install-or-update-asposewords-using-package-manager-console) no Visual Studio IDE
- Instale a biblioteca manualmente usando [instalador do Windows](https://docs.aspose.com/words/net/installation/#install-asposewords-for-net-using-installer)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

Nosso produto é totalmente multiplataforma e suporta todas as principais implementações .NET seguindo a especificação '.NET Standard 2.0':<br /><br />

- Microsoft .NET Framework, começando com a versão 2.0 mais antiga e terminando com o '.NET Framework 4.8' mais recente
- .NET Core, começando com o primeiro 2.0 e terminando com o mais recente '.NET 6'
- Mono >= 2.6.7
<br /><br />
Como o código .NET não depende do hardware ou sistema operacional subjacente, mas apenas de uma máquina virtual, você está livre para desenvolver qualquer tipo de software para Windows, macOS, Android, iOS e Linux.Apenas certifique-se de ter instalado a versão correspondente do .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin.<br /><br />
Recomendamos usar Microsoft Visual Studio, Xamarin e MonoDevelop IDE para criar aplicativos C#, F#, VB.NET.
<br /><br />
Para mais detalhes, consulte [Documentação do produto](https://docs.aspose.com/words/net/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="Perguntas frequentes" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Perguntas frequentes</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Posso usar o código .NET acima em meu aplicativo?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Sim, você pode baixar este código e utilizá-lo para desenvolver um aplicativo de anotação de documentos baseado em .NET.Este código pode servir como um recurso valioso para aprimorar a funcionalidade e os recursos de seus projetos no domínio de processamento e manipulação de documentos backend.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Este aplicativo de anotação de documentos online funciona apenas no Windows?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Você tem a flexibilidade de iniciar a anotação do documento para remoção de comentários em qualquer dispositivo, independentemente do sistema operacional em que ele é executado, seja Windows, Linux, Mac OS ou Android.Tudo o que é necessário é um navegador contemporâneo e uma conexão ativa com a Internet.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>É seguro usar o aplicativo online para anotar documentos DOTX?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Claro! Os arquivos de saída gerados por meio de nosso serviço serão removidos de forma segura e automática de nossos servidores dentro de um prazo de 24 horas.Como resultado, os links de exibição associados a esses arquivos deixarão de funcionar após esse período.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Qual navegador deve usar o aplicativo?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Você pode usar qualquer navegador moderno como Google Chrome, Firefox, Opera ou Safari para anotações online de documentos DOTX.No entanto, se você estiver desenvolvendo um aplicativo de desktop, recomendamos usar a API de processamento de documentos Aspose.Total para um gerenciamento eficiente.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}