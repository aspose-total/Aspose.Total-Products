---
title: Converter DOCM para formato JSON via Java
description: Converta o formato DOCM para JSON via Java sem usar o Microsoft Word ou o Microsoft Excel
url: /pt/java/conversion/docm-to-json/
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
1. Abra o arquivo DOCM usando a classe [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
2. Converta DOCM para HTML usando [Salvar](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) método
3. Carregue o document HTML usando a classe [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salve o document no formato JSON usando [Salvar](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions)) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e inclua bibliotecas em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/java).
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
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras opções de conversão" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/docm-to-xlam/" name="DOCM Para XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/docm-to-xlt/" name="DOCM Para XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/docm-to-csv/" name="DOCM Para CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/docm-to-xlsx/" name="DOCM Para XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/docm-to-fods/" name="DOCM Para FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/docm-to-xltm/" name="DOCM Para XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/docm-to-xlsm/" name="DOCM Para XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/docm-to-xltx/" name="DOCM Para XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/docm-to-ods/" name="DOCM Para ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/docm-to-xlsb/" name="DOCM Para XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/docm-to-excel/" name="DOCM Para EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/docm-to-sxc/" name="DOCM Para SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/docm-to-tsv/" name="DOCM Para TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/docm-to-dif/" name="DOCM Para DIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}