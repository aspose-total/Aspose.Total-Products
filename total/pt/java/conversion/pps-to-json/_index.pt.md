---
title: Converter PPS para o formato JSON via Java
description: Converta o formato PPS para JSON via Java sem usar o Microsoft Excel ou PowerPoint
url_ignore: /pt/java/conversion/pps-to-json/
family: total
platformtag: net
feature: conversion
informat: PPS
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converter PPS para o formato JSON via Java" h2="API Java no local para exportar PPS para JSON sem usar o Microsoft<sup>&reg;</sup> Excel ou PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
Converter o formato PPS para JSON via [Aspose.Total for Java](https://products.aspose.com/total/java/) é um processo simples de duas etapas. Na primeira etapa, você pode exportar PPS para HTML usando [Aspose.Slides for Java](https://products.aspose.com/slides/java/). Em segundo lugar, usando [Aspose.Cells for Java](https://products.aspose.com/cells/java/), você pode converter HTML em JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter PPS para o formato JSON via Java" %}}
1. Abra o arquivo PPS usando a classe [Apresentação](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Converta PPS em HTML usando [salvar](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) método
3. Carregue o documento HTML usando a classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salve o documento no formato JSON usando [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://releases.aspose.com/total/java/) e inclua bibliotecas em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversão" %}}
Usando a API, você também pode abrir o documento protegido por senha. Se o documento PPS de entrada estiver protegido por senha, você não poderá convertê-lo para o formato JSON sem usar a senha. A API permite que você abra o documento criptografado passando a senha correta em um objeto LoadOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converter PPS Protegido para o Formato JSON via Java" %}}
Ao converter PPS para JSON, você também pode definir o intervalo para o formato JSON de saída. Para definir o intervalo, você pode abrir o HTML convertido usando a classe Workbook, criar um intervalo de dados a ser exportado usando o método Cells.createRange, chamar o método JsonUtility.exportRangeToJson com referências de Range & ExportRangeToJsonOptions e gravar dados JSON de string no arquivo via Método BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}

Converter arquivos PPS (PowerPoint Slide Show) para JSON (JavaScript Object Notation) permite que os dados da apresentação sejam representados como objetos estruturados e legíveis por máquina. Isso é ideal para desenvolvedores web, engenheiros de dados e sistemas de IA que utilizam formatos de dados estruturados.

{{% blocks/products/pf/agp/feature-section-col title="Principais Casos de Uso" %}}

* Exportar metadados e conteúdo de texto do PowerPoint para JSON para APIs.
* Transformar dados de slides em objetos estruturados para painéis web.
* Criar conjuntos de dados JSON a partir de slides educacionais ou de pesquisa.
* Integrar análises do PowerPoint em frameworks de visualização de dados.
  {{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Cenários de Automação" %}}

* Análise automatizada de slides em JSON para sistemas de gestão do conhecimento.
* Exportações programadas em JSON para relatórios de dados baseados na web.
* Integração em bancos de dados NoSQL que armazenam conteúdo de apresentações estruturadas.
* Conversão em lote de PPS para JSON para treinamento de IA e pipelines de PNL.
  {{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}