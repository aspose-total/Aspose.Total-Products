---
title: Converter DOTX para formato JSON via Java
description: Converta o formato DOTX para JSON via Java sem usar o Microsoft Word ou o Microsoft Excel
url_ignore: /pt/java/conversion/dotx-to-json/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: JSON
otherformats: SXC XLSM XLSB TSV XLAM XLT DIF EXCEL XLTX CSV XLTM FODS ODS XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converter DOTX para formato JSON via Java" h2="On Premise Java API para converter DOTX para JSON sem usar o Microsoft<sup>&reg;</sup> Word ou Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
A conversão do formato DOTX para JSON via [Aspose.Total for Java](https://products.aspose.com/total/java/) é um processo simples de duas etapas. Usando a API de conversão e manipulação de Documentos rica em recursos [Aspose.Words for Java](https://products.aspose.com/words/java/), você pode exportar DOTX para HTML. Depois disso, usando [Aspose.Cells for Java](https://products.aspose.com/cells/java/), você pode converter HTML para JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter DOTX para formato JSON via Java" %}}
1. Abra o arquivo DOTX usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. Converta DOTX para HTML usando [Salvar](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) método
3. Carregue o Documento HTML usando a classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salve o Documento no formato JSON usando [Salvar](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://releases.aspose.com/total/java/) e inclua bibliotecas em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section h2="Requisitos de conversão" %}}
Usando a API, você também pode abrir o Documento protegido por senha. Se o Documento DOTX de entrada estiver protegido por senha, você não poderá convertê-lo para o formato JSON sem usar a senha. A API permite que você abra o Documento criptografado passando a senha correta em um objeto LoadOptions. O exemplo de código a seguir mostra como tentar abrir um Documento criptografado com uma senha:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converter DOTX protegido para formato JSON via Java" %}}
Ao converter DOTX para JSON, você também pode definir o intervalo para o formato JSON de saída. Para definir o intervalo, você pode abrir o HTML convertido usando a classe Workbook, criar um intervalo de dados a ser exportado usando o método Cells.createRange, chamar o método JsonUtility.exportRangeToJson com referências de Range & ExportRangeToJsonOptions e gravar dados JSON de string no arquivo via Método BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Convertendo **DOTX** para **JSON** permite a troca de dados estruturados, integração de API e fluxos de trabalho web modernos, tornando os dados do documento utilizáveis para serviços em nuvem, aplicativos web e pipelines de IA/ML.

## ✅ Principais Casos de Uso
- Exportações de dados prontas para API
- Integração de aplicativos web
- Serviços em nuvem
- Pipelines de dados
- Preparação de conjuntos de dados de IA/ML

## ⚙️ Cenários de Automação
- Pipelines de DOTX para JSON
- Geração automática de JSON
- Fluxos de trabalho de API em nuvem
- Integrações de sistemas empresariais
- Automação de data lake
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}