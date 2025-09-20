---
title: Converter o formato JSON para CHM via Java
description: Analisar JSON para CHM em Java sem usar o Microsoft Word
url_ignore: /pt/java/conversion/json-to-chm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: CHM
otherformats: FLATOPC DOCM WORD WORDML ODT RTF DOC MOBI OTT DOTX PCL DOT EPUB PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converter o formato JSON para CHM via Java" h2="API Java no local para analisar JSON para CHM sem usar o Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Ao usar [Aspose.Total for Java](https://products.aspose.com/total/java/), você pode converter JSON para CHM em seus aplicativos Java em um processo de duas etapas. Em primeiro lugar, usando [Aspose.Cells for Java](https://products.aspose.com/cells/java/) você pode analisar JSON para PDF. Na segunda etapa, você pode converter PDF para CHM usando a API de processamento de texto [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter o formato JSON para CHM via Java" %}}
1. Crie um novo objeto [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) e leia dados JSON válidos do arquivo
2. Importe o arquivo JSON para a planilha usando a classe [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) e [Salvar](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) como PDF
3. Carregue o documento PDF usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Salve o documento no formato CHM usando [Salvar](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) método
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
Além disso, a API permite definir opções de layout para seu JSON ao analisar JSON para CHM usando [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayouttoptions). Ele permite que você processe Array como uma tabela, ignore nulos, ignore título de array, ignore título de objeto, converta string em número ou data, defina data e formato de número e defina estilo de título. Todas essas opções permitem que você apresente seus dados conforme suas necessidades. O trecho de código a seguir mostra como definir as opções de layout.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Definir layout e converter o formato JSON para CHM via Java" %}}
Usando a API, você também pode analisar JSON para CHM com marca d'água. Para adicionar uma marca d'água ao seu documento CHM, você pode primeiro converter o arquivo JSON em PDF e adicionar uma marca d'água a ele. Para adicionar uma marca d'água, carregue o arquivo PDF recém-criado usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), crie uma instância de TextWatermarkOptions e defina suas propriedades, chame o método Watermark.setText e passe o texto da marca d'água e o objeto de TextWatermarkOptions. Depois de adicionar a marca d'água, você pode salvar o documento no CHM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Converter **JSON para CHM (Ajuda HTML Compilada)** é essencial para construir **manuais de ajuda compilados** diretamente a partir de documentação estruturada. Arquivos CHM combinam vários tópicos de ajuda em um recurso único, pesquisável e acessível offline, tornando-os ideais para suporte de software e gerenciamento de conhecimento empresarial. Ao transformar JSON em CHM, organizações podem otimizar a entrega de documentação, melhorar a usabilidade e garantir acessibilidade mesmo sem conexão com a internet.

{{% blocks/products/pf/agp/feature-section-col title="Principais Casos de Uso" %}}

- **Documentação de software** – Empacote guias técnicos em um formato compilado e amigável ao usuário.
- **Sistemas de ajuda offline** – Entregue documentação sem necessidade de acesso à internet.
- **Bases de conhecimento empresarial** – Centralize o conhecimento organizacional em um arquivo de ajuda estruturado.
- **Manuais de treinamento** – Distribua recursos de aprendizado compilados para funcionários ou alunos.
- **Referências de API de desenvolvedor** – Converta definições JSON estruturadas em referências offline pesquisáveis.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Cenários de Automação" %}}

- **Pipelines de JSON para CHM** – Automatize a conversão de dados estruturados em manuais de ajuda compilados.
- **Criação automatizada de arquivos de ajuda** – Gere arquivos CHM diretamente a partir de conteúdo baseado em JSON em evolução.
- **Compilação de dados para documentação** – Transforme documentação JSON estruturada em sistemas de ajuda acessíveis.
- **Distribuição de conhecimento offline** – Padronize manuais CHM para treinamento e suporte em toda a empresa.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}