---
title: Remova a anotação PDF on-line ou gerencie anotações usando aplicativos móveis Android
description: exclua comentários do arquivo PDF por meio do aplicativo online gratuitamente.Código API Android para gerenciar comentários de arquivos PDF.

family: total
platformtag: Android
feature: Annotate
informat: PDF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Limpar comentários do documento PDF on-line ou gerenciar por meio de aplicativos Android" h2="Desenvolva um poderoso aplicativo utilitário de anotação de documentos PDF baseado em Android.Código listado para gerenciar comentários do arquivo PDF." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Remover anotações PDF online" %}}

1. Importe o arquivo PDF para excluir comentários enviando-o
1. Faça isso clicando dentro da área de soltar arrastando e soltando do aplicativo de anotação
1. Dependendo do tamanho do arquivo PDF e da velocidade da internet, aguarde alguns segundos
1. Clique no botão 'Remover' para limpar os comentários
1. Baixe o arquivo instantaneamente

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Remover comentários de documentos PDF por meio da API do aplicativo Android" %}}

1. Adicionar referência de biblioteca ao projeto Android
1. Carregar documento por meio do objeto da classe Document
1. Selecione a página específica via getPages().get_Item(Index)
1. Use o AnnotationSelector e obtenha todas as anotações de texto via annotationSelector.getSelected()
1. Itere através de cada anotação e chame o método delete para removê-la.
1. Chame o método save para salvar o arquivo.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Código: Excluir comentários do arquivo PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-all-pdf-page-annotation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Adicionar anotação por meio da API do aplicativo Android" %}}

1. Adicionar referência de biblioteca ao projeto Android
1. Criar objeto de classe Documento
1. Adicione a nova página e conteúdo usando getPages().add()
1. Use getPages().get_Item(Index) da classe TextAnnotation
1. Defina as anotações relevantes, como título, assunto, conteúdo, etc.
1. Use getAnnotations().add para adicionar as anotações
1. Chame o método save para salvar o arquivo com comentários adicionados
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Código: Adicionar anotação PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-annotations-to-pdf-document.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Desenvolva um aplicativo Android de anotação de documentos PDF</h2>

Precisa desenvolver um aplicativo móvel ou utilitário de anotação PDF para fornecer feedback, fazer sugestões ou colaborar com outras pessoas no documento?Com [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/pt/android-java/), uma API filha do [Aspose.Total for Android via Java](https://products.aspose.com/total/pt/android-java/), qualquer desenvolvedor Android pode integrar o código API acima em seu aplicativo de anotação de documentos.A poderosa biblioteca Android permite programar qualquer solução de anotação de documentos.Além disso, pode suportar muitos formatos populares, incluindo o formato PDF.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Biblioteca Android para anotar arquivos PDF" %}}

- Hospedamos nossos pacotes Java em [Repositórios Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-pdf/). 
- Aspose.PDF for Java é um arquivo JAR comum contendo código de bytes.
- Siga o [instruções passo a passo](https://docs.aspose.com/pdf/java/installation/#install-aspose-pdf-for-java-from-maven-repository) sobre como instalar o Aspose.PDF for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

- API Android 31 e 32
- Android 4.0 e superior
- Ferramentas Android Studio e SDK

<br />
Para obter mais detalhes sobre dependências de pacotes opcionais, como JogAmp JOGL, mecanismo de fonte Harfbuzz, Java Advanced Imaging JAI, consulte [Documentação do produto](https://docs.aspose.com/pdf/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}