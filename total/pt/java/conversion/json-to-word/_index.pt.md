---
title: Converter o formato JSON para WORD via Java
description: Analisar JSON para WORD em Java sem usar o Microsoft Word
url_ignore: /pt/java/conversion/json-to-word/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: WORD
otherformats: EPUB PCL WORDML WORD RTF MOBI DOT ODT PS FLATOPC DOTX OTT DOCM DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converter o formato JSON para WORD via Java" h2="API Java no local para analisar JSON para WORD sem usar o Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Ao usar [Aspose.Total for Java](https://products.aspose.com/total/java/), você pode converter JSON para WORD em seus aplicativos Java em um processo de duas etapas. Em primeiro lugar, usando [Aspose.Cells for Java](https://products.aspose.com/cells/java/) você pode analisar JSON para PDF. Na segunda etapa, você pode converter PDF para WORD usando a API de processamento de texto [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter o formato JSON para WORD via Java" %}}
1. Crie um novo objeto [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) e leia dados JSON válidos do arquivo
2. Importe o arquivo JSON para a planilha usando a classe [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) e [Salvar](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) como PDF
3. Carregue o documento PDF usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Salve o documento no formato WORD usando [Salvar](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://releases.aspose.com/total/java/) e inclua bibliotecas em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversão" %}}
Além disso, a API permite definir opções de layout para seu JSON ao analisar JSON para WORD usando [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayouttoptions). Ele permite que você processe Array como uma tabela, ignore nulos, ignore título de array, ignore título de objeto, converta string em número ou data, defina data e formato de número e defina estilo de título. Todas essas opções permitem que você apresente seus dados conforme suas necessidades. O trecho de código a seguir mostra como definir as opções de layout.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Definir layout e converter o formato JSON para WORD via Java" %}}
Usando a API, você também pode analisar JSON para WORD com marca d'água. Para adicionar uma marca d'água ao seu documento WORD, você pode primeiro converter o arquivo JSON em PDF e adicionar uma marca d'água a ele. Para adicionar uma marca d'água, carregue o arquivo PDF recém-criado usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), crie uma instância de TextWatermarkOptions e defina suas propriedades, chame o método Watermark.setText e passe o texto da marca d'água e o objeto de TextWatermarkOptions. Depois de adicionar a marca d'água, você pode salvar o documento no WORD. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Converter **JSON para WORD** é essencial para transformar **conjuntos de dados estruturados em documentos editáveis no Microsoft Word**. Arquivos do Word permitem que organizações produzam documentos totalmente editáveis, padronizados e formatados profissionalmente diretamente a partir de dados estruturados. Ao converter JSON em Word, as empresas podem otimizar a geração de relatórios, documentação jurídica, criação de conteúdo acadêmico e gerenciamento de registros governamentais de forma eficiente.

{{% blocks/products/pf/agp/feature-section-col title="Principais Casos de Uso" %}}

- **Relatórios empresariais** – Gerar relatórios estruturados e editáveis para tomada de decisões corporativas.
- **Contratos jurídicos** – Automatizar a criação de acordos e contratos padronizados.
- **Documentos acadêmicos** – Produzir trabalhos de pesquisa, ensaios e notas de aula a partir de conjuntos de dados estruturados.
- **Registros governamentais** – Manter documentação editável pronta para conformidade para uso oficial.
- **Documentação empresarial** – Padronizar documentos corporativos para fluxos de trabalho internos e externos.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Cenários de Automação" %}}

- **Pipelines de JSON para Word** – Automatizar a transformação de dados estruturados em documentos do Word.
- **Geração automatizada de documentos** – Reduzir a criação manual de conteúdo enquanto garante consistência de formatação.
- **Fluxos de trabalho de relatórios em toda a empresa** – Escalar a produção de documentos entre departamentos de forma eficiente.
- **Criação de conteúdo orientada por JSON** – Preencher documentos do Word diretamente a partir de conjuntos de dados estruturados para precisão e velocidade.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}