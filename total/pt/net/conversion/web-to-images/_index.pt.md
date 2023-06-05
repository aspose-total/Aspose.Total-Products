---
title: Converter páginas da Web HTML em imagens usando C #
description: Raspe as páginas da web do site e exporte HTML para Imagens. Desenvolva aplicativos .NET para extrair dados de sites em JPEG, PNG, GIF, BMP, etc. 
family: total
platformtag: net
feature: conversion
informat: WEB
outformat: IMAGE
otherformats: WORD EXCEL POWERPOINT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converter páginas da Web em imagens via C #" h2="Extraia dados do site de páginas da web em HTML. Converta HTML em imagens JPG, GIF, PNG, BMP em aplicativos .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">Por que converter páginas da Web em imagens?</h2>
<p>A conversão de páginas da Web em imagens pode ser útil em várias situações. É um requisito comum para muitas aplicações. Em alguns cenários, é necessário capturar toda a página da web como uma imagem, incluindo as partes que não são visíveis na tela. Isso pode ser útil para gerar visualizações de sites, capturar recibos e faturas ou arquivar páginas da Web para fins legais. Ele pode ser usado para criar capturas de tela de páginas da Web para fins de documentação ou teste. Também pode ser usado para criar miniaturas ou visualizações de páginas da Web para uso em resultados de pesquisa ou galerias de imagens. Esteja você criando um aplicativo de área de trabalho ou um aplicativo da Web, há muitas opções disponíveis para converter páginas da Web em imagens usando C#.</p><br />

<p>A conversão de páginas da Web em imagens usando C# pode fornecer vários benefícios, incluindo:</p><br />
<ul>
<li>Acessibilidade melhorada: As imagens podem ser mais fáceis de ler e entender para pessoas com deficiência visual ou outras deficiências.</li>
<li>Maior portabilidade: As imagens podem ser facilmente compartilhadas ou incorporadas em outros documentos ou aplicativos.</li>
</ul>
<p>A conversão de páginas da Web em imagens usando C# também pode apresentar alguns desafios, incluindo:</p><br />
<ul>
<li>Suporte de formato limitado: Algumas APIs ou ferramentas podem não oferecer suporte a todos os formatos de imagem ou podem ter limitações no tamanho ou resolução das imagens de saída.</li>
<li>Problemas de compatibilidade: Algumas páginas da Web podem não ser renderizadas corretamente em todos os navegadores ou podem exigir configurações ou plug-ins específicos para serem exibidos corretamente.</li>
</ul>
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Como converter páginas da Web em imagens usando c#?" %}}
Para converter páginas da Web em imagens usando C#, você pode usar uma API Aspose.HTML para .NET que fornece essa funcionalidade para converter páginas HTML em formatos de imagem, incluindo JPEG, PNG e TIFF.</p>

1. Carregue um documento HTML usando um dos construtores disponíveis em [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/). Você pode carregar HTML de um arquivo, código HTML, um fluxo ou um URL.
2. Crie uma nova instância de [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) e defina a propriedade ImageFormat como JPEG. Por padrão, a propriedade Format é definida como PNG.
3. Utilize o [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) método da classe Converter para salvar o documento HTML como um arquivo JPEG. Você precisará fornecer HTMLDocument, ImageSaveOptions e o caminho do arquivo de saída como parâmetros para o método ConvertHTML().
4. O arquivo JPEG resultante será salvo no caminho de arquivo especificado.
 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Web Scrapping e requisitos de conversão de imagem" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou instale diretamente do Console do Gerenciador de Pacotes do Visual Studio.

Dois [Aspose.Total for .NET](https://products.aspose.com/total/net/) API filho, [Aspose.HTML for .NET](https://products.aspose.com/html/net/) será integrado.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "convert-web-pages-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}