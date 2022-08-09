---
title: API Android para converter DOCX para XLTM
description: Converta DOCX para XLTM no Android via Java sem usar o Microsoft Word ou o Microsoft Excel
url: /pt/android-java/conversion/docx-to-xltm/
family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: XLTM
otherformats: EXCEL XLSX XLTX XLSB XLT XLAM XLSM DIF TSV XLS CSV FODS SXC ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converter DOCX para XLTM em aplicativos Android" h2="Exporte DOCX para XLTM no Android via Java sem usar o Microsoft<sup>&reg;</sup> Word ou Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Ao usar o [Aspose.Total para Android via Java](https://products.aspose.com/total/android-java/), você pode integrar o recurso de conversão de DOCX para XLTM dentro de seus aplicativos Android. Em primeiro lugar, você pode converter DOCX para HTML usando a API de conversão e manipulação de docxumentos rica em recursos [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Depois disso, usando [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/), você pode converter HTML para XLTM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android para converter DOCX para XLTM" %}}
1. Abra o arquivo DOCX usando a classe [Docxument](https://reference.aspose.com/words/java/com.aspose.words/Docxument)
2. Converta DOCX para HTML usando [Salvar](https://reference.aspose.com/words/java/com.aspose.words/Docxument#save(java.lang.String,com.aspose.words.SaveOptions) ) método
3. Carregue o docxumento HTML usando a classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salve o docxumento no formato XLTM usando [Salvar](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) método
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Android via Java diretamente do [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e instale [Aspose.Cells for Android via Java](https://docxs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) e [Aspose.Words for Android via Java](https://docxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository) em seus aplicativos.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Remover informações não utilizadas de um docxumento DOCX no Android via Java" %}}
Antes de converter DOCX para XLTM, você pode remover informações não utilizadas do Docxumento DOCX por meio do [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Às vezes, pode ser necessário remover informações não utilizadas ou duplicadas para reduzir o tamanho do docxumento de saída e o tempo de processamento. A classe [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) permite especificar opções para limpeza de docxumentos. Para remover estilos duplicados ou apenas estilos ou listas não utilizados do docxumento, você pode usar o método [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Docxument#cleanup()). Você pode usar os [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) e [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) para detectar e remover estilos marcados como “não usados”.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-docxument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Salvar arquivo XLTM para transmitir no Android via Java" %}}
Depois de converter DOCX para XLTM, o [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) permite que você salve seu docxumento para transmitir. Se você precisar salvar arquivos em um Stream, deverá criar um objeto FileOutputStream e, em seguida, [salvar](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) o arquivo para esse objeto Stream chamando o método save de [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) objeto.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/docx-to-excel/" name="DOCX Para EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/docx-to-xlsx/" name="DOCX Para XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/docx-to-xltx/" name="DOCX Para XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/docx-to-xlsb/" name="DOCX Para XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/docx-to-xlt/" name="DOCX Para XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/docx-to-xlam/" name="DOCX Para XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/docx-to-xlsm/" name="DOCX Para XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/docx-to-dif/" name="DOCX Para DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/docx-to-tsv/" name="DOCX Para TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/docx-to-xls/" name="DOCX Para XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/docx-to-xltm/" name="DOCX Para XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/docx-to-fods/" name="DOCX Para FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/docx-to-sxc/" name="DOCX Para SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/docx-to-ods/" name="DOCX Para ODS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}