---
title: Converter DOCM para formato JSON via Java
description: Converta o formato DOCM para JSON via Java sem usar o Microsoft Word ou o Microsoft Excel
url_ignore: /pt/java/conversion/docm-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: JSON
otherformats: XLT XLTM FODS SXC XLAM XLS EXCEL ODS XLSM DIF XLSB XLTX TSV CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converter DOCM para formato JSON via Java" h2="On Premise Java API para converter DOCM para JSON sem usar o Microsoft<sup>&reg;</sup> Word ou Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
A conversão do formato DOCM para JSON via [Aspose.Total for Java](https://products.aspose.com/total/java/) é um processo simples de duas etapas. Usando a API de conversão e manipulação de documents rica em recursos [Aspose.Words for Java](https://products.aspose.com/words/java/), você pode exportar DOCM para HTML. Depois disso, usando [Aspose.Cells for Java](https://products.aspose.com/cells/java/), você pode converter HTML para JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter DOCM para formato JSON via Java" %}}
1. Abra o arquivo DOCM usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. Converta DOCM para HTML usando [Salvar](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) método
3. Carregue o document HTML usando a classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salve o document no formato JSON usando [Salvar](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://releases.aspose.com/total/java/) e inclua bibliotecas em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversão" %}}
Usando a API, você também pode abrir o document protegido por senha. Se o ddocumentDOCM de entrada estiver protegido por senha, você não poderá convertê-lo para o formato JSON sem usar a senha. A API permite que você abra o dodocumentriptografado passando a senha correta em um objeto LoadOptions. O exemplo de código a seguir mostra como tentar abrir um docdocumentiptografado com uma senha:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converter DOCM protegido para formato JSON via Java" %}}
Ao converter DOCM para JSON, você também pode definir o intervalo para o formato JSON de saída. Para definir o intervalo, você pode abrir o HTML convertido usando a classe Workbook, criar um intervalo de dados a ser exportado usando o método Cells.createRange, chamar o método JsonUtility.exportRangeToJson com referências de Range & ExportRangeToJsonOptions e gravar dados JSON de string no arquivo via Método BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
## Convertendo **DOCM (Documentos Habilitados para Macros do Word)** em **JSON (Notação de Objetos JavaScript)**

É vital para transformar o conteúdo estático do documento, tabelas e campos de formulário em **dados estruturados legíveis por máquina**. O JSON é leve, legível por humanos e amplamente utilizado em **APIs, análises, aplicativos da web e fluxos de automação**. Ao extrair dados do DOCM para JSON, as organizações podem desbloquear a interoperabilidade entre plataformas modernas, possibilitar integrações mais rápidas e garantir que os dados estejam prontos para **processamento em tempo real, validação e distribuição escalável**.

## ✅ Principais Casos de Uso

- **Publicação de Dados do Documento em APIs REST/GraphQL**
  Sirva o conteúdo extraído do DOCM como JSON para consumo direto em aplicativos da web e móveis.

- **Alimentação de Bancos de Dados NoSQL e Data Lakes**
  Carregue dados estruturados derivados do DOCM no MongoDB, Elasticsearch ou data lakes baseados em nuvem.

- **Alimentando Painéis com Feeds JSON em Tempo Real**
  Transmita KPIs e métricas baseadas em documentos em painéis de BI e ferramentas de monitoramento.

- **Validação de Entradas Contra Esquema JSON**
  Garanta consistência e integridade alinhando os dados de campo do DOCM com as regras do Esquema JSON.

- **Possibilitando CMS sem Cabeça ou Arquiteturas de Microsserviços**
  Integre o conteúdo do DOCM em sistemas distribuídos, API-first, onde o JSON é a língua franca.

## ⚙️ Cenários de Automação

- **Extração DOCM para JSON com Mapeamento de Campos**
  Defina mapeamentos para transformar tabelas, cabeçalhos e campos em objetos JSON estruturados.

- **Funções sem Servidor que Convertem e Emitem Eventos JSON**
  Dispare conversões no upload de arquivos, emitindo payloads JSON para sistemas orientados a eventos.

- **Trabalhos ETL que Normalizam Tipos e Chaves**
  Padronize as exportações do DOCM em estruturas JSON consistentes para análises posteriores.

- **Webhooks que Enviem JSON para Sistemas Secundários**
  Automatize exportações de DOCM para JSON que alimentam CRMs, ferramentas ERP ou aplicativos de terceiros.

- **Regras de Governança que Removem Macros e Informações PII Antes da Exportação para JSON**
  Aplique verificações de conformidade para garantir saídas JSON seguras e sanitizadas de arquivos habilitados para macros.
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}