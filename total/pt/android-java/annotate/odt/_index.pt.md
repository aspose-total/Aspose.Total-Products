---
title: Remova a anotação ODT on-line ou gerencie anotações usando aplicativos móveis Android
description: exclua comentários do arquivo ODT por meio do aplicativo online gratuitamente.Código API Android para gerenciar comentários de arquivos ODT.

family: total
platformtag: Android
feature: Annotate
informat: ODT
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Limpar comentários do documento ODT on-line ou gerenciar por meio de aplicativos Android" h2="Desenvolva um poderoso aplicativo utilitário de anotação de documentos ODT baseado em Android.Código listado para gerenciar comentários do arquivo ODT." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Remover anotações ODT online" %}}

1. Importe o arquivo ODT para excluir comentários enviando-o
1. Faça isso clicando dentro da área de soltar arrastando e soltando do aplicativo de anotação
1. Dependendo do tamanho do arquivo ODT e da velocidade da internet, aguarde alguns segundos
1. Clique no botão 'Remover' para limpar os comentários
1. Baixe o arquivo instantaneamente

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Remover comentários de documentos ODT por meio do aplicativo Android" %}}

1. Adicionar referência de biblioteca ao projeto Android
1. Carregar documento por meio do objeto da classe Document
1. Obtenha todos os comentários de todos os nós usando [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes) e NodeType.COMMENT
1. Invoque o método [clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear) para excluir todos os comentários
1. Chame o método save para salvar o arquivo.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Código: Excluir comentários do arquivo ODT" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Remover e adicionar resposta de comentário ODT" %}}

1. Adicionar referência de biblioteca ao projeto Android
1. Carregar documento por meio do objeto da classe Document
1. Obtenha comentários usando getChild
1. Use [removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment) para remover a resposta especificada a este comentário
1. Use [addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String) para adicionar qualquer resposta a este comentário
1. Chame o método save para salvar o arquivo

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Adicione comentários por meio do aplicativo Android" %}}

1. Adicionar referência de biblioteca ao projeto Android
1. Criar objeto de classe Documento
1. Use [Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/) para criar o comentário
1. Use getParagraphs().add e getFirstParagraph().getRuns().add
1. Chame o método save para salvar o arquivo with added comments

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Código: Remover e adicionar resposta de comentário do arquivo ODT" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Código: Adicionando Comentários" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Desenvolva um aplicativo Android de anotação de documentos ODT</h2>

Precisa desenvolver um aplicativo móvel ou utilitário de anotação ODT para fornecer feedback, fazer sugestões ou colaborar com outras pessoas no documento?Com [Aspose.Words for Android via Java](https://products.aspose.com/words/pt/android-java/), uma API filha do [Aspose.Total for Android via Java](https://products.aspose.com/total/pt/android-java/), qualquer desenvolvedor Android pode integrar o código API acima em seu aplicativo de anotação de documentos.A poderosa biblioteca Android permite programar qualquer solução de anotação de documentos.Além disso, pode suportar muitos formatos populares, incluindo o formato ODT.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Biblioteca Android para anotar arquivos ODT" %}}

- Hospedamos nossos pacotes Java em [Repositórios Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-words/). 
- Aspose.Words for Java é um arquivo JAR comum contendo código de bytes.
- Siga o [instruções passo a passo](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/) sobre como instalar o Aspose.Words for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

- Java SE 7 e versões Java mais recentes são suportadas.
- Pacote separado para Java SE 6 caso seja obrigado a usar JRE desatualizado.
- O pacote Java é multiplataforma e roda em todos os sistemas operacionais com implementação JVM.
- Os sistemas operacionais incluem Microsoft Windows, Linux, macOS, Android e iOS.

<br />
Para obter mais detalhes sobre dependências de pacotes opcionais, como JogAmp JOGL, mecanismo de fonte Harfbuzz, Java Advanced Imaging JAI, consulte [Documentação do produto](https://docs.aspose.com/words/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}