---
title: API Android para converter RTF para XLSX
description: Converta RTF para XLSX no Android via Java sem usar o Microsoft Word ou o Microsoft Excel

family: total
platformtag: cpp
feature: conversion
informat: RTF
outformat: XLSX
otherformats: XLTM FODS DIF CSV EXCEL XLTX XLSM XLSB XLT XLS SXC XLAM ODS TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converter RTF para XLSX em aplicativos Android" h2="Exporte RTF para XLSX no Android via Java sem usar o Microsoft<sup>&reg;</sup> Word ou Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Ao usar o [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/), você pode integrar o recurso de conversão de RTF para XLSX dentro de seus aplicativos Android. Em primeiro lugar, você pode converter RTF para HTML usando a API de conversão e manipulação de rtfumentos rica em recursos [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Depois disso, usando [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/), você pode converter HTML para XLSX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android para converter RTF para XLSX" %}}
1. Abra o arquivo RTF usando a classe [Rtfument](https://reference.aspose.com/words/java/com.aspose.words/Rtfument)
2. Converta RTF para HTML usando [Save](https://reference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String,com.aspose.words.SaveOptions) ) método
3. Carregue o rtfumento HTML usando a classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salve o rtfumento no formato XLSX usando [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) método
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total for Android via Java diretamente do [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e instale [Aspose.Cells for Android via Java](https://rtfs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) e [Aspose.Words for Android via Java](https://rtfs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository) em seus aplicativos.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Remover informações não utilizadas de um rtfumento RTF no Android via Java" %}}
Antes de converter RTF para XLSX, você pode remover informações não utilizadas do Rtfumento RTF por meio do [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Às vezes, pode ser necessário remover informações não utilizadas ou duplicadas para reduzir o tamanho do rtfumento de saída e o tempo de processamento. A classe [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) permite especificar opções para limpeza de rtfumentos. Para remover estilos duplicados ou apenas estilos ou listas não utilizados do rtfumento, você pode usar o método [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Rtfument#cleanup()). Você pode usar os [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) e [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) para detectar e remover estilos marcados como “não usados”.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-rtfument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Salvar arquivo XLSX para transmitir no Android via Java" %}}
Depois de converter RTF para XLSX, o [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) permite que você salve seu rtfumento para transmitir. Se você precisar salvar arquivos em um Stream, deverá criar um objeto FileOutputStream e, em seguida, [salvar](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) o arquivo para esse objeto Stream chamando o método save de [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) objeto.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/rtf-to-xltm/" name="RTF Para XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/rtf-to-fods/" name="RTF Para FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/rtf-to-dif/" name="RTF Para DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/rtf-to-xlsx/" name="RTF Para XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/rtf-to-excel/" name="RTF Para EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/rtf-to-xltx/" name="RTF Para XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/rtf-to-xlsm/" name="RTF Para XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/rtf-to-xlsb/" name="RTF Para XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/rtf-to-xlt/" name="RTF Para XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/rtf-to-xls/" name="RTF Para XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/rtf-to-sxc/" name="RTF Para SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/rtf-to-xlam/" name="RTF Para XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/rtf-to-ods/" name="RTF Para ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/android-java/conversion/rtf-to-tsv/" name="RTF Para TSV" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}