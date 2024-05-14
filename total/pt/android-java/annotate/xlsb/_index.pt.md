---
title: Remova a anotação XLSB on-line ou gerencie anotações usando aplicativos móveis Android
description: exclua comentários do arquivo XLSB por meio do aplicativo online gratuitamente.Código API Android para gerenciar comentários de arquivos XLSB.

family: total
platformtag: Android
feature: Annotate
informat: XLSB
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Limpar comentários do documento XLSB on-line ou gerenciar por meio de aplicativos Android" h2="Desenvolva um poderoso aplicativo utilitário de anotação de documentos XLSB baseado em Android.Código listado para gerenciar comentários do arquivo XLSB." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Remover anotações XLSB online" %}}

1. Importe o arquivo XLSB para excluir comentários enviando-o
1. Faça isso clicando dentro da área de soltar arrastando e soltando do aplicativo de anotação
1. Dependendo do tamanho do arquivo XLSB e da velocidade da internet, aguarde alguns segundos
1. Clique no botão 'Remover' para limpar os comentários
1. Baixe o arquivo instantaneamente

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Remover comentários de documentos XLSB por meio da API do aplicativo Android" %}}

1. Adicione referência de biblioteca ao projeto Android
1. Carregar documento por meio do objeto de classe Workbook
1. Selecione a planilha específica
1. Obtenha todos os comentários usando [getComments()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet/#getComments--)
1. Obtenha todos os comentários encadeados via getThreadedComments
1. Use removeAt para remover comentários e autores respectivamente
1. Chame o método save para salvar o arquivo
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Código: Remover comentários do documento XLSB" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Atualizar comentários XLSB encadeados" %}}

1. Carregar documento por meio do objeto de classe Workbook
1. Obtenha a planilha específica
1. Obtenha o comentário encadeado usando getComments().getThreadedComments(Index).get(Index)
1. Use o método setNotes para atualizar o comentário
1. Chame o método save para salvar o arquivo

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Adicionar comentários por meio da API do aplicativo Android" %}}

1. Criar documento por meio do objeto de classe Workbook
1. Obtenha a planilha específica
1. Adicionar índice de comentários via getComments().add
1. Use o método setNotes para adicionar comentários
1. Chame o método save para salvar o arquivo with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Código: Atualizar comentário encadeado do arquivo XLSB" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "update-threaded-comments-in-excel.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Código: Adicionando Comentários" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Desenvolva um aplicativo Android de anotação de documentos XLSB</h2>

Precisa desenvolver um aplicativo ou utilitário de anotação XLSB baseado em Android para fornecer feedback, fazer sugestões ou colaborar com outras pessoas no documento?Com [Aspose.Cells for Android via Java](https://products.aspose.com/cells/pt/android-java/), uma API filha do [Aspose.Total for Android via Java](https://products.aspose.com/total/pt/android-java/), qualquer desenvolvedor Android pode integrar o código API acima em seu aplicativo de anotação de documentos.A poderosa biblioteca Android permite programar qualquer solução de anotação de documentos.Além disso, pode suportar muitos formatos populares, incluindo o formato XLSB.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android para anotar arquivos XLSB" %}}

- Hospedamos nossos pacotes Java em [Repositórios Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-cells/). 
- Aspose.Cells for Java é um arquivo JAR comum contendo código de bytes.
- Siga o [instruções passo a passo](https://docs.aspose.com/cells/java/installation/#install-aspose-cells-for-java-from-maven-repository) sobre como instalar o Aspose.Cells for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

- SO Android 2.0 ou superior.
- O pacote Java é multiplataforma e roda em todos os sistemas operacionais com implementação JVM.

<br />
Para mais detalhes, consulte [Documentação do produto](https://docs.aspose.com/cells/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}