---
title: API Java para converter RTF para XLSB
description: Converta RTF para XLSB via Java sem usar o Microsoft Word ou o Microsoft Excel
url_ignore: /pt/java/conversion/rtf-to-xlsb/
family: total
platformtag: net
feature: conversion
informat: RTF
outformat: XLSB
otherformats: ODS EXCEL XLTM XLT XLTX XLSX XLSM XLSB FODS TSV SXC XLAM DIF XLS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converter RTF para XLSB via Java" h2="API Java no local para converter RTF para XLSB sem usar o Microsoft<sup>&reg;</sup> Word ou Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Converter RTF para XLSB via [Aspose.Total for Java](https://products.aspose.com/total/java/) é um processo simples de duas etapas. Usando a API de conversão e manipulação de Documentos rica em recursos [Aspose.Words for Java](https://products.aspose.com/words/java/), você pode exportar RTF para HTML. Depois disso, usando [Aspose.Cells for Java](https://products.aspose.com/cells/java/), você pode converter HTML para XLSB.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ para converter RTF para XLSB" %}}
1. Abra o arquivo RTF usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. Converta RTF para HTML usando [Salvar](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) método
3. Carregue o Documento HTML usando a classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salve o Documento no formato XLSB usando [Salvar](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e inclua [Aspose.Words for Java](https://rtfs.aspose.com/words/java/installation/) e [Aspose.Cells for Java](https://rtfs.aspose.com/cells/java/installation/) em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversão" %}}
Antes de converter RTF para XLSB, você pode remover informações não utilizadas do Documento RTF via [Aspose.Words for Java](https://products.aspose.com/words/java/). Às vezes, pode ser necessário remover informações não utilizadas ou duplicadas para reduzir o tamanho do Documento de saída e o tempo de processamento. A classe [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) permite especificar opções para limpeza de Documentos. Para remover estilos duplicados ou apenas estilos ou listas não utilizados do Documento, você pode usar o método [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Document#cleanup()). Você pode usar os [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) e [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) para detectar e remover estilos marcados como “não usados”.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-Document.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions))
{{% blocks/products/pf/feature-page-section  h2="Remover informações não utilizadas de um Documento RTF via Java" %}}
Depois de converter RTF para XLSB, o [Aspose.Cells for Java](https://products.aspose.com/cells/java/) permite que você salve seu Documento para transmitir. Se você precisar salvar arquivos em um Stream, deverá criar um objeto FileOutputStream e [salvar](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) o arquivo para esse objeto Stream chamando o método save de [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) objeto. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras opções de conversão" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/rtf-to-xlsm/" name="RTF Para XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/rtf-to-xlt/" name="RTF Para XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/rtf-to-ods/" name="RTF Para ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/rtf-to-tsv/" name="RTF Para TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/rtf-to-xls/" name="RTF Para XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/rtf-to-xlsb/" name="RTF Para XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/rtf-to-fods/" name="RTF Para FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/rtf-to-dif/" name="RTF Para DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/rtf-to-xltx/" name="RTF Para XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/rtf-to-xlam/" name="RTF Para XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/rtf-to-xlsx/" name="RTF Para XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/rtf-to-xltm/" name="RTF Para XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/rtf-to-sxc/" name="RTF Para SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/rtf-to-excel/" name="RTF Para EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}